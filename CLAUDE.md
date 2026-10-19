# LearNew (SmartLearn)

Single-file PWA (`index.html` + `sw.js`) that builds personal courses with the Google Gemini API.

## Versioning
On every change, bump the version in **both** places, keeping them equal:
- `sw.js`: `CACHE_NAME = 'smartlearn-cache-vN'`
- `index.html` header: `<span ...>vN</span>` next to "SmartLearn"
