# Local audit — FPnA_Executive_Analytics_Project

## Changes

Repaired standalone ingestion and SQL execution; all five query snapshots match, including 30/30 revenue reconciliation pairs. Rewrote documentation, normalized the swimlane filename and removed saved-directory metadata from three Excel files. Financial workbooks, author credits and original presentations remain intact.

## Validation performed

- **PASS** — FPnA_Executive_Analytics_Project/scripts/run_analysis.py: Python syntax
- **PASS** — FPnA_Executive_Analytics_Project/scripts/validate.py: Python syntax
- **PASS** — FPnA_Executive_Analytics_Project/Excel/Agile_User_Story_Backlog.xlsx: Archive CRC; XML; PBIX layout where applicable (not native execution)
- **PASS** — FPnA_Executive_Analytics_Project/Excel/Requirements_Traceability_Matrix_.xlsx: Archive CRC; XML; PBIX layout where applicable (not native execution)
- **PASS** — FPnA_Executive_Analytics_Project/Excel/FPnA_Executive_Performance_Model.xlsx: Archive CRC; XML; PBIX layout where applicable (not native execution)
- **PASS** — FPnA_Executive_Analytics_Project/Excel/FPnA_Executive_Analytics_Project_Project_Workbook.xlsx: Archive CRC; XML; PBIX layout where applicable (not native execution)
- **PASS** — FPnA_Executive_Analytics_Project/Excel/UAT_Template.xlsx: Archive CRC; XML; PBIX layout where applicable (not native execution)
- **PASS** — FPnA_Executive_Analytics_Project/Dashboard/FPnA_Executive_Analytics_Dashboard.pbix: Archive CRC; XML; PBIX layout where applicable (not native execution)
- **PASS** — FPnA_Executive_Analytics_Project/Deck/Executive_Deck.pptx: Archive CRC; XML; PBIX layout where applicable (not native execution)
- **PASS** — SQL snapshots: PASS Q01: all 6 result rows match the supplied snapshot; PASS Q02: all 6 result rows match the supplied snapshot; PASS Q03: all 5 result rows match the supplied snapshot; PASS Q04: all 30 result rows match the supplied snapshot; PASS Q05: all 0 result rows match the supplied snapshot; PASS: snapshot reconciliation; not business sign-off or native dashboard validation.
- **PASS** — portable execution: Q01: 6 rows; Q02: 6 rows; Q03: 5 rows; Q04: 30 rows; Q05: 0 rows
- **PASS** — full SQL packs: All SQL files executed successfully with the canonical schema.
- **PASS** — blank ingestion: Invalid input rejected before query execution.
- **PASS** — nonfinite ingestion: Invalid input rejected before query execution.
- **PASS** — fractional ingestion: Invalid input rejected before query execution.
- **PASS** — FPnA_Executive_Analytics_Project/Excel/Agile_User_Story_Backlog.xlsx preservation: All worksheets, formulas, chart parts, styles and other members byte-identical; changed parts: []
- **PASS** — FPnA_Executive_Analytics_Project/Excel/Requirements_Traceability_Matrix_.xlsx preservation: All worksheets, formulas, chart parts, styles and other members byte-identical; changed parts: []
- **PASS** — FPnA_Executive_Analytics_Project/Excel/FPnA_Executive_Performance_Model.xlsx preservation: All worksheets, formulas, chart parts, styles and other members byte-identical; changed parts: ['xl/workbook.xml']
- **PASS** — FPnA_Executive_Analytics_Project/Excel/FPnA_Executive_Analytics_Project_Project_Workbook.xlsx preservation: All worksheets, formulas, chart parts, styles and other members byte-identical; changed parts: ['xl/workbook.xml']
- **PASS** — FPnA_Executive_Analytics_Project/Excel/UAT_Template.xlsx preservation: All worksheets, formulas, chart parts, styles and other members byte-identical; changed parts: ['xl/workbook.xml']
- Archive members and XML were parsed where present; images decoded and screenshots reviewed. Notebook/JSON syntax and local paths were checked.
- No plaintext secret candidates, personal contact emails, promotional GitHub/LinkedIn profile links or machine-home paths were detected in the final scanned text/package content. This is a bounded local pattern scan, not proof that opaque native models contain no sensitive data.

## Remaining limitations

Power BI refresh/DAX, Excel recalculation, PowerPoint rendering and external ledger validation were not executed. Compressed PBIX DataModel content remains a native-engine inspection limitation. Source licensing/data rights are unconfirmed. UAT/sign-off examples and historical author names were retained as provenance, not genuine approval.

## Provenance and execution scope

Original source datasets and SQL are retained. No Git history was present in the five extracted folders. Original Downloads folders match their pre-copy SHA-256 hashes. No GitHub command, authentication, repository creation, commit, push or upload was performed.

Original authorship and legally required notices remain in [ATTRIBUTION.md](ATTRIBUTION.md). Personal UI redactions do not replace author attribution.
