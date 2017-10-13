# weex_demo
一个使用阿里weex制作的小Demo,包括注册，登陆界面的跳转，信息本地存储，基于json格式数据与服务器进行交换方法。
<br />后台服务程序使用PHP的ci框架编写。
<br />程序流程
<br />
1. 首次启动，进入入口文件index.vue,读取本地存储信息，如果有过往已经成功登陆信息，则自动跳转到首页home.vue，否则跳转到登陆页面login.vue。
2. 在登陆页login.vue，提交输入的用户名和密码到后台服务器进行检验，后台检测用户名和密码并且返回检验结果给login.vue
,正确则保存登陆信息到本地后跳转到首页home.vue，否则提示错误，并等待用户重新提交。
# 知识点
1. steam 提交数据和获取数据
2. storage 数据本地存储
3. navigator 页面跳转
4. modal 信息提示

# 目录说明
1. app -- 存放weex源文件
2. server --PHP后台源文件

