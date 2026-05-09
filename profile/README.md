# XRundaLab

XRundaLab 是面向 AI 应用与企业数字化场景的研发组织，聚焦平台化能力建设与业务落地交付。  
我们持续构建可复用的前后端与中台基础设施，覆盖网关、管理后台、业务服务、AI 服务、文档与部署体系。

## 我们在做什么

- AI 能力接入与推理编排
- 多租户管理与权限体系
- 业务域服务（课程、创作、门户等）
- 前端应用（管理端 / 用户端）
- 标准化部署与工程化治理

## 核心仓库（示例）

- `xruns-api-gateway`：统一入口、鉴权与路由
- `xruns-admin-service`：租户、用户、角色、权限等管理能力
- `xruns-business-service`：核心业务域服务
- `xruns-ai-service`：模型调用与 AI 能力服务
- `xruns-admin-frontend`：管理后台前端
- `xruns-user-frontend`：用户端前端
- `xrunda-common` / `xrunda-middleware`：公共基础库与中间件能力
- `xruns-deploy`：部署与运维配置
- `xruns-docs`：项目文档中心

## 工程原则

- 明确边界：按服务职责拆分，避免跨域耦合
- 统一规范：接口、日志、错误处理与配置管理标准化
- 可观测与可维护：以稳定性、可排障与可演进为目标
- 安全优先：敏感信息隔离，权限最小化，环境分级管理
