# ansible-kafka-cluster
通过ansible-playbook创建kafka集群

## 部署示例
### 配置hosts清单文件
```shell
vim hosts
[kafka_cluster]
kafka01    ansible_ssh_host=192.168.156.123    ansible_ssh_user="root"    ansible_ssh_pass="password"     kafka_node_id=1
kafka02    ansible_ssh_host=192.168.156.124    ansible_ssh_user="root"    ansible_ssh_pass="password"     kafka_node_id=2
kafka03    ansible_ssh_host=192.168.156.125    ansible_ssh_user="root"    ansible_ssh_pass="password"     kafka_node_id=3
```