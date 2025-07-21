# 如何贡献

Fork 本仓库（右上角），然后添加一个新的 PR，当您的分支通过审核后，合并到主分支时，会触发 CI/CD，如果 action job 一切正常，会自动更新本文档（可能存在 5 分钟左右的延迟）。

文档支持以下 md 特性：

- Katex 的 latex 代码解析、渲染
- Mermaid 的流程图
- 高亮文本提示块，参见 [Flexible-Alerts](https://github.com/fzankl/docsify-plugin-flexible-alerts), 采用默认名称.

静态资源推荐放置在 md 同级目录下的 `static` 内, 建议上传文件大小不要超过 2MB, 或者外部链接图床.

## 推荐工作流

在 `docs` 里编辑文档内容，在 `_sidebar.md` 里编辑导航栏.

## 本地预览

本项目由 docsify 构建

```bash
npm i docsify-cli -g
docsify serve
```
