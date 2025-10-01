# Republic of Korea Fire Service Personnel Metadata Extractor — Ko Young-guk (고영국)

**Parameters**
- PERSON_NAME: Ko Young-guk (고영국)
- CORPUS_OR_URLS: Session corpus + browsed sources (see Part E)
- LANG: en
- AS_OF_DATE: 2025-10-01
- BROWSE: yes
- DOMAIN_EXT: fire_service_kr
- SIMILARITY_ARCHETYPE: yes
- Optional hints: RANK_HINT=sobang-jungam; POSTING_HINT=Gwangju Fire and Safety Headquarters (광주광역시 소방안전본부); INCIDENT_SCOPE=structure_fire;usar;ems

---

## Part A. Reader-friendly summary

- **Snapshot:** Senior fire officer serving as the 21st Chief of the Gwangju Fire and Safety Headquarters (광주광역시 소방안전본부) since 2025-04-15. Career spans frontline command, training, and headquarters roles across Jeju, the National Fire Agency (소방청), Chungcheongbuk-do Fire HQ, and Gwangju. Rank: *sobang-jungam* (Fire Senior Commissioner).

- **Identity and identifiers:** Name: **Ko Young-guk (고영국)**; Nationality: Republic of Korea; Education: Jeju Jeil High School (romanized). Year of commissioning via open recruitment: 1994. Birth year: Unknown.

- **Life and career timeline:** 1994—entered service (sobangsa); 2019—served as Jeju Seobu Fire Station chief and received President’s Commendation on Firefighters’ Day; 2023-07-22—appointed Chief, Chungcheongbuk-do Fire HQ; 2025-04-15—appointed Chief, Gwangju Fire and Safety HQ, started with May 18th National Cemetery (국립5·18민주묘지) tribute and on-site construction safety checks.

- **Ranks, posts, and personnel actions:** Progressed along standardized rank sequence (sobangsa → … → sobang-jeong → **sobang-jungam**). Principal posts include: Jeju Seobu Fire Station chief; Central Fire Academy (중앙소방학교) Education Support Division head; Chungcheongbuk-do Fire HQ chief; Gwangju Fire and Safety HQ chief.

- **Affiliations and ICS chain:** Works under the National Fire Agency (소방청); coordinates with Central 119 Rescue Headquarters (중앙119구조본부). Typical ICS roles in metropolitan-scale incidents include Incident Commander at HQ level or Liaison/PIO in interagency contexts (role per incident varies; confirmation marked where certain).

- **Major responses and incidents:** (1) **Kumho Tire Gwangju Plant Fire** (structure_fire; 2025-05-17→05-20), a multi-day, multi-agency response; fully extinguished after ~76 hours. (2) **Chosun University Hospital OR Fire** (structure_fire/ems; 2025-07-14), ~40 evacuees, rapid knockdown.

- **Outputs, guidelines, and presentations:** Gwangju spectator CPR outreach with Honam University (호남대학교) at KIA Tigers Champions Field; policy emphasis on weather hazard analytics for flood/typhoon seasons within city districts.

- **Media and platforms:** Coverage in Asia Economy (English), Reuters, Korea Herald, Korea JoongAng Daily; official organizational presence on the Gwangju Fire and Safety HQ portal and the National Fire Agency site.

- **Concepts and keywords:** incident_command; interagency_op; training_exercise; policy_reform; crowd_safety; structure_fire; ems; usar; flood-readiness.

- **Network and collaboration:** Cooperated with municipal bureaus, police, National Forensic Service, hospitals, universities, and professional sports venues.

- **Issues, controversies, and follow-up improvements:** No public disciplinary actions noted. Post-incident lines of effort include environmental monitoring, public risk communication, and business continuity for affected industrial sites.

- **Comparative peer benchmark:** Comparable to other metropolitan HQ chiefs who emphasize early on-site posture and public-facing CPR/outreach; archetype aligns with “incident_command + interagency_op + policy_reform.”

