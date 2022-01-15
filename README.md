# muke_58
Kubernetes 入门到进阶实战
Kubernetes 入门到进阶实战
👇👇👇👇👇👇👇👇点击图片跳转下载地址👇👇👇👇👇👇👇
### 第1章 课程导学 

#### 本章作为课程内容引入，主要介绍课程实战项目，课程的学习方法以及课程内容具体安排，希望大家都能通过这门课程，学有所成，学有所归。
1-1 课前必读

1-2 课程介绍与学习指南 (09:12)


### 第2章 课前准备之项目准备 

#### 本章先带大家了解课程知识脉络，理清Kubernetes知识体系，实战贯穿课程的博客项目的打包、容器化运行过程，为后续学习打好基础。
2-1 Kubernetes知识体系 (06:02)

2-2 实战博客项目介绍 (05:05)

2-3 博客项目架构及核心代码 (06:21)

2-4 博客应用运行环境搭建 (03:08)

2-5 Virtualbox虚拟机配置双网卡实现固定IP (13:09)

2-6 安装Docker&环境配置 (09:46)

2-7 Docker运行Mysql Server (05:31)

2-8 博客项目编译打包运行 (02:44)

2-9 在数据库配置文件中url


### 第3章 Kubernetes之Docker必知必会

#### 学好Kubernetes，容器是前提，本章带大家从命令和原理快速入门Docker容器基础，实战把博客应用运行在容器上，为课程后续Kubernetes镜像拉取做铺垫。
3-1 为什么需要Docker (12:35)

3-2 Docker namespace隔离 (09:50)

3-3 CGroups实现资源配额 (12:31)

3-4 Docker镜像特性&原理 (12:46)

3-5 为博客项目编写Dockerfile (07:17)

3-6 为博客项目构建Docker镜像 (07:30)

3-7 Docker run -link运行博客项目 (09:47)


### 第4章 Kubernetes基础及集群搭建 

#### 本章带大家分析Kubernetes产生原因，逐层剖析Kubernetes架构，从零开始使用 kubeadm搭建Artifactory集群。
4-1 Kuberentes的起源和发展 (06:18)

4-2 为什么需要Kubernetes (06:27)

4-3 Kubernetes的架构和核心概念 (07:03)

4-4 Kubernetes部署方案 (04:06)

4-5 安装基础软件 (13:42)

4-6 Master节点安装kubeadm (03:46)

4-7 初始化Kubernetes Master (08:11)

4-8 安装配置worker node节点 (11:07)

4-9 剖析Kubeadm安装过程及错误排查 (18:55)

4-10 安装Dashboard (09:30)

4-11 Kubectl create 和 apply


### 第5章 Kubernetes的调度单元Pod

#### 本章先从Pod组成原理、生命周期、事件处理等方面带大家掌握围绕Kubernetes的核心组件Pod，实战如何将应用以Pod方式运行在Kubernetes上。
5-1 创建Nginx Pod (04:50)

5-2 Pod实现原理 (07:26)

5-3 容器和Pod的生命周期 (06:39)

5-4 为容器生命周期提供事件处理 (06:17)

5-5 创建包含Init容器的Pod (08:05)

5-6 用探针检查Pod的健康性 (06:31)

5-7 为容器设置启动时要执行的命令和参数 (07:55)

5-8 为容器定义相互依赖的环境变量 (08:19)

5-9 为容器进行配额管理 (06:03)

5-10 安装第二个worker node (09:57)

5-11 使用亲和性调度节点 (07:55)

5-12 将configmap数据注入容器 (06:28)

5-13 root vs特权用户 (06:51)

5-14 非root用户运行Pod (12:09)

5-15 加餐：字段选择器

5-16 Pod的Init 容器

5-17 Pod 里容器


### 第6章 Kubernetes的网络实现

#### 运行好Pod之后，本章带大家掌握如何让外部用户访问Pod运行的资源，实战Service和 Ingress的使用方式。
6-1 Service对象&实践 (06:57)

6-2 用Service暴露Pod服务地址 (11:30)

6-3 集群内Pod通信机制 (06:14)

6-4 实践Service创建DNS记录 (10:34)

6-5 从集群外部访问Service (08:09)

6-6 ingress实践 (10:05)

6-7 实战Ingress控制器 (08:20)

