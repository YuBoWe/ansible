## k8s安装说明
> 在当前目录执行ansible命令

### 系统配置
> ubuntu2204

### 使用docker作为容器运行时
```
ansible-playbook ubuntu_install_docker_ce.yml
ansible-playbook ubuntu_init_calico.yml
```

代理要在初始化k8s前配置完
