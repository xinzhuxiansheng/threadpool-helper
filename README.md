## threadpool-helper(线程池助手)

* 该项目是对JDK线程池功能衍生，例如参数调整、监控等。 
* 该项目参考 dynamic-tp,hippo4j开源项目

>一个不是在造轮子，就是在造轮子路上的程序员  

## 使用痛点 

使用线程池 ThreadPoolExecutor过程中你是否有以下痛点？
1. 使用JDK ThreadPoolExecutor线程池，但不知道参数设置多少合适，例如初识线程数，队列大小等等。
2. 线程数、队列设置不合理容易删除任务拒绝，那如何根据实际情况动态调整线程池参数
3. 监控，及时了解线程池运行状况
4. 提供自定义线程池功能，当线程池达到核心线程数时，先创建新线程，直到线程数达到最大线程数之后再放入队列等优化，适合低延迟场景。

