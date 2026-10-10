# Ruihan Wang 的个人主页

基于 [Academic Pages](https://academicpages.github.io/) 模板（Jekyll）搭建的学术主页，部署在 GitHub Pages：https://yaoweiwei-1005.github.io

## 目录结构（只保留实际用到的部分）

```
├── _config.yml        # 全站配置：姓名、头像、联系方式、社交账号等
├── _pages/            # 页面
│   ├── about.md       # 首页（自我介绍）
│   ├── cv.md          # CV 页
│   ├── awards.html        # 奖项页（自动列出 _awards/ 下的内容）
│   ├── publications.html  # 论文列表页（自动列出 _publications/ 下的内容）
│   ├── portfolio.html     # 学术服务页（同上，数据来自 _portfolio/）
│   ├── talks.html         # 报告页（数据来自 _talks/）
│   ├── teaching.html      # 授课页（数据来自 _teaching/）
│   ├── category-archive.html / tag-archive.html
│   └── 404.md
├── _publications/     # 论文，一篇论文一个 .md（夹内有 README 模板）
├── _portfolio/        # 学术服务（审稿等），一条一个 .md
├── _talks/            # 学术报告，一次一个 .md
├── _teaching/         # 授课/助教，一条一个 .md
├── _awards/           # 奖项荣誉，一个 .md
├── _data/
│   └── navigation.yml # 顶部导航栏（Publications/Service/Talks/Teaching/Awards）
├── _includes/ _layouts/ _sass/ assets/   # 模板主题核心，一般不用动
├── images/            # 头像 profile.png 和网站图标
└── files/             # 论文 PDF、slides 等附件（需要时再建）
```

## 常见修改

- **改个人信息 / 头像 / 邮箱 / GitHub 链接**：`_config.yml`
- **改导航栏**：`_data/navigation.yml`
- **加一篇论文**：在 `_publications/` 下按里面 README 的模板新建 .md；PDF 放 `files/`
- **加奖项/报告/授课/服务**：分别在 `_awards/`、`_talks/`、`_teaching/`、`_portfolio/` 下新建 .md，格式见各自文件夹里的 README
- **改首页自我介绍**：`_pages/about.md`
- **改 CV**：`_pages/cv.md`

模板完整文档见 https://academicpages.github.io/
