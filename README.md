# UnityPlayerActivity





如果您不希望自己的应用或 Activity 在多窗口模式下运行，请设置 `android:resizeableActivity false`。在这种情况下，应用会始终全屏显示。系统会根据 Android 操作系统级别控制完成此操作的方式：

- 如果您的应用定位到 Android 8.0（API 级别 26）或更高版本，它会根据其布局填充整个屏幕。
- 如果您的应用定位到 Android 7.1（API 级别 25）或更低版本，则系统会将应用界面的大小限制为宽高比为 16:9（约为 1.86）的窗口。如果应用在具有较大屏幕宽高比的设备上运行，则该应用会以一个 16:9 的宽屏显示（上下各留出一部分屏幕不用）。



想在Android 8.0支持上下各留出一部分屏幕不用。添加了RelativeLayout用来做视口的匹配。

IOS同样可以修改OC文件。

