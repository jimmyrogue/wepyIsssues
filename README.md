# wepyIsssues
此项目为我在微信小程序开发过程中遇到的坑以及wepy使用中遇到的问题的集合。
欢迎提交PR(滑稽)

# 目录



# 正文
 ### 新建项目报错
 
 关闭小程序开发者工具内ES6转ES5
 
 ![](https://ws1.sinaimg.cn/large/006tNc79gy1fhfpfosip4j31hw0bc0wc.jpg)
 
 
 ### promise无法使用
 
 在app.wpy内的constructor内添加``` this.use('promisify') ```
 
 ![](https://ws1.sinaimg.cn/large/006tNc79gy1fhfpjff1ztj30f2078jrt.jpg)
 
 
 ### 如何关闭（打开）ESlint?
 
 在项目wepy.config.js内eslint设置为false(true)
 
 ![](https://ws1.sinaimg.cn/large/006tNc79gy1fhfplm5w4xj30eo06eglz.jpg)
 
 



