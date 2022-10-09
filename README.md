# myssh

依赖
```
python3
python3-pexpect
```

配置文件在 ~/.myssh/ssh_config
```
Host example1
    HostName 127.0.0.1
    Port 22
    User root
    Password 123456
```

```
# 打印帮助
myssh -h

# 列出所有连接
myssh list keyword

# 列出所有连接
myssh sel keyword

# 连接到服务
myssh cc name

```
