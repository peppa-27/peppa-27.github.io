# peppa-27 的小小开发部

一个轻松的二次元风格个人主页，放一点代码、一点项目和一点碎碎念。

访问地址：[peppa-27.github.io](https://peppa-27.github.io/)

## 页面内容

个人介绍、项目展示、技能标签、歌单和待更新的笔记入口。页面使用原生 HTML 与 CSS 编写，样式直接放在 `index.html` 中，没有额外的前端框架和构建步骤。

## 本地预览

可以直接用浏览器打开 `index.html`，也可以在仓库根目录启动静态文件服务：

```bash
python -m http.server 8000
```

然后访问 <http://localhost:8000>。

## 文件说明

| 文件 | 用途 |
| --- | --- |
| `index.html` | 页面内容、布局和样式 |
| `1.png` | 页面背景图 |
| `background_title.png` | 仓库中的另一张图片素材，当前页面未引用 |

## 日常更新

在 `index.html` 中修改个人介绍、项目卡片、链接和笔记内容；更换背景时，更新 `1.png` 或对应 CSS 图片路径即可。

仓库作为 GitHub Pages 个人站点使用，具体发布分支和方式以仓库的 **Settings → Pages** 配置为准。
