# awesome-actions

A curated list of awesome actions to use on GitHub

### 官方资源

- [官方站点](https://github.com/features/actions)
- [官方文档](https://help.github.com/en/actions)
- [官方 Actions 组织](https://github.com/actions)
  - [GitHub Actions 虚拟环境](https://github.com/actions/virtual-environments)
  - [GitHub Actions 运行器](https://github.com/actions/runner)

### 常用工作流示例

- [基础工作流](https://github.com/actions/starter-workflows)
- [服务容器示例工作流](https://github.com/actions/example-services)

### 官方 Actions

#### 工作流工具 Actions

- [actions/checkout](https://github.com/actions/checkout) - 设置并获取仓库代码
- [actions/upload-artifact](https://github.com/actions/upload-artifact) - 上传工作流生成的文件
- [actions/download-artifact](https://github.com/actions/download-artifact) - 下载构建的文件
- [actions/cache](https://github.com/actions/cache) - 缓存依赖和构建输出
- [actions/github-script](https://github.com/actions/github-script) - 编写 GitHub API 脚本

#### GitHub 自动化 Actions

- [actions/create-release](https://github.com/actions/create-release) - 创建 GitHub 发布版本
- [actions/upload-release-asset](https://github.com/actions/upload-release-asset) - 上传发布资源
- [actions/stale](https://github.com/actions/stale) - 标记长期未更新的 issues 和 PR
- [actions/labeler](https://github.com/actions/labeler) - 自动给 PR 打标签

#### 设置编程语言环境

- [actions/setup-node](https://github.com/actions/setup-node) - 设置 Node.js 环境
- [actions/setup-python](https://github.com/actions/setup-python) - 设置 Python 环境
- [actions/setup-java](https://github.com/actions/setup-java) - 设置 Java 环境

### 创建自定义 Actions

- [actions/toolkit](https://github.com/actions/toolkit) - 开发 GitHub Actions 的工具包
- [actions/hello-world-javascript-action](https://github.com/actions/hello-world-javascript-action) - JavaScript Actions 示例模板

### 社区资源

- [同步 GitHub 标签](https://github.com/micnncim/action-label-syncer)
- [GitHub Release 自动化发布](https://github.com/elgohr/Github-Release-Action)
- [GitHub 本地运行 Actions](https://github.com/nektos/act) - 在本地终端运行 GitHub Actions
- [构建并发布 Android 调试 APK](https://github.com/ShaunLWM/action-release-debugapk)

### 工具与实用 Actions

- [SSH-Agent 设置](https://github.com/webfactory/ssh-agent) - 配置多 SSH 密钥访问私有仓库
- [生成 GitHub Actions 状态徽章](https://github.com/atrox/github-actions-badge)
- [在 GitHub Actions 中运行 LaTeX 编译](https://github.com/xu-cheng/latex-action)
- [自动标签或指派 Issues](https://github.com/Naturalclar/issue-action)
- [GitHub Wiki 页面操作](https://github.com/Andrew-Chen-Wang/github-wiki-action)

### 常见编程语言与工具的 GitHub Actions

- [Terraform](https://github.com/hashicorp/setup-terraform)
- [Golang](https://github.com/cedrickring/golang-action)
- [PHP](https://github.com/shivammathur/setup-php)
- [Rust](https://github.com/actions-rs)
- [Flutter](https://github.com/subosito/flutter-action)

### 环境配置

- 创建环境文件 [链接](https://github.com/SpicyPizza/create-envfile)
- 导出全局环境变量用于后续构建步骤 [链接](https://github.com/zweitag/github-actions)
- 设置环境变量供后续步骤使用 [链接](https://github.com/allenevans/set-env)
- 安装 Conda 环境 [链接](https://github.com/goanpeca/setup-miniconda)

### 依赖管理

- 使用缓存安装 NPM 依赖 [链接](https://github.com/bahmutov/npm-install)
- 高亮显示新添加的 NPM 依赖 [链接](https://github.com/hiwelo/new-dependencies-action)
- 缓存 NPM 依赖 [链接](https://github.com/c-hive/gha-npm-cache)
- 缓存 Yarn 依赖 [链接](https://github.com/c-hive/gha-yarn-cache)

### 语义化版本管理

- 自动生成下一个版本号 [链接](https://github.com/WyriHaximus/github-action-next-semvers)
- 根据搜索字符串获取最新版本和分支名 [链接](https://github.com/jessicalostinspace/github-action-get-regex-branch)
- 更新语义化版本 [链接](https://github.com/christian-draeger/increment-semantic-version)

### 静态分析

- PHP 静态代码分析 [链接](https://github.com/OskarStark/phpstan-ga)
- GraphQL 检查器 [链接](https://github.com/kamilkisiela/graphql-inspector)
- PowerShell 静态分析 [链接](https://github.com/devblackops/github-action-psscriptanalyzer)

### 测试

- 通过 Puppeteer 运行测试 [链接](https://github.com/ianwalter/puppeteer)
- 发送测试结果到 Slack [链接](https://github.com/ivanklee86/xunit-slack-reporter)
- 运行 TestCafe 测试 [链接](https://github.com/DevExpress/testcafe-action)
- 运行 Cypress E2E 测试 [链接](https://github.com/cypress-io/github-action)

### 代码风格检查

- PHP 代码风格修复 [链接](https://github.com/OskarStark/php-cs-fixer-ga)
- 使用 ESLint 检查 JavaScript 代码 [链接](https://github.com/reviewdog/action-eslint)
- 自动格式化 Python 代码 [链接](https://github.com/peter-evans/autopep8)
- 运行 TSLint 检查 TypeScript 代码 [链接](https://github.com/mooyoul/tslint-actions)

### 安全性

- Docker 镜像漏洞扫描 [链接](https://github.com/phonito/phonito-scanner-action)
- 自动合并 Dependabot 更新 [链接](https://github.com/ridedott/dependabot-auto-merge-action)

### 代码覆盖率

- SonarCloud 扫描代码 [链接](https://github.com/sonarsource/sonarcloud-github-action)
- 将代码覆盖率数据发送到 Codecov [链接](https://github.com/codecov/codecov-action)

### 性能监控

- 使用 Lighthouse 检查网页性能 [链接](https://github.com/jakejarvis/lighthouse-action)
- 检查代码包大小限制 [链接](https://github.com/carlesnunez/check-my-bundlephobia)

### Pull Request 管理

- 自动设置 PR 审核人 [链接](https://github.com/pullreminders/assignee-to-reviewer-action)
- 自动合并准备好的 PR [链接](https://github.com/pascalgn/automerge-action)
- 自动为 PR 添加标签 [链接](https://github.com/banyan/auto-label)

### GitHub Pages

- 部署静态网站到 GitHub Pages [链接](https://github.com/peaceiris/actions-gh-pages)
- 部署 Hugo 网站到 GitHub Pages [链接](https://github.com/khanhicetea/gh-actions-hugo-deploy-gh-pages)

### 通知和消息

- [发送 Discord 通知](https://github.com/Ilshidur/action-discord)
- [通过 GitHub Actions 发送 Slack 消息](https://github.com/pullreminders/slack-action)
- [通过 GitHub Actions 发送 SMS (Nexmo)](https://github.com/nexmo-community/nexmo-sms-action)
- [发送 Telegram 消息](https://github.com/appleboy/telegram-action)
- [发送邮件 (SendGrid)](https://github.com/peter-evans/sendgrid-action)
- [发送 Push 通知 (Pushbullet)](https://github.com/ShaunLWM/action-pushbullet)

### 部署

- [部署到 Netlify](https://github.com/netlify/actions)
- [部署静态网站到 Azure 存储](https://github.com/feeloor/azure-static-website-deploy)
- [通过 GitHub Actions 部署 Docker 镜像](https://github.com/machine-learning-apps/gpr-docker-publish)
- [通过 GitHub Actions 部署 VS Code 插件](https://github.com/lannonbr/vsce-action)

### Docker

- [更新 Docker Hub 仓库描述](https://github.com/peter-evans/dockerhub-description)
- [通过 GitHub Actions 发布 Docker 镜像到 Amazon ECR](https://github.com/appleboy/docker-ecr-action)

### Kubernetes

- [部署到 Kubernetes](https://github.com/steebchen/kubectl)

### AWS

- [同步上传文件到 AWS S3](https://github.com/jakejarvis/s3-sync-action)
- [部署 Lambda 代码到 AWS](https://github.com/appleboy/lambda-action)

### Terraform

- [生成 Terraform 文档](https://github.com/Dirrk/terraform-docs)

### 外部服务

- [Firebase GitHub Action](https://github.com/w9jds/firebase-action)
- [Google Cloud Platform (GCP) GitHub Action](https://github.com/exelban/gcloud)

### 机器学习

- [查询 Weights & Biases 实验结果](https://github.com/machine-learning-apps/wandb-action)

### 构建工具

- [通过 GitHub Actions 构建 Go 应用程序](https://github.com/izumin5210/action-go-crossbuild)

### 数据库

- [设置 Cassandra 模式](https://github.com/fabasoad/setup-cassandra-action)

### 网络

- [通过 GitHub Actions 设置 ZeroTier 网络](https://github.com/zerotier/github-action)

### 本地化

- [自动修正代码中的拼写和语法问题](https://github.com/sobolevn/misspell-fixer-action)
- [翻译文本](https://github.com/fabasoad/translation-action)

### 有趣

- [在 README 中添加“点赞”按钮](https://github.com/ariary/Readme-Like-Button)

### GitHub Actions 备忘单

- [GitHub Actions 品牌备忘单](https://haya14busa.github.io/github-action-brandings/)
