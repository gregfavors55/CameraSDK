# CameraSDK帮助文档

  
  

## 一.首先在项目的gradle中引用：

    allprojects {
    repositories {
        jcenter()
        maven { url 'https://jitpack.io' } //
        }
    }



## 二.其次在dependencies中添加：
<pre><code>
dependencies {
    compile 'com.github.lmiot:CameraSDK:1.0'
}
</code></pre>


## 三.启动摄像头页面：
<pre><code>

               /**
                  * 进入摄像头页面
                  * @param sessionID 用户sessionID
                  */
                 private void startCamera(String sessionID) {
                     SPUtil.setSessionID(sessionID);
                     startActivity(new Intent(MainActivity.this, CameraDevices.class));
                 }


</code></pre>

## 四.建议修改目标版本为22：

      targetSdkVersion 22

## 五.参考效果图：
![](https://github.com/alijiahua/Image/blob/master/circleCorlorBg.png)

## 六.联系方式：980846919@qq.com

