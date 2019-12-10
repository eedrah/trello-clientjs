# trello-clientjs

This package is the downloaded version of [Trello's client-unminified.js](https://api.trello.com/1/client-unminified.js), to be `require`d in nodejs or in the browser.

It contains nothing else other than a script in package.json to download `client-unminified.js` and the downloaded file.

We use the unminified version so you can do your own minification in your bundle.

## Contributing

Let me know if you find this package ever out of date with Trello's `client.js`, and I'll run `npm version major && npm publish` to publish the new version.
