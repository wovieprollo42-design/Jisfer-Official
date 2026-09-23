# Jisfir Cepriano, Portfolio

Static one page portfolio, branded from the client resume (orange #F57602, charcoal #302F2E, Poppins). No build step, no dependencies.

## Structure

- `index.html` , the entire site (HTML, CSS and JS inline)
- `images/` , profile photos, social icons and tool logos pulled from the client Drive folder
- `images/logos/` , tech stack logos
- `resume.pdf` , linked from the hero and contact sections
- `vercel.json` , static hosting config

## Local preview

Any static server works, for example:

    npx -y serve .

## Deploy

    npx -y vercel --prod --yes

## Open items

1. Social links in the contact card use placeholder hrefs. Search for `data-placeholder`
   in `index.html` and swap in the real LinkedIn, Facebook and Instagram URLs.
2. `images/logos/_unknown-a.png` and `images/logos/_unknown-b.png` came from the Drive
   folder but could not be identified with confidence at their 67px source size, so they
   are not shown on the page. Name them and they can be added to the stack grid.
3. Tool logos are 67x67 source files. If higher resolution versions are available they
   will look sharper on retina screens.
