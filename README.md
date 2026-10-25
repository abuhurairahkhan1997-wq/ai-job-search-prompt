# AI Career Search Prompt: jobs, PhDs and every kind of opportunity

> **PUBLIC BETA · Version 2.3.** It is designed to check every opportunity it suggests, but AI assistants can still make mistakes. Always open the link yourself before you apply.

A free, copy-and-paste prompt for **anyone, anywhere in the world**, at any stage of their career. Paste it into an AI assistant (Claude, ChatGPT, Gemini, Copilot, DeepSeek, Grok and others) and it becomes an honest career coach that is designed to:

- help you **work out which career suits you**, even if you're not sure yet
- find **real, currently open opportunities**: jobs, apprenticeships, internships, graduate schemes, fully funded PhDs, fully funded degrees, salaried fellowships, volunteering and free training
- **check each one** before recommending it
- help you **apply** with a tailored, ATS-friendly CV, cover letter or personal statement in your country's language and conventions

I built it for my own search in the UK life sciences sector as an international graduate, and I'm sharing it so others can find their careers too.

## Who it's for
School leavers, students, graduates, career changers, people returning to work, people building a career in a new country, and experienced professionals. It adapts to your country, your visa or fee status, your field and your level.

## What it does
- **Interviews you** and builds your own reusable profile, so it only uses facts you have given it.
- **EXPLORE:** suggests 3–5 realistic career paths that fit your profile, with keywords and free ways to close gaps.
- **Search modes:** SEARCH JOBS, SEARCH PHD, SEARCH STUDY, SEARCH BOTH (jobs and PhDs) or SEARCH ALL (all three). Combined searches give one main pick per category.
- **Each search** also gives one career-building opportunity you can do now (a job, volunteering, virtual work experience or a free course), checked for cost, age limits and visa restrictions.
- **Visa checks (if you need sponsorship):** designed to check the employer's licence, the likely occupation code, the salary threshold and any time limits. It treats "this employer holds a licence" and "this job offers sponsorship" as different things, and won't confirm a visa route when the salary isn't published.
- **Funding checks:** separate tests for fully funded degrees (tuition at your fee status **and** a living allowance), salaried fellowships (salary or stipend) and free training (no hidden fees).
- **Scam checks:** flags anyone asking you to pay for a job, training or a sponsorship certificate, while recognising that official government visa fees are normal.
- **Clear statuses:** VERIFIED, ASK FIRST, UNVERIFIED or REJECTED, with links as evidence. If nothing passes, it says so instead of padding the list.
- **Score out of 10:** an informal way to prioritise, not a prediction of whether you'll get an offer or place.
- **Documents (only after you say PROCEED):** CV, cover letter, personal statement and a copy-paste version, following your country's conventions. No degree? It leads with your experience, apprenticeship, training or school qualifications, and never invents a qualification or grade.
- **Applying and tracking:** helps with form questions from screenshots, and keeps a tracker you save and paste back in.
- **Never applies for you** or sends emails on your behalf.

## How to use it (2 minutes, plus a 10–15 minute interview the first time)
1. Open [`master-job-search-prompt.md`](master-job-search-prompt.md) and click **Copy raw file** (the copy icon at the top right).
2. Paste it into your AI assistant. **Switch on web search** if it offers it.
3. Answer the interview questions. The assistant builds **MY PROFILE**. **Copy and save it** in a private note or document.
4. Type a command, for example **EXPLORE**, **SEARCH JOBS** or **SEARCH ALL**.
5. Type **PROCEED** and the opportunity's name to get tailored documents. Send screenshots of application forms for help, and type **APPLIED** when you have submitted.
6. At the end of each session, save the updated **MY PROFILE** and **MY TRACKER** privately. In a new chat, paste the prompt plus both.

**Commands:** EXPLORE · DAILY · SEARCH JOBS · SEARCH PHD · SEARCH STUDY · SEARCH BOTH · SEARCH ALL · PROCEED · IS THIS A GOOD OPPORTUNITY? · UPDATE PROFILE · INTERVIEW PREP · FOLLOW-UP · APPLIED · TRACKER

**Prefer to fill in your details yourself?** Use the shorter [`quick-template-prompt.md`](quick-template-prompt.md). It follows the same core safeguards, commands and statuses, but it leaves out some detailed procedures: the interview, EXPLORE, DAILY, UPDATE PROFILE, form help, interview preparation, follow-up messages, the full tracker table and some step-by-step checks.

