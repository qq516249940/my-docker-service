FROM registry.cn-hangzhou.aliyuncs.com/anoy/yapi

WORKDIR /api/vendors

CMD ["server/app.js"]

EXPOSE 3000


# 容器中执行更改时区
#apk update && apk add curl tree tzdata
#cp /usr/share/zoneinfo/Hongkong /etc/localtime