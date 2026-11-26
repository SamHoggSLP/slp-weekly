# Benchline: dental lab prototype

A single-file, clickable prototype of a case-management system for one Australian dental lab. Open `index.html` in a browser. All data is example data kept in the browser's localStorage, and there is no backend.

- **Cases**: seven working stages (Booked, Received, Models & scan, Design, Mill / print, Ceramics, QC) plus Dispatched. A morning brief shows overdue cases, stalled cases, unassigned work and how loaded ceramics is.
- **Rx intake**: paste an emailed, dictated or Seazona Rx. It fills in the case, including FDI teeth on a tooth chart, checks for missing details (shade, implant system, bridge span) and drafts a request to the dentist.
- **Turnaround**: units are counted from the tooth chart and the return date is set by per-item rules (base working days, plus a day per extra units). The rules are editable in Billing.
- **Lab slip**: generated from the booking, with department finish-by dates worked back from the due date. The typed Word slip is no longer needed.
- **Allocation**: a skills matrix and daily capacity per technician. It suggests the least-loaded technician with the right skills, with anterior ceramics and implant design handled as separate sign-offs.
- **Bench**: each technician's queue, a time clock and piece-rate pay (optional; paper still works).
- **Dentist portal**: booking that starts from the tooth chart, plus case progress and invoices.
- **Billing**: GST invoices, remakes credited, AR aging and a Xero import CSV.
- **Photos and TGA statement**: photos attached to each case, and a custom-made medical device statement.

The stage names, turnaround rules and skills are guesses to be replaced once the lab's actual process has been mapped.
