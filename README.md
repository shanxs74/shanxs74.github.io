# 0xShanxs: Cybersecurity & Blue Team Writeups

Source of my technical blog, live at **https://shanxs74.github.io**.

Built with [Astro](https://astro.build) and the [Fuwari](https://github.com/saicaca/fuwari) theme (MIT), and deployed to GitHub Pages with GitHub Actions on every push to `main`.

## Local development

Requires Node.js 22+ and [pnpm](https://pnpm.io).

```sh
pnpm install
pnpm dev        # http://localhost:4321
pnpm build      # production build into ./dist
```

## Writing a post

```sh
pnpm new-post my-first-writeup
```

Posts live in `src/content/posts/`. Site settings (title, profile links, banner, theme hue) are in `src/config.ts`.
