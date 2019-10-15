# Madsen dialog website repo

## legge til innlegg
- naviger til /content/posts/
- mappene heter " åååå-mm-dd--tittel-link " . 
-- eks. mappe navn: .../ "2019-01-01--et-blogg-innlegg " <-her blir linken dittdomene.com/et-blogg-innlegg og satt til publisert dato 01/01/2019
- Inne i mappen skal det opprettes en index.md fil. 
- see eksempel og bruk "blogg malen" og endre mappe navnet til ønsket dato og tittel til relevant tittel med bindestrek. PS! husk -- mellom dato og tittel-link



A [GatsbyJS](https://www.gatsbyjs.org/) project. <br /><br />


## Description

website repo build on gatsbyjsith netlify for Continious Deployment and

The starter was initially built for Gatsby v1. Now, Gatsby v2. Thank you Mohsen :)

The original version of the starter is preserved as the branch `gatsby-v1`.

## Features:

- Easy editable content in **Markdown** files (posts, pages and parts)
- **CSS** with `styled-jsx` and `PostCSS`
- **SEO** (sitemap generation, robot.txt, meta and OpenGraph Tags)
- **Social** sharing (Twitter, Facebook, Google, LinkedIn)
- **Comments** (Facebook)
- **Images** lazy loading and `webp` support (gatsby-image)
- Post **categories** (category based post list)
- Full text **searching** (Algolia)
- **Contact** form (Netlify form handling)
- Form elements and validation with `ant-design`
- **RSS** feed
- 100% **PWA** (manifest.webmanifest, offline support, favicons)
- Google **Analytics**
- App **favicons** generator (node script)
- Easy customizable base **styles** via `theme` object generated from `yaml` file (fonts, colors, sizes)
- React **v.16.3** (gatsby-plugin-react-next)
- **Components** lazy loading (social sharing)
- **ESLint** (google config)
- **Prettier** code styling
- Webpack `BundleAnalyzerPlugin`
- **Gravatar** image (optional) instead local Avatar/Logo image

## Prerequisites

If you do not have Gatsby Cli installed yet, do it first.

```text
npm install --global gatsby-cli
```

More information on [GatsbyJS.org](https://www.gatsbyjs.org/tutorial/part-one)

## Getting started


##### External services

The starter uses external services for some functions: comments, searching, analytics. To use them you have to secure some access data. All services are free to use or have generous free tiers big enough for a personal blog.

Create an `.env` file like below in the root folder. Change `...` placeholders with real data.
<br />By default, your `.env` file will be ignored by git. Remove `.env` from `.gitignore` in order to be able to push the file to your repository.

```text
GOOGLE_ANALYTICS_ID=...
ALGOLIA_APP_ID=...
ALGOLIA_SEARCH_ONLY_API_KEY=...
ALGOLIA_ADMIN_API_KEY=...
ALGOLIA_INDEX_NAME=...
FB_APP_ID=...
```

### Instructions & tutorials


## Authors
- Martin Andersen
- Greg Lobinski 




