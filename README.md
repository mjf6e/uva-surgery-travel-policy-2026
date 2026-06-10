# UVA Department of Surgery — Resident Travel Policy Website

A web-based resource for categorical residents, fellows, and clinical instructors in the **University of Virginia Department of Surgery** to navigate travel policy, funding guidelines, approval workflows, and program contacts.

---

## 🌐 Live Site

> _Replace the URL below with your GitHub Pages URL once published._

```
https://[your-username].github.io/[repository-name]/
```

---

## 📋 About

This site presents the **Categorical Resident Travel Policy (Version 2026-05)** in an accessible, easy-to-navigate format. It is intended for use by residents, fellows, clinical instructors, and program coordinators within the Department of Surgery.

---

## 🗂️ Site Sections

| Tab | Contents |
|-----|----------|
| **Overview** | Policy summary, quick-reference funding limits, and eligibility by resident category |
| **Funding** | Full funding table by resident type, overage responsibilities, and key funding notes |
| **Travel Rules** | Booking requirements, lodging, meals, transportation, receipts, and downloadable Travel Application form |
| **International Travel** | Travel registry, export controls, digital security, sanctions, and non-U.S. citizen guidance |
| **Process** | Step-by-step approval workflow and key deadline timeline |
| **Contacts** | Program coordinators by division, funding contacts, and Outlook Web compose links |
| **Resident Travel Information Form** | Embedded Microsoft Form for residents to submit traveler information to their coordinator |
| **Policy Document** | Full policy PDF embedded for inline viewing with download option |

---

## ✨ Features

- **UVA-branded** design using official navy (`#232D4B`) and orange (`#E57200`) color palette
- **Responsive layout** — works on desktop, tablet, and mobile
- **Tabbed navigation** for quick access to each section
- **Expandable/collapsible cards** to keep content organized and scannable
- **Embedded PDFs** — Travel Application form and full Policy Document, both downloadable
- **Embedded Microsoft Form** for resident travel information submission
- **Mailto and Outlook Web links** for all program coordinators and funding contacts
- **Color-coded alerts** — red for warnings, green for tips, amber for cautions, navy for info
- **All links included** — UVA registry, export control forms, UVA policy documents, and external resources

---

## 📁 Files

```
index.html        # Main website — single self-contained file
README.md         # This file
```

> Both PDFs (Travel Application and Policy Document) are embedded directly in `index.html` as base64-encoded data URIs, so no additional files are needed.

---

## 🔄 Updating the Site

All content is contained in a single file: **`index.html`**. To make updates:

1. Edit `index.html` locally or via the GitHub file editor
2. Commit the changes to the `main` branch
3. GitHub Pages will automatically rebuild and publish within ~60 seconds

### Common updates
- **Policy text changes** — Search for the relevant section in `index.html` and update the HTML content
- **Contact changes** — Search for the contact name and update the `href` and display text
- **New PDF version** — Re-encode the PDF as base64 and replace the existing `data:application/pdf;base64,...` string
- **Form URL change** — Search for `forms.cloud.microsoft` and update the `src` attribute of the iframe

---

## 👤 Maintained By

**Michael Freeman**
Senior Administrative Assistant, Division of Surgical Sciences
University of Virginia Department of Surgery
📧 [mjf6e@virginia.edu](mailto:mjf6e@virginia.edu)

---

## 📌 Policy Reference

**Categorical Resident Travel Policy — Version 2026-05**
University of Virginia, Department of Surgery
Effective: May 2026