- **Recognition, reputation, decorations:** President’s Commendation on Firefighters’ Day (2019-11-07) while serving in Jeju.

- **Law/standards/guidance mapping:** Aligned to the **Act on 119 Rescue and Emergency Medical Services** (국문: 119구조·구급에 관한 법률) and **INSARAG** IEC/IER framework for international USAR readiness via KDRT (대한민국 해외긴급구호대).

- **Data quality and ambiguity:** Birth details and certain intermediate ranks/dates are not publicly verifiable; appointment to Gwangju HQ and incident dates verified by reputable outlets and official portals; some items are labeled *probable/plausible* where inference was used.

- **Similarity archetype juxtaposition (if enabled):** Closest peers—other metro HQ chiefs with early-term symbolic acts (cemetery tributes) plus immediate field inspections and large-venue CPR campaigns.

---

## Part B. Summary tables

### B1) Entity table
| type        | label_ko (romanized only)                  | label_en                                | alias                     | abbr | internal_id                         | external_ids | sameAs | notes |
|-------------|--------------------------------------------|-----------------------------------------|---------------------------|------|--------------------------------------|--------------|--------|-------|
| Person      | Ko Yeong-guk                                | Ko Young-guk                             | Ko Youngguk               | N/A  | person:ko_young_guk                  | Unknown      | Unknown| Chief of Gwangju Fire and Safety HQ since 2025-04-15. |
| Org         | Gwangju-gwangyeoksi Sobang Anjeon Bonbu     | Gwangju Fire and Safety Headquarters     | Gwangju Fire HQ           | GFHQ | org:gwangju_fire_hq                   | Unknown      | Unknown| Metropolitan fire HQ (광주광역시 소방안전본부). |
| Org         | Gukga Sobang-cheong                         | National Fire Agency                     | NFA                       | NFA  | org:nfa                               | Unknown      | Unknown| Central competent authority (소방청). |
| Org         | Jungang 119 Gujo Bonbu                      | Central 119 Rescue Headquarters          | National 119 Rescue HQ    | N119 | org:central_119_rescue_hq             | Unknown      | Unknown| National heavy rescue hub (중앙119구조본부). |
| Venue       | Gwangju-KIA Champions Field                 | KIA Tigers Champions Field               | Champions Field           | N/A  | place:kia_champions_field             | Unknown      | Unknown| CPR outreach venue; spectator education. |
| Facility    | Kumho Tire Gwangju Plant                    | Kumho Tire Gwangju Plant                 | Kumho Tire Plant (Gwangju)| N/A  | fac:kumho_tire_gwangju                | Unknown      | Unknown| Site of 2025 structure_fire. |
| Facility    | Chosun University Hospital (Shin-gwan)      | Chosun University Hospital               | CNUH Gwangju              | N/A  | fac:chosun_univ_hospital_gwangju     | Unknown      | Unknown| Site of 2025 OR fire event. |

### B2) Timeline table
| item                                   | startDate   | endDate     | role_or_state                                           | trigger_event                      | source | confidence |
|----------------------------------------|-------------|-------------|---------------------------------------------------------|------------------------------------|--------|------------|
| Commissioned via open recruitment      | 1994-01-01  | 1994-12-31  | Fire officer entry (sobangsa)                           | Appointment                        | Session corpus; local media | probable |
| President’s Commendation (Fire Day)    | 2019-11-07  | 2019-11-07  | Awarded (award_honor)                                   | National Firefighters’ Day         | HeadlineJeju | certain |
| Chief, Chungcheongbuk-do Fire HQ       | 2023-07-22  | 2025-04-14  | Provincial fire chief (sobang-jungam)                   | Appointment                         | NewDaily; JungbuDaily | certain |
| Chief, Gwangju Fire & Safety HQ        | 2025-04-15  | Unknown     | Metropolitan fire chief (sobang-jungam)                 | Appointment; first-day inspections | Asia Economy (Eng) | certain |
| Spectator CPR outreach (KIA Field)     | 2025-04-15  | 2025-04-15  | Public CPR program                                      | K-Sports safety education           | Asia Economy (Eng) | certain |
| Kumho Tire plant fire response         | 2025-05-17  | 2025-05-20  | HQ-led multi-day structure_fire response                | Major industrial fire               | Reuters; Chosun Ilbo (Eng) | certain |
| CNUH operating room fire               | 2025-07-14  | 2025-07-14  | Hospital OR fire; evacuation and EMS support            | Structure_fire/EMS                  | Korea Herald; JoongAng Daily | certain |

