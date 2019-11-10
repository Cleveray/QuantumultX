# Quantumult X
Quantumult Rebuilt from Scratch

### New Features
* MitM HTTPS decryption and rewrite are both working with traffic through TUN interface.
* Enable HTTP Analyzer can record whole HTTP request and response including body.
* Filter works on UDP traffic and UDP destination port can be set as whitelist.
* Server can have its own server_check_url instead of the global server_check_url.
* Supports V2Ray websocket and websocket + tls over shadowsocks, read sample configuration for details. Only compatible with server side deployed by V2Ray not shadowsocks v2ray-plugin.
* User-Agent(lower priority than Host) type of filter works on TUN traffic.
* Customized DNS setting supports customized port and IPv6 address.
* Improved the DNS mechanism by enable expired answers and start new query at the same time.
* Policy status and request history will keep the record of the full policy route like A -> B -> C -> D.
* The DNS results will be recorded along with the first responded DNS server, response time and the TTL.
* Modify configuration won't trigger reconnecting anymore.
* Rewrite HTTP request headers and response body.

Quantumult X

量子从零开始重建

###新功能

*MitM HTTPS解密和重写都是通过TUN接口处理流量的。   
*启用HTTP分析器可以记录整个HTTP请求和响应，包括正文。    
*过滤工作在UDP流量和UDP目的端口可以设置为白名单。    
*服务器可以有自己的server_check_url，而不是全局的server_check_url。    
*支持V2Ray websocket和websocket + tls在shadowsocks，阅读样本配置的细节。只兼容服务器端部署的V2Ray，而不是shadowsocks V2Ray插件。    
*用户代理(优先级低于主机)类型的过滤器在TUN流量上工作。   
*定制的DNS设置支持定制的端口和IPv6地址。   
*通过启用过期的答案并同时启动新的查询，改进了DNS机制。  b   
*策略状态和请求历史记录将保留整个策略路由的记录，如A -> B -> C -> D。   
*DNS结果将与第一个响应的DNS服务器、响应时间和TTL一起记录。   
*修改配置将不再触发重新连接。
*重写HTTP请求头和响应体。
