"部分笔记" 
1.自动化导入
  用法require.context(directory,useSubdirectories,regExp)
  参数：读取文件的路径、是否遍历文件的子目录、，
  返回一个函数,并且这个函数有3个属性
  resolve {Function} -接受一个参数request,request为test文件夹下面匹配文件的相对路径,返回这个匹配文件相对于整个工程的相对路径
  keys {Function} -返回匹配成功模块的名字组成的数组
  id {String} -执行环境的id,返回的是一个字符串,主要用在module.hot.accept,应该是热加载?
1. 一行文本超出就隐藏并且显示省略号：

  overflow:hidden; //超出的文本隐藏

  text-overflow:ellipsis; //溢出用省略号显示

  white-space:nowrap; //溢出不换行
  
2.文本超出2行时隐藏并显示省略号：

  overflow:hidden; 

  text-overflow:ellipsis;

  display:-webkit-box; 

  -webkit-box-orient:vertical;

  -webkit-line-clamp:2; 
3.文本两端对齐
  text-align-last:justify
js获取某月的天数：new Date(year, month, 0).getDate();
```Javascript
ctrl+d退出选框//ps
filezilla  ftp免费工具
webstorm补充分号 alt+enter

vue-cli局域网访问修改config里面的host:"localhost"为host:"0.0.0.0"

vue-cli 解决Invalid Host header
在webpack.dev.conf.js中添加：disableHostCheck: true
```
watchOptions: {
poll: config.dev.poll,
},
disableHostCheck: true     加上这段
}
```
win 10激活时间
win+r
slmgr.vbs -xpr

npm 查看全局安装
npm ls -g --depth 0

参考知乎上下拉效果
vue微信登录分享http://www.jb51.net/article/116844.htm

http://www.cnblogs.com/zhengweijie/p/6922808.html
mysql 执行sql文件命令mysql> source   d:/myprogram/database/db.sql;
mysql链接Navicat错误
navicat 连接 mysql 出现Client does not support authentication protocol requested by server解决方案
mysql>
ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY '831015';
其中831015为密码。

git分支
git checkout -b 本地分支名x origin/远程分支名x

其中： v- 是这些类名的前缀
v-enter：定义进入过渡的开始状态。在元素被插入时生效，在下一个帧移除。
v-enter-active：定义过渡的状态。在元素整个过渡过程中作用，在元素被插入时生效，在 transition/animation 完成之后移除。这个类可以被用来定义过渡的过程时间，延迟和曲线函数。
v-enter-to: 2.1.8版及以上 定义进入过渡的结束状态。在元素被插入一帧后生效 (与此同时 v-enter 被删除)，在 transition/animation 完成之后移除。
v-leave: 定义离开过渡的开始状态。在离开过渡被触发时生效，在下一个帧移除。
v-leave-active：定义过渡的状态。在元素整个过渡过程中作用，在离开过渡被触发后立即生效，在 transition/animation 完成之后移除。这个类可以被用来定义过渡的过程时间，延迟和曲线函数。
v-leave-to: 2.1.8版及以上 定义离开过渡的结束状态。在离开过渡被触发一帧后生效 (与此同时 v-leave 被删除)，在 transition/animation 完成之后移除。
 
vue-cli配置的说明
https://www.cnblogs.com/eer123/p/9167311.html
https://segmentfault.com/a/1190000014804826#articleHeader2


vuex mapGetters：http://www.imooc.com/article/14741

browser-sync使用
browser-sync start --server开启局域网

create-react-app修改端口号
 react-script  -> scripts ->  utils.js -> start.js


pxe mof
```
