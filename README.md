# @aemeath-projects/fonts

"Lahai-Roi"、"Ragunna" 和 "Septimont" 字体的 CSS 及 Web 字体文件。基于 Fontsource v5 规范构建

## 快速安装

```bash
pnpm install @aemeath-projects/fonts
```

## 使用方式

在应用入口文件或站点组件中导入 CSS：

```js
import "@aemeath-projects/fonts";               // 默认 — Lahai-Roi weight 400
import "@aemeath-projects/fonts/lahai-roi.css"; // 仅 Lahai-Roi
import "@aemeath-projects/fonts/ragunna.css";   // 仅 Ragunna
import "@aemeath-projects/fonts/septimont.css"; // 仅 Septimont
import "@aemeath-projects/fonts/400.css";       // 所有字体家族，weight 400
```

## 支持的字体家族

| 字体家族         | 字重   | 样式    | 子集   |
| ---------------- | ------ | ------- | ------ |
| Lahai-Roi        | 400    | normal  | latin  |
| Ragunna          | 400    | normal  | latin  |
| Septimont        | 400    | normal  | latin  |

## CSS 用法

```css
body {
  font-family: "Lahai-Roi", sans-serif;
}

h1 {
  font-family: "Ragunna", cursive;
}

code {
  font-family: "Septimont", monospace;
}
```

## 许可证

SIL Open Font License, Version 1.1 (OFL-1.1)。详见 [LICENSE](./LICENSE)。
