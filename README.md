# 公用工具
# Extension:
  对Boolean,Context,Date,Double,Float,String,View等进行扩展
# Base:
  BaseActivity,BaseFragment基类扩展
  ViewIndcator底部导航栏
# Util:
  Gilde:图片显示
  Toast:通知显示(使用是请init()初始化)
  CommonUtils:基本常用方法
  CompressPhotoUtils:图片压缩
  DownLoadUtils:文件下载
  NotificationUtils:系统通知
  PopWindowUtils:弹窗
  SPUtils:sharePreferences缓存(使用是请init()初始化)
# view:
  自定义控件
  CommonDialog:进度加载
  CustomEditText,CustomGridView,CustomListView
  CustomLoadingDialog,DeleteEditView,XEditText
  
# 使用 
 repositories { 
        maven { url "https://raw.githubusercontent.com/WWSteven/CommonUtils/master" }
    }
 implementation 'com.steven:common_utils:1.0.0'
 
