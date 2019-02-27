# 第二组 组长：查伦 组员：谭振豪，程启伦，尚可珂
本程序语言为基于Eclipse编译的java
上传文件中包含java project：Onlinelearning-blockchain以及gson-2.6.2.jar文件
1. 下载好这两个文件后，进入Eclipse，点击Open file选中下载好的java project打开程序
2. 在Eclipse menu里打开Windows >preferences, 选择Java >Build path > User Libraries. 点击 new 建立一个新的User Library 取名为 “gson_lib” 点击确认. 选中gson_lib，按右边添加外部的JARs找到你存的gson-2.6.2.jar 应用并关闭
3. 添加User Libarary到你的java project中：右键你的java project的package选择 package explorer > Build path > Add Libraries. 选择User Libraries中你新建的 “gson_lib” 然后点击结束在代码中使用它需Import，Import it with import com.google.gson.*;
4.进入程序页面，选择到类Blockchain中，点击运行即可。