## Your privacy
- **Share only what you need.** Town or city and country is enough for location. Contact details are optional until you want application documents.
- **Never share** passwords, bank details, or passport or national ID numbers with any AI. Remove them from any CV or screenshot before you upload it.
- **Keep your profile and tracker private.** Don't post them in a public GitHub repository, a public document or a shared chat link. If you fork this repository, don't commit your personal profile to it.
- **Personal circumstances** (such as a disability or caring responsibilities) are always optional.
- **Under 18?** Follow your AI assistant's age rules, and ask a parent, carer, teacher or careers adviser to help you. Don't share your home address, phone number or full date of birth.

## Which assistant and plan?
- Any assistant that follows long instructions can run it. **Free plans can work**, but they often limit messages, file uploads and web search, and these limits change. Check what your plan includes.
- **Web search matters most.** Without it, the assistant can't find live opportunities, so paste adverts in yourself and use IS THIS A GOOD OPPORTUNITY?
- Image upload helps with form screenshots. Projects or memory features can keep your profile, but keep your own private copy anyway.

## Visual guide
New to this? Read the 13-slide [visual guide (PDF)](AI_Job_and_PhD_Search_Prompt_Guide.pdf): how it works, the four statuses, which AI to use, tips, limits and staying safe.

## Limits (please read)
- **This is a public beta.** It is designed to verify opportunities, but results depend on your assistant's browsing and how well it follows instructions, and they can vary between assistants and days. **Always open the link yourself** and check the closing date, criteria and funding.
- **Testing so far:** besides independent documentary reviews, the tests in [`TESTING.md`](TESTING.md) were run in **one assistant (Claude)** on 25 October 2026: 19 of 19 simulated tests and 2 of 2 live searches passed, with a few small fixes made afterwards. They have **not** yet been run in a second assistant, so results elsewhere may differ. Simulated tests use made-up adverts in **SIMULATION ONLY** mode, so they are never mistaken for real vacancies.
- **Live searches use a lot of messages.** A full SEARCH ALL can involve 30–40 web searches and page opens. On a free plan, run one search command at a time.
- **Saving your profile and tracker is up to you.** Many assistants don't remember past chats. Saving your tracker is what prevents repeated recommendations.
- **Country rules differ.** The most detailed visa and funding examples are for the UK and EU. For other countries, the prompt tells the assistant to use official government and funder sources, but you should check them too.
- **This is not legal, immigration or financial advice.** Visa and funding rules change. Confirm them on official sources (in the UK, [GOV.UK](https://www.gov.uk/skilled-worker-visa) and [UKRI](https://www.ukri.org)) or with a qualified adviser.

## Tips
- Keep your profile accurate and up to date (UPDATE PROFILE). The AI may only use what is in it.
- Type **APPLIED** (or send your confirmation screenshot) after each application.
- Read every document before you send it, and add a personal touch in your own words.
- Never pay anyone for a job offer.

## Files in this repository
| File | What it is |
|---|---|
| `master-job-search-prompt.md` | The full prompt (start here) |
| `quick-template-prompt.md` | Shorter fill-in version |
| `AI_Job_and_PhD_Search_Prompt_Guide.pdf` | 13-slide visual guide |
| `TESTING.md` | Tests anyone can run, and the results log |
| `CHANGELOG.md` | What changed in each version |
| `LICENSE` | Full CC BY 4.0 legal code |
| `NOTICE.md` | Copyright and how to credit this project |

## Updates and feedback
I update this prompt as I learn what works. See [`CHANGELOG.md`](CHANGELOG.md). Click **Watch** or **Star** to follow changes. If a test fails or something goes wrong, open an issue and say which assistant you used (please don't include personal data).

## Licence
Free to use, share and adapt, including commercially, with credit, under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). The full legal code is in [`LICENSE`](LICENSE), and [`NOTICE.md`](NOTICE.md) shows how to credit this project. Only I can edit this repository. To make your own version, copy the prompt or fork the repository, credit the original and say what you changed.

---
Made by **Abuhurairah Rahman Pathan**, MSc Bioinformatics, University of Liverpool · [LinkedIn](https://www.linkedin.com/in/pathan-abuhurairah-rahman-1997-khan) · [GitHub](https://github.com/abuhurairahkhan1997-wq)
