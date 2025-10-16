# cachecow.xyz

A simple, clean directory site showcasing projects and experiments at various subdomains. Built with [Astro](https://astro.build) as a static site.

Live at [cachecow.xyz](https://cachecow.xyz)

## Development

All commands are run from the root of the project:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro ...`       | Run CLI commands like `astro add`, `astro check` |

## Structure

- `src/pages/index.astro` - Main landing page with tile grid
- `src/components/Tile.astro` - Individual tile component
- `src/layouts/Layout.astro` - Base HTML layout

## Adding New Tiles

Edit the `tiles` array in `src/pages/index.astro`:

```js
const tiles = [
  {
    title: 'Your Project',
    description: 'Project description',
    url: 'https://subdomain.cachecow.xyz',
    color: '#HexColor'
  },
  // ...
];
```
