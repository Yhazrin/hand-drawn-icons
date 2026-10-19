# Yhazrin Hand-drawn Icons

来自 [Yhazrin 创作手记](https://blog.yhazrin.xyz/) 的手绘感 SVG 图标，和 [apple-motion-icons](https://github.com/Yhazrin/apple-motion-icons) 分开维护。

8 个图标：飞碟、信封、轨道球、眼睛、文件夹、打印机、设置、收纳筐。保留桌面版的原始路径、配色和描边；不依赖框架，不是 Apple 官方素材。

## 使用

```html
<img src="./icons/folder.svg" alt="文章" width="64" height="64">
```

或同源使用 sprite（隐藏装饰图标）：

```html
<svg width="64" height="64" fill="none" aria-hidden="true">
  <use href="./sprite.svg#icon-folder"></use>
</svg>
```

每个文件采用 80 × 80 viewBox，建议以 40–96px 显示。需要改色时直接编辑 SVG fill；请保留有意使用的黑白高光。`manifest.json` 给出名称、路径与 SHA256。

## 预览

直接打开 `index.html`，或在此目录运行 `python3 -m http.server 8080`。预览页只提供轻微悬停反馈，并尊重减少动态偏好。

## 范围与许可

MIT。此库只发布本站实现的 8 个矢量图标及预览代码，不包含博客全文、参考截图、第三方演示、字体、账户配置或网站部署文件。复古桌面和手绘风格是视觉方向，不表示与 Apple 或参考艺术家存在关联。未来新增图标请保持相同 viewBox、描边和可读性，并更新 manifest。
