# Forgery Verification Methods for National Tax Certificates (국세증명)

> English conversion and structuring of the provided corpus. All proper nouns include original script in parentheses.

## 1) Scope and Purpose

- Document focus: How to verify forgery/tampering of National Tax Certificates (국세증명) issued by the National Tax Service (국세청).
- Primary use cases:
  - Vendor or contractor onboarding
  - Grant/loan applications
  - Compliance and audit checks

## 2) Core Verification Steps (Recommended Order)

1. Confirm the `issuance number` on the certificate.
2. Validate the certificate through official systems:
   - Hometax (홈택스)
   - Mobile Hometax (모바일홈택스)
   - Government24 (정부24) for documents issued via Government24
3. Perform barcode-based cross-check:
   - 3-part segmented barcode (bottom area)
   - Audio-conversion QR barcode (top-right area)
4. Conduct visual anti-forgery checks:
   - Watermark (central round emblem and wave pattern)
   - Copy-protection microtext/pattern (left-bottom “National Tax Service” style text)
5. Archive evidence (screenshots of system results, barcode scans).

## 3) Security Features and How to Check

| Feature (Original Script) | Location on Document | How to Check | What a Valid Result Looks Like | Notes |
|---|---|---|---|---|
| Issuance number (발급번호) | Top-left area | Enter on official verification page of Hometax (홈택스) / Mobile Hometax (모바일홈택스) | System returns certificate metadata (type, name, date) | Typically verifiable within a limited window (e.g., 90 days from issuance). |
| 3-part segmented barcode (3단 분할 바코드) | Bottom horizontal band (three segments) | Scan with supported verification app | Decodes to integrity data linked to issuance | Low-quality copies may fail to scan. Prefer original or high-resolution print. |
| Audio-conversion QR barcode (음성변환 바코드) | Top-right area | Scan with MarkAny (마크애니) app or equivalent | App confirms original/authentic status | Some scanners require stable lighting; avoid screen glare. |
| Watermark (워터마크) | Center area (round NTS emblem with wave pattern) | Tilt under light; compare density and crisp edges | Clear emblem and consistent wave texture | Photocopies often blur/flatten watermark effects. |
| Copy-protection microtext/pattern (복사방지코드) | Left-bottom patterned area | Visual inspection or magnifier | Repeating “National Tax Service (국세청)” microtext/pattern | Copying/scanning degrades contrast and legibility. |

## 4) Official Verification Channels

| Channel (Original Script) | Access Path | Supported Document Types | Validation Window | Steps |
|---|---|---|---|---|
| Hometax (홈택스) | Web portal | National Tax Certificates (국세증명) issued via Hometax | Typically limited-time window (e.g., 90 days) | Go to `Civil Certificates (민원증명)` → `Original Verification (원본 확인)` → Enter issuance number and required fields. |
| Mobile Hometax (모바일홈택스) | Mobile app | Same as Hometax | Same as Hometax | Open app → `Civil Certificates (민원증명)` → `Original Verification (원본 확인)` → Input issuance number. |
| Government24 (정부24) | Web/mobile | Certificates issued through Government24 | As guided by Government24 | Open issued certificate details → Use built-in verification function. |

## 5) Barcode and App Guidance

- Recommended app: MarkAny (마크애니).
- Usage notes:
  - Use the audio-conversion QR barcode (top-right) and/or the 3-part segmented barcode (bottom) for cross-verification.
  - Ensure good lighting; avoid reflective screens or low-DPI prints.
  - If a scan fails, retry with the original PDF print or request a reprint in higher quality.

## 6) On-Site Verification Checklist

- [ ] Check the issuance number format and position (top-left).
- [ ] Verify the issuance number on Hometax (홈택스) / Mobile Hometax (모바일홈택스).
- [ ] If issued via Government24 (정부24), verify using Government24’s function.
- [ ] Scan the 3-part segmented barcode (bottom band).
- [ ] Scan the audio-conversion QR barcode (top-right) using MarkAny (마크애니).
- [ ] Inspect the watermark (central emblem and wave pattern).
- [ ] Inspect the copy-protection microtext/pattern (left-bottom).
- [ ] Capture and store screenshots of verification outcomes.

## 7) Common Failure Modes and How to Respond

| Symptom | Likely Cause | Response |
|---|---|---|
| Barcode scan fails repeatedly | Low-resolution copy, screen glare, or compression artifacts | Request the original PDF or a high-resolution print; scan again under proper lighting. |
| Issuance number not found | Expired validation window or altered number | Ask for a freshly reissued certificate; re-verify immediately. |
| Watermark looks flat | Photocopy/scan artifact | Treat as insufficient evidence; rely on issuance number and barcode verification. |
| Mismatch between system data and document | Possible tampering | Reject the document and request a new, directly issued certificate. |

## 8) Evidence and Record-Keeping

- Save verification screenshots (portal confirmation pages, app results).
- Note the verification timestamp, verifier’s name, and method used (issuance number, barcode types).
- Retain a copy of the submitted certificate (prefer original PDF print) with a reference ID for audit trails.

## 9) Quick Decision Flow

1. Issuance number verification succeeds → proceed.
2. Barcode cross-check (3-part and/or audio QR) succeeds → accept.
3. Visual checks confirm watermark/microtext → finalize.
4. Any failure or mismatch → request reissuance and re-verify.

## 10) References to Systems and Apps

- National Tax Service (국세청)
- Hometax (홈택스)
- Mobile Hometax (모바일홈택스)
- Government24 (정부24)
- MarkAny (마크애니)

