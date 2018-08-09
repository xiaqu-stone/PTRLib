

## 说明

大神开源库的再打包，大神链接传送门如下：

- [GitHub](https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh)
- [中文文档](https://github.com/liaohuqiu/android-Ultra-Pull-To-Refresh/blob/master/README-cn.md)
- [我眼中的下拉刷新（原理介绍）](https://android-ultra-ptr.liaohuqiu.net/cn/)



### gradle 

```
implementation "com.sqq.xiaqu:ptr-lib:1.0.0"
```

增加PtrFrameLayout自动刷新的延迟设置

```
    public void autoRefresh() {
        postDelayed(new Runnable() {
            @Override
            public void run() {
                autoRefresh(false);
            }
        }, 150);
    }

```
