# Wuwa Fonts

鸣潮字体库

![NPM Version](https://img.shields.io/npm/v/%40aemeath-projects%2Fwuwa-fonts?style=for-the-badge)
![License](https://img.shields.io/github/license/aemeath-projects/wuwa-fonts?style=for-the-badge)

## 快速安装

```bash
npm install @aemeath-projects/wuwa-fonts
```

在应用入口文件或站点组件中导入即可。

```js
import "@aemeath-projects/wuwa-fonts";               // 默认 — Lahai-Roi, weight 400
import "@aemeath-projects/wuwa-fonts/lahai-roi.css"; // 仅 Lahai-Roi
import "@aemeath-projects/wuwa-fonts/ragunna.css";   // 仅 Ragunna
import "@aemeath-projects/wuwa-fonts/septimont.css"; // 仅 Septimont
import "@aemeath-projects/wuwa-fonts/400.css";       // 所有家族, weight 400
```

## 支持的字体家族

| 字体家族   | 字重 | 样式   | 子集  |
|-----------|------|--------|-------|
| Lahai-Roi | 400  | normal | latin |
| Ragunna   | 400  | normal | latin |
| Septimont | 400  | normal | latin |

## CSS 用法

导入后即可在 CSS 样式表、CSS Module 或 CSS-in-JS 中引用字体名称。

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

在使用字体进行商业用途前，请务必仔细阅读 SIL Open Font License 1.1。如有疑问，请参阅 OFL 常见问题解答。字体文件本身基于 OFL-1.1 许可。

本项目与原始字体作者无关，原作者：[哔哩哔哩](https://www.bilibili.com/video/BV16E6jB1EVy)。

