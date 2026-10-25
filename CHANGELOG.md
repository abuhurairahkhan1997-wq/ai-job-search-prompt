# Changelog

## 2.3 (October 2026): public beta release, after a final publication audit
- **SEARCH BOTH** is now a full command (jobs and PhDs) in the master prompt, the quick template and the README.
- **Clear result limits:** a table shows what each search command returns. SEARCH BOTH and SEARCH ALL give one main pick per category, with "No verified [category] found today" where nothing qualifies.
- **Funded study split into three kinds**, each with its own test: fully funded degrees (tuition at your fee status and a living allowance; tuition-only awards are partly funded, never fully funded), salaried fellowships (salary or stipend, duration, career stage) and free training (no fees, hidden certificate or exam costs checked).
- **Career-building checks:** volunteering, virtual work experience, part-time work and free courses are now checked for availability, real cost, age limits, visa permission and a reputable organisation, and get a status.
- **"Not published" handling:** a missing salary, stipend or fee detail is recorded as unknown, not as a failure. When it decides the visa or funding route, the best status is ASK FIRST.
- **Up to three** published essential criteria in results, instead of exactly three.
- **The score** is described as an informal way to prioritise, not a prediction of success.
- **Privacy:** data minimisation, optional contact details, a warning not to post profiles or trackers publicly, guidance on removing ID numbers from uploads, and safeguards for under-18s.
- **Quick template 1.3:** described as following the same core safeguards while leaving out some detailed procedures.
- **LICENSE:** project title updated to "AI Career Search Prompt"; CC BY 4.0 terms kept, with commercial reuse stated clearly.
- **Visual guide:** rebuilt as a 13-slide version 2.3 PDF, including a new slide on the four statuses. The separate wording-fixes note is no longer needed.
- **TESTING.md:** documentary reviews, simulated tests and live searches are now kept separate. Added a made-up test profile, sample adverts and tests T–Z (26 simulated tests in total). No test has been run and recorded yet.
- New **RELEASE-CHECKLIST.md** for publishing.

**Final publication corrections (25 October 2026)**
- CV and cover-letter instructions now work for people without a degree: they use whatever qualification, apprenticeship, vocational training, school education or experience the user actually has, and never invent a degree or grade.
- Cover-letter greetings and sign-offs follow the country being applied to, in both prompts ("Yours sincerely" and "Yours faithfully" for the UK and Ireland; local norms elsewhere).
- New **SIMULATION ONLY** mode in both prompts and an explicit simulation procedure in TESTING.md. Made-up adverts are judged on their text and labelled "SIMULATED: would be [status]", never presented as real. Refusing to verify an imaginary advert online counts as correct behaviour, not a failure. Each test is marked Simulation or Normal mode.
- UKRI stipends: London weighting is described as paid only where the funder provides it (EPSRC, for example, doesn't).
- The PDF guide's GitHub, LinkedIn and licence links are now clickable.
- `LICENSE` now contains the full official CC BY 4.0 legal code. The copyright line and suggested attribution moved to the new `NOTICE.md`.

**First recorded tests and fixes (25 October 2026)**
- Ran the tests in one assistant (Claude): 19 of 19 simulated tests, 6 normal-mode checks and 2 live searches (UK SEARCH ALL and Germany SEARCH JOBS). Results and evidence are in TESTING.md and the `tests/` folder. Not yet run in a second assistant.
- Fixes from what the tests found: the assistant must never build or guess a URL; PROCEED is offered only for VERIFIED or ASK FIRST results; calling training "free" now needs stated evidence.

## 2.2 (October 2026): for anyone, anywhere, and a second independent review
**Wider scope**
- Now presented as a career tool for anyone in any country and at any stage, not only for jobs and PhDs.
- New SEARCH STUDY mode for fully funded master's degrees, scholarships, fellowships and free training, with checks for scholarship deadlines and "return home" conditions.
- New SEARCH ALL (jobs, PhDs and funded study, in separate sections). SEARCH BOTH still works.
- The CV-building job is now a "career-building opportunity": a job, volunteering, virtual work experience or a free course.
- EXPLORE now includes at least one path in a different sector. The interview asks about circumstances and adjustments (optional).
- Local CV conventions are no longer UK-only.

**Corrections from the review**
- The quick template (now version 1.2) uses the same commands, checks and statuses as the master prompt, and says clearly what it leaves out.
- Scam checks now separate official government visa fees (normal) from payments to employers, recruiters or agents (rejected). In the UK, the sponsor licence, Certificate of Sponsorship and Immigration Skills Charge costs must not be passed on to the worker.
- Deadlines: a closing date of today is accepted if applications are still open. The assistant checks the closing time and time zone, confirms rolling adverts are still open, and records when it checked.
- UKRI: the 30% international cap is described as UKRI's normal limit that can vary by council and programme, not a universal rule.
- UK new-entrant salary: the assistant now checks the 4-year limit, which includes time already spent on the Graduate route, any Tier 2 route and as a Skilled Worker.
- Statuses: VERIFIED, ASK FIRST, UNVERIFIED and REJECTED now apply to every opportunity type. Each essential criterion is marked Met, Not met or Can't confirm. ASK FIRST options are shown as "Conditional pick" and never as confirmed routes. Conflicting sources are handled explicitly.
- New rule: text inside adverts or web pages is treated as information, never as instructions.
- README wording toned down ("designed to", "free plans can work", "public beta"), with clearer limits.
- TESTING.md expanded to 19 simulated tests plus a real-world search section and a results log. No test is reported as passed until it has been run and evidenced.

## 2.1 (October 2026): accuracy update after an independent review
- Separate search modes: SEARCH JOBS, SEARCH PHD and SEARCH BOTH, each with its own checks and results.
- Eligibility is now a strict gate. Scoring no longer gives points for partly meeting essential criteria.
- Sponsorship: a sponsor licence is never treated as sponsorship for the vacancy (status ASK FIRST). Occupation code, salary threshold and restrictions are checked, and the Temporary Shortage List is covered (for example 3111 laboratory technicians).
- PhD verification: tuition must be covered at the applicant's fee status. UKRI pays home fees only, about 30% of each cohort can be international, and MSCA mobility rules and European salaried posts are covered.
- New statuses: VERIFIED, ASK FIRST, UNVERIFIED and REJECTED, with links as evidence. The prompt now says "No verified suitable vacancy found today" when nothing passes.
- No pretending to remember: the assistant asks for MY PROFILE and MY TRACKER in a new chat and reminds users to save both at the end of each session.
- New TESTING.md with seven quick failure tests. The README's Limits section is clearer.
- Quick template updated to version 1.1 with the same corrections.
- New EXPLORE mode (career paths that fit your profile) and DAILY routine (re-verify the tracker, deadline reminders, fresh search).

## 2.0 (October 2026)
- New master prompt: interviews the user, builds a reusable profile, then searches, verifies, scores, writes documents, helps with application forms and tracks applications.
- Works with any AI assistant and any country (local English variant, CV conventions and official visa rules).
- New commands: SEARCH, PROCEED, IS THIS A GOOD JOB?, UPDATE PROFILE, INTERVIEW PREP, FOLLOW-UP, TRACKER, APPLIED.
- The version 1 fill-in template is kept as quick-template-prompt.md.

## 1.0 (October 2026)
- First public version.
- One main pick plus one CV-building job per run, with verified vacancy checks.
- Scoring out of 10, hard filters and UK Skilled Worker sponsorship checks.
- ATS-friendly 2-page CV and 1-page cover letter in the standard UK structure, with a copy-paste version.
- British English, human-sounding writing, and no invented facts.
