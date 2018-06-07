# Review_of_Computer_Graphics
计算机图形学复习

> 适用人群： 上课没好好听课或者似懂非懂迷迷糊糊的同学

- 教材：Interactive Computer Graphics: A Top-Down Approach with Shader-Based OpenGL Sixth Edition. 
https://inspirit.net.in/books/academic/Interactive%20Computer%20Graphics.pdf

- 教材课后习题部分答案：https://sxbb.me/GUsHv

计算机图形学的**pipeline**分为以下几个部分：
> 1. 顶点处理模块
> 2. 裁剪模块和图元组装模块
> 3. 光栅化模块
> 4. 片元处理模块


下面就每个部分的重点整理出一些高质量的链接来帮助理解与复习

### **顶点处理模块**
> 1. **关于坐标变换**

> 模型坐标系到世界坐标系再到相机坐标系是如何处理的？
  
> 到达相机坐标系后是如何进行投影的(正交投影与透视投影)？
  
> 投影完成后是如何进行视口变换的？
  
> https://blog.csdn.net/zhongjling/article/details/8488844

> https://blog.csdn.net/zhanglongit/article/details/7525918  
  
> http://www.360doc.com/content/10/0917/09/1066008_54279529.shtml

> 2. **关于glLookAt()和glPerspective() 函数的解释**

> https://blog.csdn.net/ivan_ljf/article/details/8764737

> https://blog.csdn.net/augusdi/article/details/19936239

> 3. **关于图元绘制**

> http://www.mamicode.com/info-detail-1139707.html

> 4. **关于四元数**

> https://www.zhihu.com/question/23005815 第二个回答


### **裁剪模块**

> 1. **直线裁剪:**

> **Cohen-Sutherland Algorithm**

    -这个算法见教材 p311,总共分为四步，但是想要了解真正的步骤，还需要一个例子。参考 exam/CG2017spring试卷-B-答案.doc PartII 的第四题。
    
> **Liang-Barsky Clipping**
    
    -这个算法的实现在 powerpoint/AngelCG21.ppt 的18，19页。
    
一个关于两个算法的链接 https://blog.csdn.net/pleasecallmewhy/article/details/8393445    
    
> 2. **多边形裁剪:**

> **sutherland-hodgman algorithm**

> 一个粗略的解释:https://blog.csdn.net/damotiansheng/article/details/43274183

> 一个让你理解算法是如何运行的视频: https://www.youtube.com/watch?v=Euuw72Ymu0M

### **直线/圆生成与多边形填充算法**

> 1. **DDA**




