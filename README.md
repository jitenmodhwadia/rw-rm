# rw-rm

Deployment repo for **rm.richwealth.in** — the Richwealth Daily RM Client Tracker entry page.

`index.html` is generated; it is not edited by hand. The build sources
(`form_template.html`, `logo.txt`, `build.py`) live on Jiten's PC at
`rw_rm_page` and are deliberately not published here.

To change the page: edit the template there, run `python build.py`, then commit and
push the regenerated `index.html`.

Entries post into a Google Form backend on richwealth214 and land in the
"Richwealth Daily RM Tracker (Responses)" sheet (tabs: Daily Summary + RM Entries).