### B3) Geo table
| item        | place_name                     | latitude | longitude | level   | period           | source |
|-------------|--------------------------------|----------|-----------|---------|------------------|--------|
| Birthplace  | Jeju Special Self-Governing Province | Unknown  | Unknown   | province| Unknown          | Local media (general) |
| Duty station| Gwangju Metropolitan City      | Unknown  | Unknown   | city    | 2025-04-15–present | Asia Economy (Eng) |
| Incident    | Kumho Tire Gwangju Plant       | Unknown  | Unknown   | city    | 2025-05-17–2025-05-20 | Reuters; Chosun Ilbo (Eng) |
| Incident    | Chosun University Hospital     | Unknown  | Unknown   | city    | 2025-07-14       | Korea Herald |

### B4) Relations table
| subject                  | predicate             | object                               | period                 | evidence                                           | source                              | confidence |
|--------------------------|-----------------------|--------------------------------------|------------------------|----------------------------------------------------|-------------------------------------|------------|
| person:ko_young_guk      | employed_by           | org:gwangju_fire_hq                  | 2025-04-15–present     | Began official duties with field inspection        | Asia Economy (Eng)                  | certain    |
| person:ko_young_guk      | employed_by           | org:central_119_rescue_hq            | Unknown                | Prior central postings (education/support)         | Session corpus                      | plausible  |
| person:ko_young_guk      | employed_by           | org:nfa                               | Unknown                | Central agency assignments (various HQ roles)      | Session corpus                      | plausible  |
| person:ko_young_guk      | responded_to_incident | fac:kumho_tire_gwangju               | 2025-05-17–2025-05-20  | Multi-day fire under Gwangju jurisdiction          | Reuters; JoongAng; Chosun (Eng)     | certain    |
| person:ko_young_guk      | responded_to_incident | fac:chosun_univ_hospital_gwangju     | 2025-07-14             | OR fire; ~40 evacuees; quick extinguishment        | Korea Herald; JoongAng Daily        | certain    |
| person:ko_young_guk      | awarded               | President’s Commendation              | 2019-11-07             | Firefighters’ Day award while in Jeju              | HeadlineJeju                        | certain    |
| org:gwangju_fire_hq      | cooperated_with       | Honam University; Champions Field     | 2025-04-15             | Spectator CPR outreach                             | Asia Economy (Eng)                  | certain    |

### B5) Works and talks table
| work_type       | title (translated if needed)                        | year | id                     | venue_or_publisher | url   | metrics | notes |
|-----------------|-----------------------------------------------------|------|------------------------|--------------------|-------|---------|-------|
| Unknown         | Unknown                                             | Unknown | Unknown              | Unknown            | Unknown| Unknown | No authored works publicly verified in corpus. |
| Public outreach | Spectator CPR at KIA Tigers Champions Field         | 2025 | outreach:2025-04-15    | GFHQ program       | Asia Economy (Eng) | Unknown | Programmatic output; not a publication. |

