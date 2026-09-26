# Employee_Raise_Issue

# Employee Raise Issue — ServiceNow Implementation Documentation

This folder contains the complete documentation for the **Employee Raise Issue** project — a ServiceNow solution that lets employees raise workplace issues (IT, access, hardware, network, etc.) through a guided Record Producer on a dedicated Service Portal, instead of email or informal channels.

**Instance:** dev218486.service-now.com
**Application:** Employee Raise Issue (built within the Employee Center scope)
**Portal:** Requesting Portal (`/employee_request`)

---

## What's in this folder

| File | Description | Length |
|---|---|---|
| `Employee_Raise_Issue_Documentation.docx` | **Master document.** Full end-to-end project documentation covering all 7 phases plus architecture, security, deployment, training, support model, and reference appendices. | 41 pages |
| `Phase_Documents_PDF/Phase1_Creating_a_Custom_Application.pdf` | Standalone guide: creating the scoped application container. | 10 pages |
| `Phase_Documents_PDF/Phase2_Creating_a_Custom_Table_and_Fields.pdf` | Standalone guide: building the Employee Issue table and its fields. | 10 pages |
| `Phase_Documents_PDF/Phase3_Creating_UI_Policies_and_Dependency.pdf` | Standalone guide: dynamic form behavior, UI Policies, and field dependencies. | 10 pages |
| `Phase_Documents_PDF/Phase4_Creating_a_Record_Producer.pdf` | Standalone guide: building the employee-facing intake form. | 10 pages |
| `Phase_Documents_PDF/Phase5_Creating_a_New_Service_Portal.pdf` | Standalone guide: setting up the Service Portal and its pages. | 10 pages |
| `Phase_Documents_PDF/Phase6_Creating_Widgets_and_Adding_to_the_Page.pdf` | Standalone guide: building and placing the custom widgets. | 10 pages |
| `Phase_Documents_PDF/Phase7_Testing_and_Validation.pdf` | Standalone guide: functional, security, UI/UX, and performance testing. | 10 pages |

---

## Which document should I read?

- **New to the project, or need the full picture (architecture, security, deployment, training, support model)?** → Read the **master document**.
- **Working on (or reviewing) just one phase?** → Use the matching **Phase PDF**. Each one is self-contained — title page, objective, prerequisites, step-by-step instructions, real screenshots from the working instance, troubleshooting, best practices, FAQs, and a deliverables checklist. No need to open the master document to follow it.

## Project phases

1. Creating a Custom Application
2. Creating a Custom Table and Fields
3. Creating UI Policies and Dependency
4. Creating a Record Producer
5. Creating a New Service Portal
6. Creating Widgets and Adding to the Page
7. Testing and Validation

(The master document also includes Phase 8 — Conclusion — which wraps up the project; this is not broken out as a separate phase document.)

## Notes

- All screenshots throughout these documents were captured directly from the working dev218486 instance — they reflect the actual build, not a generic template.
- The Phase PDFs are final and not intended to be edited; the master document is provided as an editable `.docx` for anyone who needs to update it.
- If a phase's actual configuration differs slightly from a general best-practice description in the text (for example, category naming), a **NOTE** callout box in that section calls it out explicitly.

## Version

Document set version 1.0.
