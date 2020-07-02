> 交互式应用程序安全测试（Interactive Application Security Testing）是2012年Gartner公司提出的一种新的应用程序安全测试方案，通过代理、VPN或者在服务端部署Agent程序，收集、监控Web应用程序运行时函数执行、数据传输，并与扫描器端进行实时交互，高效、准确的识别安全缺陷及漏洞，同时可准确确定漏洞所在的代码文件、行数、函数及参数。IAST相当于是DAST和SAST结合的一种互相关联运行时安全检测技术

### IAST分类
- 主动式IAST
- 被动式IAST

#### 主动式IAST
主动式IAST通过在被测试应用程序中部署Agent，然后使用外部扫描器触发流量由agent进行捕获、检测是否存在漏洞

#### 被动式IAST
被动式IAST通过在被测试应用程序中部署Agent，然后获取程序执行的代码上下文信息及数据流向，根据数据流向及程序执行的代码上下文信息梳理污点链路，判断是否存在漏洞


### 灵芝IAST
1.灵芝IAST属于被动式IAST，具有近实时检测、高检出率、低误报率、低漏报率等优点；

2.灵芝IAST不需要重放数据包，可覆盖加密、防重放、验证码等真实业务场景；

3.灵芝IAST不产生脏数据，不对测试人员工作造成干扰