# 广州漫游手册

<p align="center">
  <strong>一份用轻松路线发现广州的响应式静态旅行指南</strong><br>
  美食 · City Walk · 周末出逃 · 出行小提醒
</p>

<p align="center">
  <a href="https://github.com/Echo-cln/Guangzhou-Guide">GitHub 仓库</a> ·
  <a href="https://github.com/Echo-cln/Guangzhou-Guide/issues">反馈问题</a>
</p>

## 项目介绍

广州漫游手册是一个以广州城市漫游为主题的静态网站。它将餐饮推荐、城市步行路线、周末目的地和出行提示整理成可浏览、可跳转的页面，并使用原创插画与响应式布局呈现内容。

项目使用原生 HTML、CSS 与 JavaScript，可直接通过静态托管发布。它不需要服务器端业务服务或数据库。

## 页面与内容

| 页面 | 内容 |
| --- | --- |
| `index.html` | 首页与分类入口 |
| `overview.html` | 分类目录和内容概览 |
| `food.html` | 广州餐饮与地点推荐 |
| `citywalk.html` | 城市步行路线 |
| `weekend.html` | 周末出游目的地 |
| `tips.html` | 漫游与出行提示 |

页面中的分类入口、区域卡片和目录锚点可以在页面间导航。网站采用同一套响应式 HTML/CSS，适配桌面与移动屏幕。

## 预览

当前仓库使用 `main` 分支中的页面和素材。若仓库已连接 GitHub Pages 或其他静态托管，可在仓库的 Pages / 部署设置中查看线上地址；本 README 不固定填写未经核实的域名。

## 本地预览

无需安装依赖。克隆仓库后，可直接打开 `index.html`，或从仓库根目录启动一个静态文件服务器：

```bash
git clone https://github.com/Echo-cln/Guangzhou-Guide.git
cd Guangzhou-Guide
python -m http.server 8000
```

访问 `http://localhost:8000`。

## 项目结构

```text
.
├── index.html
├── overview.html
├── food.html
├── citywalk.html
├── weekend.html
├── tips.html
└── assets/
    ├── css/
    └── images/
```

图片素材按页面用途组织在 `assets/images/` 下。添加或替换图片时请同步检查页面中的相对路径和移动端裁切效果。

## 部署

### GitHub Pages

1. 将仓库推送到 GitHub。
2. 打开仓库 **Settings → Pages**。
3. 选择从 `main` 分支的根目录（`/`）发布。
4. 等待部署完成后使用 Pages 页面给出的地址访问。

也可将仓库导入支持静态站点的托管平台。项目没有构建步骤，发布仓库文件即可。

## 贡献指南

欢迎提出路线内容、无障碍体验、插画和页面交互方面的改进。提交 Issue 时请说明页面、设备/浏览器、复现步骤和预期效果；提交 Pull Request 时请尽量保持静态依赖轻量，并在桌面和窄屏下检查布局。

涉及餐饮、营业时间、交通或开放信息的贡献者应附上可核对的来源与核验日期。地点信息可能变化，出行前请再次确认。

## 免责声明

本项目为旅行信息整理与前端展示作品，不代表景点、商户或交通运营方。营业时间、路线、票务和开放情况可能变化，请以官方渠道及现场信息为准。

## 许可

请查看仓库根目录的许可证文件。若仓库没有许可证，代码和图片默认受版权法保护；复用或再发布前请先联系维护者。
