# nginx

## 父镜像地址
```shell script
https://c.163yun.com/hub#/library/repository/info?repoId=2967
```
## 镜像信息
```shell script

https://cr.console.aliyun.com/repository/cn-beijing/meowbite/nginx/build

registry.cn-beijing.aliyuncs.com/meowbite/nginx:1.13.0

```

## 使用方法
```shell script
docker pull registry.cn-beijing.aliyuncs.com/meowbite/nginx:1.13.0

docker run --name some-nginx -v /some/content:/usr/share/nginx/html:ro -d registry.cn-beijing.aliyuncs.com/meowbite/nginx:1.13.0
```

