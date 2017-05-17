# ToastUtils
#在使用的时候需要在你的application中调用ToastUtils.init(Context context)，给Toast传入一个上下文对象

#使用方法
#Step 1.Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
#Step 2. Add the dependency

	dependencies {
	         compile 'com.github.hanxiaoqiangfly:ToastUtils:1.0.4'
	}
