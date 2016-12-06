# 版本： 1.0.0

11月份的时候就一直开始写这个主题了，主题来自收费静态html模板angulr，是一套国外开发的主题。界面十分友好，扁平化设计。主要css来自于静态html模板，自己写了部分js和php代码。功能十分强大，**总体积除去图片不足400K**。

主题分为两个版本：**开发版**和**使用版**。两者功能完全相同，但是**开发版**完全保留了未压缩代码并且使用npm配置了grunt自动压缩任务，更方便修改代码。

## 主题特色

1. 主题使用instantclick.js ，鼠标悬浮在链接上即可预加载页面，速度提升。
2. 主题使用bootstrap框架,自适应任何屏幕尺寸。在手机端仍然界面友好。
3. 主题内置**3套自定义页面模板**，**4种布局**、**14种风格**，每一处的颜色，随意改变，随心打造你想要的风格界面。
4. 主题内置两套自定义页面模板——“时光机”和“文章归档”。
5. “时光机”——类似于 **说说**，方便记录生活的一言一语，并且在首页会显示最新三条。
6. “文章归档”——页面使用时间线的css风格，美观好看
7. 全站有各种小部件，如“热门文章”、“最新评论”、“随机文章”、“标签云”，满足大多数的需求。
7. 前台可以登录，注销，操作方便。
8. 首页文章缩略图功能，输出顺序分别书:thumb字段——附件第一个图片——文章插入第一张图片——随机输出缩略图
9. 使用`links`插件，管理友情链接更简单！
10. 强大的后台功能，在这里，设置一切你想改动的。

## 使用说明
1. 从github下载最新版本，重命名主题文件夹名称为`handsome`，然后将`插件`文件夹里面的两个插件文件夹复制到`usr\plugins`目录下。最后删除主题文件夹下面的`插件`文件夹即可。
2. 主题必须安装以下两个插件：
 * BufannaoCms：右侧边栏热门文章、随机文章（可在插件后台填写输出文章数目）
 * Links ： 首页的友情链接 （链接分类填：`ten`）
3. 使用独立页面的自定义模板：
 * “时光机”：独立页面的缩略名必须是：`cross`，与前台一些内容已经绑定了。
 * “文章归档”： 缩略名随意
 * “友情链接”：缩略名随意，该自定义页面模板调用`links`插件的链接。请填写链接描述，无需填写`链接图片`和`自定义数据`。
    * 链接分类`ten`:为全站链接
    * 链接分类`one`:为内页链接
    * 链接分类`goog`:为推荐链接
4. 建议开启**伪静态**，否则可能出现未知错误（暂未做对未开启伪静态的适配）：后台——设置——永久链接——是否使用地址重写功能（选择是）
5. 不提供QQ自定义服务，有任何问题或者bug可以提交issue、评论或者email（ihewro@163.com）。

## 推荐插件

以下插件与本主题完全兼容。

1. [AutoTags](https://dt27.org/php/autotags-for-typecho/)
2. [CommentToMail](http://typecho.byends.com/post/CommentToMail-v2-0-0.html)
3. [QNUpload](http://ysido.com/qnupload_v_1_2_0.html)
4. [SmartSpam](http://www.yovisun.com/archive/typecho-plugin-smartspam.html)


## 下载地址

https://github.com/ihewro/typecho-theme-handsome/

## 版权声明

1. 在主题代码注释中尽量把引用代码来源注明清楚，一并感谢。
    * 主题后台界面风格来自[`material主题`](https://viosey.com/)
    * 主题function.php部分代码来自 [`qqdie`](http://qqdie.com)
    * 感谢 links插件作者 [`寒泥`](http://www.imhan.com/)
    * 主题cross自定义模板代码来自 [`breeze主题`](https://shansing.com/)by闪闪的星
2. 希望保留页脚版权信息，否则请不要使用TA。

----
如果你喜欢这款主题，欢迎`star`，给我继续更新的动力吧。
欢迎提出issue和fork代码。