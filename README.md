项目：使用Ansible Playbook部署安装Kubernetes高可用集群，Node节点以及相关组件如下

部署系统：建议使用CentOS 7.x的最新版本

Master节点：k8s-master1、k8s-master2、k8s-master3

Worker节点：k8s-worker1、k8s-worker2、k8s-worker3

HAproxy版本：v2.0.0

Keepalived版本：v1.4.5

Docker版本：v19.03.8

Etcd版本：v3.4.3-0

K8S软件包版本：v1.17.4

CNI网络插件：Calico_v3.13.2 或 Flannel_v0.12.0

K8S-Dashboard版本：v2.0.0-rc7

Metrics-Server监控版本：v0.3.6

CoreDNS版本：v1.6.5

Nginx-Ingress-Controller版本：0.30.0

用法：ansible-playbook -i hosts **.yml
