# GLaDOS_Checkin
GLaDOS automatic check-in bypassing CloudFlare using github action

## 功能描述
1. 每日自动进行签到（本项目可通过CloudFlare反爬机制）

## 使用方法
### 1. 添加 Cookie 至 Secrets
- 建立名为`GLADOS_COOKIE`的 secret，值为`Cookie`内容，最后点击`Add secret`
### 2. 启用 Actions
- 本项目由Workflow控制，每日0时10分自动执行。
- 本项目目前可以正常运行，如果有其他使用问题请在Issues留言。
