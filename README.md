# Amazon HQ2 Proposals

This repo contains a simple single page app that aggregates links to all the
Amazon HQ2 proposals that can be found on the internet.

## Adding a Proposal

You found a proposal somewhere online? This is *great* news! :tada:

Adding it to this app is pretty simple. If you edit `index.html`, you'll see a
`PROPOSALS` variable along the top. All you need to do is populate it with the
data you found about said proposal and open a PR to get it published.

```json
{
  "location": "Portland, OR",
  "country": "United States",
  "loc": [45.5231, -122.6765],
  "pdf": "https://greaterportlandinc.com/assets/documents/greaterportlandinc-amazonhq2.pdf",
  "video": "",
  "website": "",
  "locations": ""
}
```

## Development

Development requires node and NPM. To setup your environment, just run `npm
install`. The only real "build" step is to compile the CSS, which can be done
with `npm run-script build`.

## Contributors

* [Sebastian Prokuski](https://github.com/sprokusk)
* [Brad Heller](https://github.com/bradhe)
* [Daniel Levine](https://github.com/dlevine815)
