1、搭建框架

2、基础指令
1）ng-model
双向绑定
2）ng-minlength ng-maxlength
长度约束
<input class = "form-control"
    ng-model="name"
    type="text"
    ng-minlength="2"
    ng-maxlength="10" 
    >
<div>{{name}}</div>    
3）ng-submit and ng-class
ng-submit提交后触发
ng-class 根据不同情况进行css设置
4）ng-if
ng-if做一些判断，进行表单验证
5）ng-disabled

3、表单的建立
注意基本格式。

4、指令与表单合作验证
1）controller

2）传入用户数据和创建验证规则
涉及到指令

3）显示相关信息
ng-class：has-success
添加图标，字体 #font-awsome

4）总结 
控制器的意义
指令的意义
表单的验证
Angular api