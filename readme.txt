旋转木马效果

用到的知识点：
1、CSS
--定位，层级，透明度。。。
2、JS
--类的封装prototype，this，参数配置，位置关系分析，旋转逻辑
--JQ api next,prev,animate,find,children,事件

使用
将图片放如文件夹中，并修改index.html文件中图片的src地址(建议图片尺寸为640*270)，

在html div里配置参数。详情参考index.html文件中的事例配置样例。
参数设置：
"width": 1000,		    //幻灯片的宽度
"height": 270,		    //幻灯片的高度
"posterWidth": 640,	  //幻灯片第一帧的宽度
"posterHeight": 270,	//幻灯片第一帧的高度
"scale": 0.9,		      //记录显示比例关系
"speed": 500,         //切换速度
"autoPlay": false,    //是否自动播放
"delay": 5000,        //自动播放时间
"verticalAlign": "middle" //top，middle，bottom幻灯片展示样式

学习心得：
学习js的封装方法，以及封装过程中需要注意的一些细节。主要体会项目开发的整个流程。