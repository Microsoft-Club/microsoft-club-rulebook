# 📘 Microsoft Club GIKI — Official Rulebook

The official governing document of the Microsoft Club at Ghulam Ishaq Khan Institute of Engineering Sciences and Technology (GIKI).

---

## 📄 Overview

This repository contains the official rulebook of the Microsoft Club GIKI. It serves as the single source of truth for the club's constitution, governance structure, membership policies, wing structure, and code of conduct.

The rulebook is maintained as a version-controlled document to ensure full transparency, accountability, and an auditable history of every change made over time.

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `Microsoft_Club_GIKI_Rulebook.docx` | The official rulebook — all edits happen here. This is the single source of truth. |
| `README.md` | This file — repository guide and governance process. |
| `history/` | Archive of all signed PDFs from every ratified version. |

> **Active Club Roster** is maintained as a separate Google Doc owned by the Club's official email. It is not stored in this repository. See the link below.
>
> 📄 **[Wings Registry — Google Doc](https://docs.google.com/document/d/1DqZ8fGxEoY18ZvkwLm-5rayrInOqzw1m2310hY7yL2g/edit?usp=sharing)** *(link maintained by current EC)*

---

## 🔄 Amendment & Change Process

Any changes to the rulebook must follow the formal amendment process described below to be considered official and binding.

### Step-by-Step Process

```
1. Propose Amendment
   └─ Raise the proposal in the official EC group

2. EC Review & Approval
   └─ The Executive Committee (EC) reviews and votes on the proposal
   └─ A 2/3 supermajority is required (per Article XVII of the Rulebook)

3. Update the Rulebook
   └─ Edit Microsoft_Club_GIKI_Rulebook.docx with the approved changes

4. Commit to Repository
   └─ Commit with a clear message: "Amendment [#]: [Short Description]"

5. Export PDF
   └─ Export a PDF version from the updated .docx

6. Sign via DocuSign
   └─ The current EC members sign the PDF through DocuSign

7. Archive Signed PDF
   └─ Upload the signed PDF to /history/ using the naming convention below

8. Tag the Release
   └─ Create a Git tag: e.g., v2.1-signed-2026-05
```

---

## 🗂️ Registery Updates

The Active Wings Registery is maintained in a **Google Doc** owned by the Club's official email address. Google Docs' built-in version history automatically tracks every change — who made it, what changed, and when — without requiring any Git knowledge.

Each update should be named in Google Docs version history for clarity:

```
File → Version History → Name this version
Example: "Brainees elevated to Official Wing — May 2026"
```

### Update Process

```
1. EC votes on the roster change
   └─ Simple majority for Provisional Wings
   └─ 2/3 supermajority for Official Wings
   └─ (per Article IV § 4.4 of the Rulebook)

2. Edit the Active Club Roster Google Doc directly

3. Name the version in Google Docs version history
```

> Roster updates do **not** require DocuSign or a new PDF export. Google Docs version history serves as the transparent, timestamped record of every change.

---

## ✍️ DocuSign Signing Requirement

Any amendment to the **rulebook** becomes effective only after the updated PDF has been:

1. Exported from the latest version of `Microsoft_Club_GIKI_Rulebook.docx`
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

> The current EC members and all active wing leads are listed in the Active Club Roster Google Doc.

---

## 📌 Governance Notes

- This repository is **append-only in spirit** — old versions are never deleted, only superseded.
- The `main` branch always reflects the **latest ratified version** of the rulebook.
- Branches may be used for **drafting amendments** before they are formally approved.
- During leadership transition, the incoming EC must be granted edit access to the Active Club Roster Google Doc and write access to this repository.

---

## 📬 Contact

For questions about the rulebook or the amendment process, reach out to the current EC through official Microsoft Club GIKI communication channels.

---

*Maintained by the Executive Committee of Microsoft Club GIKI · All amendments are version-controlled and DocuSign-certified*
