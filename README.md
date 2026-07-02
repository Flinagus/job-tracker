# Internship Tracker

A free, phone-friendly companion app for the private `job-watcher` repo.
Tracks internship applications; one-tap "applied / remove" actions clean up
the daily watcher email.

- **Hosted:** GitHub Pages (this repo — code only, no personal data)
- **Data:** lives in the owner's *private* `job-watcher` repo (`tracker.json`,
  `resumes/`, `files/`), accessed straight from the browser with a
  fine-grained personal access token (Contents read/write on that one repo).
- No server, no build step, no dependencies — one `index.html`.
