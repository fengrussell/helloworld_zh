## 令人眼前一亮的MariaDB参数

#### back_log

指当数据库暂时停止响应新的请求之前（比如连接数超过max_connections的时候），短时间内可存放多少请求在堆栈中等待资源的释放。当数据库中出现大量的unauthor user(表示等待连接的进程)的时候 可能需要考虑扩大这个值。

