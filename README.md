
## pnpm install

> 注：本项目使用 pnpm 作为包管理工具，请升级 Node 版本到 16.22.2 以上

<img
alt="Static Badge"
src="https://img.shields.io/badge/%E8%84%9A%E6%89%8B%E6%9E%B6-vite-red" />
<img
alt="Static Badge"
src="https://img.shields.io/badge/%E5%89%8D%E7%AB%AF%E6%A1%86%E6%9E%B6-Vue3-%236495ed" />
<img
alt="Static Badge"
src="https://img.shields.io/badge/UI-TailWind-green" />
<img
alt="Static Badge"
src="https://img.shields.io/badge/%E8%84%9A%E6%9C%AC%E8%AF%AD%E8%A8%80-TypeScript-%25236495ed" />
<img
alt="Static Badge"
src="https://img.shields.io/badge/UI-fri_element_plus-%238a2be2" />

本以为会用到 postcss，结果还真没在 template 里写 css = = 习惯了 TW 是真的爽。
在优化实践章节已去掉。

## 配置参考

### postcss.config.cjs

参考官网配置即可 <https://tailwindcss.com/docs/installation>

```js
module.exports = {
  plugins: [
    require('postcss-import'),
    require('postcss-nested'),
    require('autoprefixer'),
    require('tailwindcss'),
    require('tailwindcss/nesting'),
  ],
}
```

### vite.config.js

为打包后的文件提供传统浏览器兼容性支持

> Vite 社区还有很多实用插件，可自行尝试

- compression 打包生成 .gz
- chunkSplitPlugin 打包不同的 vendor
- prefetchPlugin 打包后的 .html 添加 prefetch


### 以上為原作者付寅生提供
在線瀏覽 [blue4545.netlify.app](https://blue4545.netlify.app/)
