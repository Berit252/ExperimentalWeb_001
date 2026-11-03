# SYMBIONT · 共生实验室

一个以模块化微观生物为灵感的交互网页。纯 HTML、CSS、JavaScript，无构建步骤或 npm 依赖。

## 本地体验

安装 Git 和 Python 3，然后运行：

```bash
git clone https://github.com/Berit252/ExperimentalWeb_001.git
cd ExperimentalWeb_001
python3 -m http.server 3000
```

Windows 可将最后一行替换为 `py -m http.server 3000`。
在**自己电脑**浏览器打开 http://localhost:3000 。按 Ctrl+C 停止服务。
也可以直接双击 `index.html` 打开体验。

## 交互

- 在培养皿内移动鼠标，生物会避让和摆动；点击产生涟漪。
- 不操作时，翼膜、触须和个体持续自然游动。
- 切换翼膜、花冠、游丝结构及五种色素，调整生命活性。
- 默认每 30 秒自动繁衍，后代混合不同形态和颜色，逐渐长大。
- 可暂停自动繁衍、手动触发或重置实验；最多保留 7 个个体。

## 文件

- `index.html`：页面与控制台
- `style.css`：桌面与手机布局
- `app.js`：Canvas 动画、交互和繁衍逻辑

可选字体来自 Google Fonts；不可访问时使用本地字体，不影响交互。
