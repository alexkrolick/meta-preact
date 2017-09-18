# meta-preact

A metapackage that includes useful libraries for building web apps with [`preact`](https://github.com/developit/preact).

- CSS-in-JS with [Emotion](//emotion.sh)
- Linting with [Prettier](//prettier.io) and [ESLint](//eslint.org)
- Client-side routing with [Preact Router](https://github.com/developit/preact-router) (React-Router works well too, but isn't bundled)
- Modals/Popovers with [Preact Portal](https://github.com/developit/preact-portal)

## Usage

- Install `npm install --save alexkrolick/meta-preact`
- Copy `preact.config.js` to your project root to enable the customizations to the [`preact-cli`](https://github.com/developit/preact-cli) config, if you are using it.
- Add options to `package.json`

```json
{
    "eslintConfig": {
        "extends": ["eslint-config-alexkrolick"]
    }
}
