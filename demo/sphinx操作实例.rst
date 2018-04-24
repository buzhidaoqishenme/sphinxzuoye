=======================
Sphinx的一个实例操作
=======================
Author：李昊

github中有些项目，是用reStructuredTex标记语言写的开源书籍，当你下载下来阅读时有时会发现下载下来的目录里面有很多各种格式的文件，并不能直接阅读，这时sphinx编译成我们可以阅读的格式，比如html，pdf等格式。

以用sphinx编译此开源书籍项目:https://github.com/me115/linuxtools_rst产生html格式为例。
 1.先到https://github.com/me115/linuxtools_rst下载开源书籍项目，然后解压到新建文件夹目录.
图片1:                                                     
                                                                
.. image:: .C:\Users\apple\Desktop\sphinx-demo\source\demo\tupain1.png                                 
    :width: 200px 

2.安装sphinx

3.进入工程目录查看makefile，可以看到makefile中有多个目标，每个目标代表一种格式，可以编译成多种格式，在此将编译成html格式的文档，下达如下命令开始编译:
图片2:                                                     
                                                                
.. image:: .C:\Users\apple\Desktop\sphinx-demo\source\demo\tupain2.png                                 
    :width: 200px 
编译完成后会提示编译结果输出到了那个目录，在此输出到了_build目录
图片3:                                                     
                                                                
.. image:: .C:\Users\apple\Desktop\sphinx-demo\source\demo\tupain3.png                                 
    :width: 200px 

4.查看编译结果

      
