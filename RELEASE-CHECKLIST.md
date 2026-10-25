# Release checklist: version 2.3 public beta

Tick each item before you announce the release. Times are rough.

## A. Upload the files to GitHub (15 min)
Repository: `github.com/abuhurairahkhan1997-wq/ai-job-search-prompt`. Use exactly these file names:
- [ ] `README.md`
- [ ] `master-job-search-prompt.md`
- [ ] `quick-template-prompt.md`
- [ ] `AI_Job_and_PhD_Search_Prompt_Guide.pdf` (the new 13-slide version 2.3)
- [ ] `TESTING.md`
- [ ] `CHANGELOG.md`
- [ ] `LICENSE` (no file extension, no number in the name; contains the full CC BY 4.0 legal code)
- [ ] `NOTICE.md` (copyright and suggested attribution)
- [ ] `RELEASE-CHECKLIST.md` (optional; you can keep this private)
- [ ] `tests/` folder (test scenarios and results; made-up profile only)
- [ ] Delete `PDF-guide-wording-fixes.md` if you uploaded it earlier. The new PDF replaces it.
- [ ] Delete the old 12-slide PDF if it has a different name.
- [ ] No personal profile, tracker, CV or certificate is in the repository.

## B. Check the published repository (10 min)
- [ ] Open the repository in a private browser window, signed out. It loads and is public.
- [ ] Every link in README.md opens the right file.
- [ ] "Copy raw file" on master-job-search-prompt.md copies the whole prompt.
- [ ] The PDF opens, has 13 slides and shows "Public beta · Version 2.3" on slide 1.
- [ ] The GitHub link on slide 13 is clickable and opens the repository.
- [ ] The GitHub link on the last slide of the PDF matches the real repository address.
- [ ] GitHub shows the licence as CC BY 4.0 in the sidebar.

## C. Run the tests (about 1–2 hours in total)
- [x] Tests in TESTING.md in **Assistant 1** (Claude), 25 Oct 2026: done and recorded (test Q and separate SEARCH commands still to run).
- [ ] Tests A–Z in **Assistant 2** (for example ChatGPT or Gemini).
- [ ] Live SEARCH JOBS, SEARCH PHD and SEARCH STUDY in both assistants.
- [ ] One live search with a non-UK country.
- [ ] Every result checked against the official application page.
- [ ] Results logged in TESTING.md with evidence (screenshots or shared links, with personal data removed).
- [ ] Anything that failed: fix the prompt, note it in CHANGELOG.md, and re-test.

You can publish the public beta before section C is finished, because README.md and TESTING.md say exactly which tests have and haven't been run.

## D. Announce it (20 min)
- [ ] LinkedIn post: use the words **Free Public Beta**, never "Fully Verified". Say what it does, who it's for, and invite feedback.
- [ ] Don't claim it is "fully tested", "verified" or "always accurate".
- [ ] Attach the PDF guide or a slide image, and link to the repository.
- [ ] Ask people to open a GitHub issue if something goes wrong, without personal data.

## E. After release (ongoing)
- [ ] Re-check UK figures (salary thresholds, UKRI stipend) whenever GOV.UK or UKRI updates them.
- [ ] Add test results to TESTING.md as they come in.
- [ ] Move out of beta only after both assistants pass the simulated tests and the live searches are documented.
