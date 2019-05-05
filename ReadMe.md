### 实验目的

1. 按照官网的教程https://kubernetes.io/docs/setup/independent/create-cluster-kubeadm/ ，尝试安装kubernetes最新稳定版，总结遇到的问题；
2. 按照AS组自定义的方法 https://github.com/kubesys/kubeos ， 安装kubernetes，确认国内外环境对其安装的影响；
3. 尝试使用Ansible脚本，在离线环境下安装kubernetes，并学习其安装过程和运行时组件；
4. 绘制关键组件的拓扑关系图，确定安装时哪些可以并行化，通过图模型刻画安装先后关系；
5. 针对安装时遇到的问题（os预检查，repo，镜像，yum依赖等），尝试给出kubeadm方式安装的检查工具；
6. 部署dashboard，查看集群健康状态，使用yaml和kubectl对集群进行管理。

天梯云管理平台的安装与使用

中科院研发，企业支撑，交付电科院、佰仟金融等企业，具备成熟的管理能力和规划方案
