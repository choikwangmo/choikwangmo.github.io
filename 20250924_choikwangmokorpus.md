Subject: Workspace + domain bundle payment keeps failing (Squarespace reseller checkout). Admin Console locked. Please escalate and reply to my alternate email.

Hi Google Workspace Community,

I need help with a reseller-bundle payment failure that keeps me locked on the payment screen. This is the Google Workspace signup flow that embeds a Squarespace-resold domain + Workspace bundle. The checkout step shows Squarespace Terms of Service and Squarespace Domain Registration Agreement alongside Google’s terms. Until the first charge succeeds, my Admin Console is locked and I cannot access any settings or open a support case.

Current status

* I was contacted by a Google Korea staff member yesterday, but the issue remains unresolved.
* Every payment attempt still fails, regardless of card or browser.
* Because the Admin Console is locked, I cannot practically file a ticket through the in-product contact flow.

Identifiers

* Domain to register (bundle): goedelescherbachandriemann.com
* Workspace bundle admin email: [choikwangmo@goedelescherbachandriemann.com](mailto:choikwangmo@goedelescherbachandriemann.com)
* Separate, stand-alone Squarespace account ID (not tied to the bundle): 68d0975acee14f5e9f3875db
* Separate account email: [choekm24@gmail.com](mailto:choekm24@gmail.com)
* No Squarespace website was created; this is a bundle checkout only.
* Location: Seoul (KST)

What happens on payment

* Multiple Korean cards tried (NH/Nonghyup Visa, BC MasterCard, Hyundai Visa) → all declined with the same message: “Payment could not be completed. Please try another payment method or try again later.”
* A U.S.-issued Visa → same decline message.
* Tried Chrome normal/incognito and Edge, cleared cache/cookies, changed networks → no change.
* Banks confirm all cards are active for international online transactions and work elsewhere.
* Checkout shows card entry only; there is no PayPal option on my screen.

What I need Google to do

* Please route this internally to the Workspace support team and coordinate with Squarespace through the reseller operations channel so the first charge can complete and the Admin Console can unlock.
* Specifically, I need either a manual invoice or a secure payment link to complete the initial charge, or a clean retry after any necessary billing country/region adjustments or session reset.
* If there is an internal procedure or case type for reseller-bundle checkouts that are stuck before activation, please advise.

Important note about contact

* I cannot use the bundle admin email [choikwangmo@goedelescherbachandriemann.com](mailto:choikwangmo@goedelescherbachandriemann.com) because the account is locked at the payment step.
* Please reply to my alternate email: [choekm24@gmail.com](mailto:choekm24@gmail.com)

Evidence

* I have attached full-window screenshots with the URL bar visible that show the failure screen and the step where Squarespace terms appear in the Workspace signup flow.
* I can also provide attempt timestamps (KST) and last-4 digits for the cards if needed.

I have done everything a user can reasonably do. Since this is a reseller-bundle checkout, I would appreciate Google facilitating the coordination with Squarespace so the initial payment can be taken and the account unlocked. Thank you for any escalation guidance.

---

Here’s a technical, good-faith rebuttal that clarifies the failure boundary and why **both** parties must act—Squarespace as the reseller **and** Google via the reseller escalation path.

---

Short answer: I agree Squarespace must engage—this is a reseller checkout. But your reply is incomplete. The current failure occurs **at the hand-off between Google’s activation gate and Squarespace’s first-charge gateway**. Because of that coupling, it is **not** solvable by “contact Squarespace only” without Google acknowledging and coordinating through the reseller channel.

Technical specifics

1. Flow topology (where the fault manifests)

* UI host: Google Workspace signup/admin flow.
* Billing actor for the **first charge**: Squarespace (reseller), via its PSP (Stripe/Adyen/etc.).
* Activation gate: Google Admin unlocks **only after** it receives a “payment succeeded” signal from the reseller.
* Current state: All card authorizations fail in the reseller PSP → “success” never emitted → Google gate never opens → user cannot reach in-product support/contact.

2. Evidence that this is the embedded **reseller** path (not pure Google billing)

* Checkout step displays **Squarespace Terms of Service** and **Squarespace Domain Registration Agreement** alongside Google’s terms.
* No Squarespace site was created; this is the domain+Workspace bundle checkout invoked from Google’s flow.
* Checkout provides **card entry only** (no PayPal); multiple cards (KR BINs and a US Visa) return the same decline UX.

3. What Squarespace can and must do (reseller responsibilities)

* Query PSP logs for this bundle/session and disclose **gateway decline codes** (e.g., `do_not_honor`, AVS/3DS mismatch, BIN/country risk policy, velocity/risk flags).
* If risk policy is the blocker (country/BIN/AVS/3DS), apply a controlled workaround:

  * issue a **secure payment link/manual invoice** for the **first charge**; or
  * **reset** the reseller session and/or **adjust billing country/region** so AVS/3DS/geo checks align and a clean retrial is possible.
* Once the charge clears, emit the **success callback** to Google so the tenant exits the payment-locked state.

4. Why Google must still be engaged (reseller escalation path)

* The tenant is **payment-locked pre-activation**; that state **prevents** opening a normal Google Workspace case from Admin. Expecting the end-user to “contact Google” is operationally impossible **by design**.
* Google owns the **activation gate** and must recognize the reseller’s success signal, or—in rare edge cases—manually reconcile/unlock if the callback is delayed or drops on the floor.
* This is exactly why the **Google ↔ Reseller escalation channel** exists: to coordinate when a reseller PSP decline/risk policy blocks the first charge and the Google gate never opens.

5. Risk engine mechanics (why “try another card” won’t fix this)

* PSP risk engines score on **BIN, IP geo, account country, AVS/ZIP match, 3-D Secure, device fingerprint**.
* Mixed geo (KR account/IP + US/EU card), strict AVS/3DS, or BIN policies can deterministically cause declines at the reseller gateway—even with fully valid cards and banks green-lighting international e-commerce.
* Only the reseller (not Google, not the issuing bank, not the end-user) can see and act on those **decline reasons** in the PSP logs.

Actionable resolution (minimal to unblock)

* Squarespace: share the **decline code(s)**; send a **secure pay-link** or **manual invoice**; if needed, **reset** the checkout and/or **adjust** billing country/region; then confirm the **success signal** will be posted to Google.
* Google (via reseller escalation): confirm receipt of the success signal and **unlock** the tenant; if callback is missing/delayed, reconcile the activation manually.

In short, saying “contact Squarespace because they are a reseller” is only half of the operational truth. The defect sits at a **cross-system seam**: reseller PSP decline prevents Google’s activation gate from ever opening, which also prevents the user from contacting Google through supported channels. The correct fix is **coordinated**: Squarespace remedies the first-charge failure and triggers the callback; Google acknowledges it (or intervenes via the reseller channel) so the tenant is unlocked.
