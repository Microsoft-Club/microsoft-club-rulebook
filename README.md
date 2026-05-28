# 📘 Microsoft Club GIKI — Official Rulebook

The official governing document of the Microsoft Club at Ghulam Ishaq Khan Institute of Engineering Sciences and Technology (GIKI).

---

## 📄 Overview

This repository contains the official rulebook of the Microsoft Club GIKI. It serves as the single source of truth for the club's constitution, governance structure, membership policies, wing structure, and code of conduct.

The rulebook is maintained as a version-controlled document to ensure full transparency, accountability, and a human-readable, auditable history of every change made over time.

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `Microsoft_Club_GIKI_Rulebook.md` | ⭐ Source of truth — all edits happen here. Every word change is tracked line-by-line in Git history. |
| `Microsoft_Club_GIKI_Rulebook.docx` | Export artifact — generated from the `.md` file for DocuSign and PDF export only. Do not edit directly. |
| `active-club-roster.md` | Living document — tracks the current Official and Provisional Wings roster. Updated by simple majority EC vote. |
| `README.md` | This file — repository guide and governance process. |
| `history/` | Archive of all signed PDFs from every ratified version. |

> **Why `.md` as the source of truth?**
> A `.docx` is a binary file. When changed, GitHub only shows `Binary file changed` — no detail, no accountability. A `.md` file is plain text, so GitHub shows the exact lines added, removed, or modified in every commit. This is the foundation of our transparency commitment.

---

## 🔄 Amendment & Change Process

Any changes to the rulebook must follow the formal amendment process described below to be considered official and binding.

### Step-by-Step Process

```
1. Propose Amendment
   └─ Open a GitHub Issue describing the proposed change and rationale

2. EC Review & Approval
   └─ The Executive Committee (EC) reviews and votes on the proposal
   └─ A 2/3 supermajority is required (per Article XVII of the Rulebook)

3. Update the Source File
   └─ Edit Microsoft_Club_GIKI_Rulebook.md with the approved changes
   └─ Every change is now permanently and readably tracked in Git history

4. Commit to Repository
   └─ Commit with a clear message: "Amendment [#]: [Short Description]"

5. Generate Export Files
   └─ Export Microsoft_Club_GIKI_Rulebook.docx from the updated .md file
   └─ Export a PDF version from the .docx

6. Sign via DocuSign
   └─ The current EC members sign the PDF through DocuSign

7. Archive Signed PDF
   └─ Upload the signed PDF to /history/ using the naming convention below

8. Tag the Release
   └─ Create a Git tag: e.g., v2.1-signed-2026-05
```

---

## 🗂️ Roster Updates

The `active-club-roster.md` file tracks the current state of all Official and Provisional Wings. It is a **living document** governed by its own lighter update process:

```
1. EC votes on the roster change (simple majority for Provisional Wings,
   2/3 supermajority for Official Wings — per Article IV § 4.4)

2. Edit active-club-roster.md directly

3. Commit with a clear message: "Roster Update: [Short Description]"
```

> Roster updates do **not** require DocuSign or a new PDF export. The commit history itself serves as the transparent, timestamped record of every change.

---

## ✍️ DocuSign Signing Requirement

Any amendment to the **rulebook** becomes effective only after the updated PDF has been:

1. Generated from the latest version of `Microsoft_Club_GIKI_Rulebook.md`
2. Signed by all current EC members via DocuSign
3. Archived in this repository under the `/history/` directory

> ⚠️ An unsigned or uncommitted amendment is not considered valid or enforceable.

### Signed PDF Naming Convention

```
Microsoft_Club_GIKI_Rulebook_v<VERSION>_signed_<YYYY-MM>.pdf
```

**Example:** `Microsoft_Club_GIKI_Rulebook_v2.1_signed_2026-05.pdf`

---

## 🗃️ Version History

All historical signed PDFs are stored in the `/history/` directory. Each entry corresponds to a formally ratified amendment.

| Version | Date | Description | Signed By |
|---------|------|-------------|-----------|
| v1.0 | 2026-05 | Initial ratification of the rulebook | EC 2026–27 |

> New entries are added to this table with every ratified amendment.

---

## 👥 Executive Committee (EC)

The Executive Committee is the governing body responsible for maintaining and enforcing this rulebook. The current EC must sign any rulebook amendment for it to take effect.

Roles include:
- President
- Vice President
- Program Manager
- Dev Director

> The current EC members and all active wing leads are listed in `active-club-roster.md`.

---

## 📌 Governance Notes

- This repository is **append-only in spirit** — old versions are never deleted, only superseded.
- All amendment proposals must be made via **GitHub Issues** for full transparency.
- The `main` branch always reflects the **latest ratified version** of the rulebook.
- Branches may be used for **drafting amendments** before they are formally approved.
- The `.docx` file is an **export artifact only** — never edit it directly. All edits go into the `.md` source file.

---

## 📬 Contact

For questions about the rulebook or the amendment process, reach out to the current EC through official Microsoft Club GIKI communication channels.

---

*Maintained by the Executive Committee of Microsoft Club GIKI · All amendments are version-controlled and DocuSign-certified*
