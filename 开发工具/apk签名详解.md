task:apk签名有什么用？

    1.只有使用相同的key，才能在安装时覆盖掉老版本的apk，并且包名需要相同。
    2.Android系统允许多个签名相同的应用程序跑在一个进程里，系统将这些应用看成是一个应用，所以我们可以理解成多个应用程序变为了几个模块，我们可以针对模块进行独立的更新，应用程序之间也可以进行共享代码和数据。
    