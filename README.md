# One Small Win

A single-file to-do list app — categories, a Sunday-first week calendar, a completed-tasks report with PDF export, per-category progress pies, an "Add to Calendar" checkbox, and a few AI-assisted extras (Daily Brief, Quick Add, Summarize) when opened as a Claude Artifact.

## Running it

Open `index.html` directly in a browser, or serve it with GitHub Pages (Settings → Pages → Deploy from branch `main`, folder `/`) for a real `https://` URL — needed for the microphone (voice add) feature and generally more convenient on mobile.

Data is stored in the browser's `localStorage` unless opened as a Claude Artifact with the `db` capability, which syncs tasks across devices.

Originally split out from [Hyrox-Tracker](https://github.com/IsyandJayB/Hyrox-Tracker).
