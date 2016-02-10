Ideas:
- `.gitignore` file: Get rid of these `.DS_Store` files
- Update jQuery (Better yet: Use CDN version)
- Do we really need `parsley.js`?
- Code style guide
- `imageData` from `api.js` will probably not behave as expected. It might not have the data at the time we expect it to have. Rather use callback or promise-style `$.ajax` API
- Step 1: Build a namespace for our functions -> Step 2: IIFEs for better capsulation

Nitpicks:
- Remove `readme.txt`
