

# 中国航母重器主题介绍网站核心技术说明文档

> 网站主题：中国海洋探索主题——航母重器介绍网站
>
> 小组成员：刘译霜，王怡璇，吴文源
>
> 分工：刘译霜：航母首页界面；航母发展界面
>
> ​			王怡璇：航母知识界面；航母成就界面；注册页；说明文档撰写
>
> ​			吴文源：登录界面；联系我们

## 技术

基于html、css以及javascript技术的网站开发

- html：承载网页主题内容与超链接
- css：定义通用主题样式&每个网页具体样式
- js：定义网页中包含的具体逻辑功能与动画（如登录逻辑、轮播动画）

## 测试

完整内容如下分点详叙：

1. 航母首页：包含上方固定导航栏（母版网页超链接至各子网页）、滚动轮播精华摘要图、中国航母展示宣传视频、航海家风姿展示图片以及航母知识介绍。其中滚动动画通过`lunbo.js`控制。

   ![](src\1.jpeg)

2. 航母发展：根据历史发展时间线逐一介绍航母发展的重要时间节点、中国航母发展沿革、首艘辽宁号、后继发展福建舰的简介。

   ![](src\2.jpeg)

3. 航母成就：介绍辽宁舰、山东舰、福建舰以及舰载机歼-35。

   ![](src\3.jpeg)

4. 航母知识：主题内容介绍航母各核心组件，包括飞行甲板、斜角飞行甲板、航母舰岛、升降机组、舰载机库、舰上武库。

   ![](src\4.jpeg)

5. 注册：按照要求输入信息即可注册成功并通过消息提示框显示“注册成功”。此部分通过`login.js`控制。

   ![](src\5.jpeg) 

6. 登录：按照注册信息正确输入手机号和密码即可成功登录，并通过消息提示框显示“注册成功”。

   ![](src\6.jpeg)

7. 联系我们：包括姓名、电话、邮箱和建议输入文本框。

   ![](src\7.jpeg)