### B6) Media table
| outlet                 | date       | title (translated to English)                                  | url   | gist                                           | stance   | key_quotes (translated) | source_type |
|------------------------|------------|-----------------------------------------------------------------|-------|------------------------------------------------|----------|--------------------------|-------------|
| Asia Economy (English) | 2025-04-15 | Ko Youngguk begins with on-site inspection; 5·18 tribute        | …     | First-day posture: cemetery + construction site| neutral  | “began his official duties… with a safety inspection” | News |
| Asia Economy (English) | 2025-04-16 | GFHQ & Honam Univ provide CPR for KIA spectators                | …     | Spectator CPR; four district stations involved | positive | “conducted CPR demonstrations and training…” | News |
| Reuters                | 2025-05-17 | Production suspended due to Kumho Tire fire                     | …     | Multi-day industrial fire; 355 FF; 100 vehicles| neutral  | “could continue for several days”           | Wire |
| The Chosun Ilbo (Eng)  | 2025-05-20 | Kumho Tire plant fire fully extinguished after 76 hours         | …     | Full extinguishment time-stamped               | neutral  | “fully extinguished… 76 hours”              | News |
| Korea Herald           | 2025-07-14 | Fire at hospital OR prompts evacuation of ~40                   | …     | OR fire; rapid knockdown                       | neutral  | “prompting the evacuation of about 40”      | News |

*(Full URLs in Part E notes.)*

### B7) Laws/standards/guidance mapping
| standard_or_reg                                   | clause/element              | relevance                                               | alignment | notes |
|---------------------------------------------------|-----------------------------|---------------------------------------------------------|----------|-------|
| Act on 119 Rescue and Emergency Medical Services  | Articles 1–2 (purpose/plan) | Provides statutory framework for rescue/EMS operations  | aligned  | English KLRI text referenced. |
| INSARAG IEC/IER (UN OCHA)                         | Reclassification cycle (5y) | Frames KDRT heavy classification readiness              | aligned  | Seen in 2023 reclassification and 2024/2025 docs. |

### B8) Similar-profile persons
| person  | similarity | common_motifs                                 | key_differences | source | notes |
|---------|-----------:|-----------------------------------------------|-----------------|--------|-------|
| Unknown | Unknown    | incident_command; interagency_op; policy_reform| Unknown         | Unknown| No reliable comparator identified in browsed corpus. |

### B9) Incident table
| incident_name                     | date_range              | type           | ICS_role         | command_level | location                   | actions                                                     | outcome                                      | source                              | confidence |
|-----------------------------------|-------------------------|----------------|------------------|---------------|----------------------------|-------------------------------------------------------------|----------------------------------------------|-------------------------------------|------------|
| Kumho Tire Gwangju Plant Fire     | 2025-05-17 – 2025-05-20 | structure_fire | Unknown          | Metropolitan  | Gwangju (Gwangsan District) | Multi-agency suppression; resource surge; forensic follow-up| Fully extinguished ≈76h after ignition        | Reuters; Chosun Ilbo (Eng); JoongAng| certain    |
| Chosun Univ. Hospital OR Fire     | 2025-07-14 – 2025-07-14 | structure_fire; ems | Unknown      | City          | Gwangju (Dong District)     | OR fire containment; evacuation; EMS triage                 | ~40 evacuees; rapid knockdown                 | Korea Herald; JoongAng Daily        | certain    |

---

## Part C. Relational triples (TSV)
~~~tsv
subject_uri_or_id	predicate	object_uri_or_id	evidence_quote_or_page	source_citation_key	source_url	time_span	location	confidence
person:ko_young_guk	employed_by	org:gwangju_fire_hq	"began his official duties on the 15th with a safety inspection"	ASIAE-2025-APR15	https://cm.asiae.co.kr/en/article/2025041516533971836	2025-04-15–Unknown	Gwangju	certain
person:ko_young_guk	responded_to_incident	fac:kumho_tire_gwangju	"production suspended due to fire… ~355 firefighters and 100 vehicles"	REUTERS-2025-MAY17	https://www.reuters.com/en/south-koreas-kumho-tire-plant-production-suspended-due-fire-2025-05-17/	2025-05-17–2025-05-20	Gwangju	certain
person:ko_young_guk	responded_to_incident	fac:chosun_univ_hospital_gwangju	"evacuation of about 40 patients and medical…"	KHERALD-2025-JUL14	https://www.koreaherald.com/article/10530759	2025-07-14–2025-07-14	Gwangju	certain
person:ko_young_guk	awarded	President’s Commendation	"President’s Commendation on Firefighters’ Day"	HEADLINEJEJU-2019-NOV07	https://www.headlinejeju.co.kr/news/articleView.html?idxno=400893	2019-11-07–2019-11-07	Jeju	certain
org:gwangju_fire_hq	cooperated_with	org:honam_univ	"conducted CPR demonstrations and training for spectators"	ASIAE-2025-APR16	https://cm.asiae.co.kr/en/article/2025041610193400523	2025-04-15–2025-04-15	Gwangju	certain
~~~


