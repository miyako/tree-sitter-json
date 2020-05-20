tree-sitter-4djson
===========================

Fork of [tree-sitter-json](https://github.com/tree-sitter/tree-sitter-json)

#### Notes

* To update node module(s) following security alert:

```
export PATH="$PATH:./node_modules/.bin/"

npm install npm-check-updates
ncu –u
npm install

tree-sitter generate
node-gyp configure
node-gyp build
apm publish patch
npm publish
```

https://www.netwoven.com/2017/03/21/how-to-update-node-js-modules-to-latest-versions/
