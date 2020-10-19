- **项目特性：** 使用Ansible Playbook部署安装Kubernetes高可用集群，Node节点以及相关组件如下

  **Master节点：**k8s-master1、k8s-master2、k8s-master3

  **Worker节点：**k8s-worker1、k8s-worker2、k8s-worker3

- **相关组件及支持：**

  | **组件**           | **支持**                                       |
  | :----------------- | :--------------------------------------------- |
  | OS系统             | 建议使用 CentOS 7.x 或 RedHat 7.x 的最新版本   |
  | HAproxy            | v2.0.0                                         |
  | Keepalived         | v1.4.5                                         |
  | Etcd               | v3.4.3-0                                       |
  | Docker             | v19.03.12                                      |
  | Kubernetes         | v1.18.9                                        |
  | CoreDNS            | v1.6.7                                         |
  | Network plugin     | Flannel_v0.12.0, **Calico_v3.16.1**            |
  | K8S-Dashboard      | v2.0.4                                         |
  | Metrics-Server     | v0.3.7                                         |
  | Ingress controller | Nginx-Ingress_v0.32.0                          |

  **用法：**ansible-playbook -i hosts **.yml
