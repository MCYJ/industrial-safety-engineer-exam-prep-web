# Industrial Safety Engineer Exam Prep Web — Project Context

## Scope and ownership

- Marketing and study site for released catalog app `KOR-0048` only.
- Source app identity was read from `/Users/youngjunma/Documents/various test prep apps project/services/kor/00/kor-0048`; that source directory remains unmodified.
- Website repository: `industrial-safety-engineer-exam-prep-web`.
- Android package and iOS bundle: `app.mcyj.examprep.kor0048`.
- No cross-promotion of other RushLabs apps.

## Verified public identity

- Google Play: `https://play.google.com/store/apps/details?id=app.mcyj.examprep.kor0048` returned HTTP 200 on 2026-09-18.
- Apple lookup returned one matching app with track ID `6797288640`, version `1.0.1`, on 2026-09-18.
- App Store link: `https://apps.apple.com/kr/app/id6797288640`.

## Official-source boundaries

- Q-Net item code: `1431`.
- Current Q-Net structure checked 2026-09-18: six written subjects, 20 items and 30 minutes each; combined practical listed as written response 60 minutes/55 points plus task approximately 60 minutes/45 points.
- Written pass rule: 40 or higher in every subject and 60 or higher average. Practical pass rule: 60 or higher.
- The site links to the Q-Net qualification page, exam details, fee/subject page and the 2024–2026 official specification.
- Schedules, fees, eligibility and specifications can change; current Q-Net instructions control.

## Product and design

- Bilingual Korean/English static site with ten independently written guides per locale, FAQ, privacy, terms, support and contact routes.
- Safety-mint system: `#F7FCFB`, `#CDECE5`, `#75B7AA`, `#39796F`, ink `#203735`.
- Hazard-identification visual language uses diagonal risk markings and identify-assess-control sequencing.
- Global `word-break: keep-all` with emergency wrapping only for long URLs and email addresses.
- Google Play and App Store controls use a shared 194×75 frame while preserving each official badge asset's aspect ratio.

## Work log

- 2026-09-18: Created the isolated site workspace from the established static-site structure, replaced all exam content with KOR-0048-specific material, added the safety-mint visual direction, and verified the exact released Store identities.
- 2026-09-18: Local build/check passed for 36 HTML files and 34 indexable routes. Local route QA returned HTTP 200 for every sitemap route and four required assets, with HTTP 404 for an unknown route.
- 2026-09-18: Created public repository `MCYJ/industrial-safety-engineer-exam-prep-web`. The first deployment run `35359090141` failed only because Pages was not yet enabled; Pages was then enabled with GitHub Actions as the build source.
- 2026-09-18: GitHub Pages deployment run `35359133328` passed. Production QA returned HTTP 200 for all 34 sitemap routes and four required assets, HTTP 404 for a missing route, confirmed deployed `word-break: keep-all` and shared Store badge frames, Google Play HTTP 200, and Apple lookup result count 1 with exact track ID `6797288640` and bundle ID `app.mcyj.examprep.kor0048`.
