DEMO
===========================

![](https://i.imgur.com/gw6xa2k.png)
## 环境依赖 ##
1.操作系统
node v0.10.28+
reids ~
2.依赖
3.其他软硬件要求

## 部署步骤 ##
1. 添加系统环境变量
    export $PORTAL_VERSION="production" // production, test, dev


2. npm install  //安装node运行环境

3. gulp build   //前端编译

4. 启动两个配置(已forever为例)
    eg: forever start app-service.js
        forever start logger-service.js


## 目录结构描述 ##


*   [1\. 探索GitHub](http://www.worldhello.net/gotgithub/01-explore-github/index.html)
    *   [1.1\. 什么是GitHub](http://www.worldhello.net/gotgithub/01-explore-github/010-what-is-github.html)
    *   [1.2\. GitHub亮点](http://www.worldhello.net/gotgithub/01-explore-github/020-github-hightlights.html)
    *   [1.3\. 探索GitHub](http://www.worldhello.net/gotgithub/01-explore-github/030-explore-github.html)
*   [2\. 加入GitHub](http://www.worldhello.net/gotgithub/02-join-github/index.html)
    *   [2.1\. 创建GitHub账号](http://www.worldhello.net/gotgithub/02-join-github/010-account-setup.html)
    *   [2.2\. 浏览托管项目](http://www.worldhello.net/gotgithub/02-join-github/020-browse-repo.html)
    *   [2.3\. 社交网络](http://www.worldhello.net/gotgithub/02-join-github/030-be-social.html)
*   [3\. 项目托管](http://www.worldhello.net/gotgithub/03-project-hosting/index.html)
    *   [3.1\. 创建新项目](http://www.worldhello.net/gotgithub/03-project-hosting/010-new-project.html)
        *   [3.1.1\. 新版本库即是新项目](http://www.worldhello.net/gotgithub/03-project-hosting/010-new-project.html#new-repo)
        *   [3.1.2\. 版本库初始化](http://www.worldhello.net/gotgithub/03-project-hosting/010-new-project.html#init-by-clone)
        *   [3.1.3\. 从已有版本库创建](http://www.worldhello.net/gotgithub/03-project-hosting/010-new-project.html#init-by-push)
    *   [3.2\. 操作版本库](http://www.worldhello.net/gotgithub/03-project-hosting/020-repo-operation.html)
        *   [3.2.1\. 强制推送](http://www.worldhello.net/gotgithub/03-project-hosting/020-repo-operation.html#noff-push)
        *   [3.2.2\. 新建分支](http://www.worldhello.net/gotgithub/03-project-hosting/020-repo-operation.html#new-branch)
        *   [3.2.3\. 设置默认分支](http://www.worldhello.net/gotgithub/03-project-hosting/020-repo-operation.html#default-branch)
        *   [3.2.4\. 删除分支](http://www.worldhello.net/gotgithub/03-project-hosting/020-repo-operation.html#del-branch)
        *   [3.2.5\. 里程碑管理](http://www.worldhello.net/gotgithub/03-project-hosting/020-repo-operation.html#git-tags)
    *   [3.3\. 公钥认证管理](http://www.worldhello.net/gotgithub/03-project-hosting/030-repo-authz.html)
        *   [3.3.1\. 用户级公钥管理](http://www.worldhello.net/gotgithub/03-project-hosting/030-repo-authz.html#pubkeys)
        *   [3.3.2\. 项目级公钥管理](http://www.worldhello.net/gotgithub/03-project-hosting/030-repo-authz.html#deploy-keys)
    *   [3.4\. 版本库钩子扩展](http://www.worldhello.net/gotgithub/03-project-hosting/040-repo-hooks.html)
        *   [3.4.1\. 邮件通知功能](http://www.worldhello.net/gotgithub/03-project-hosting/040-repo-hooks.html#mail-notify-hook)
        *   [3.4.2\. 和Redmine整合](http://www.worldhello.net/gotgithub/03-project-hosting/040-repo-hooks.html#redmine)
    *   [3.5\. 建立主页](http://www.worldhello.net/gotgithub/03-project-hosting/050-homepage.html)
        *   [3.5.1\. 创建个人主页](http://www.worldhello.net/gotgithub/03-project-hosting/050-homepage.html#user-homepage)
        *   [3.5.2\. 创建项目主页](http://www.worldhello.net/gotgithub/03-project-hosting/050-homepage.html#project-homepage)
        *   [3.5.3\. 使用专有域名](http://www.worldhello.net/gotgithub/03-project-hosting/050-homepage.html#dedicate-domain)
        *   [3.5.4\. 使用Jekyll维护网站](http://www.worldhello.net/gotgithub/03-project-hosting/050-homepage.html#jekyll)
*   [4\. 工作协同](http://www.worldhello.net/gotgithub/04-work-with-others/index.html)
    *   [4.1\. Fork + Pull模式](http://www.worldhello.net/gotgithub/04-work-with-others/010-fork-and-pull.html)
        *   [4.1.1\. 版本库派生](http://www.worldhello.net/gotgithub/04-work-with-others/010-fork-and-pull.html#fork)
        *   [4.1.2\. Pull Request](http://www.worldhello.net/gotgithub/04-work-with-others/010-fork-and-pull.html#pull-request)
        *   [4.1.3\. 手工合并](http://www.worldhello.net/gotgithub/04-work-with-others/010-fork-and-pull.html#merge-by-hands)
        *   [4.1.4\. 在线编辑](http://www.worldhello.net/gotgithub/04-work-with-others/010-fork-and-pull.html#online-edit)
        *   [4.1.5\. 简化的 Fork + Pull Request](http://www.worldhello.net/gotgithub/04-work-with-others/010-fork-and-pull.html#fork-pull-request)
    *   [4.2\. 共享版本库](http://www.worldhello.net/gotgithub/04-work-with-others/020-shared-repo.html)
        *   [4.2.1\. 版本库授权](http://www.worldhello.net/gotgithub/04-work-with-others/020-shared-repo.html#collaborators)
        *   [4.2.2\. 与传统集中式工作模式的异同](http://www.worldhello.net/gotgithub/04-work-with-others/020-shared-repo.html#central-model)
        *   [4.2.3\. 合并后推送](http://www.worldhello.net/gotgithub/04-work-with-others/020-shared-repo.html#merge-and-push)
        *   [4.2.4\. 合并还是变基](http://www.worldhello.net/gotgithub/04-work-with-others/020-shared-repo.html#rebase-and-push)
    *   [4.3\. 组织和团队](http://www.worldhello.net/gotgithub/04-work-with-others/030-organization.html)
        *   [4.3.1\. 创建新组织](http://www.worldhello.net/gotgithub/04-work-with-others/030-organization.html#new-org)
        *   [4.3.2\. 组织管理](http://www.worldhello.net/gotgithub/04-work-with-others/030-organization.html#org-settings)
        *   [4.3.3\. 版本库管理](http://www.worldhello.net/gotgithub/04-work-with-others/030-organization.html#org-repo-mgmt)
        *   [4.3.4\. 个人还是组织](http://www.worldhello.net/gotgithub/04-work-with-others/030-organization.html#pros-of-org)
    *   [4.4\. 代码评注](http://www.worldhello.net/gotgithub/04-work-with-others/040-code-review.html)
        *   [4.4.1\. 提交评注](http://www.worldhello.net/gotgithub/04-work-with-others/040-code-review.html#commit-comments)
        *   [4.4.2\. 逐行评注](http://www.worldhello.net/gotgithub/04-work-with-others/040-code-review.html#line-comments)
    *   [4.5\. 缺陷跟踪](http://www.worldhello.net/gotgithub/04-work-with-others/050-issue.html)
        *   [4.5.1\. 标签](http://www.worldhello.net/gotgithub/04-work-with-others/050-issue.html#labels)
        *   [4.5.2\. 里程碑](http://www.worldhello.net/gotgithub/04-work-with-others/050-issue.html#milestone)
        *   [4.5.3\. Issue的生命周期](http://www.worldhello.net/gotgithub/04-work-with-others/050-issue.html#issue)
        *   [4.5.4\. Pull Requst也是Issue](http://www.worldhello.net/gotgithub/04-work-with-others/050-issue.html#pull-requstissue)
    *   [4.6\. 维基](http://www.worldhello.net/gotgithub/04-work-with-others/060-wiki.html)
        *   [4.6.1\. 维基初始化](http://www.worldhello.net/gotgithub/04-work-with-others/060-wiki.html#wiki-init)
        *   [4.6.2\. 使用维基](http://www.worldhello.net/gotgithub/04-work-with-others/060-wiki.html#use-wiki)
        *   [4.6.3\. 维基与Git](http://www.worldhello.net/gotgithub/04-work-with-others/060-wiki.html#git)
*   [5\. 付费服务](http://www.worldhello.net/gotgithub/05-commercial-github/index.html)
    *   [5.1\. GitHub收费方案](http://www.worldhello.net/gotgithub/05-commercial-github/non-free-plans.html)
    *   [5.2\. GitHub企业版](http://www.worldhello.net/gotgithub/05-commercial-github/github-enterprise.html)
*   [6\. GitHub副产品](http://www.worldhello.net/gotgithub/06-side-projects/index.html)
    *   [6.1\. GitHub:Gist](http://www.worldhello.net/gotgithub/06-side-projects/gist.html)
        *   [6.1.1\. 数据的粘贴和引用](http://www.worldhello.net/gotgithub/06-side-projects/gist.html#paste)
        *   [6.1.2\. Gist背后的Git库](http://www.worldhello.net/gotgithub/06-side-projects/gist.html#gistgit)
        *   [6.1.3\. Greasemonkey](http://www.worldhello.net/gotgithub/06-side-projects/gist.html#greasemonkey)
        *   [6.1.4\. 命令行操作Gist](http://www.worldhello.net/gotgithub/06-side-projects/gist.html#gist-cli)
    *   [6.2\. 其他版本控制工具支持](http://www.worldhello.net/gotgithub/06-side-projects/other-scm.html)
        *   [6.2.1\. 用SVN操作GitHub](http://www.worldhello.net/gotgithub/06-side-projects/svn.html)
        *   [6.2.2\. 用Hg操作GitHub](http://www.worldhello.net/gotgithub/06-side-projects/hg-git.html)
    *   [6.3\. 客户端工具](http://www.worldhello.net/gotgithub/06-side-projects/tools.html)
        *   [6.3.1\. github:mac](http://www.worldhello.net/gotgithub/06-side-projects/github-mac.html)
        *   [6.3.2\. hub](http://www.worldhello.net/gotgithub/06-side-projects/hub.html)
        *   [6.3.3\. iOS应用](http://www.worldhello.net/gotgithub/06-side-projects/ios.html)
    *   [6.4\. 其他](http://www.worldhello.net/gotgithub/06-side-projects/others.html)
        *   [6.4.1\. GitHub:Jobs](http://www.worldhello.net/gotgithub/06-side-projects/jobs.html)
        *   [6.4.2\. GitHub:Shop](http://www.worldhello.net/gotgithub/06-side-projects/shop.html)
        *   [6.4.3\. GitHub短网址服务](http://www.worldhello.net/gotgithub/06-side-projects/short-url.html)
        *   [6.4.4\. GitHub Open Source](http://www.worldhello.net/gotgithub/06-side-projects/opensource.html)
*   [7\. 附录：轻量级标记语言](http://www.worldhello.net/gotgithub/appendix/markups.html)

</div>



## V1.0.0 版本内容更新 ##（仅列出重要更新)
1. 新功能	 aaaaaaaaa
2. 新功能	 bbbbbbbbb
3. 新功能	 ccccccccc
4. 新功能	 ddddddddd