6-8 加餐：图解跨主机Pod通信机制

6-9 加餐：Service的域名解析


### 第7章 Kubernetes控制器

#### 本章将带大家掌握Kubernetes的多种控制器管理 Pod 的生命周期，了解Daemon Pods是如何被调度的，最后实战Job 任务。
7-1 ReplicaSet管理副本 (09:15)

7-2 深入理解deployment (09:47)

7-3 有状态的应用StatefulSets (11:05)

7-4 DeamonSet后台任务 (10:16)

7-5 Daemoset如何调度 (06:24)

7-6 Job任务实战 (07:47)


### 第8章 Kubernetes持久化存储业务数据

#### 本章带大家掌握如何管理一个有状态的应用，以及如何持久化有状态数据，并实战 PV、PVC挂载NFS。
8-1 Kuberentes的卷volume (10:25)

8-2 实战挂载NFS卷 (11:34)

8-3 持久化存储PersistantVolume (07:03)

8-4 PVC持久化卷Claim (06:26)

8-5 存储类Storage Class (04:37)

8-6 实战PVC&Storage挂载NFS (11:22)

8-7 PV 持久化卷的应用场景


### 第9章 Kubernetes之应用与配置分离

#### 本章将实战Configmap和Secret秘钥管理，还会带大家掌握Kubernetes配置管理的最佳实践。
9-1 Configmap的概念和实战 (05:33)

9-2 Secret秘钥管理实战 (02:42)

9-3 Kubernetes配置管理最佳实践 (05:17)


### 第10章 Kubernetes之容器镜像中心

#### 本章将带大家深入理解私有容器镜像中心，配置私有镜像中心，完成博客应用的镜像打包和上传。
10-1 如何使用公有镜像仓库 (05:36)

10-2 实战搭建私有镜像中心 (05:53)

10-3 配置私有镜像中心 (06:30)

10-4 配置私有镜像仓库 (06:53)

10-5 推送镜像到私有镜像仓库 (04:44)


### 第11章 Kubernetes之部署博客项目

#### 本章将大家将一个完整的博客应用部署到Kubernetes，配置stateful set的Mysql数据库，实现空间隔离和镜像晋级。
11-1 StatefulSet部署mysql (08:22)

11-2 编写博客应用的Service和Deployment文件 (09:09)

11-3 使用私有镜像中心拉取镜像 (08:47)

11-4 为博客应用进行配置分离 (12:35)

11-5 空间隔离和镜像晋级 (07:41)


### 第12章 使用Helm部署应用

#### 本章将大家了解Helm，完成Helm的安装，部署Helm Chart，创建私有Helm并为博客项目创建Helm chart，最终实现应用和数据库的联合部署。
12-1 Helm介绍和安装 (03:58)

12-2 部署一个Helm Chart (06:54)

12-3 创建并配置Helm仓库 (03:51)

12-4 创建博客应用的Helm Chart (09:29)

12-5 Helm Chart上传到JCR (07:49)

12-6 Helm进行升级，回滚 (05:09)

12-7 在不同环境中部署Helm Chart (07:50)


### 第13章 使用Prometheus和Grafana实现Kubernetes监控

#### 在上一章部署好应用之后，本章给大家带来了云原生日志监控平台Prometheus，使用Prometheus监控Kubernetes集群，并完成部署配置Grafana。
13-1 云原生日志监控平台Prometheus (07:13)

13-2 安装部署node exporter (07:07)

13-3 Prometheus监控主机和K8S集群 (09:00)

13-4 部署配置Grafana (05:59)

13-5 为kubeblog暴露监控数据 (11:27)

13-6 Prometheus监控kubeblog (11:20)


### 第14章 Kubernetes的扩展

#### 本章将助力大家进阶Kubernetes，扩展Kubernetes平台，实现自定义的功能。
14-1 Custom Resource自定义资源 (06:09)

14-2 实战扩展CranTab资源类型 (05:39)

14-3 为CRD字段添加校验 (05:07)


### 第15章 课程总结

#### 本章作为课程的最后一章，我们将带你整体梳理课程所学的内容，并提供一些后续的学习建议，在课程问答区老师等着与你进一步交流。
15-1 课程总结 (04:42)


[下载地址](https://51xueit.vip "下载地址")
