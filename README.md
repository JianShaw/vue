## 如何开启sourceMap

在`package.json`的`scripts:dev`修改为`"rollup -w -c scripts/config.js --environment TARGET:web-full-dev  --sourcemap"`。在执行`npm run dev`后就会在`dist`目录下出现`vue.js.map`文件。

打开`examples`下任意文件夹目录，将`html`文件引入的`vue.min.js`修改为`vue.js`即可。
