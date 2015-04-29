title: "图标和图像尺寸"
date: 2015-04-29 16:05:54
tags:
-Blog

---
**译文**-原文来自[苹果官方文件](https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/IconMatrix.html#//apple_ref/doc/uid/TP40006556-CH27-SW1)


每款App都需要一个APP图标，一个启动文件或者启动画面。不仅如此，一些APP需要自定义图标来表达APP的具体内容，功能或者导航栏，工具栏和标签栏的风格和app内其他的配图不同。表格41-1中的图标和图像必须符合一定的标准才能让显示效果达到最佳。而且，有些图标和图像是有命名上的要求的（如何给这些文件命令，请参考[应用图标](https://developer.apple.com/library/ios/documentation/iPhone/Conceptual/iPhoneOSProgrammingGuide/ExpectedAppBehaviors/ExpectedAppBehaviors.html#//apple_ref/doc/uid/TP40007072-CH3-SW1)和[应用启动画面](https://developer.apple.com/library/ios/documentation/iPhone/Conceptual/iPhoneOSProgrammingGuide/ExpectedAppBehaviors/ExpectedAppBehaviors.html#//apple_ref/doc/uid/TP40007072-CH3-SW3)）


**表格41-1** 尺寸图标和图像的尺寸（像素）
{% asset_img Tab41-1.jpg %}



所有的图像和图标建议用png格式，需要避免使用交错型的png文件格式。
标准的图标和图像的位深（每像素占用的字节）是24位，红，绿，蓝通道分别为8位，再加上透明通道的8位，总共有32位。
你不需要把你的调色板限制在web安全色里。