# RESEARCH.md — Family Hearing Practice | Tinnitus Landing Page (Flower Mound, TX)

**Step:** 2 — Website Research & Content Extraction (research only; no design, no final copy)
**Prepared:** November 27, 2026
**Primary location for this page:** Flower Mound, TX (4491 Long Prairie Rd #400)

---

## 0. READ FIRST — CRITICAL FINDINGS FOR CODEX

| # | Finding | Impact | Action needed |
|---|---|---|---|
| 1 | **The client website has no dedicated tinnitus page.** The sitemap lists only Home, About Us, Hearing Aids, Assistive Listening Devices, Hearing Tests, Custom Earmolds, Contact Us, and Privacy Policy. Tinnitus evidence is scattered across provider bios, the homepage, meta descriptions, and hearing-test symptom lists. | Tinnitus-specific copy (process, technology, outcomes) is thinly sourced. High risk of inventing claims. | Build the page around what IS verified (TRT-certified audiologist, diagnostic hearing evaluation, personalized plans). Request client-approved tinnitus service details (see §10). |
| 2 | **Phone number mismatch.** Brief: **(817) 994-4084**. Every page of the client site (header, footer, contact page) and the NPI registry: **(817) 997-4084**. A July 2026 sponsored article uses a third number, 817-783-9916. | Wrong number = lost calls. 994 may be a campaign tracking number or a one-digit typo. | **Confirm with Ads team / CSM before build.** If 994 is a tracking number, use it consistently; do not mix with 997. |
| 3 | **Provider-to-location mapping is not stated.** The two providers tied to tinnitus therapy (Dr. Cristina Reddy, Dr. Rachel Frederick) are not assigned to Flower Mound or Roanoke anywhere on the site. | Cannot claim "TRT available at our Flower Mound office" as verified fact. | Confirm which tinnitus-trained provider(s) see patients at Flower Mound. |
| 4 | **GHL form embed uses `inline-` iframe ID prefix** (`inline-We5C6Wk3loKV4pUwY0Kp`) with `data-height="415"`. | Standard OnspirePulse convention: `formEmbed-` prefix prevents the GHL autoscroll bug; 415px may clip the submit button. | Treat the ID-prefix change as a "technically necessary" modification; verify rendered height. Load `form_embed.js` once. |
| 5 | **Homepage team photo filename is `ChatGPT-Image-Jun-2-2026-11_25_25-PM.jpg`.** | Appears AI-generated or AI-edited. Presenting it as an authentic clinic/team photo is a trust and accuracy risk in healthcare marketing. | Do not use as "real team photo" without client confirmation. Prefer individual headshots. |
| 6 | **Google rating:** site's Google review widget (Trustindex) displays 5 full stars and **632 Google reviews**; no decimal rating shown. | Rating value (e.g., 4.9 vs 5.0) is unverified. | Pull exact rating + count from the review screenshots the user will supply; they override this figure. |

### Provenance tags used throughout
- **[SITE]** — familyhearingpractice.com (client's own website; primary source)
- **[BRIEF]** — PROJECT_BRIEF supplied by the user
- **[3P-SPONSORED]** — Cross Timbers Gazette sponsored content (paid placement; client-approved at time of publishing but not on client site — use with care)
- **[3P-DIRECTORY]** — NPI registry / directory listings (verification aid only; do not use as page copy without confirmation)
- **[INFERRED]** — Analyst interpretation, not a fact
- **[EXTERNAL-GENERAL]** — General tinnitus literature; NOT a clinic claim

### Source register
| ID | Source | URL | Notes |
|---|---|---|---|
| S1 | Project brief | — | Supplied by user |
| S2 | Homepage | https://familyhearingpractice.com/ | Last modified 2026-09-18 |
| S3 | About Us | https://familyhearingpractice.com/about-us/ | Last modified 2026-08-07; team bios |
| S4 | Hearing Tests | https://familyhearingpractice.com/hearing-tests/ | Most relevant service page for tinnitus evaluation |
| S5 | Hearing Aids | https://familyhearingpractice.com/hearing-aids/ | |
| S6 | Custom Earmolds | https://familyhearingpractice.com/custom-earmolds/ | Noise protection |
| S7 | Assistive Listening Devices | https://familyhearingpractice.com/assistive-listening-devices/ | |
| S8 | Contact Us | https://familyhearingpractice.com/contact-us/ | Booking widget, hours, maps |
| S9 | Sitemap | https://familyhearingpractice.com/sitemap/ | Confirms no tinnitus page |
| T1 | Cross Timbers Gazette, Jul 26 2026 (sponsored) | https://www.crosstimbersgazette.com/2026/07/26/family-hearing-practice-can-help-you-reconnect-with-life/ | Contains tinnitus-related patient testimonial |
| T2 | Cross Timbers Gazette, Jul 21 2023 (sponsored) | https://www.crosstimbersgazette.com/2023/07/21/better-hearing-is-now-available-in-roanoke-and-flower-mound/ | "Since 2015"; ages served |
| T3 | NPI registry listing — Dr. Allison Liberio | https://npifinder.com/1427323310/allison-marie-liberio | Credential AuD, CCC-A; TX license |
| T4 | Older CTG sponsored articles | crosstimbersgazette.com (?p=25427, ?p=33743) | Outdated address (2913 Corporate Circle) — do not use for location |

---

## 1. COMPANY SUMMARY

- **What it is:** An audiology practice owned and operated by Dr. Allison Liberio, based in Flower Mound, TX, with a second location in Roanoke, TX. [SITE S2]
- **Specialization (as self-described):** Auditory evaluations and hearing aid customizations. [SITE S2]
- **Who it serves:** Patients of all ages — newborns and young children through adults and seniors; welcomes patients from across the Dallas/Fort Worth area. [SITE S3, S8]
- **Primary services (site navigation):** Hearing tests (adult + pediatric diagnostics), hearing aids (selection, fitting, adjustments, maintenance/repair), assistive listening devices, custom earmolds (hearing protection, swim molds, musician monitors). [SITE S2, S9]
- **Tinnitus positioning on site:** Homepage states the practice has a reputation for helping patients resolve hearing loss, tinnitus, and hearing aid difficulties; the site meta description lists "tinnitus treatment" among services. [SITE S2]
- **Other specialties referenced in bios:** Pediatric audiology, cochlear implants, osseointegrated/bone-conduction devices, Tinnitus Retraining Therapy (TRT), misophonia, hyperacusis. [SITE S3]
- **Locations:**
  - Flower Mound — 4491 Long Prairie Rd #400, Flower Mound, TX 75028 [SITE, BRIEF]
  - Roanoke — 100 Country View Dr Suite 200, Roanoke, TX 76262 [SITE]

---

## 2. SERVICE / TOPIC RESEARCH — TINNITUS

> ⚠️ No standalone tinnitus page exists. Everything below is assembled from bios, homepage statements, and the hearing-test page. Gaps are explicitly marked.

### 2.1 Service description
- **Verified:** Dr. Cristina Reddy is certified to administer Tinnitus Retraining Therapy (TRT) and can treat tinnitus, misophonia, and hyperacusis. [SITE S3]
- **Verified:** Dr. Rachel Frederick's adult services include tinnitus retraining therapy (alongside hearing aid fittings, bone-conduction devices, cochlear implants). [SITE S3]
- **Verified:** Practice-level reputation for helping patients resolve tinnitus issues. [SITE S2]
- **Verified:** Site SEO meta description lists "tinnitus treatment" as a service. [SITE S2 meta]
- **Verified (sponsored):** Practice offers "support for tinnitus (ringing in the ears)" for patients of all ages. [3P-SPONSORED T1]
- **NOT on site:** Any description of what a tinnitus appointment, tinnitus assessment, or TRT program involves at this clinic.

### 2.2 Conditions / problems addressed
- Tinnitus (ringing/buzzing in the ears) [SITE S2, S3, S4]
- Hyperacusis and misophonia (sound-sensitivity conditions) — Dr. Reddy [SITE S3]
- Hearing loss (often co-presenting; noise-induced, age-related, trauma to the ears listed as hearing issues the practice treats) [SITE S2]

### 2.3 Symptoms mentioned on the site
- "Ringing or buzzing in your ears (tinnitus)" listed as a sign you may need a hearing test. [SITE S4]
- Adult hearing-test section groups: trouble hearing conversations, ringing in the ears, ear pressure, dizziness — described as possible signs of an underlying hearing or balance issue that should be evaluated by an audiologist. [SITE S4]
- Other hearing-loss signs on the same list (often co-occurring): asking people to repeat, difficulty in noise, high TV volume, phone difficulty, people seem to mumble, avoiding social situations, family history. [SITE S4]
- ⚠️ Balance/vestibular services are **not** listed anywhere on the site. Do not imply dizziness treatment.

### 2.4 Benefits mentioned
- **Tinnitus-specific benefits: NONE stated on site.**
- Practice-level benefits that can be used truthfully: personalized hearing evaluations; customized treatment plans aligned with lifestyle; education and ongoing support; advanced diagnostic technology; long-term hearing health management. [SITE S3]
- Testimonial evidence (sponsored article): a patient reports Dr. Liberio calmed her nerves and gave her tips for coping with tinnitus during a sudden hearing-loss episode. [3P-SPONSORED T1] — see §3 and §7 for handling.

### 2.5 Treatment / service process (closest verified pathway)
The site documents the **hearing evaluation** process; it does not document a tinnitus-specific protocol.
1. **Comprehensive hearing evaluation** — identifies hearing loss, determines its cause, informs treatment recommendations; guides patients toward medical attention or hearing aids as appropriate. [SITE S4]
2. **Adult tests performed:** Tympanometry (middle-ear/eardrum function), Speech Recognition Threshold, Pure-Tone Audiometry (degree/type/location of hearing loss; whether medical treatment may help), Word Recognition Testing. [SITE S4]
3. **Duration:** typically 30–60 minutes. **Comfort:** safe, non-invasive, painless. **Results:** reviewed during the same appointment with next steps discussed. [SITE S4 FAQ]
4. **Personalized recommendations** based on concerns, lifestyle, goals. [SITE S3]
5. **Coordination with physicians:** Dr. Liberio partners with the patient and their primary care doctor. [SITE S3] Sponsored content adds coordination with ENT surgeons in the Flower Mound/Denton area. [3P-SPONSORED T4 — older article] Testimonial in T1 describes results sent to an ENT for an emergency visit.
6. **Management options available at practice level** — linking these to tinnitus is **[INFERRED]** except TRT:
   - Tinnitus Retraining Therapy (verified as offered by Dr. Reddy / Dr. Frederick) [SITE S3]
   - Hearing aids, if hearing loss is present [SITE S5] — ⚠️ site does NOT claim hearing aids help tinnitus
   - Custom hearing protection for noise exposure [SITE S6] — ⚠️ site does NOT claim earmolds treat tinnitus
   - Ongoing support and follow-up [SITE S3, S5]

### 2.6 Technologies / techniques / procedures
- **Verified:** TRT (named only; not described). [SITE S3]
- **Verified:** Tympanometry, SRT, pure-tone audiometry, word recognition testing; pediatric OAE, VRA, CPA, sound booth testing. [SITE S4]
- **Verified (general):** "modern diagnostic equipment"; "advanced hearing technology." [SITE S3]
- **NOT on site:** Tinnitus pitch/loudness matching, tinnitus questionnaires, sound generators, tinnitus-masking hearing aid features, apps, or any branded tinnitus program.
- Hearing-aid brands: a "Brands We Work With" carousel exists on S5 but logos did not extract as text. Assistive-device imagery shows Phonak, ReSound, and Roger products [SITE S7 images] — brand relationships **not confirmed in text**.

### 2.7 Provider qualifications relevant to tinnitus
| Provider | Relevant facts | Source |
|---|---|---|
| **Dr. Cristina Reddy, AuD** | Certified to administer TRT; treats tinnitus, misophonia, hyperacusis. AuD — University of Texas at Dallas; BS Biology + MS Communication Science & Disorders — Texas Woman's University. Former teacher of the deaf. Full diagnostic testing for all ages; passionate about pediatrics; hearing aids, osseo-devices, cochlear implants. Fluent English & Spanish; capable in ASL. | [SITE S3] |
| **Dr. Rachel Frederick, AuD** | Offers tinnitus retraining therapy to adult patients. AuD — University of Cincinnati (2023); BS magna cum laude — UW-Eau Claire (2018); capstone on auditory processing in older adults. Lives in Northlake. | [SITE S3] |
| **Dr. Allison Liberio, AuD** (owner) | Founded the practice; 5 years at a DFW ENT practice before founding; bachelor's + doctorate from University of North Texas; has taught Audiology at UNT (fall 2018) and guest-lectures/mentors. Partners with patients' primary care doctors. Credential "AuD, CCC-A" and active Texas audiology license appear in NPI registry. No tinnitus-specific certification stated. | [SITE S3]; credential [3P-DIRECTORY T3] |
| **Scott O'Leary, MS** | MS Audiology, University of North Texas (1990); degree in Habilitation of the Deaf, TCU. Site says 25 years practicing in DFW; sponsored article says 30+ years — **inconsistent; do not quote a year figure without confirmation.** Not "Dr." No tinnitus-specific credential stated. | [SITE S3]; [3P-SPONSORED] |
| **Dr. Sara Ennis, AuD** | AuD — University of Oklahoma HSC; BS — Oklahoma State. Interests: hearing aid technology, osseointegrated devices, cochlear implants for adults. Humanitarian outreach (Yucatán). No tinnitus-specific credential stated. | [SITE S3] |

⚠️ Location assignment for every provider: **not stated**.

### 2.8 Suitable candidates (where supported)
- Anyone noticing ringing or buzzing in the ears → site recommends a hearing evaluation. [SITE S4]
- People with sound sensitivity (hyperacusis, misophonia) → Dr. Reddy treats these. [SITE S3]
- Adults (TRT via Dr. Frederick's adult-focused practice). [SITE S3]
- Children: practice serves all ages and Dr. Reddy treats tinnitus and works with all ages; **pediatric tinnitus care is not explicitly stated** — [INFERRED], confirm before claiming.
- Existing hearing-aid wearers (practice works with aids purchased elsewhere). [SITE S5]
- Noise-exposed individuals seeking protection (hunters, musicians, industrial workers, noise-sensitive individuals). [SITE S6]

### 2.9 Limitations, caveats, disclaimers
- **No cure, outcome, or success-rate claims for tinnitus exist anywhere in client sources.** Do not write "eliminate," "stop," "cure," or "silence" tinnitus.
- Site states hearing aids do not cure hearing loss (they improve hearing/communication). [SITE S5] Apply the same honesty standard to tinnitus.
- Some concerns may require medical attention rather than devices. [SITE S4]
- Sudden-onset hearing changes: the T1 testimonial shows the clinic treated sudden hearing loss as urgent and referred to ENT. Any "seek prompt care" language should be client-approved. [3P-SPONSORED T1]
- [EXTERNAL-GENERAL — for Codex awareness only, not page copy]: TRT is generally described as a habituation approach combining counseling and sound therapy; it aims to reduce the reaction to tinnitus rather than eliminate the sound. This is the reason outcome language must stay at "manage / reduce how much it bothers you"-level and be approved by the client.

### 2.10 Patient education points (supported)
- Tinnitus = ringing or buzzing in the ears; it is a recognized reason to get a hearing evaluation. [SITE S4]
- Hearing loss often develops gradually and early signs are easy to miss. [SITE S4]
- Hearing evaluation looks at full ear health and hearing comprehension, not just hearing level. [SITE S2]
- Noise exposure (hunting, music, industrial work) is a hearing risk; custom protection reduces harmful exposure. [SITE S6]
- Regular evaluations are recommended even for existing hearing-aid users. [SITE S4]

### 2.11 Especially persuasive facts
1. Team includes an audiologist **certified to administer TRT** who also treats misophonia and hyperacusis. [SITE S3]
2. **Multiple Doctors of Audiology** on staff (Liberio, Reddy, Frederick, Ennis) plus MS audiologist O'Leary. [SITE S3]
3. Owner's **5-year ENT practice background** and stated coordination with primary care physicians. [SITE S3]
4. **632 Google reviews** displayed with 5 stars on the site widget. [SITE S2] (confirm via screenshots)
5. Evaluation is **painless, 30–60 minutes, results same visit.** [SITE S4]
6. **Spanish-speaking audiologist** (Dr. Reddy). [SITE S3]
7. Real patient account (sponsored article) describing calm, reassuring care and tinnitus coping tips. [3P-SPONSORED T1]

---

## 3. TRUST SIGNALS

| Signal | Detail | Source & context | Status |
|---|---|---|---|
| Years in business | Serving Flower Mound "since 2015" | T2 sponsored article (2023) | ⚠️ Not on client site — confirm before use |
| Google reviews | 5 stars displayed, **632 Google reviews** | S2 homepage Trustindex widget | ✅ Site-verified count; exact decimal rating unverified — use supplied screenshots |
| Older review figures | 5-star rating, 459–464 reviews | reviews.nextadagency.com (older snapshots) | ❌ Outdated — do not use |
| Credentials | AuD degrees: Liberio (UNT), Reddy (UT Dallas), Frederick (U. Cincinnati), Ennis (OU HSC); O'Leary MS (UNT) | S3 About Us | ✅ |
| CCC-A | Dr. Liberio "AuD, CCC-A" | T3 NPI registry | ⚠️ Not on client site — confirm before display |
| Certification | Dr. Reddy certified to administer TRT | S3 | ✅ Key tinnitus trust signal |
| Clinical background | Dr. Liberio: 5 years at DFW ENT practice before founding | S3 | ✅ |
| Academic involvement | Dr. Liberio taught a UNT Audiology course (fall 2018), guest lectures, mentors students | S3 | ✅ |
| Physician coordination | Partners with patient's primary care doctor | S3 | ✅ (ENT coordination: sponsored/older only) |
| Number of locations | 2 — Flower Mound and Roanoke | S2, S8 | ✅ |
| Ages served | Newborns → seniors; "birth to 99+" in sponsored copy | S3; T2 | ✅ (site wording) / ⚠️ "99+" sponsored only |
| Languages | English, Spanish (Dr. Reddy); ASL capable | S3 | ✅ |
| Media / recognition | "HelloNation Featured" badges for Flower Mound and Roanoke in site footer; PR Newswire syndication of a HelloNation article featuring Dr. Liberio on early signs of hearing loss (that release oddly places the practice in Southlake) | S2 footer; webull/PR Newswire | ✅ Badge on site / ⚠️ Southlake reference inconsistent |
| Local press | Multiple Cross Timbers Gazette features | T1, T2 | Sponsored content — do not present as editorial "as seen in" without client OK |
| Community involvement | Dr. Liberio active in church and community; Dr. Ennis humanitarian outreach in Yucatán; Dr. Frederick volunteer hearing screenings | S3 | ✅ (minor relevance) |
| Patient experience details | Review mentions not waiting past appointment time and a coffee/tea bar | S2 review widget (Valerie von Bergen) | ✅ Review content — location of coffee bar not specified |
| Guarantees | None found | — | ❌ Do not state any |
| Awards | None found on site | — | ❌ |
| Associations (AAA, ASHA, etc.) | None stated on site | — | ❌ |

---

## 4. LOCATION INFORMATION — FLOWER MOUND (primary)

| Item | Detail | Source |
|---|---|---|
| Address | 4491 Long Prairie Rd #400, Flower Mound, TX 75028 | SITE S2/S8; BRIEF |
| Phone (site) | (817) 997-4084 — header reads "Call Us or Text Us Today!" | SITE S2 |
| Phone (brief / campaign) | **(817) 994-4084** — ⚠️ mismatch, confirm | BRIEF |
| Fax | 817-333-1190 | SITE S2 |
| Hours | Mon–Fri 9:00 AM–5:00 PM; Saturday open only the first Saturday of the month; Sunday closed | SITE S2/S8 |
| Hours conflicts | Directory sites list 9–4:30 and Sat 9–12 | 3P-DIRECTORY — ❌ ignore, site is authoritative |
| Directions link | https://maps.app.goo.gl/BQ5WpUHKeXvXgpUD7 | SITE S2 |
| Map embed | Brief's embed uses place ID `0x864c2d5e0c146e0d:0x622de3cf6a6af62c` — **matches** the site's Flower Mound map embed and the brief's Google Reviews link (`lrd=0x864c2d5e0c146e0d:0x622de3cf6a6af62c`) | BRIEF; SITE S8 — ✅ consistent |
| Booking widget | myhearingportal.com clinic param in brief **matches** the widget on the site's Contact page | BRIEF; SITE S8 — ✅ |
| Areas served | "Flower Mound, Roanoke, and surrounding communities"; patients welcome "from across the Dallas/Fort Worth area" | SITE S2, S8 |
| Nearby towns named | Argyle, Northlake, west/south Flower Mound — but named in relation to the **Roanoke** office | 3P-SPONSORED T1/T2 — do not attach to Flower Mound page |
| Parking / access | Not provided | — |
| Outdated address | 2913 Corporate Circle #300 (older listings/articles) | T4 — ❌ do not use |
| Old domain | flowermoundfamilyhearing.com (older articles) | T4 — ❌ do not use |

**Roanoke (secondary, for reference only):** 100 Country View Dr Suite 200, Roanoke, TX 76262 · (817) 767-9970 · Mon–Thu 9–5, Fri closes at noon, Sat–Sun closed. [SITE]

---

## 5. PATIENT PROBLEMS, MOTIVATIONS & OBJECTIONS

Grounded in source material; intent interpretations tagged.

### Problems prospects are trying to solve
- Persistent ringing/buzzing in the ears and wanting to know why. [SITE S4 symptom list]
- Ringing accompanied by trouble hearing conversations, ear pressure, or dizziness. [SITE S4]
- Sensitivity to everyday sounds (hyperacusis) or strong reactions to specific sounds (misophonia). [SITE S3]
- Sudden changes in hearing with tinnitus (as in T1 testimonial). [3P-SPONSORED T1]
- Hearing difficulties affecting relationships, confidence, work, school. [SITE S3; T1 quote from Dr. Liberio]

### Desired outcomes [INFERRED from service context — not clinic promises]
- Understanding the cause; reassurance; a clear plan; feeling less bothered by the sound; better hearing if loss is present; protection from further noise damage.

### Concerns / objections and available reassurance
| Concern | Reassurance available in sources | Gap |
|---|---|---|
| "Is the test uncomfortable?" | Painless, non-invasive [S4] | — |
| "How long will it take?" | 30–60 min; results same visit [S4] | Tinnitus-specific appointment length unknown |
| "Will I be pushed into hearing aids?" | Personalized, lifestyle-based recommendations; "multiple options" (review) [S3, S2] | — |
| "Do they actually know tinnitus?" | TRT-certified audiologist; treats misophonia/hyperacusis [S3] | Provider location unknown |
| "Could this be medical?" | Evaluation determines cause; may require medical attention; coordination with primary care doctor [S4, S3] | ENT coordination only in sponsored content |
| "What will it cost / is it covered?" | Nothing on site | ❌ Pricing & insurance not provided |
| "Can it be cured?" | — | ❌ Must not claim; needs client-approved expectation language |
| "Will they be patient with me / my elderly parent?" | Reviews describe patience, kindness, thoroughness (incl. 99-year-old patient) [S2] | — |
| "Spanish speaker?" | Dr. Reddy fluent in Spanish [S3] | Location unknown |
| "Can I come on a weekend?" | First Saturday of month only [S2] | — |
| Anxiety / nerves | T1 testimonial: calming, reassuring, coping tips [T1] | Verify on Google for verbatim use |

---

## 6. FAQ SOURCE MATERIAL

Answers below are **source facts only**, not final copy. Per house rule, final FAQ wording should match the client site where the site has an answer — pull exact text from the cited URL at build time.

| # | Question | Source material available | Status |
|---|---|---|---|
| 1 | Do you treat tinnitus? | Dr. Reddy certified in TRT and treats tinnitus; Dr. Frederick offers TRT; homepage reputation for resolving tinnitus issues. [S3, S2] | ✅ Supported |
| 2 | What is Tinnitus Retraining Therapy? | Site names TRT but never defines it. | ⚠️ Needs client-approved description |
| 3 | What happens at my first visit? | Comprehensive evaluation: tympanometry, SRT, pure-tone audiometry, word recognition; personalized recommendations. [S4, S3] | ✅ (general eval) / ⚠️ tinnitus-specific steps unknown |
| 4 | How long does the evaluation take? | 30–60 minutes depending on tests. [S4 FAQ] | ✅ |
| 5 | Is testing painful? | Safe, non-invasive, painless. [S4 FAQ] | ✅ |
| 6 | Will I get results right away? | Yes — reviewed during the appointment with next steps. [S4 FAQ] | ✅ |
| 7 | What causes tinnitus / why is my ear ringing? | Evaluation identifies hearing loss and determines its cause; listed alongside pressure/dizziness as signs of possible hearing or balance issue. [S4] | ⚠️ No cause list on site |
| 8 | Can tinnitus be cured? | Nothing on site. | ❌ Do not answer with outcome claims; client must approve |
| 9 | Will hearing aids help my tinnitus? | Site: hearing aids improve hearing/communication but don't cure hearing loss. No tinnitus claim. [S5] | ❌ Do not claim tinnitus relief from hearing aids without client confirmation |
| 10 | Can you help with sound sensitivity (hyperacusis / misophonia)? | Dr. Reddy can treat both. [S3] | ✅ |
| 11 | Do you see children with ringing in the ears? | Practice serves all ages; Reddy works with all ages and treats tinnitus. [S3] | ⚠️ Pediatric tinnitus not explicit |
| 12 | My ringing started suddenly with hearing loss — what should I do? | T1 testimonial: clinic treated sudden hearing loss seriously, coordinated urgent ENT visit. [T1] Coordination with primary care. [S3] | ⚠️ Medical-urgency wording needs client approval |
| 13 | I already have hearing aids — can you help? | Yes, works with patients who already have hearing aids; adjustments, maintenance, repair. [S5] | ✅ |
| 14 | Can you help protect my hearing from noise? | Custom earplugs/monitors for hunters, musicians, workers, sleep, noise-sensitive individuals. [S6] | ✅ |
| 15 | Do I need a referral? | Not stated. | ❌ |
| 16 | Do you accept insurance / what does it cost? | Not stated on site. (Directory site Vitals lists plans — unverified, do not use.) | ❌ |
| 17 | When are you open? | Mon–Fri 9–5; first Saturday of month; Sun closed. [S2] | ✅ |
| 18 | Do you have Spanish-speaking providers? | Dr. Reddy fluent in Spanish; capable in ASL. [S3] | ✅ (location TBC) |

---

## 7. CONTENT INVENTORY

| Area | Available content | Source |
|---|---|---|
| **Hero / value proposition** | Site positioning: personalized hearing solutions from trusted audiologists; personalized treatment plans built around lifestyle; reputation for resolving tinnitus issues; Flower Mound location; Book an Appointment CTA. | S2, S3 |
| **Benefits** | Personalized evaluations; customized plans; education & ongoing support; advanced diagnostic technology; long-term management; care for all ages. (Tinnitus-specific benefits: none.) | S3 |
| **Symptoms / problems** | Ringing/buzzing; ringing + pressure + dizziness; difficulty in conversation/noise; sound sensitivity (hyperacusis/misophonia). | S4, S3 |
| **Services / treatments** | TRT; diagnostic hearing evaluation; hearing aids; assistive listening devices; custom hearing protection. | S3, S4, S5, S6, S7 |
| **Provider / about** | Five provider bios with education; owner story (ENT background, founded own practice, UNT teaching); "Why Families Choose" five-point list (Experienced Audiologists, Personalized Treatment Plans, Advanced Technology, Care for All Ages, Ongoing Support); mission statement. | S3 |
| **Process / how it works** | Adult hearing evaluation components + FAQ facts (duration, painless, same-visit results). | S4 |
| **Technology** | Tympanometry, SRT, pure-tone, word recognition; pediatric OAE/VRA/CPA; general "modern diagnostic equipment." | S4, S3 |
| **Testimonials / reviews** | Homepage widget (Google, 5 stars each): Jeff Strickland (attentive, thorough testing, multiple options — names Dr. Liberio); Deborah Nichols (short positive); Dale Bomgardner (fast, friendly, knowledgeable — names Dr. Liberio); Melissa Kisver (professional and caring); Carla Faulkner (kind, helpful, part of hearing journey); Deb Bean (patience with 99-year-old mother — names Dr. Liberio); Valerie von Bergen (on-time, coffee/tea bar, thorough audiologist); Gene Cherrnay (feels like family — names Cristina). **Tinnitus-relevant review:** T1 sponsored article quotes a patient describing sudden hearing loss, ENT coordination, restored hearing, and tinnitus coping tips from Dr. Liberio. | S2, T1 |
| **FAQs** | Hearing-test FAQ (5), hearing-aid FAQ (6), earmold FAQ (5), ALD FAQ (5) — see §6 for tinnitus-relevant subset. | S4–S7 |
| **Location** | Flower Mound address, hours, phone, fax, directions link, map embed. | S2, S8 |
| **Appointment / contact** | Booking widget (myhearingportal); "Call Us or Text Us"; GHL form (brief). | S8, BRIEF |
| **Final CTA** | Site pattern: "Schedule an appointment at our Flower Mound or Roanoke location today." | S3 |

**Review handling notes:**
- Verbatim review text must come from the Google screenshots the user will supply; do not rewrite meaning. [BRIEF]
- The T1 tinnitus testimonial is the single most topic-relevant review. Locate it on Google (or in supplied screenshots) to use verbatim with the reviewer's name; if it cannot be found on Google, it should not be presented as a Google review.
- Several reviews name specific providers (Liberio, Cristina). Fine to show; they also reinforce provider credibility.

---

## 8. BRAND EXTRACTION

| Element | Value | Source / confidence |
|---|---|---|
| Primary (CTA) | **#197fc4** | BRIEF — authoritative |
| Secondary (headline text) | **#4e3110** | BRIEF — authoritative |
| Supporting colors | Not supplied; not reliably extractable from text-only crawl | ❌ Design decision for Codex (e.g., tints/neutral backgrounds) — label as design choice, not brand fact |
| Heading font | **Outfit** | BRIEF |
| Body font | **Montserrat** | BRIEF |
| Logo (main) | https://files.leadconnectorhq.com/file/653975156a376482eea3c57b/logo-300x189.png | BRIEF (300×189 — stacked/near-landscape aspect; check header sizing) |
| Logo (white) | https://files.leadconnectorhq.com/file/64d50f8e304c101bb48e7ff4/white-logo.png | BRIEF |
| Site's own header logo | https://familyhearingpractice.com/wp-content/uploads/2026/06/horizontal-logo.png | SITE — horizontal variant; brief logos take precedence |
| Favicon | https://familyhearingpractice.com/wp-content/uploads/2026/06/cropped-cropped-favicon-192x192-1-270x270.png | SITE |
| Button style / border radius / card treatment | **Cannot be confidently determined** from page extraction (WordPress + Elementor / JupiterX theme) | ❌ Inspect visually if needed |
| Observed structural patterns | Utility top bar (Call/Text, Write a Review, Facebook, Book an Appointment); logo + 6-item nav; per-location phone numbers in header; Book an Appointment as repeated CTA label; accordion FAQs; text + paired-image two-column sections; icon-free "Why Choose" headed list; footer with both locations, hours, fax, directions | SITE ✅ |
| CTA wording used on site | "Book an Appointment", "Schedule a Hearing Test", "Call Us or Text Us Today!" | SITE ✅ (brief specifies "Book Appointment") |
| Photography style | Predominantly Adobe Stock: audiometry booth testing, otoscope exams, hearing aids in ear, product accessory shots; individual provider headshots; warm, clinical-friendly. | SITE ✅ |
| Tone | Warm, family-centered ("treat every patient like family"), patient-first, reassuring. | SITE S3; T1 |

---

## 9. IMAGE / VISUAL SOURCE INVENTORY (inventory only — nothing downloaded)

### Provider portraits (real) — SITE S3
- Dr. Cristina Reddy — https://familyhearingpractice.com/wp-content/uploads/2026/08/Cristiana-Headshot-1.jpg
- Scott O'Leary — https://familyhearingpractice.com/wp-content/uploads/2026/06/Scotts-Headshot.jpg
- Dr. Allison Liberio — https://familyhearingpractice.com/wp-content/uploads/2026/06/New-headshot.jpg
- Dr. Rachel Frederick — https://familyhearingpractice.com/wp-content/uploads/2026/06/Rachels-Headshot.jpg
- Dr. Sara Ennis — https://familyhearingpractice.com/wp-content/uploads/2026/08/Sara-Headshot-1.jpg
- Press photo of team (Liberio, Reddy, Frederick, O'Leary) — https://www.crosstimbersgazette.com/crosstimbersgazette/wp-content/uploads/2026/07/Dr_Allison_Liberio_26.jpg [3P — rights belong to publisher/client; confirm before use]

### Team / clinic
- ⚠️ "Staff in front of office" — https://familyhearingpractice.com/wp-content/uploads/2026/06/ChatGPT-Image-Jun-2-2026-11_25_25-PM.jpg (AI-image filename; see Critical Finding #5)
- Clinic exterior / interior / treatment rooms: **none found on site** → request GBP photos

### Testing / clinical (stock) — SITE
- Audiometry booth exam — .../2026/06/AdobeStock_527674545.jpeg
- Ear-anatomy consultation — .../2026/06/AdobeStock_1889007948.jpeg
- Otoscope exam (woman) — .../2026/06/79d62b0780-1.jpg
- Man at hearing checkup — .../2026/06/36f7729794.jpg
- Child otoscope exam — .../2026/06/dc3ecd1ccd.jpg
- Hearing-test service card — .../2026/06/AdobeStock_2026757424.png
- Mature man with hearing problem — .../2026/06/AdobeStock_197909117.jpeg (closest existing visual to a "symptom" image)
- Unlabeled about-page image — .../2026/06/fdf788c0a7.jpg

### Hearing aids / devices — SITE
- .../2026/06/AdobeStock_2034214640.png (homepage OG image)
- .../2026/06/662b40f58b82b058df1ff267_hearing-aid-user.webp
- .../2026/06/man-wearing-hearing-aid-1024x682-1.jpg.jpg
- .../2026/06/Day_30941-1.jpg
- Phonak accessories, ReSound wireless accessories, Roger imagery (S7)

### Hearing protection — SITE S6
- Ear impression process — .../2026/06/c3fc84c5cf-1.jpg, .../2026/06/ef9764ffef.jpg
- Molded earplug in ear — .../2026/06/c442099e26.jpg

### Badges / logos
- HelloNation Featured badge — https://familyhearingpractice.com/wp-content/uploads/2024/05/HelloNation_Featured_A.png
- Google review badge assets: will come from user-supplied screenshots [BRIEF]
- Brand logos: see §8

### Video
- Homepage embedded video: https://elocallink.tv/e/player.php?v=L76&ap=1 (content not reviewed; autoplay parameter present)

**Tinnitus-specific imagery:** none exists on site. Any tinnitus visual (e.g., person holding ear) would be new stock — flag as stock.

---

## 9A. KEYWORD & SEARCH-INTENT RELEVANCE

### Supplied inputs (verbatim from brief)
- Primary Target Keyword(s): **[NOT PROVIDED]**
- Secondary / Supporting Keyword(s): **[NOT PROVIDED]**
- Ad Group / Keyword Theme: **[NOT PROVIDED]**
- Target Location / Location Modifier: **(blank in brief)** — Flower Mound implied by brief's location and CONTENT section
- Campaign name, ad headlines, ad descriptions, promoted offer: **[NOT PROVIDED]**
- Primary conversion action: **[BOOKING]** · Source of keyword data: **[ADS TEAM]**
- Keyword Research Input Status: all **NO** → per brief, Step 2B (AI-assisted keyword discovery → KEYWORD_RESEARCH.md) is triggered as a **separate step**; no keyword candidates are recorded here.

### Mapping table
| Keyword / ad-group theme | Visitor need | Source-backed answer | Gap / caveat |
|---|---|---|---|
| [NOT PROVIDED] — service topic per brief: Tinnitus | Find a local professional for ringing/buzzing in the ears [INFERRED] | Flower Mound audiology practice; tinnitus listed among practice's areas of reputation; TRT-certified audiologist on team [S2, S3] | No tinnitus page; provider location unconfirmed |
| [NOT PROVIDED] | Understand what's causing the ringing [INFERRED] | Comprehensive evaluation identifies hearing loss and its cause; same-visit results [S4] | No tinnitus-specific assessment described |
| [NOT PROVIDED] | Find a treatment / relief option [INFERRED] | TRT offered (Reddy, Frederick); personalized plans [S3] | No outcome or efficacy claims allowed; TRT undescribed |
| [NOT PROVIDED] | Sound sensitivity help [INFERRED] | Dr. Reddy treats hyperacusis & misophonia [S3] | Secondary intent — mention, don't headline |
| [NOT PROVIDED] | Whether hearing aids help tinnitus [INFERRED] | Hearing aids available; personalized fitting [S5] | ❌ No site claim linking aids to tinnitus relief |
| [NOT PROVIDED] | Trust / proof before booking [INFERRED] | 632 Google reviews (5-star widget); AuD credentials; ENT background [S2, S3] | Rating decimal pending screenshots |
| [NOT PROVIDED] | Convenient local appointment [INFERRED] | Flower Mound address, hours, booking widget, call/text [S2, S8] | Campaign phone mismatch |
| [NOT PROVIDED] | Sudden ringing with hearing change — urgency [INFERRED] | Clinic coordinated urgent ENT care in testimonial [T1] | Sponsored source; medical-urgency wording needs approval |
| [NOT PROVIDED] | Offer/price [INFERRED] | — | ❌ No offer, price, or insurance info supplied |

### Ad copy / offer match check
- No ad copy or offer supplied → nothing to validate. If the Ads team runs offers like "free tinnitus consultation/screening," **there is no source support**; such language must not appear until confirmed (cf. prior client correction elsewhere where "free assessment" had to become "free screening").

### Search Intent & Message-Match Summary (for Codex)
- **Strongest intent [INFERRED]:** local, problem-aware visitors in/near Flower Mound with ringing or buzzing in their ears who want to find out why and what can be done, and want a credible clinic to book with.
- **Best supporting evidence:** (1) TRT-certified audiologist who also treats hyperacusis/misophonia; (2) comprehensive, painless 30–60 min evaluation with same-visit results; (3) Doctors of Audiology team + owner's ENT background + physician coordination; (4) 632 Google reviews; (5) Flower Mound address with booking widget.
- **Conflicts:** phone number (994 vs 997); provider-location unknown; "since 2015" and CCC-A only in third-party sources; Scott O'Leary experience figure inconsistent (25 vs 30+ years).
- **Unanswered:** actual keywords and ad promise; tinnitus evaluation steps; TRT program description; tinnitus device options; pricing/insurance; offer.
- **Guardrail:** Message-match the *problem* (ringing in the ears) and the *next step* (evaluation with an experienced audiology team in Flower Mound). Do not message-match an outcome ("relief," "stop the ringing") as a promise; if used, frame as goal/support language and get client approval.

---

## 10. MISSING INFORMATION (cannot be verified from available sources)

**Blocking / high priority**
1. Correct phone number for the page: (817) 994-4084 (brief) vs (817) 997-4084 (site). Also whether the campaign number accepts texts (site advertises "Call or Text" on 997).
2. Which tinnitus-trained providers (Dr. Reddy, Dr. Frederick) practice at the Flower Mound location, and on which days.
3. Client-approved description of tinnitus services: what a tinnitus evaluation includes, what TRT involves at this clinic (sessions, duration, devices), and acceptable outcome/expectation language.
4. Keywords, ad groups, ad headlines/descriptions, and any promoted offer (all [NOT PROVIDED]).
5. Google rating value and review count from the user-supplied screenshots (site shows 632; decimal rating not displayed).

**Important**
6. Whether hearing aids with tinnitus features / sound generators are offered (site does not say).
7. Pricing, insurance accepted, payment/financing options.
8. Whether a referral is required.
9. Whether children with tinnitus are seen.
10. Years in business on record ("since 2015" is from a sponsored article only).
11. Dr. Liberio's CCC-A for on-page display (NPI registry only) and any professional association memberships.
12. Scott O'Leary's correct years-of-experience figure.
13. Hearing-aid brands carried ("Brands We Work With" carousel not readable).
14. Authentic clinic photography (exterior, lobby, test booth) — none on site; GBP photos needed.
15. Confirmation that the homepage team photo (ChatGPT-named file) is not AI-generated if it's to be used.
16. The verbatim Google source of the T1 tinnitus testimonial.

**Nice to have**
17. Parking / building access details for 4491 Long Prairie Rd.
18. Brand supporting colors, button style, border-radius conventions.
19. Whether the "first Saturday of the month" schedule is still current.
20. Content of the homepage elocallink video.

---

## APPENDIX — TECHNICAL NOTES CARRIED FORWARD FROM BRIEF REVIEW
- **Booking widget** (popup, primary CTA): clinic param verified identical to the live Contact page widget. ✅
- **GHL form**: rename iframe id `inline-We5C6Wk3loKV4pUwY0Kp` → `formEmbed-We5C6Wk3loKV4pUwY0Kp` (and `data-layout-iframe-id` to match) to avoid GHL autoscroll; load `form_embed.js` exactly once; verify 415px height doesn't clip submit.
- **Map**: brief's `pb=` embed matches the site's Flower Mound embed/place ID ✅ — do not modify the `pb=` string; handle responsiveness via CSS container only. "Get Directions" target: https://maps.app.goo.gl/BQ5WpUHKeXvXgpUD7 (site's own directions link).
- **Footer**: `© {current year} {{location.name}} | All rights reserved.` — `{{location.name}}` is a GHL merge field; leave as-is.
- **Privacy link**: https://familyhearingpractice.com/privacy-policy-and-website-terms-of-use/ ✅ (present in site footer).
