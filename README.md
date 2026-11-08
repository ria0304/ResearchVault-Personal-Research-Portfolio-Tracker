# Research Portfolio

A personal, single-file tracker for my research projects, patents, conference papers and journals . Open `research-portfolio.html` in any browser. No install, server or account is needed.

## What it tracks

| Section | What you record |
| --- | --- |
| Research Projects | Stage, next milestone, GitHub repo, description, objectives, technical progress |
| Patents | Application status, IDF, publication fee, publication, grant decision, application number, filing date, inventors, institution, payment details, document links |
| Conferences | Status, paper ID, venue, website, conference dates, submission and registration deadlines, notification date, acceptance letter, camera-ready, presentation, proceedings, indexing |
| Journals | Workflow status, journal, publisher, manuscript ID, dates, decision, revision, APC, manuscript link |

Every record also has a **Notes** box and a **checklist**. Each section has its own checklist as well.

## Pages

- **Dashboard:** counts of projects, papers, accepted papers, papers awaiting a decision, journals in progress, patents and book proposals, plus deadlines in the next 30 days, open checklist items, recent activity and recently updated records.
- **Timeline:** full change history and upcoming dates grouped by month.
- **Notes & Archive:** archived records and all checklists in one place.
- **Search:** the top search bar searches every record across all sections.

## Using it

1. Click a record's arrow to expand it.
2. Edit any field. Changes save automatically as you type.
3. Click **Save changes** to confirm and log the update in the history.
4. Use **Archive** for finished or dropped work, or **Delete** to remove a record permanently.
5. Link patents, conference papers and journals to a project with the **Project** field. They then appear under that project.
6. Switch between dark and light mode from the sidebar.

Status changes made through dropdowns are logged automatically, for example "Fees pending to Fees paid".

## Where your data lives

Data is stored in your browser's `localStorage` under the key `research-portfolio-v1`. Nothing is sent anywhere.

- It stays on one browser on one device. Another browser or device starts from the built-in starting data.
- Clearing site data or using a private window loses it.

### Backups

- **Export backup (JSON):** downloads all your data. Do this regularly.
- **Import backup (JSON):** replaces everything in the current browser with a backup file. Use it to move data to another browser or device.
- **Download checklists:** exports every checklist as a Markdown file.

## Privacy

This is a personal tool with a single user: me. There are no accounts, no sharing features and no server. Keep the file and any exported backups private, since they contain unpublished work, paper IDs and patent details.


## Files

- `research-portfolio.html`: the whole app (HTML, CSS and JavaScript)
- `README.md`: this file
