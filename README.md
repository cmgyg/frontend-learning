前端工程化学习笔记
一、Git 版本控制
常用命令
bash
git init                  # 初始化仓库
git add .                 # 添加所有文件到暂存区
git commit -m "信息"       # 提交
git push                  # 推送到远程
git pull                  # 拉取远程更新
git status                # 查看状态
git log --oneline         # 查看提交历史
提交规范
bash
feat: 新功能
fix: 修复bug
docs: 文档更新
style: 代码样式
refactor: 重构
chore: 构建工具
二、项目初始化
必备文件
README.md - 项目说明文档

.gitignore - 忽略不需要提交的文件

.gitignore 核心内容
text
node_modules/
dist/
.env
.DS_Store
*.log
三、工作流程
text
修改代码 → git add . → git commit -m "信息" → git push
四、工程化核心概念
概念	说明
版本控制	Git 管理代码历史
构建工具	Webpack/Vite 打包编译
代码规范	ESLint + Prettier
包管理	npm/yarn/pnpm
自动化	CI/CD 持续集成
五、常用工具
包管理：npm / yarn / pnpm

构建：Webpack / Vite

代码检查：ESLint

代码格式化：Prettier

Git钩子：husky

