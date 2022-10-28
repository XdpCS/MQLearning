# RabbitMQ

## 安装

```shell
brew install rabbitmq
```

## 启动

```shell
brew services start rabbitmq
```

## 停止

```shell
brew services stop rabbitmq
```

## 编辑配置文件

```shell
vim /opt/homebrew/etc/rabbitmq/rabbitmq-env.conf
```

## 内网协作

```markdown
CONFIG_FILE=/opt/homebrew/etc/rabbitmq/rabbitmq
NODE_IP_ADDRESS=192.168.50.105 // 将此地址改成内网ip，默认是本机的回环地址
NODENAME=rabbit@localhost
RABBITMQ_LOG_BASE=/opt/homebrew/var/log/rabbitmq
```