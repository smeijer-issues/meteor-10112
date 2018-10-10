```bash
git clone git@github.com:smeijer/meteor-10112.git
meteor npm install
meteor --production
```

```bash
=> Started proxy.
=> Started MongoDB.
=> Errors prevented startup:

   While minifying app stylesheet:
   packages/minifyStdCSS_plugin.js:130:34: Cannot read property 'getContentsAsString' of undefined
   at packages/minifyStdCSS_plugin.js:130:34
   at Array.map (<anonymous>)
   at packages/minifyStdCSS_plugin.js:129:32
   at CssToolsMinifier.processFilesForBundle (packages/minifyStdCSS_plugin.js:33:16)


   While minifying app stylesheet:
   packages/minifyStdCSS_plugin.js:130:34: Cannot read property 'getContentsAsString' of undefined
   at packages/minifyStdCSS_plugin.js:130:34
   at Array.map (<anonymous>)
   at packages/minifyStdCSS_plugin.js:129:32
   at CssToolsMinifier.processFilesForBundle (packages/minifyStdCSS_plugin.js:33:16)


=> Your application has errors. Waiting for file change.
```
