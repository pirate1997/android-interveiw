## activity声明周期？
![activity声明周期](https://github.com/knowledgeIsMoney/android-interveiw/blob/master/images/%E7%94%9F%E5%91%BD%E5%91%A8%E6%9C%9F.jpg)
## A启动B的生命周期过程？
    AActivity: onPause
    BActivity: onCreate
    BActivity: onStart
    BActivity: onResume
    AActivity: onStop
## B返回A的生命周期过程？
    BActivity: onPause
    AActivity: onRestart
    AActivity: onStart
    AActivity: onResume
    BActivity: onStop
    BActivity: onDestroy
