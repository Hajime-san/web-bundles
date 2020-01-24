# Read docs
[https://web.dev/web-bundles/](https://web.dev/web-bundles/)

[https://github.com/WICG/webpackage/tree/master/go/bundle](https://github.com/WICG/webpackage/tree/master/go/bundle)

[https://www.npmjs.com/package/wbn](https://www.npmjs.com/package/wbn)

# generate .wbn

## with Golang

```gen-bundle -dir dist -baseURL https://example.org -primaryURL https://example.org -o app.wbn```

## with Node.js npm

```npx wbn --dir dist --baseURL https://example.org/ --output out.wbn```
