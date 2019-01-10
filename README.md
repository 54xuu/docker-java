# docker-java

根据oracle官网实际情况修改以下参数后构建容器：

- ENV JAVA_VERSION 8
- ENV JAVA_UPDATE 191
- ENV JAVA_BUILD 12
- ENV JAVA_PATH 96a7b8442fe848ef90c96a2fad6ed6d1

```shel
sudo docker build --no-cache -t xuu54/java:8u191 .
```