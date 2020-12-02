# Android 面试

## 1. Android

[Android 操作系统架构开篇](http://gityuan.com/android/)

[Android Interview Questions Cheat Sheet — Part I](https://android.jlelse.eu/android-interview-questions-cheat-sheet-96ea01c88def)

[Android Interview Questions](https://github.com/MindorksOpenSource/android-interview-questions)

[Android Interview Questions and Answers](https://www.raywenderlich.com/11107559-android-interview-questions-and-answers#toc-anchor-032)

[今日头条 Android 面试题及答案 ](https://www.jianshu.com/p/5e5908ab3ea9)

[**Android高级面试题**](https://github.com/JsonChao/Awesome-Android-Interview/blob/master/Android%E7%9B%B8%E5%85%B3/Android%E9%AB%98%E7%BA%A7%E9%9D%A2%E8%AF%95%E9%A2%98.md)

[史上最全的Android面试题集锦](https://juejin.cn/post/6844903891625050119)

### 1.1 View

#### View 绘制流程

[深入理解Android之View的绘制流程](https://www.jianshu.com/p/060b5f68da79)

[[View绘制流程](https://www.cnblogs.com/andy-songwei/p/10955062.html)](https://www.cnblogs.com/andy-songwei/p/10955062.html)

#### 自定义 View

[Measure, Layout, Draw, Repeat: Custom Views and ViewGroups](https://academy.realm.io/posts/360andev-huyen-tue-dao-measure-layout-draw-repeat-custom-views-and-viewgroups-android/)

[Creating custom and compound views in Android](https://www.vogella.com/tutorials/AndroidCustomViews/article.html)

[PerfMatters introduction to custom ViewGroups to improve performance — Part 2](https://android.jlelse.eu/perfmatters-introduction-to-custom-viewgroups-to-improve-performance-part-2-f14fbcd47c)

[Android Custom View Level 1 Basic Terms and Creation of Custom View](https://proandroiddev.com/android-custom-view-level-1-67ed1c3febe1)

[手把手教你写一个完整的自定义 View](https://juejin.cn/post/6844903482089013256)

[自定义View，有这一篇就够了](https://www.jianshu.com/p/c84693096e41)

#### CustomView performance tips

[CustomView performance tips](https://riptutorial.com/android/example/17883/customview-performance-tips)

* 不要在 onDraw() 方法创建对象

* 仅更新其中的一小部分，不要重绘整个视图以， 而是重新绘制视图的特定部分。

  ```java
  invalidate(boundToBeRefreshed);
  ```

* 不要在视图的`onDraw`方法中进行任何计算，而应该在调用`invalidate()`之前完成计算。

[**Android性能优化：那些不可忽略的绘制优化 **](https://www.jianshu.com/p/cbdaeb1bede5)

[Android 鬼点子 - 举例说明自定义 View 性能优化](https://juejin.cn/post/6844903477718548487)

[**Android自定义View——从零开始实现书籍翻页效果（性能优化篇）** ](https://juejin.cn/post/6844903533595066375)

#### 滑动冲突



### 事件分发

[Android事件分发机制](http://gityuan.com/2015/09/19/android-touch/)

[Android事件分发机制 详解攻略](https://blog.csdn.net/carson_ho/article/details/54136311)



### 1.3 Hanlder



### 1.4 Binder



### 1.5 Android 系统





