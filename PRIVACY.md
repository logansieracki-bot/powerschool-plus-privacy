# PowerSchool+ — Privacy Policy

_Last updated: 2026-11-08_

PowerSchool+ is a browser extension that restyles PowerSchool parent/student pages and adds tools (themes, a GPA
calculator, grade analytics, grade-change alerts and chess-style ratings). **It collects nothing, sends nothing, and has
no server.**

## What it reads
Only PowerSchool pages you open yourself (the `/guardian/` pages of your school's PowerSchool site). It first checks that
the page really is PowerSchool and does nothing otherwise. It reads the grades, assignments and class names that
PowerSchool already shows you on that page, so it can calculate your GPA, draw charts and tell you what changed since
your last visit.

## What it stores — on your device only
Saved with the browser's local extension storage (`chrome.storage.local`) and the page's own local storage (a small
cached copy of your theme so pages don't flash white):

- your settings (theme, colours, layout, GPA options, alert options);
- images or GIFs you upload for a custom theme;
- snapshots of your grades over time and your assignment lists (for the analytics charts);
- your recent alerts ("Algebra went from B+ to A-") and the last-seen grades used to produce them.

This data never leaves your browser. It is not uploaded, shared, sold, used for advertising, or used for anything other
than the features above. There is no analytics, tracking, telemetry or crash reporting, and the extension downloads and
runs no remote code.

## Your control
- **Export / import** your data, **delete** grade history and alerts, or **reset everything** from the extension's
  options page (Theme Studio → "Your data & privacy").
- Each feature (alerts, analytics, chess ratings, GPA) can be switched off in the toolbar popup.
- Removing the extension deletes all of its stored data.

## Permissions, and why
| Permission | Why |
|---|---|
| `storage`, `unlimitedStorage` | Save your settings, grade history and theme images locally (GIF backgrounds can be large). |
| Run on `https://*/guardian/*` | PowerSchool is hosted on each school district's own web address; the only thing they all share is the `/guardian/` path of the parent/student portal. The extension checks the page is PowerSchool before doing anything, and never reads or changes any other site. |

## Children and students
The extension is meant for students and parents using their own PowerSchool account. It does not knowingly collect any
personal information from anyone — nothing is collected at all.

## Not affiliated
PowerSchool+ is an independent, unofficial project made by Logan Sieracki. It is not affiliated with, endorsed by or
sponsored by PowerSchool Group LLC or Chess.com. Those names are trademarks of their owners, used only to describe
what the extension works with or is playfully inspired by.

## Contact
Questions or concerns: **Logan Sieracki — logan.sieracki@icloud.com**

If this policy changes, the date above will change and the change will be listed in the release notes.
