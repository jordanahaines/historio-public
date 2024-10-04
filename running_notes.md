_These aren't notes about running. Yuck. No, this is a list to capture quick notes of notes on what I'm doing in Historio so that I can include them in future posts (where relevant)_

# Notes
- Setup with nextui cli
  - Added sass support by following [instructions](https://nextjs.org/docs/app/building-your-application/styling/sass) and then importing styles modules. Will co-locate module and page styles alongside the page.and style typescript files.
  - Added drizzle. Installing was easy - figuring out scalable file structure/configuration was tricky.
  - This [NextJS boilerplate](https://github.com/ixartz/Next-js-Boilerplate/blob/main/src/models/Schema.ts) seems useful for structuring more complex project
  - Had to add `.prettierrc` to get Pretter to work (eslintrc wasn't enough).
    - By the way - AI is great at adjusting eslint configuration!
- Publishing with Cloudflare pages
  - Don't zip on mac!
  - Upload static assets in pages. Automatically cached. Easy to connect custom domain (especially if it's registered with Cloudflare)
  - Could write a section on the evolution of deployment and how we're going back to basics. My journey: FTP -> Manual Git with scripts -> Automated deployment -> Continues Delivery

## Future How-Tos
- How to upsert using Drizzle