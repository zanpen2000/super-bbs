# super-bbs
一个基于Flask的bbs论坛类项目
前端有用户和管理员两套界面

# python版本

`3.6`

# 初始化数据库结构

```
$ flask db init
$ flask db migrate -m "init"
$ flask db upgrade
```
or 
```
$ python manage.py db init
$ python manage.py db migrate
$ python manage.py db upgrade
$ python manage.py db --help
```
# 初始化数据

```
python manage.py init_app
```

# 运行flask(dev)

```
export FLASK_APP=./super_bbs/app.py
export FLASK_ENV=development
flask run
```


# 运行web(dev)

```
yarn run serve
```

# 查看运行效果
 
`http://localhost:1024`


生产环境启动命令:

```gunicorn -w 8 -k gevent  --log-level warning -b 0.0.0.0:8000 prod_run:app```


### 声明： 严重高仿(照抄)V2EX
### 开发原因： 前后端分离，替换原来的FakeV2EX项目
### 用户界面图片展示：

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/bbs1.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/bbs2.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/bbs3.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/bbs6.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/bbs7.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/bbs8.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/bbs9.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/bbs10.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/bbs11.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/bbs12.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/bbs13.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/bbs14.png)


## 管理界面图片展示：

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/admin1.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/admin2.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/admin3.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/admin4.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/admin5.png)

![](https://raw.githubusercontent.com/lgphone/super-bbs/master/docs/pic/admin6.png)
