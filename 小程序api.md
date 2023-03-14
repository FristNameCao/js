# 基础API

##### getApp()：获取小程序实例

##### getCurrentPages()：获取当前页面栈

##### wx.showModal()：显示模式弹窗

##### wx.showToast()：显示消息提示框

##### wx.showLoading()：显示加载提示框

##### wx.hideLoading()：隐藏加载提示框

##### wx.showNavigationBarLoading()：在当前页面显示导航条加载动画

##### wx.hideNavigationBarLoading()：隐藏导航条加载动画

##### wx.setNavigationBarTitle()：动态设置当前页面的标题

##### wx.setNavigationBarColor()：设置导航栏颜色

##### wx.setTabBarBadge()：设置tabBar某一项的右上角的文本

##### wx.removeTabBarBadge()：移去tabBar某一项右上角的文本

##### wx.showTabBarRedDot()：显示tabBar某一项的红点

##### wx.hideTabBarRedDot()：隐藏tabBar某一项的红点

# 界面API

wx.navigateTo()：保留当前页面，跳转到应用内的某个页面
wx.redirectTo()：关闭当前页面，跳转到应用内的某个页面
wx.reLaunch()：关闭所有页面，打开应用内的某个页面
wx.switchTab()：跳转到tabBar页面，并关闭其他所有非tabBar页面
wx.navigateBack()：关闭当前页面，返回上一页或多级页面
wx.setTabBarStyle()：动态设置tabBar的样式
wx.setTabBarItem()：动态设置tabBar某一项的内容
wx.setTopBarText()：动态设置设置顶部栏文字内容

# 网络API

wx.request()：发起网络请求
wx.uploadFile()：上传文件
wx.downloadFile()：下载文件
wx.connectSocket()：创建一个WebSocket连接
wx.onSocketOpen()：监听WebSocket连接打开事件
wx.onSocketError()：监听WebSocket错误事件
wx.sendSocketMessage()：通过WebSocket连接发送数据
wx.onSocketMessage()：监听WebSocket接收到服务器的消息事件
wx.closeSocket()：关闭WebSocket连接
wx.onSocketClose()：监听WebSocket连接关闭事件

# 媒体API

wx.chooseImage()：从本地相册选择图片或使用相机拍摄照片
wx.previewImage()：预览图片
wx.getImageInfo()：获取图片信息
wx.saveImageToPhotosAlbum()：保存图片到手机相册
wx.startRecord()：开始录音
wx.stopRecord()：停止录音
wx.playVoice()：播放语言音
wx.pauseVoice()：暂停播放放语音
wx.stopVoice()：停止播放放语音
wx.getBackgroundAudioPlayerState()：获取背景音乐播放状态
wx.playBackgroundAudio()：播放背景音乐
wx.pauseBackgroundAudio()：暂停播放放背景音乐
wx.seekBackgroundAudio()：控制背景音乐播放进入度
wx.stopBackgroundAudio()：停止播放背景音乐

# 位置API

wx.getLocation()：获取当前用户的位置
wx.openLocation()：使用微信内设置地图查看位置
wx.chooseLocation()：打开地图选择位置

# 设备API

wx.getSystemInfo()：获取系统信息
wx.getNetworkType()：获取网络状态
wx.makePhoneCall()：拨打电话
wx.scanCode()：扫码
wx.getClipboardData()：获取剪切贴板内容
wx.setClipboardData()：设置剪贴板内容
wx.vibrateLong()：使手机产生长时间的振动
wx.vibrateShort()：使手机产生短时间的振动

# 打开接口API

wx.login()：登录
wx.checkSession()：检查登录状态是否过期
wx.getUserInfo()：获取用户信息
wx.requestPayment()：发起微信支付
wx.chooseAddress()：获取用户收货地址
wx.openSetting()：打开设置页面
wx.getSetting()：获取用户的当前设置
wx.authorize()：提前向用户发起授权请求
wx.getShareInfo()：获取转发详细信息
wx.updateShareMenu()：更新转发属性
wx.showShareMenu()：显示当前页面的转发按钮
wx.hideShareMenu()：隐藏当前页面的转发按钮