<h2>Webpack Template: Basic</h2>
<p><em></em></p>

### Summary

- Standard loaders configured: (stylesheet, css, html, image assets).
- Uses webpack-merge to split webpack configs into dev and prod.
- Watch enabled for src/template.html.
- Entry point: index.js.
- Stylesheet has basic resets.
- `npm run dev` and `npm run build` scripts configured.

> [!NOTE]
> This template repo uses ES6-style imports and exports in config files.

### Jest

- Add the following lines in package.json to use Jest via npm:
  - To root: `"type": "module"`
  - To the scripts property: `"test": "node --experimental-vm-modules node_modules/jest/bin/jest.js"`
- The above will allow Jest to use ES6-style imports as well.
