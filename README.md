# STARFIELD 业务流程图

用一个 HTML 页面呈现 STARFIELD 产品的 9 个核心业务流程，方便产品讨论、需求梳理和评审。页面使用 Mermaid 10 绘制图表。

## 内容导航

1. 核心业务总览：获客、体验、留存、变现与增长。
2. 注册与首次体验：触达、授权、生辰输入、名片、匹配与聊天。
3. 匹配引擎数据流：输入、计算、AI 解读、评分与输出。
4. 用户生命周期与转化。
5. 增长裂变闭环。
6. 商业化与付费流程。
7. 技术架构数据流。
8. 产品版本演进与 Go/No-Go。
9. 关键漏斗与预警。

## 查看方式

下载后直接在浏览器打开 [index.html](./index.html)，或在仓库根目录运行：

```bash
python3 -m http.server 8000 --bind 127.0.0.1
```

然后访问 <http://127.0.0.1:8000>。Mermaid 从 jsDelivr 加载，首次打开需要网络连接。

## 修改与维护

图表定义、页面样式和初始化脚本集中在 `index.html`。修改对应的 `.mermaid` 区块后，在浏览器刷新并检查图表排版；页面包含打印样式，可通过浏览器打印为 PDF。

页面中的价格、转化目标、匹配权重及版本节点属于方案展示内容，使用时应与最新需求核对。

## 相关仓库

- [personal-site](https://github.com/wbx125133/personal-site)：个人网站与作品集。
- [AIPM-Vibecoding-Skill](https://github.com/wbx125133/AIPM-Vibecoding-Skill)：将产品想法整理成 AI 可执行 PRD。
