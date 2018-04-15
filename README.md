# template-veiw
    前端部署
    本项目提供了element-ui及adminlte两套主题，推荐使用element-ui主题【基于vue、element-ui构建开发】 

# element-ui主题
    git clone
    # 克隆项目
    git clone https://github.com/zjf2671/template-veiw/tree/master/template-vue
    # 安装依赖
    npm install
    # 启动服务
    npm run dev
            
# adminlte主题
    git clone
    # 克隆项目
    git clone https://github.com/zjf2671/template-veiw/tree/master/template-adminlte
    # 安装Nginx，并配置Nginx
    server {
        listen       80;
        server_name  localhost;
        location / {
            root   E:\\git\\template-adminlte;
            index  index.html index.htm;
        }
    }
    # 启动Nginx后，访问如下路径即可
    http://localhost
            
登录的账号密码：admin/admin
