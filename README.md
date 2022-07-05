This is a starter template for [Learn Next.js](https://nextjs.org/learn).

## Bitmovin steps to fail

```
npm run dev
```

We get this error in the console:

```
> @ dev /home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail
> next dev

ready - started server on 0.0.0.0:3000, url: http://localhost:3000
event - compiled client and server successfully in 1480 ms (158 modules)
wait  - compiling / (client and server)...
event - compiled client and server successfully in 1572 ms (229 modules)
wait  - compiling /_error (client and server)...
event - compiled client and server successfully in 57 ms (230 modules)
TypeError: document.querySelector is not a function
    at new StyleSheet (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/styled-jsx/dist/index/index.js:136:44)
    at new StyleSheetRegistry (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/styled-jsx/dist/index/index.js:491:33)
    at Object.createStyleRegistry (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/styled-jsx/dist/index/index.js:667:10)
    at Object.renderToHTML (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/render.js:348:46)
    at async doRender (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/base-server.js:917:38)
    at async cacheEntry.responseCache.get.isManualRevalidate.isManualRevalidate (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/base-server.js:1022:28)
    at async /home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/response-cache.js:69:36
error - TypeError: document.querySelector is not a function
    at new StyleSheet (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/styled-jsx/dist/index/index.js:136:44)
    at new StyleSheetRegistry (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/styled-jsx/dist/index/index.js:491:33)
    at Object.createStyleRegistry (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/styled-jsx/dist/index/index.js:667:10)
    at Object.renderToHTML (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/render.js:348:46)
    at async doRender (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/base-server.js:917:38)
    at async cacheEntry.responseCache.get.isManualRevalidate.isManualRevalidate (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/base-server.js:1022:28)
    at async /home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/response-cache.js:69:36
TypeError: document.querySelector is not a function
    at new StyleSheet (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/styled-jsx/dist/index/index.js:136:44)
    at new StyleSheetRegistry (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/styled-jsx/dist/index/index.js:491:33)
    at Object.createStyleRegistry (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/styled-jsx/dist/index/index.js:667:10)
    at Object.renderToHTML (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/render.js:348:46)
    at async doRender (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/base-server.js:917:38)
    at async cacheEntry.responseCache.get.isManualRevalidate.isManualRevalidate (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/base-server.js:1022:28)
    at async /home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/response-cache.js:69:36
TypeError: document.querySelector is not a function
    at new StyleSheet (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/styled-jsx/dist/index/index.js:136:44)
    at new StyleSheetRegistry (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/styled-jsx/dist/index/index.js:491:33)
    at Object.createStyleRegistry (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/styled-jsx/dist/index/index.js:667:10)
    at Object.renderToHTML (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/render.js:348:46)
    at async doRender (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/base-server.js:917:38)
    at async cacheEntry.responseCache.get.isManualRevalidate.isManualRevalidate (/home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/base-server.js:1022:28)
    at async /home/mabasic/code/src/github.com/rtl-hrvatska/nextjs-bitmovin-fail/node_modules/next/dist/server/response-cache.js:69:36
```