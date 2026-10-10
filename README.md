# Inti South American Club website

A single-page static site: `index.html` plus a `photos/` folder. No build step.

## Fill in your details
Open `index.html` and edit the `SITE` block near the bottom (it's marked "EDIT THIS BLOCK"):

- **name, school, tagline, email**: shown in the header and footer.
- **calendarEmbed**: Google Calendar > Settings > your calendar > *Integrate calendar* > copy the `src="..."` URL from *Embed code*. The calendar must be public.
- **calendarId**: the Calendar ID on the same page; adds an "Add to my Google Calendar" button.
- **newsletterForm / interestForm**: in Google Forms, *Send* > `<>` tab > copy the `src="..."` URL. For the newsletter, a form that collects email addresses works well; responses land in a Google Sheet you can send to from Gmail.
- **instagram, instagramHandle, discord**: your profile URL and Discord invite link (make the invite never expire).
- **board**: one entry per officer (role, name, major/year, optional photo). Without a photo, their initials show inside a chakana frame.
- **photos**: drop images into `photos/` and list them, e.g. `{ src: "photos/welcome.jpg", caption: "Welcome night" }`.

The About section text is written directly in the HTML; replace the bracketed parts.

## Putting it online (free)
- **GitHub Pages**: create a repo, upload these files, then Settings > Pages > deploy from the main branch.
- **Netlify Drop**: drag this folder onto app.netlify.com/drop.
