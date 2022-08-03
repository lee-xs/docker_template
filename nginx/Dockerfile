# 基础镜像
FROM nginx

# author
MAINTAINER alees

# 挂在目录
VOLUEME /home/alees/projects/vue3-download-analysis

# 创建目录
RUN mkdir -p /home/alees/projects/vue3-download-analysis

# 指定工作路径
WORKDIR /home/alees/projects/vue3-download-analysis

# 复制conf配置文件到路径
COPY ./conf/nginx.conf /etc/nginx/nginx.conf

# 复制html文件到路径
COPY ./html/dist /home/alees/projects/vue3-download-analysis

