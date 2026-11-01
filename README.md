# englishweb

零基础英语学习网站：语法课堂、阅读实验室、生词本、练习中心、词组学习与翻译练习。

## 在线访问

https://wangjun070301-art.github.io/englishweb/

## 本地运行

直接用静态服务器打开本目录，例如：

```bash
python -m http.server 8000
```

然后访问 `http://127.0.0.1:8000/`。

## 部署

站点为纯静态资源，`main` 分支根目录即发布目录，GitHub Pages 使用 `main` 分支 `/` 路径。学习数据保存在浏览器 `localStorage`，不会上传到服务器。

## 目录

- `index.html` — 页面入口
- `styles.css` — 站点样式
- `app.js` — 主应用逻辑
- `practice.js` — 练习中心
- `phrase-learning.js` / `phrase-data.js` — 词组学习
- `translation-practice.js` / `translation-data.js` — 翻译练习
- `grammar-data.js` — 语法课程数据
- `cet4-words.js` — 四级词表
- `videos.js` — 视频映射
- `ui-enhancements.js` — 主题、字号、FAQ 等增强