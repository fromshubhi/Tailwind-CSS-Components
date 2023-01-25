<div align="center">
  <img alt="Astro Theme Cactus logo" src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/Tailwind_CSS_Logo.svg/2048px-Tailwind_CSS_Logo.svg.png" width="70" />
</div>
<h1 align="center">
  🚀 Tailwind CSS C omponents 🌵
</h1>

## Demo 💻

Check out the [Demo](), hosted on Netlify

## Commands

Replace pnpm with your choice of npm / yarn

| Command        | Action                                                         |
| :------------- | :------------------------------------------------------------- |
| `pnpm install` | Installs dependencies                                          |
| `pnpm dev`     | Starts local dev server at `localhost:3000`                    |
| `pnpm build`   | Build your production site to `./dist/`                        |
| `pnpm preview` | Preview your build locally, before deploying                   |
| `pnpm sync`    | Generate types based on your config in `src/content/config.ts` |

## Configure

- Edit the config file `src/site.config.ts` for basic site meta data
- Update file `astro.config.ts` site property with your own domain
- Replace & update files within the `/public` folder:
  - favicon.ico & other social icons
  - robots.txt - update the Sitemap url to your own domain
  - manifest.webmanifest
- Modify file `src/styles/global.css` with your own light and dark styles
- Create / edit posts for your blog within `src/content/post/` with .md/mdx file(s). See below for more details.
- Optional:
  - Fonts: This theme sets the body element to the font family `font-mono`, located in the global css file `src/styles/global.css`. You can change fonts by removing the variant `font-mono`, after which TailwindCSS will default to the `font-sans` [font family stack](https://tailwindcss.com/docs/font-family).

## Acknowledgment

This theme is inspired by Hexo Theme Cactus

## License

Licensed under the MIT License, Copyright © 2023
