# watchify-issue144
Demonstrate Issue #144 https://github.com/substack/watchify/issues/144

```
npm install

npm run watch
```

You will find that bundle.js is created, but after modifying index.js and saving, the bundle.js size goes to 0 and it is not rebuilt.
