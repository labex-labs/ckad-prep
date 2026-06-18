# CKAD 备考指南

## 支持语言

🇨🇳 [简体中文](README_zh.md) 🇪🇸 [Español](README_es.md) 🇫🇷 [Français](README_fr.md) 🇩🇪 [Deutsch](README_de.md) 🇯🇵 [日本語](README_ja.md) 🇷🇺 [Русский](README_ru.md) 🇰🇷 [한국어](README_ko.md) 🇧🇷 [Português](README_pt.md) 🇺🇸 [English](README.md) 

[![CKAD 备考指南](https://course-cover.labex.io/ckad-prep.png?lang=zh)](https://labex.io/zh/courses/ckad-prep)

[![Start-Learning](https://img.shields.io/badge/Start-Learning-whitesmoke?style=for-the-badge)](https://labex.io/zh/courses/ckad-prep)

这是一门面向初学者的 CKAD 备考课程，包含 42 个引导式 Kubernetes 应用开发实验。内容涵盖从 kubectl 和对象基础，到工作负载、配置、部署、可观测性及网络等核心知识点。

![kubernetes](https://img.shields.io/badge/kubernetes-whitesmoke?style=for-the-badge&logo=kubernetes)
![ckad](https://img.shields.io/badge/ckad-whitesmoke?style=for-the-badge&logo=ckad)


## 练习

|   序号 | 名称                           | 难度   | 练习                                                                                                                                  |
|------|------------------------------|------|-------------------------------------------------------------------------------------------------------------------------------------|
|   01 | 🧩  探索 kubectl、上下文与命名空间       | 初级   | <a target='_blank' href='https://labex.io/zh/labs/explore-kubectl-contexts-and-namespaces-663587?course=ckad-prep'>开始实验</a>         |
|   02 | 🧩  检查 Kubernetes API 资源      | 初级   | <a target='_blank' href='https://labex.io/zh/labs/inspect-kubernetes-api-resources-663608?course=ckad-prep'>开始实验</a>                |
|   03 | 🧩  创建并检查 Pod                 | 初级   | <a target='_blank' href='https://labex.io/zh/labs/create-and-inspect-a-pod-663597?course=ckad-prep'>开始实验</a>                        |
|   04 | 🧩  编写 Pod 清单                 | 初级   | <a target='_blank' href='https://labex.io/zh/labs/write-a-pod-manifest-663628?course=ckad-prep'>开始实验</a>                            |
|   05 | 🧩  使用标签与选择器                  | 初级   | <a target='_blank' href='https://labex.io/zh/labs/use-labels-and-selectors-663626?course=ckad-prep'>开始实验</a>                        |
|   06 | 🧩  使用 kubectl 生成和编辑清单        | 初级   | <a target='_blank' href='https://labex.io/zh/labs/generate-and-edit-manifests-with-kubectl-663604?course=ckad-prep'>开始实验</a>        |
|   07 | 🧩  创建 Deployment             | 初级   | <a target='_blank' href='https://labex.io/zh/labs/create-a-deployment-663596?course=ckad-prep'>开始实验</a>                             |
|   08 | 🧩  扩展 Deployment             | 初级   | <a target='_blank' href='https://labex.io/zh/labs/scale-a-deployment-663618?course=ckad-prep'>开始实验</a>                              |
|   09 | 🧩  运行一次性任务 (Jobs)            | 初级   | <a target='_blank' href='https://labex.io/zh/labs/run-one-time-jobs-663616?course=ckad-prep'>开始实验</a>                               |
|   10 | 🧩  调度 CronJob                | 初级   | <a target='_blank' href='https://labex.io/zh/labs/schedule-cronjobs-663619?course=ckad-prep'>开始实验</a>                               |
|   11 | 🧩  选择合适的工作负载资源               | 初级   | <a target='_blank' href='https://labex.io/zh/labs/choose-the-right-workload-resource-663592?course=ckad-prep'>开始实验</a>              |
|   12 | 🧩  添加初始化容器 (Init Containers) | 初级   | <a target='_blank' href='https://labex.io/zh/labs/add-init-containers-663589?course=ckad-prep'>开始实验</a>                             |
|   13 | 🧩  添加 Sidecar 容器             | 初级   | <a target='_blank' href='https://labex.io/zh/labs/add-a-sidecar-container-663588?course=ckad-prep'>开始实验</a>                         |
|   14 | 🧩  在 Pod 中使用临时卷和持久卷          | 初级   | <a target='_blank' href='https://labex.io/zh/labs/use-ephemeral-and-persistent-volumes-in-pods-663624?course=ckad-prep'>开始实验</a>    |
|   15 | 🧩  使用 ConfigMap 配置应用程序       | 初级   | <a target='_blank' href='https://labex.io/zh/labs/configure-applications-with-configmaps-663593?course=ckad-prep'>开始实验</a>          |
|   16 | 🧩  使用 Secret 配置应用程序          | 初级   | <a target='_blank' href='https://labex.io/zh/labs/configure-applications-with-secrets-663594?course=ckad-prep'>开始实验</a>             |
|   17 | 🧩  注入环境变量                    | 初级   | <a target='_blank' href='https://labex.io/zh/labs/inject-environment-variables-663607?course=ckad-prep'>开始实验</a>                    |
|   18 | 🧩  挂载配置文件                    | 初级   | <a target='_blank' href='https://labex.io/zh/labs/mount-configuration-files-663609?course=ckad-prep'>开始实验</a>                       |
|   19 | 🧩  使用投射卷 (Projected Volumes) | 初级   | <a target='_blank' href='https://labex.io/zh/labs/use-projected-volumes-663627?course=ckad-prep'>开始实验</a>                           |
|   20 | 🧩  设置资源请求与限制                 | 初级   | <a target='_blank' href='https://labex.io/zh/labs/set-resource-requests-and-limits-663620?course=ckad-prep'>开始实验</a>                |
|   21 | 🧩  应用命名空间资源配额                | 初级   | <a target='_blank' href='https://labex.io/zh/labs/apply-namespace-resource-quotas-663590?course=ckad-prep'>开始实验</a>                 |
|   22 | 🧩  使用专用 ServiceAccount 运行应用  | 初级   | <a target='_blank' href='https://labex.io/zh/labs/run-with-a-dedicated-serviceaccount-663617?course=ckad-prep'>开始实验</a>             |
|   23 | 🧩  加固 Pod 安全上下文              | 初级   | <a target='_blank' href='https://labex.io/zh/labs/harden-a-pod-security-context-663605?course=ckad-prep'>开始实验</a>                   |
|   24 | 🧩  发现并使用自定义资源                | 初级   | <a target='_blank' href='https://labex.io/zh/labs/discover-and-use-custom-resources-663602?course=ckad-prep'>开始实验</a>               |
|   25 | 🧩  执行滚动更新                    | 初级   | <a target='_blank' href='https://labex.io/zh/labs/perform-a-rolling-update-663610?course=ckad-prep'>开始实验</a>                        |
|   26 | 🧩  回滚故障部署                    | 初级   | <a target='_blank' href='https://labex.io/zh/labs/roll-back-a-faulty-deployment-663614?course=ckad-prep'>开始实验</a>                   |
|   27 | 🧩  调整 Deployment 更新策略        | 初级   | <a target='_blank' href='https://labex.io/zh/labs/tune-deployment-update-strategy-663622?course=ckad-prep'>开始实验</a>                 |
|   28 | 🧩  实现金丝雀发布                   | 初级   | <a target='_blank' href='https://labex.io/zh/labs/implement-a-canary-release-663606?course=ckad-prep'>开始实验</a>                      |
|   29 | 🧩  切换蓝绿部署流量                  | 初级   | <a target='_blank' href='https://labex.io/zh/labs/switch-blue-green-traffic-663621?course=ckad-prep'>开始实验</a>                       |
|   30 | 🧩  部署本地 Helm Chart           | 初级   | <a target='_blank' href='https://labex.io/zh/labs/deploy-a-local-helm-chart-663600?course=ckad-prep'>开始实验</a>                       |
|   31 | 🧩  使用 Kustomize 自定义应用程序      | 初级   | <a target='_blank' href='https://labex.io/zh/labs/customize-an-application-with-kustomize-663598?course=ckad-prep'>开始实验</a>         |
|   32 | 🧩  构建并运行本地应用程序镜像             | 初级   | <a target='_blank' href='https://labex.io/zh/labs/build-and-run-a-local-application-image-663591?course=ckad-prep'>开始实验</a>         |
|   33 | 🧩  读取日志与事件                   | 初级   | <a target='_blank' href='https://labex.io/zh/labs/read-logs-and-events-663611?course=ckad-prep'>开始实验</a>                            |
|   34 | 🧩  使用 exec 和端口转发进行调试         | 初级   | <a target='_blank' href='https://labex.io/zh/labs/use-exec-and-port-forwarding-for-debugging-663625?course=ckad-prep'>开始实验</a>      |
|   35 | 🧩  配置存活探针与就绪探针               | 初级   | <a target='_blank' href='https://labex.io/zh/labs/configure-liveness-and-readiness-probes-663595?course=ckad-prep'>开始实验</a>         |
|   36 | 🧩  调试 CrashLooping 应用        | 初级   | <a target='_blank' href='https://labex.io/zh/labs/debug-a-crashlooping-application-663599?course=ckad-prep'>开始实验</a>                |
|   37 | 🧩  更新已弃用的 API 清单             | 初级   | <a target='_blank' href='https://labex.io/zh/labs/update-deprecated-api-manifests-663623?course=ckad-prep'>开始实验</a>                 |
|   38 | 🧩  使用 Service 暴露 Deployment  | 初级   | <a target='_blank' href='https://labex.io/zh/labs/expose-a-deployment-with-a-service-663603?course=ckad-prep'>开始实验</a>              |
|   39 | 🧩  诊断 Service DNS 访问         | 初级   | <a target='_blank' href='https://labex.io/zh/labs/diagnose-service-dns-access-663601?course=ckad-prep'>开始实验</a>                     |
|   40 | 🧩  使用 Ingress 路由 HTTP 流量     | 初级   | <a target='_blank' href='https://labex.io/zh/labs/route-http-traffic-with-ingress-663615?course=ckad-prep'>开始实验</a>                 |
|   41 | 🧩  使用 NetworkPolicy 限制应用流量   | 初级   | <a target='_blank' href='https://labex.io/zh/labs/restrict-application-traffic-with-networkpolicy-663613?course=ckad-prep'>开始实验</a> |
|   42 | 🧩  修复命名服务端口路由                | 初级   | <a target='_blank' href='https://labex.io/zh/labs/repair-named-service-port-routing-663612?course=ckad-prep'>开始实验</a>               |

## 关于 LabEx

[LabEx](https://labex.io) 是一个专注于编程和技术的交互式动手学习平台。它结合了实验室、AI 辅助和虚拟机，提供无视频的实践学习体验。采用严格的'边学边做'方法，浏览器内的交互式在线环境具有自动化的逐步检查，基于技能树的结构化内容组织系统，以及不断增长的学习资源（包含 30 个技能树和超过 6,000 个实验），[LabEx](https://labex.io) 提供全面的实践教育。该平台包含基于最新 AI 模型构建的学习助手 Labby，提供对话式学习体验。

## 更多

- 🔗 [CKAD 培训 编程课程](https://github.com/labex-labs/awesome-programming-courses)
- 🔗 [CKAD 培训 编程项目](https://github.com/labex-labs/awesome-programming-projects)
- 🔗 [CKAD 培训 免费教程](https://github.com/labex-labs/ckad-free-tutorials)

