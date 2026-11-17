# Learning & Talent Study Lab

One self-contained HTML app in the same sidebar-based format as the earlier Extend and Integration study apps. No installation, build command, API key, account, or server is required for local use.

## Open the app

1. Extract this ZIP.
2. Open `index.html` in Chrome, Edge, Firefox, or Safari. The separately supplied `Workday_Learning_Talent_Study_App.html` is the same app; rename it to `index.html` if you use that download for GitHub hosting.
3. Choose **Learning** or **Talent & Performance** in the subject selector.

All questions and explanations are embedded in `index.html`, so local study works offline. External reference links need internet access and may require your Workday credentials.

## Questions included

| Collection | Entries |
|---|---:|
| Learning original question bank, including 20 supplied samples | 150 |
| Talent original question bank, including 20 supplied samples | 150 |
| Talent business-process scenario bank | 200 |
| New Talent reference-based question bank | 300 |
| Total source entries | **800** |

Shared questions are merged into **641 unique questions: 150 Learning and 491 Talent**. Every source collection label is retained. Collection filters let you revisit any original bank without duplicates in mixed practice. Clarifications from the new reference are used where applicable, including in-progress-review goal loading and talent-review send-back after manual advancement.

The new Talent bank follows the supplied 30% / 35% / 25% / 10% blueprint. Learning uses the supplied 40% / 35% / 15% / 10% blueprint. A weighted exam rounds fractional question counts to whole questions. A restricted collection may not contain enough questions in every domain; the app then asks you to broaden the selection or use an unweighted session.

## Features

- **Learning mode:** choose a collection and domain, check answers, and read explanations with source references.
- **Exam mode:** configurable question count and time, randomized questions and options, flagging, navigation, and results after submission. The timer continues when you leave or close the page; an expired exam is submitted when the app next runs.
- **Question bank:** search, domain/topic/collection filters, supplied-sample filter, bookmarks, missed questions, and highlighted-answer display.
- **Reference notes:** topic-based explanations from the questions, with links or attachment page references.
- **Progress:** checked-answer accuracy, domain coverage, bookmarks, up to 60 completed sessions, and JSON backup import/export.

Progress belongs to this browser and address. Opening the local file, moving to GitHub Pages, or switching browsers can create a separate progress store. Use **Your progress → Export progress** before moving, then **Import progress** at the new address. If browser storage is unavailable, the app displays a notice and allows a manual backup. Import replaces current progress after confirmation.

## Host on GitHub Pages

1. Sign in to GitHub and create a repository, for example `workday-learning-talent`. A public repository works with GitHub Free.
2. Extract this ZIP. In the repository, use **Add file → Upload files** and upload `index.html` and `README.md` into the repository root. Upload the extracted files, not the ZIP or a folder wrapped around them. Commit the upload to `main`.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** and **/(root)**, then **Save**.
6. After deployment completes, use the site link shown on the Pages screen. Its usual format is `https://YOUR-USERNAME.github.io/workday-learning-talent/`.

No GitHub Actions configuration or build command is needed. Pages publishes the uploaded app, and its question content is visible to site visitors.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

### Add it to an existing study homepage

If you already host your Extend and Integration apps, create a `learning-talent` folder in that repository and put this app's `index.html` inside it. Keep the existing homepage. Add this link to that homepage:

```html
<a href="./learning-talent/">Learning &amp; Talent Study Lab</a>
```

The new app will be available at `https://YOUR-USERNAME.github.io/REPOSITORY/learning-talent/`.

### Update the app later

Replace `index.html` in the same location and commit. Keep the same site address to retain that browser's progress. Export a backup before a substantial update. If an older version is displayed, hard-refresh the page.

### Troubleshooting

- **404:** confirm that `index.html` is at the root of the selected publishing folder, the filename is lowercase, and the Pages deployment has completed.
- **README appears instead of the app:** confirm `index.html` was uploaded beside the README, not inside an extra ZIP folder.
- **No progress after moving:** import the backup from the previous browser/address.
- **Source link requires access:** the app itself works offline; official Workday documentation may require an authorized account.

## Source and format notes

The new 300-question PDF is supplied separately. Its questions are all included in this app. The full proprietary reference manual, videos, and earlier app content for Extend/Integration are not bundled; those apps informed the interface format. Attachment page references mean file pages in the supplied 332-page `talent.pdf`, not the printed guide page numbers.

The questions are independent practice material and supplied samples. They are not an official exam or a guarantee of live-exam wording or results. The original uploaded exam guides determine the practice blueprint; check your current enrollment materials for official exam requirements.

Version: 17 November 2026.
