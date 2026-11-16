# 我的技术文档

这是使用 MkDocs + GitHub Actions 自动部署到 GitHub Pages 的实践项目。

- 网站链接：https://7uuu-uuu.github.io/my-docs/
- 个人实验报告：[点击这里查看我的实验报告](report/README.md)

## 本地预览命令

如果你想在本地运行此项目，请执行以下命令：

```bash
python -m venv .venv
source .venv/Scripts/activate  # Windows Git Bash
python -m pip install -r requirements.txt
python -m mkdocs serve