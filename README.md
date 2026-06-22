# Grant Pinkerton Portfolio

Static personal portfolio site for recruiters and professional contacts.

## Files

- `index.html` - root entry point for hosting providers
- `Portfolio.html` - main portfolio page
- `Pinkerton.Grant.Resume.pages` - editable resume source file
- `netlify.toml` - Netlify static hosting configuration
- `vercel.json` - Vercel static hosting configuration

## Preview Locally

Run this from the project folder:

```sh
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy Option 1: Netlify

1. Go to `https://app.netlify.com/drop`.
2. Drag this entire folder into the upload area.
3. Netlify will publish the site and give you a public URL.
4. Rename the site in Netlify settings if you want a cleaner subdomain.

This is the fastest no-code path.

## Deploy Option 2: Vercel

1. Create a GitHub repository for this folder.
2. Push these files to the repository.
3. Import the repository at `https://vercel.com/new`.
4. Keep the framework preset as static/no framework and deploy.

## Deploy Option 3: GitHub Pages

1. Create a public GitHub repository.
2. Push these files to the repository.
3. In GitHub, open Settings -> Pages.
4. Set the source to the main branch root folder.
5. GitHub will publish the site at a `github.io` URL.

## Custom Domain

After publishing, buy or connect a domain such as `grantpinkerton.com`, then add it in the hosting provider's domain settings. Netlify and Vercel both provide the DNS records to copy into your domain registrar.
