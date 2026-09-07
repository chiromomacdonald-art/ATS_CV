# ATS CV Builder Deployment

This is a static web app. Open `index.html` locally or upload the contents of this folder to a static host.

## Deploy

- Netlify: drag the deployment folder into the Sites area.
- Vercel: import the folder and choose the static/other preset with no build command.
- GitHub Pages: publish the folder contents from a repository branch.
- Traditional hosting: upload `index.html` to the public web directory.

## Requirements

The app loads fonts and browser libraries from public CDNs, so the deployed page needs internet access for:

- PDF and Word export
- PDF and Word CV import
- Web fonts

No backend, database, environment variables, or server-side build is required.

## Privacy

CV content is processed in the browser. The page does not send CV data to an application server. Imported files are read locally by the browser.