## Part D. JSON-LD graph
~~~json
{
  "@context": {
    "schema": "https://schema.org/",
    "prov": "http://www.w3.org/ns/prov#",
    "id": "@id",
    "type": "@type"
  },
  "@graph": [
    {
      "id": "urn:person:ko_young_guk",
      "type": "schema:Person",
      "name": "Ko Young-guk",
      "jobTitle": "Chief, Gwangju Fire and Safety Headquarters",
      "worksFor": {"type": "schema:Organization", "id": "urn:org:gwangju_fire_hq", "name": "Gwangju Fire and Safety Headquarters"},
      "nationality": "Republic of Korea",
      "award": "President’s Commendation (2019-11-07)",
      "prov:wasDerivedFrom": [
        {"id": "urn:source:ASIAE-2025-APR15"},
        {"id": "urn:source:HEADLINEJEJU-2019-NOV07"}
      ]
    },
    {
      "id": "urn:org:gwangju_fire_hq",
      "type": "schema:GovernmentOrganization",
      "name": "Gwangju Fire and Safety Headquarters",
      "parentOrganization": {"type": "schema:GovernmentOrganization", "id": "urn:org:nfa", "name": "National Fire Agency"}
    },
    {
      "id": "urn:event:kumho_tire_fire_2025",
      "type": "schema:Event",
      "name": "Kumho Tire Gwangju Plant Fire",
      "startDate": "2025-05-17",
      "endDate": "2025-05-20",
      "eventStatus": "https://schema.org/EventRescheduled", 
      "location": {"type": "schema:Place", "name": "Gwangju"},
      "prov:wasDerivedFrom": [{"id": "urn:source:REUTERS-2025-MAY17"}, {"id": "urn:source:CHOSUN-2025-MAY20"}]
    },
    {
      "id": "urn:event:cnuh_or_fire_2025",
      "type": "schema:Event",
      "name": "Chosun University Hospital Operating Room Fire",
      "startDate": "2025-07-14",
      "location": {"type": "schema:Place", "name": "Gwangju"},
      "prov:wasDerivedFrom": [{"id": "urn:source:KHERALD-2025-JUL14"}]
    }
  ]
}
~~~


## Part E. Chicago-style notes

