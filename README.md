# 眼视光分类实验成果汇报

公开网页由 `site/index.html` 提供。推送到 `main` 后，GitHub Actions 自动部署到 GitHub Pages。

在眼视光项目目录更新网页：

```sh
python3 code/build_eye_report.py --horizontal
cd 眼视光实验结果/在线汇报
git add site/index.html
git commit -m "Update report"
git push
```

生成脚本会同时更新项目内的左右翻页版 HTML 和本站首页。本站只有汇总结果、特征排名和图表，不包含逐位受试者的原始记录。
