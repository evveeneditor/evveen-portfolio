# EVVEEN Portfolio

Official source code for the EVVEEN video-editing portfolio.

## Hosting

This website is a static HTML site ready for Netlify. Import the GitHub repository `evveeneditor/evveen-portfolio` into Netlify and use these settings:

- **Production branch:** `main`
- **Build command:** leave empty
- **Publish directory:** `.` (repository root)

Netlify also reads these settings from `netlify.toml`. When GitHub is connected to Netlify, new commits to `main` trigger redeployment automatically.

## Editing

- Edit `index.html` to change website text, styling, links, and sections.
- All portfolio video links are the ones supplied in the original Canva HTML.
- The site uses Tailwind CSS via its browser CDN, as the Canva HTML originally did. A future optimization could compile its CSS locally.
- The six project images are remote Pexels placeholders from the original design, not actual video thumbnails.

## Notes

The Canva-specific SDK scripts and large bootstrap font registry were removed because they rely on Canva's platform and are not needed on Netlify. The visible page content and styling remain based on the original HTML.

Contact: evveeneditor@gmail.com
