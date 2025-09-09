# Yops 运维面板

[Yops 官网](https://www.yops.cn) ｜ [文档中心](https://docs.yops.cn)

Yops 是一款轻量化、高性能的 **运维管理面板**，面向开发者、站长与运维工程师，帮助快速管理和运维服务器环境。
它采用 **Go 语言开发**，底层基于 **Docker 容器**，具有占用低、扩展性强、部署简单的特点。
无论是个人开发者管理一台服务器，还是企业同时管理上百台服务器，Yops 都能保持一致的高效与稳定。

<img width="2560" height="1346" alt="1" src="https://github.com/user-attachments/assets/53f928a4-9340-4516-aaec-84f087a80770" />


## 📌 核心特性

Yops 运维面板围绕 **多机管理、容器化运维、安全防护与站点管理** 四个核心方向，提供一套完整的可视化与自动化运维方案。

* **轻量高效**

  * 面板由 Go 语言开发，内存占用极低，单机仅需约 **24MB**，即使管理十余台节点也能保持流畅运行。
  * 启动速度快，运行稳定，不依赖 PHP 或冗余服务。




* **多机与容器管理**

  * 支持单面板统一管理多台服务器，远程节点可一键接入。
  * 内置 Docker 容器管理，涵盖镜像拉取、容器启动/停止、端口与挂载配置、日志监控等功能。
  * 无论是单机网站，还是分布式集群，都能轻松掌控。

<img width="2560" height="1345" alt="多机" src="https://github.com/user-attachments/assets/55303ba3-7802-4112-aa87-fba49284be4e" />
<img width="2560" height="1345" alt="2" src="https://github.com/user-attachments/assets/739b6cc1-4679-4e33-b7dc-79bfc8ec54d6" />
<img width="2560" height="1345" alt="7" src="https://github.com/user-attachments/assets/4e9b24c2-e456-45bb-bd2b-d965bc7500d6" />


* **站点管理**

  * 快速创建网站，支持多域名绑定、Nginx 配置、反向代理、伪静态与访问日志分析。
  * 提供 SSL 证书管理，可选自签、Let’s Encrypt 免费证书、第三方证书导入，并支持自动续签。

<img width="4000" height="2538" alt="19" src="https://github.com/user-attachments/assets/f2ddd4eb-3ce2-426b-941a-940d6eebe9a1" />
<img width="2560" height="1346" alt="7" src="https://github.com/user-attachments/assets/6b326983-fa24-4a9c-8f25-9304b82c991c" />
<img width="2560" height="1345" alt="10" src="https://github.com/user-attachments/assets/5099957d-0558-46fb-af12-af3ab599a529" />


* **安全与监控**

  * 集成 WAF（Web 应用防火墙），可抵御常见攻击（SQL 注入、XSS、恶意扫描、CC 攻击等）。
  * 文件监控与安全告警，及时发现可疑行为。
  * 系统资源监控（CPU / 内存 / 磁盘 / 网络），并支持多节点可视化展示。
 
<img width="2159" height="1515" alt="36" src="https://github.com/user-attachments/assets/a9caae17-daa0-4773-bdb5-633f2629c511" />
<img width="2560" height="1346" alt="6" src="https://github.com/user-attachments/assets/6f4dadde-851a-4985-ab75-4ff639038fb1" />
<img width="2560" height="1346" alt="5" src="https://github.com/user-attachments/assets/cd7671dc-ea0c-463d-ac68-d9daa49f4b0f" />
<img width="2048" height="1993" alt="3" src="https://github.com/user-attachments/assets/0184cc8e-0a74-49e7-bd88-5f75ef9b542c" />



* **应用与扩展**

  * 应用商店提供常见环境与工具的一键安装（Nginx、Redis、Node.js、GitLab 等）。
  * 支持插件与 API 扩展，未来将逐步开放更多生态能力。
 

<img width="2560" height="1348" alt="image" src="https://github.com/user-attachments/assets/3316826b-ce33-4f73-9c9b-b83b49c61a39" />


## 🚀 快速安装

###  一键安装脚本
```bash
sudo bash -c "$(curl -sSL https://download.yops.cn/package/install.sh)"
```

## 🚀 使用场景

* **个人开发者**：快速搭建个人博客、作品站点、测试环境。
* **中小型团队**：集中管理多台服务器，降低重复配置与运维成本。
* **企业运维**：批量管理大规模节点，配合监控、告警与安全策略，提升整体运维效率。

## 🛠️ 技术栈

* **后端语言**：Go
* **容器支持**：Docker
* **Web 前端**：现代化 UI（支持暗黑模式 / 响应式布局）
* **数据库**：MySQL

## 📖 文档与社区

* 官网地址：[www.yops.cn](https://www.yops.cn)
* 使用文档：[docs.yops.cn](https://docs.yops.cn)
* 视频教程（B站）：[www.yops.cn](https://space.bilibili.com/)]([https://www.yops.cn](https://space.bilibili.com/3546897876781601?spm_id_from=333.1387.follow.user_card.click)
* 社区交流群：支持用户交流与反馈
<img width="536" height="540" alt="企微号" src="https://github.com/user-attachments/assets/19fe3625-19e7-4471-bc5d-584be9af5113" />


## 🔮 未来规划

* 应用生态扩展：更多一键应用与开发框架支持
* 自动化脚本与任务调度
* Kubernetes / 容器编排支持
* 高级告警与通知系统
* 插件化与开放 API，支持第三方开发者扩展

---

⚡ **Yops 致力于为开发者和运维人员提供一个简单、高效、安全的运维面板，帮助你把精力更多放在业务开发，而不是环境运维。**

---