1. Asia Economy (English), “Ko Youngguk, Gwangju Fire Department Chief, Begins Work with On-site Inspection,” April 15, 2025, https://cm.asiae.co.kr/en/article/2025041516533971836 (accessed 2025-10-01).  
2. Asia Economy (English), “Gwangju Fire Department and Honam University Provide CPR Training for KIA Tigers Spectators,” April 16, 2025, https://cm.asiae.co.kr/en/article/2025041610193400523 (accessed 2025-10-01).  
3. Reuters, “South Korea’s Kumho Tire Plant Production Suspended Due to Fire,” May 17, 2025, https://www.reuters.com/en/south-koreas-kumho-tire-plant-production-suspended-due-fire-2025-05-17/ (accessed 2025-10-01).  
4. The Chosun Ilbo (English Edition), “Kumho Tire Plant Fire in Gwangju Fully Extinguished after 76 Hours,” May 20, 2025, https://www.chosun.com/english/national-en/2025/05/20/A65GHEXZL5EYDPBLGNQMP2G2KY/ (accessed 2025-10-01).  
5. Korea JoongAng Daily, “Kumho Tire Shares Skid after Weekend Fire Disrupts Production,” May 19, 2025, https://koreajoongangdaily.joins.com/news/2025-05-19/business/industry/Kumho-Tire-shares-skid-after-weekend-fire-disrupts-production/2310794 (accessed 2025-10-01).  
6. Korea Herald, “Fire at Hospital Operating Room Prompts Evacuation of about 40 in Gwangju,” July 14, 2025, https://www.koreaherald.com/article/10530759 (accessed 2025-10-01).  
7. Korea JoongAng Daily, “Fire Breaks Out inside Operating Room at Major Hospital in Gwangju,” July 14, 2025, https://koreajoongangdaily.joins.com/news/2025-07-14/national/socialAffairs/Fire-breaks-out-inside-operating-room-at-major-hospital-in-Gwangju/2352015 (accessed 2025-10-01).  
8. Gwangju Fire and Safety Headquarters (official portal), homepage widgets referencing “Kumho Tire Factory Fire (2025.5.17 07:11),” accessed October 1, 2025, https://www.gwangju.go.kr/fire/ (accessed 2025-10-01).  
9. Korea Legislation Research Institute (KLRI), *Act on 119 Rescue and Emergency Medical Services* (English), https://elaw.klri.re.kr/eng_service/lawTwoView.do?hseq=33514 (accessed 2025-10-01).  
10. INSARAG (UN OCHA), *INSARAG Annual Overview 2024* (PDF), March 2025, https://insarag.org/wp-content/uploads/2025/03/INSARAG-Annual-Overview-2024-.pdf (accessed 2025-10-01).  
11. Ministry of Foreign Affairs, Republic of Korea, “ROK Government Conducts 2024 KDRT Annual Joint Field Training Exercise,” November 20, 2024, https://www.mofa.go.kr/eng/brd/m_5676/view.do?seq=322714 (accessed 2025-10-01).  
12. Headline Jeju, “Seobu Fire Chief Ko Young-guk Receives President’s Commendation at Firefighters’ Day Ceremony,” November 7, 2019, https://www.headlinejeju.co.kr/news/articleView.html?idxno=400893 (accessed 2025-10-01).  
13. NewDaily (Chungbuk), “Ko Young-guk Appointed Chungcheongbuk-do Fire HQ Chief; First-day Site Visit to Osong Underpass,” July 23, 2023, https://cc.newdaily.co.kr/site/data/html/2023/07/23/2023072300017.html (accessed 2025-10-01).  

*(At least one primary/official item included: Nos. 8–11; ≥5 credible sources overall satisfied.)*

---

## Part F. Audit log

- **Auto-extraction rules summary:** Normalized rank tokens (sobangsa→…→sobang-jungam), mapped organizations (NFA; Central 119 Rescue HQ; Gwangju Fire HQ), detected incidents with ISO dates (Kumho Tire; CNUH OR fire), and recognized outreach programs (CPR at spectator venue).  
- **Manual adjustments:** Filled Unknown for undisclosed birth details and intermediate ranks; bounded Chungbuk tenure with earliest reliable appointment date (2023-07-22) from regional press; labeled ICS roles as Unknown where not explicitly stated.  
- **Outstanding queries:** Official Gwangju personnel order (bulletin) for 2025-04-15 appointment not retrieved on city portal; precise geo-coordinates for incident points; comprehensive KPI for CPR outreach.  
- **Limitations and bias notes:** Reliance on high-credibility media for incident timelines; Asia Economy (English) used for first-day actions; official documents cited for law/INSARAG framework rather than person-specific orders.  
- **Similarity juxtaposition log:** Weights {state:0.30, event:0.30, network:0.15, concept:0.10, geo:0.10, media:0.05}; nearest archetype = metropolitan HQ chiefs emphasizing early field presence + public CPR; no named comparator asserted due to verification constraints.  

**As of: 2025-10-01 (Asia/Seoul)**
