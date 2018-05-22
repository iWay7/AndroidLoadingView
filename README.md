# AndroidLoadingView
Android 仿 iOS Loading 视图。

### 本应用的示例

![image](https://github.com/iWay7/AndroidLoadingView/blob/master/sample.gif)   

### 本示例基于 AndroidHelpers 库，访问 https://github.com/iWay7/AndroidHelpers 添加依赖。

#### 开始使用：
##### 在布局文件中声明一个 LoadingView 视图即可使用：
```
<site.iway.androidhelpers.LoadingView
    android:layout_width="32dp"
    android:layout_height="32dp"
    app:layout_constraintBottom_toBottomOf="parent"
```

##### 支持的可配置属性：
```
app:loadingDrawable 旋转的 Drawable
app:rotateFrameSpan 单帧旋转的角度，以度为单位
app:rotateFrameTime 单帧间隔时间，以毫秒为单位
```