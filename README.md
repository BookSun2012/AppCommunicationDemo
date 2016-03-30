# AppCommunicationDemo
学习应用之间如何互相调用，又如何传参数
假设需求是这样的：由一个app1跳转到app2之后，app2完成某项任务之后，怎么把app2的完成信息传到app1（自己的程序是app1），
传的是什么类型的数据，怎么进行解析？

使用App1作为第一个app的URL Schemes，App2为第二个app的URL Schemes。
