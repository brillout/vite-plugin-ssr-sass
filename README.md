Example of using [`vite-plugin-ssr`](https://vite-plugin-ssr.com) with [Sass](https://sass-lang.com/).

To add Sass support, all we have to do is to add `sass` in the list of dependencies,
see this commit [cdefbe22](https://github.com/brillout/vite-plugin-ssr-sass/commit/cdefbe2237db47c8bb8c966f3bfe46f4dd4943b5) and
see [Vite Docs - CSS pre-processors](https://vitejs.dev/guide/features.html#css-pre-processors).

For Vue users: note how the `.vue` SFC components use `<style lang="sass">`.

For React users: note how Sass files are imported from `_default.client.js` (you can also import your Sass files from `PageLayout.jsx` or any other component).

To run this example:
```bash
git clone git@github.com:brillout/vite-plugin-ssr-sass
cd vite-plugin-ssr-sass/
npm install
npm run dev
```
