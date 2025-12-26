# The Mythical Man-Month 中文翻译项目上下文

## 项目概述

这是一个《人月神话》(The Mythical Man-Month) 书籍的中文翻译项目。该项目使用 VuePress 构建，提供了比 GitHub Markdown 更好的阅读体验。

- 在线阅读地址：http://gdut_yy.gitee.io/doc-tmmm/
- 原书作者：Frederick P. Brooks Jr.
- 中文译者：gdut-yy 等贡献者

## 项目结构

```
.
├── docs/                    # 文档目录
│   ├── .vuepress/          # VuePress 配置
│   │   └── config.js       # VuePress 配置文件
│   ├── ch1.md - ch19.md    # 各章节内容
│   ├── cover.jpg           # 封面图片
│   └── README.md           # 文档首页
├── package.json            # 项目配置和脚本
├── README.md               # 项目说明
├── LICENSE                 # MIT 许可证
└── gitee-deploy.sh         # Gitee 部署脚本
```

## 技术栈

- **VuePress**: 用于构建静态网站的 Vue 驱动的静态站点生成器
- **Node.js**: 运行环境
- **Yarn**: 包管理器

## 开发和部署命令

### 本地开发
```bash
# 安装 VuePress 全局依赖
yarn global add vuepress

# 启动本地开发服务器
yarn docs:dev
```

### 构建生产版本
```bash
# 构建静态站点
yarn docs:build
```

### 部署
项目使用 `gitee-deploy.sh` 脚本部署到 Gitee Pages：
```bash
./gitee-deploy.sh
```

## 内容组织

书籍内容按章节组织，每个章节对应一个 Markdown 文件：

1. 第 1 章 焦油坑（The Tar Pit）
2. 第 2 章 人月神话
3. 第 3 章 外科手术队伍
4. 第 4 章 贵族专制、民主政治和系统设计
5. 第 5 章 画蛇添足
6. 第 6 章 贯彻执行
7. 第 7 章 为什么巴比伦塔会失败？
8. 第 8 章 胸有成竹
9. 第 9 章 削足适履
10. 第 10 章 提纲挈领
11. 第 11 章 未雨绸缪
12. 第 12 章 干将莫邪
13. 第 13 章 整体部分
14. 第 14 章 祸起萧墙
15. 第 15 章 另外一面
16. 第 16 章 没有银弹－软件工程中的根本和次要问题
17. 第 17 章 再论《没有银弹》
18. 第 18 章 《人月神话》的观点：是或非？
19. 第 19 章 20 年后的人月神话

## 许可证

本项目采用 MIT 许可证。