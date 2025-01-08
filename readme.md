## 版本
- python3.12.7
- tengine-2.3.3.tar.gz

## 配置和启动app1
```bash
# 创建虚拟环境
python3 -m venv venv
# 激活虚拟环境
source venv/bin/activate
# 安装依赖
pip install -r requirements.txt
# 启动app2的app.py
python3 app.py
```

## 配置和启动app2
```bash
cd app2
# 创建虚拟环境
python3 -m venv venv
# 激活虚拟环境
source venv/bin/activate
# 安装依赖
pip install -r requirements.txt
# 启动app2的app.py
python3 app.py
```

## 启动nginx
```bash
# 启动nginx
nginx -c /root/test_2app_nginx/nginx_log/conf/nginx.conf -p /root/test_2app_nginx/nginx_log/
```