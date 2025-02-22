---
title: gitee-pages-action
categories: ['python', 'actions', 'gitee-pages']
---
## [gitee-pages-action](https://github.com/yanglbme/gitee-pages-action)

### 🤖 Auto Deploy Gitee Pages by GitHub Action | 无须人为干预，由 GitHub Action 自动部署 Gitee Pages


| 参数             | 描述                         | 是否必传 | 默认值   | 示例                            |
| ---------------- | ---------------------------- | -------- | -------- | ------------------------------- |
| `gitee-username` | Gitee 用户名                 | 是       | -        | `yanglbme`                      |
| `gitee-password` | Gitee 密码                   | 是       | -        | `${{ secrets.GITEE_PASSWORD }}` |
| `gitee-repo`     | Gitee 仓库（严格区分大小写） | 是       | -        | `doocs/leetcode`                |
| `branch`         | 要部署的分支（分支必须存在） | 否       | `master` | `main`                          |
| `directory`      | 要部署的分支上的目录         | 否       |          | `src`                           |
| `https`          | 是否强制使用 HTTPS           | 否       | `true`   | `false`                         |
