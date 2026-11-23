# Broadway Cares Emails

Mailchimp email templates and reusable pieces for Broadway Cares/Equity Fights AIDS, kept here so the team can find, reuse and update them.

- **`templates/`**: complete emails, ready to load into Mailchimp.
- **`components/`**: smaller pieces (signatures, headers, footers and more) to paste into any email.

---

## Folder structure

```
BroadwayCaresEmails/
├── templates/                     # Full, send-ready emails
│   └── YYYY-MM-campaign-name/
│       ├── YYYY-MM-campaign-name.html
│       └── preview.png
│
└── components/                    # Reusable pieces
    ├── signatures/                # Staff sign-offs
    │   └── 2025-danny-whitman-signature/
    ├── headers/                   # Logo bars, banners
    ├── footers/                   # Address, social links, unsubscribe text
    ├── buttons/                   # Donate / Learn more / Register buttons
    └── content-blocks/            # Repeated sections (event promos, donation asks, etc.)
```

Each template or component has its **own folder** containing:

| File | What it is |
| --- | --- |
| `YYYY-name.html` | The HTML you paste into Mailchimp |
| `preview.png` | Screenshot of how it looks |
| Any other `.png` / `.jpg` | Backup copies of images used (the live versions are hosted in Mailchimp) |

---

## Naming rules

**Always put the year first.** This keeps the newest versions easy to spot and stops old versions from being overwritten.

| Type | Pattern | Example |
| --- | --- | --- |
| Template | `YYYY-MM-campaign-name` | `2025-12-holiday-appeal` |
| Component | `YYYY-component-name` | `2025-danny-whitman-signature` |

- Use lowercase letters and hyphens only (no spaces).
- When something changes for a new year, **make a new folder** (`2026-danny-whitman-signature`) instead of editing the old one. Older years are a record of what was sent.

---

## Using these in Mailchimp

### Adding a component to an email
1. Open the `.html` file in this repo and copy all of the code (on GitHub, click the file, then the **Copy raw file** button).
2. In the Mailchimp email builder, add a **Code** block, or open a **Text** block and switch to its source/code view.
3. Paste the HTML and save.
4. Preview the email to check it.

### Loading a full template
1. In Mailchimp, go to **Content → Email templates → Create template → Code your own**.
2. Choose **Paste in code** and paste the template's HTML, or use **Import HTML** to upload the file.
3. Name the template to match its folder (for example `2025-12-holiday-appeal`).

### Saving a new template from Mailchimp into this repo
1. In Mailchimp, open the template's menu and choose **Export as HTML**.
2. Make a new folder in `templates/` named `YYYY-MM-campaign-name`.
3. Put the exported HTML in it with the same name, and add a `preview.png` screenshot.

### Images
Images in emails must be hosted online, so they live in Mailchimp's **Content Studio**, and the HTML links to them there (`mcusercontent.com/...`). The image files in this repo are **backups only**. If an image changes, upload the new one to Mailchimp first and then update the link in the HTML.

---

## What's here

### Components
| Component | Year | Location |
| --- | --- | --- |
| Danny Whitman signature (Executive Director) | 2025 | [`components/signatures/2025-danny-whitman-signature`](components/signatures/2025-danny-whitman-signature) |

### Templates
_None yet._

> Update these tables whenever you add something.

---

## Checklist before adding something

- [ ] Folder and HTML file start with the year
- [ ] `preview.png` included
- [ ] Images are uploaded to Mailchimp and the links work
- [ ] Sent a test email to yourself and checked it on desktop and phone
- [ ] Added it to the **What's here** tables above
