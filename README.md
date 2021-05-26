# H5toM.html 文件只支持手机游览器打开小程序
# H5ToMinWechat.html 文件多做了微信游览器打开小程序 当然配置也需要更多


## H5toM.html 打开小程序的配置
1. 只需要讲生成的 生成小程序URL Scheme ![](https://i.postimg.cc/xdR6bKdB/image.png) 
2. 然后将生成的t值传入[![image.png](https://i.postimg.cc/W3cJjKjv/image.png)](https://postimg.cc/cKTJBFr9)
3. 最后将H5toM.html服务器url后拼接上生成的t即可 
4. 例：http://10.04.36.159:8080/H5toM.html?t=asdcdes (举例只是显示格式无法跳转请更具实际情况配置)

## H5ToMinWechat.html 打开小程序的配置
* 此配置比较复杂，需要替换文件中的 replace 参数标记的位置（建议全文见搜索替换）