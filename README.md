在 InfluxDB 1.8 版本中，官方镜像没有像 MySQL 或 Postgres 那样直接通过环境变量（如 ADMIN_USER）来自动创建初始用户的机制

在 README 中加入使用说明，保存后用 git status 和 git diff 确认只改了需要的内容，再提交并推送分支。

git branch -d 分支名
