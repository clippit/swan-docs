---
title: 错误码列表
header: develop
nav: api
sidebar: errorcode
---


## iOS 通用错误码  


|错误码|说明|
|--|--|
|101|掉漆协议版本不支持|
|201|解析失败，请检查调起协议是否合法|
|202|解析失败，请检查参数是否正确|
|301|找不到调起协议对应端能力模块|
|302|找不到调起协议对应端能力方法|
|401|安全校验失败|
|402|安全性检查：访问控制校验失败|

## Android 通用错误码

|错误码|说明|
|--|--|
|101|掉漆协议版本不支持|
|201|解析失败，请检查调起协议是否合法|
|202|解析失败，请检查参数是否正确|
|301|找不到调起协议对应端能力模块|
|302|找不到调起协议对应端能力方法|
|401|安全校验失败|
|402|安全性检查：访问控制校验失败|
|403|协议开关检查:访问控制开关关闭 |
|1001|执行失败|
|1002|打开APP失败|



## 位置
### 获取位置
#### getLocation
* Andriod

|错误码|说明|
|--|--|
|201|解析失败，请检查调起协议是否合法|
|401|安全校验失败|
|1001|文件不存在|

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确      |
|10005|系统拒绝|

#### chooseLocation
* Andriod

|错误码|说明|
|--|--|
|1002|用户取消错误码                                |
|1003|没有获取位置的权限|
|1007|地图服务异常|

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确       |
|1002|用户取消操作错误码|
|1003|没有获取位置的权限|
|1007|地图服务异常|

### 查看位置

#### openLocation 

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确      |

### 地图组件控制
#### createMapContext
* Andriod

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确      |
|1001||
|2000|地图lib包加载失败|

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确      |
## 界面
### 绘图
 
#### canvasGetImageData
* Andriod

|错误码|说明|
|--|--|
|201|解析失败，请检查调起协议是否合法|

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确      |
#### canvasPutImageData
* Andriod

|错误码|说明|
|--|--|
|201|解析失败，请检查调起协议是否合法|
|1001|执行失败|

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确      |
#### canvasToTempFilePath(OBJECT, this)
* Andriod

|错误码|说明|
|--|--|
|201|解析失败，请检查调起协议是否合法|
|1001|执行失败|

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确      |
 
#### canvasContext.measureText
* Andriod

|错误码|说明|
|--|--|
|201|解析失败，请检查调起协议是否合法|

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确      |
 
#### canvasContext.draw
* Andriod

|错误码|说明|
|--|--|
|201|解析失败，请检查调起协议是否合法|

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确      |
 

### 交互反馈
#### showToast
* Andriod

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确      |
|302|找不到调起协议对应端能力方法|

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确      |
#### showLoading
* Andriod

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确      |
|1001|执行失败|

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确      |
#### hideToast
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败                                            |


                                                         |
#### hideLoading
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败                                            |


                                                          |
#### showModal
* Andriod

|错误码|说明|
|--|--|
|201|解析失败，请检查调起协议是否合法|
* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确      |

#### showActionSheet
* Andriod

|错误码|说明|
|--|--|
|201|解析失败，请检查调起协议是否合法|
|202|解析失败，请检查参数是否正确|


   

###导航栏
#### setNavigationBarTitle
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败   |

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确   |
#### showNavigationBarLoading
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败   |


                
#### hideNavigationBarLoading
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败                                      |


                                   

#### setNavigationBarColor
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败                                      |

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确   |

###设置tabBar
#### setTabBarBadge
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败            |

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确   |
|1001|当前页面不含tabbar|

#### removeTabBarBadge
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败      |

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确   |
|1001|当前页面不含tabbar|

#### showTabBarRedDot
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败     |

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确  |
|1001|当前页面不含tabbar|

#### hideTabBarRedDot
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败   |

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确|
|1001|当前页面不含tabbar|

#### setTabBarStyle
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败   |

* iOS

|错误码|说明|
|--|--|
|1001|当前页面不含tabbar  |
#### setTabBarItem
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败  |

* iOS

|错误码|说明|
|--|--|
|202|解析失败，请检查参数是否正确   |
|1002|超过icon文件最大值|

#### showTabBar
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败   |

* iOS

|错误码|说明|
|--|--|
|1001|当前页面不含tabbar  |

#### hideTabBar
* Andriod

|错误码|说明|
|--|--|
|1001|执行失败   |

* iOS

|错误码|说明|
|--|--|
|1001|当前页面不含tabbar  |

