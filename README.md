[Web API Controversy](https://webapicontroversy.com)

**Work in progress, help is very appreciated**

## Building

Running

```sh
$ npm install
```

```
$ npm run build
```

will build `index.html`. Commit that file to master and update `gh-pages` branch to the same commit. By pushing to the repository, the live version of the website is updated.

## Data

All the data for the table is in `data.json`.

The browsers are defined in the `browser` property. The logo for the browser must be in the `logos` directory and must be named `${browser.tag}.svg`.

The APIs are defined in teh `api` property.

If a “Details” button is clicked, a “dialog” is openend, showing the contents of `partials/${api.tag}_${browser.tag}.html`.

## Based on

[Is Houdini Ready Yet?](https://ishoudinireadyyet.com)

## License
Apache 2

