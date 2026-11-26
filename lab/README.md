# Benchline: dental lab prototype

A single-file prototype of a case-management system for one Australian dental lab. Open `index.html` in a browser.

- **Cases**: a pipeline from Received to Design, Milling, Finishing, QC and Dispatched, with a morning brief that flags overdue and stalled cases
- **Rx intake**: paste an emailed, dictated or scanned Rx and it fills in the practice, dentist, patient, FDI teeth, VITA shade, restoration and due date for checking
- **Bench**: each technician's queue, a time clock, and piece-rate pay credited when a stage is closed
- **Dentist portal**: what each practice sees (case progress, invoices, new orders)
- **Billing**: per-practice discounts, GST invoices, remakes credited, AR aging, and a CSV in Xero's import layout
- **TGA statement**: a custom-made medical device statement for each case

All data is example data stored in the browser's localStorage. There is no backend yet.
