# 使用指南

[返回首页](index.md)

1. 修改 docs 目录中的 Markdown 文件。
2. 在本地预览并检查页面及链接。
3. 提交修改并推送到 main 分支。
4. 在 Actions 页面查看构建与部署状态。
5. 打开网站检查内容是否更新。

## 常用命令

在本地使用终端运行以下命令，可以极大提高效率：

```bash
# 启动本地预览服务器
python -m mkdocs serve

# 构建网站并严格检查警告（Actions里就用的这个）
python -m mkdocs build --strict