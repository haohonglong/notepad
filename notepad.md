# notepad
    EBNF(扩展巴科斯范式):
        
    MAC:
        homebrew 命令集
            brew update                        #更新brew可安装包，建议每次执行一下
            brew search php55                  #搜索php5.5
            brew tap josegonzalez/php          #安装扩展<gihhub_user/repo>   
            brew tap                           #查看安装的扩展列表
            brew install php55                 #安装php5.5
            brew remove  php55                 #卸载php5.5
            brew upgrade php55                 #升级php5.5
            brew options php55                 #查看php5.5安装选项
            brew info    php55                 #查看php5.5相关信息
            brew home    php55                 #访问php5.5官方网站
            brew services list                 #查看系统通过 brew 安装的服务
            brew services cleanup              #清除已卸载无用的启动配置文件
            brew services restart php55        #重启php-fpm
            
            如果你希望以mac下的apache作为web server，编译时要加 --with-apache；如果你的web server 是 nginx这类，就需要加上 --with-fpm。
            tip: 详细资料看QQ空间

    liunx 常用命令：
        netstat -an | grep 80   #查看被监听 80端口信息
        ps -e | grep php        #查看 运行php进程的信息
        
        
        远程操作
            ssh 主机名@主机IP #远程登录上Linux主机
            scp #拷贝文件
            exit #关闭与对方的连接
            
        
        
    MYSQL：
        IN 的语法实例：
            SELECT * FROM table WHERE `id` IN (1, 2, 3);        #查找条件符合 id=1,id=2,id=3 的 row
            UPDATE table set status=1 where `id` in(1, 2, 3);   #更新条件符合 id=1,id=2,id=3 的 row
    PHP：
        date:
            strtotime('+5 days');
    
    yii2：
        