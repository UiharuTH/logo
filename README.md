# logo边框和米徕边框的图像库

## 使用docker打开

### 1. 需要先打包docker镜像，已经打包可以忽略

```sh
docker build -t logo:1.0.0 .
```

### 2. 运行镜像

```sh
docker run -d --name logo -p 8080:80 logo:1.0.0
```

### 3. 浏览器打开

[logo](http://localhost:8080)

## 使用tomcat打开

### 1. 直接将项目根文件夹复制到tomcat的webapps路径下

### 2. 浏览器打开

[logo](http://localhost:8080/logo/)
