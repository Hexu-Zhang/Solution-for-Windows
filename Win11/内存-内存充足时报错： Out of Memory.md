# 问题描述

内存充足时出现报错：Out of Memory，如图所示：

![alt text](ac14ee543c98254fa373d77d729a8a88-1.png)

# 解决方法

**扩大虚拟内存**

操作步骤如下：

1. 打开文件资源管理器
    1. 方法：
        1. Win + E
        2. 随意打开一个文件夹
    2. 结果：
        
        ![alt text](6a56ba8e787f200dc0a8f6c39ebb9741.png)
        
2. 右键此电脑，点击**属性**
    1. 方法
        
        ![alt text](9be99ecf6a8e25a929425dda60210f9d.png)
        
    2. 结果
        1. 进入该界面
            
            ![alt text](c820d95b603009284a86010320f5929c.png)
            
3. 下滑，打开高级系统设置
    1. 方法
        
        ![alt text](f1a71ce48a9378e86afdca4f94ed86e2.png)
        
    2. 结果
        
        ![alt text](2d11007d3815a74520b5e3bd24aefcfa.png)
        
4. 打开高级-设置-高级-更改
    1. 方法
        
        ![alt text](cbff4f6c7958d40bb8c7763bc97fc55c.png)
        
    2. 结果
        
        ![alt text](c490d39276333eee4dd717def099e4ea.png)
        
5. 关闭：自动管理所有驱动器的分页文件大小，选择可用空间较高的盘，自定义大小，数值为：初始大小：内存大小×1024，最大值：初始大小×1.5-初始大小×2
    1. 操作
        
        ![alt text](4d8ec93d2d4bf526d8cbdd4fdaf8017c.png)
        
6. 最终：设置-确定，重启即可
    
    ![alt text](a47c516ab5e40fb79c5b50ba08adfc6c.png)