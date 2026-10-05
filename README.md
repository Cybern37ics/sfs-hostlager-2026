# sfs-hostlager-2026

Stockholm Freeski & Snowboard Club - Höstläger Kläppen 2026 weekend schedule.

The camp ran 2–4 October 2026. The site now shows a short "the camp is over" page.

The schedule app as it ran is kept at the tag `hostlager-2026`. To reuse it for a future camp, take its files from that tag into a new repo:

```
git clone https://github.com/Cybern37ics/sfs-hostlager-2026.git
cd sfs-hostlager-2026
git checkout hostlager-2026 -- index.html logo.png
```

`index.html` is the whole app. It reads a published Google Sheets tab as CSV (`SHEET_CSV`, top of the main script), and falls back to the CSV embedded in `<script type="text/csv" id="snapshot">` when the sheet can't be reached. Replace both, plus the title and dates in the header, for the new camp.
