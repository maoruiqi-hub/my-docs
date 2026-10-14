# my-docs

基于 MkDocs 的示例文档项目，通过 GitHub Actions 自动构建并部署到 GitHub Pages。

## 本地预览

```bash
pip install mkdocs-material
mkdocs serve
```

## 部署

推送到 `main` 分支（改动 `docs/**` 或 `mkdocs.yml`）后，GitHub Actions 会自动构建并发布到 `gh-pages` 分支。

访问地址：https://maoruiqi-hub.github.io/my-docs/
