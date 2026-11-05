# pref.tools landing page

Static landing page for [pref.tools](https://pref.tools/): `index.html` plus
thumbnails in `img/`. Each tool lives in its own subfolder on the server and is
deployed from its own repository.

A push to `main` that touches the page or images publishes it over FTP
(`.github/workflows/deploy.yml`, secrets `FTP_USERNAME` and `FTP_PASSWORD`).
Run the workflow manually with "dry run" ticked to preview the changes.
