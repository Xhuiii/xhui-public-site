# Xhuiiii / Career

何小慧的公开职业展示网站，呈现产品体验设计方向、2022–2026 年成长路径、四个代表项目和邮箱联系。

## 内容范围

四个项目方向为畅连与无网通信、短信与智能信息、智控键、全场景协同。项目图用于解释交互关系；概念探索明确标注，不代表正式上线效果。

## 文件结构

- index.html：主页面，内含样式和交互。
- career/index.html：兼容 Career 路径并跳转到首页。
- .nojekyll：静态页面配置。
- robots.txt：搜索引擎抓取规则。

## 版本和维护

当前为基于 Career v0.4 整理的公开候选版，移除了未完成的照片、视频和简历占位。完整个人系统和原版历史归档单独保存。

纯静态页面，无需安装依赖。仓库上传与网站上线是两个步骤；托管尚需另外配置。后续只将确认适合公开的页面和素材加入此仓库。

## Public portfolio layer / 公开作品层

This repository is the curated public layer of the personal work system. It contains finished or intentionally public projects, selected capability evidence, public-facing writing, and the website that presents them.

这个仓库是个人工作系统的精选公开层，只收纳已经完成或明确允许公开的项目、精选能力证据、面向公众的表达，以及用于展示这些内容的网站。

The full personal atlas remains private. Drafts, unfinished experiments, private planning, personal records, sensitive evidence, and unreleased plans stay in the private source repository.

完整的个人 Atlas 保持私有。草稿、未完成实验、私人规划、个人记录、敏感证据和未公开规划，都留在私有源仓库中。

## Structure / 结构

- `content/projects/`: selected public project stories / 精选公开项目案例
- `content/capabilities/`: verified public capability evidence / 已验证的公开能力证据
- `content/profile/`: public profile and short biography / 公开个人介绍与轻量简介
- `index.html` and `career/`: current public website routes / 当前公开网站页面与路由

The structured content layer is being prepared gradually. The current HTML page remains intact while new content is added in small, reviewable changes.

结构化内容层会逐步建立。当前 HTML 页面保持不变，后续新增内容采用小步、可审查的方式进行。

## Public boundary and review / 公开边界与审查

Before adding content, confirm that it is intentionally public, useful to an external reader, free of private or confidential information, and accurate enough to serve as public evidence. Every meaningful public change should go through a Pull Request before entering `main`.

新增内容前必须确认：内容明确允许公开、对外部读者有价值、不包含私人或保密信息，并且足够准确，可以作为公开证据使用。每个有意义的公开改动都必须先经过 Pull Request 审查，再进入 `main`。

Do not copy the private atlas wholesale into this repository. Publish a finished, understandable result instead of the entire working process.

不要把私有 Atlas 整体复制到这里。公开已经完成、可理解的成果，而不是公开全部工作过程。
