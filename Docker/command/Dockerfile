# 要从官方导入的Python 版本
FROM python:2.7-slim



# 设置工作目录
WORKDIR /app

# 将当前目录文件复制到工作目录 /app 中
ADD . /app



# 导入所需的包
RUN pip install -i https://pypi.douban.com/simple --trusted-host pypi.python.org -r requirements.txt



# 外部端口号
EXPOSE 80



# 环境变量
ENV NAME World

# 在容器中用 python 运行 app.py


CMD ["python", "app.py"]
