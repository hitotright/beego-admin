##beego-admin

>框架 

前端：[amazeui](http://amazeui.org/getting-started)
后端：[beego](https://beego.me/docs/intro/)
>#### 安装步骤
```
go get github.com/astaxie/beego
go get github.com/go-sql-driver/mysql
git clone https://github.com/hitotright/beego-admin.git
cd beego-admin
#修改 conf/app.conf 的数据库配置 
go build
./beego-admin.exe -init
./beego-admin.exe
```
>#### 开发模式
```
go get github.com/beego/bee
go get github.com/shiena/ansicolor
bee run
```
