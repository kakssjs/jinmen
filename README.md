# 津门游 · 天津沉浸式文化之旅

一个以天津城市文化为主题的互动网页项目，通过文化浏览、旅程探索与小游戏体验津门风貌。

## 内容与玩法

- 首页：城市文化展示与互动入口。
- 文化页面与旅程页面：浏览天津特色文化，探索主题内容。
- 海河漂流、通关文牒、津门寻宝、时光穿越：四个独立互动游戏。
- 印章收集：完成游戏后在首页查看印章；进度使用浏览器 localStorage 保存在当前浏览器中，可通过首页重置。

## 本地运行

项目使用 HTML、CSS 和 JavaScript，无需安装前端依赖或执行构建。安装 Python 3 后运行：

```bash
git clone https://github.com/kakssjs/jinmen.git
cd jinmen
python -m http.server 8000
```

打开 http://localhost:8000 即可。也可使用现有的静态文件服务器。页面引用 Google Fonts，字体加载需要网络连接。

## 文件结构

| 文件或目录 | 用途 |
| --- | --- |
| `index.html` | 首页与印章展示 |
| `culture.html` | 文化内容 |
| `journey.html` | 旅程入口 |
| `game1-river.html` | 海河漂流 |
| `game2-passport.html` | 通关文牒 |
| `game3-treasure.html` | 津门寻宝 |
| `game4-timetravel.html` | 时光穿越 |
| `assets/` | 图片等静态资源 |

## 继续开发

优先在对应页面中修改现有 HTML、样式与脚本，复用已有资源及进度存储规则。修改后检查页面导航、游戏交互、印章展示、进度持久化与移动端布局。

许可证内容见 [LICENSE](LICENSE)。
