# Byron Aldas portfolio v2

Separate preview of Byron's React portfolio. The original `byrnald/portfolio` repository and its Pages deployment remain independent.

## Development

Requires Node.js 22.13 or newer.

```sh
npm ci
npm run dev
```

```sh
npm run build
```

## GitHub Pages

Pushes to `main` deploy through GitHub Actions. Enable **Settings → Pages → Source → GitHub Actions**. The workflow obtains the site's base path automatically so scripts, favicon, and the bundled resume work at `/portfolio-v2/` or a future custom-domain root.

Content lives in `lib/portfolio-data.ts` and `components/ui/`. Theme tokens are in `app/globals.css`. The PDF is `public/resume.pdf`.

The border-beam component adapts the Magic UI example using Framer Motion and monochrome theme tokens: https://magicui.design/docs/components/border-beam.

Do not replace or alter the original portfolio until the new version has been reviewed and approved.
