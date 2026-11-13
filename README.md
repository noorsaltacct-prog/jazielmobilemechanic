# Jaziel Mobile Mechanic | Website

Ready-to-deploy static website for GitHub + Vercel.

## Deploy
1. Extract this ZIP.
2. Upload the **contents** of the `jaziel-site` folder to the root of a GitHub repository.
3. Import the repository in Vercel. Choose **Other**, no build command, output directory left blank.
4. Deploy.

## Business information
- **Name:** Jaziel Mobile Mechanic
- **Phone/text:** +1 (443) 500-6987
- **Locations:** Baltimore, Glen Burnie, Catonsville, Lansdowne, Ellicott City, Brooklyn, Pasadena, MD
- **Services:** diagnostics, brakes, tune-ups, suspension, AC/heating, timing jobs, general repairs; all makes/models

## Photography + video
The ten user-supplied photos are compressed WebP files in `assets/`. The supplied 9-second engine-removal video is `assets/engine-work.mp4`, with a real poster image. It is click-to-play, not auto-play, and will not consume bandwidth until played on supporting browsers.

## Important notes
- The site intentionally does not invent years in business, certifications, pricing, testimonials, business hours, or warranty claims.
- The 4-step quote experience **prepares an SMS draft** to the mechanic. It does not send or store inquiries on a server. The visitor must tap Send in their messaging app. Draft field values persist in the same browser tab via sessionStorage until cleared.
- The SMS flow should be tested on a physical phone; desktop browsers may not have an SMS app.
- Fonts use Google Fonts; system fallbacks are provided. For completely offline use, replace with licensed local fonts.
- No canonical tag or sitemap URL is included because the deployed domain has not been provided. Add these after the domain is chosen.
- Verify the intended geographic meaning of Brooklyn, MD with the business owner and review service availability before publishing.
- Photographs are presented as the business's own images based on the uploaded files; do not use them without rights/permission.

## Customization
Edit copy and SEO metadata in `index.html`, colors and layout in `styles.css`, contact number in all `tel:`/`sms:` links and `script.js`. Replace photos with optimized files of the same names to preserve layout.
