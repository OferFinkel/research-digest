# Ofer's Research and Business Digest

A daily digest of research and business news on robotic earth and concrete printing, funicular shells, print monitoring, self-driving labs, physical AI, funding and events.

Site: https://oferfinkel.github.io/research-digest/

- `index.html` is the whole site.
- `data/index.json` lists editions; `data/digests/<id>.json` holds each edition.
- `data/events.json`, `data/profile.json` (the agent's filters) and `data/ratings.json` (processed ratings).
- Ratings are sent from the site as GitHub issues labelled `ratings`; the daily agent merges them into `data/ratings.json` and closes the issue.

A Claude scheduled task updates the data every morning at 07:00 Israel time.
