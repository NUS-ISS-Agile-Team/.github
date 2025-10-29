# NUS-ISS 敏捷开发团队 🚀

<div align="center">

![组织头像](https://avatars.githubusercontent.com/u/227807822?s=200&v=4)

**SWE5006/SWE5001 课程 Group12 项目**

[![地区](https://img.shields.io/badge/地区-新加坡-red)](https://github.com/NUS-ISS-Agile-Team)
[![仓库数量](https://img.shields.io/badge/仓库数量-14-blue)](https://github.com/orgs/NUS-ISS-Agile-Team/repositories)
[![许可证](https://img.shields.io/badge/许可证-MIT-green)](LICENSE)

[English Documentation](README.md)

</div>

## 📖 关于我们

我们是来自新加坡国立大学系统科学院（NUS-ISS）的敏捷开发团队，致力于 SWE5006 和 SWE5001 课程的 Group 12 项目。我们的团队践行现代软件开发方法论和最佳实践，致力于构建可扩展、可维护的企业级应用程序。

## 🎯 主要项目：CeramiCraft

CeramiCraft 是一个采用微服务架构构建的综合性陶瓷电商平台，展示了我们团队在现代云原生应用开发方面的能力。

### 🏗️ 系统架构

我们的项目采用微服务架构，前后端分离：

#### 前端服务
- **[ceramicraft-customer-frontend](https://github.com/NUS-ISS-Agile-Team/ceramicraft-customer-frontend)** - 客户端 Web 应用（TypeScript/Vue.js）
- **[ceramicraft-merchant-frontend](https://github.com/NUS-ISS-Agile-Team/ceramicraft-merchant-frontend)** - 商家管理后台（TypeScript/Vue.js）

#### 后端微服务
- **[ceramicraft-user-mservice](https://github.com/NUS-ISS-Agile-Team/ceramicraft-user-mservice)** - 用户管理服务（Go）
- **[ceramicraft-commodity-mservice](https://github.com/NUS-ISS-Agile-Team/ceramicraft-commodity-mservice)** - 商品目录服务（Go）
- **[ceramicraft-order-mservice](https://github.com/NUS-ISS-Agile-Team/ceramicraft-order-mservice)** - 订单处理服务（Go）
- **[ceramicraft-payment-mservice](https://github.com/NUS-ISS-Agile-Team/ceramicraft-payment-mservice)** - 支付处理服务（Go）
- **[ceramicraft-comment-mservice](https://github.com/NUS-ISS-Agile-Team/ceramicraft-comment-mservice)** - 评论和评价服务（Go）

#### DevOps 与基础设施
- **[ceramicraft-deploy](https://github.com/NUS-ISS-Agile-Team/ceramicraft-deploy)** - 部署配置
- **[ceramicraft-argocd-deploy](https://github.com/NUS-ISS-Agile-Team/ceramicraft-argocd-deploy)** - ArgoCD GitOps 部署（Helm charts）
- **[ceramicraft-iac](https://github.com/NUS-ISS-Agile-Team/ceramicraft-iac)** - 基础设施即代码（Terraform/HCL）
- **[ceramicraft-mservice-template](https://github.com/NUS-ISS-Agile-Team/ceramicraft-mservice-template)** - 微服务模板，用于快速开发

## 🛠️ 技术栈

### 前端
- Vue.js / TypeScript
- 现代化 UI 框架 (ElementUI)

### 后端
- Go (Golang) - 主要后端语言
- 微服务架构
- RESTful APIs

### DevOps 与云平台
- **容器编排**: Kubernetes
- **GitOps**: ArgoCD
- **基础设施即代码**: Terraform (HCL)
- **CI/CD**: 自动化部署流水线
- **云平台**: 云原生基础设施

## 🌟 核心特性

- ✅ **微服务架构** - 可扩展和可维护的服务设计
- ✅ **云原生** - 基于 Kubernetes 的部署
- ✅ **GitOps** - 使用 ArgoCD 实现声明式持续交付
- ✅ **基础设施即代码** - 使用 Terraform 实现可复现的基础设施
- ✅ **敏捷开发** - 持续集成的迭代开发
- ✅ **全栈开发** - 完整的前后端实现

## 📚 开发实践

我们的团队遵循行业最佳实践：

- **敏捷方法论**: 基于冲刺的开发与定期迭代
- **版本控制**: 基于 Git 的工作流程与 Pull Request 评审
- **代码质量**: 代码审查和自动化测试
- **文档**: 为所有服务提供全面的文档
- **DevOps**: 持续集成与持续部署（CI/CD）
- **微服务**: 独立、可扩展的服务架构

## 📊 项目统计

- **仓库总数**: 10+
- **主要语言**: Go
- **前端框架**: Vue.js、TypeScript
- **基础设施**: Terraform、Kubernetes、ArgoCD、Docker Swarm
- **许可证**: MIT License

## 📧 联系方式

- **地区**: 新加坡
- **组织**: [NUS-ISS-Agile-Team](https://github.com/NUS-ISS-Agile-Team)

## 📄 许可证

所有项目均采用 MIT 许可证 - 详情请参阅各个仓库的 LICENSE 文件。

---

<div align="center">

**由 NUS-ISS 敏捷开发团队用 ❤️ 构建**

*学习、构建、共同成长*

</div>
