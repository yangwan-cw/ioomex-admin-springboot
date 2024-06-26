# ioomex-admin-springboot

### <p style="display:inline;color:#00B900">01</p> 项目介绍

### <p style="display:inline;color:#00B900">02</p> 项目目标

- 全局异常处理
- 全局返回
- 项目打包
- 配置环境属性
- 读取资源文件
- Bean配置
- 基于yml的多profile配置
- 文件上传
- 文件服务器
- 拦截器
- druid 数据库连接池
- 定时调度
- 整合Restfui框架


### <p style="display:inline;color:#00B900">02</p> 技术选型


### <p style="display:inline;color:#00B900">03</p> 项目部署

### <p style="display:inline;color:#00B900">04</p> 分支介绍

在开发过程中，使用合理的分支体系可以有效管理代码库，提高协作效率。以下是一个常用的 Git 分支体系：

- ![Master Branch](https://img.shields.io/badge/Master-000000?style=flat-square&logo=git&logoColor=white)
    - 主分支，保存了稳定的生产环境代码。所有的功能和修复都最终会合并到这个分支上。

- ![Develop Branch](https://img.shields.io/badge/Develop-29A19C?style=flat-square&logo=git&logoColor=white)
    - 开发分支，包含了所有即将发布的功能。开发人员在这个分支上进行日常的开发工作。

- ![Feature Branch](https://img.shields.io/badge/Feature-FFA500?style=flat-square&logo=git&logoColor=white)
    - 功能分支，从 `develop` 分支创建，用于开发新功能。功能完成后合并回 `develop` 分支。分支命名通常为 `feature/功能描述`。

- ![Release Branch](https://img.shields.io/badge/Release-007ACC?style=flat-square&logo=git&logoColor=white)
    - 预发布分支，从 `develop` 分支创建，用于准备新版本发布。这个分支上会进行最后的测试和修正，完成后合并到 `main`
      和 `develop` 分支。分支命名通常为 `release/版本号`。

- ![Hotfix Branch](https://img.shields.io/badge/Hotfix-FF4500?style=flat-square&logo=git&logoColor=white) `hotfix/*`
    - 热修复分支，从 `main` 分支创建，用于快速修复生产环境中的紧急问题。修复完成后合并到 `main` 和 `develop`
      分支。分支命名通常为 `hotfix/修复描述`。
