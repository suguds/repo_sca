# huggingface/transformers安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1702387003512635392.svg)](https://www.murphysec.com/console/report/1674674849786388480/1702387003512635392)

仓库描述：🤗 Transformers: State-of-the-art Machine Learning for Pytorch, TensorFlow, and JAX.

仓库地址：[https://github.com/huggingface/transformers](https://github.com/huggingface/transformers)

| star：111787 | watch：1051 | fork：22202 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-15 01:51:33 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-15 02:21:45 | 组件总数：376 | 漏洞总数：210 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|psutil 资源管理错误漏洞|双重释放|[MPS-2019-14454](https://www.oscs1024.com/hd/MPS-2019-14454)|CVE-2019-18874|高危|
|Google TensorFlow 缓冲区错误漏洞|缓冲区溢出|[MPS-2020-15185](https://www.oscs1024.com/hd/MPS-2020-15185)|CVE-2020-15266|高危|
|Google TensorFlow 缓冲区错误漏洞|对未经初始化资源的使用|[MPS-2020-17213](https://www.oscs1024.com/hd/MPS-2020-17213)|CVE-2020-26266|中危|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2020-17218](https://www.oscs1024.com/hd/MPS-2020-17218)|CVE-2020-26269|高危|
|Google TensorFlow 缓冲区错误漏洞||[MPS-2020-17219](https://www.oscs1024.com/hd/MPS-2020-17219)|CVE-2020-26271|低危|
|Google TensorFlow 数字错误漏洞|数值类型间的不正确转换|[MPS-2021-17260](https://www.oscs1024.com/hd/MPS-2021-17260)|CVE-2021-37645|中危|
|Google TensorFlow 验证错误漏洞|对数据真实性的验证不充分|[MPS-2021-17314](https://www.oscs1024.com/hd/MPS-2021-17314)|CVE-2021-37692|中危|
|NumPy 安全漏洞|不充分的比较|[MPS-2021-25631](https://www.oscs1024.com/hd/MPS-2021-25631)|CVE-2021-34141|中危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-31964](https://www.oscs1024.com/hd/MPS-2021-31964)|CVE-2021-41195|中危|
|Google TensorFlow 数字错误漏洞|超界折返|[MPS-2021-31965](https://www.oscs1024.com/hd/MPS-2021-31965)|CVE-2021-41196|中危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-31966](https://www.oscs1024.com/hd/MPS-2021-31966)|CVE-2021-41197|中危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-31967](https://www.oscs1024.com/hd/MPS-2021-31967)|CVE-2021-41198|中危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-31968](https://www.oscs1024.com/hd/MPS-2021-31968)|CVE-2021-41199|中危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2021-31969](https://www.oscs1024.com/hd/MPS-2021-31969)|CVE-2021-41200|中危|
|Google TensorFlow 缓冲区错误漏洞|使用未经初始化的指针|[MPS-2021-31970](https://www.oscs1024.com/hd/MPS-2021-31970)|CVE-2021-41201|高危|
|Google TensorFlow 安全漏洞|数值类型间的不正确转换|[MPS-2021-31971](https://www.oscs1024.com/hd/MPS-2021-31971)|CVE-2021-41202|中危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-31972](https://www.oscs1024.com/hd/MPS-2021-31972)|CVE-2021-41203|高危|
|Google TensorFlow 缓冲区错误漏洞|使用未经初始化的指针|[MPS-2021-31973](https://www.oscs1024.com/hd/MPS-2021-31973)|CVE-2021-41204|中危|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2021-31974](https://www.oscs1024.com/hd/MPS-2021-31974)|CVE-2021-41205|高危|
|Google TensorFlow 安全漏洞|完整性检查值验证不恰当|[MPS-2021-31975](https://www.oscs1024.com/hd/MPS-2021-31975)|CVE-2021-41206|高危|
|Google TensorFlow 数字错误漏洞|除零错误|[MPS-2021-31976](https://www.oscs1024.com/hd/MPS-2021-31976)|CVE-2021-41207|中危|
|Google TensorFlow 安全漏洞|空指针取消引用|[MPS-2021-31977](https://www.oscs1024.com/hd/MPS-2021-31977)|CVE-2021-41208|高危|
|Google TensorFlow 数字错误漏洞|除零错误|[MPS-2021-31978](https://www.oscs1024.com/hd/MPS-2021-31978)|CVE-2021-41209|中危|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2021-31979](https://www.oscs1024.com/hd/MPS-2021-31979)|CVE-2021-41210|高危|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2021-31980](https://www.oscs1024.com/hd/MPS-2021-31980)|CVE-2021-41211|高危|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2021-31981](https://www.oscs1024.com/hd/MPS-2021-31981)|CVE-2021-41212|高危|
|Google TensorFlow 资源管理错误漏洞|不恰当的同步机制|[MPS-2021-31982](https://www.oscs1024.com/hd/MPS-2021-31982)|CVE-2021-41213|中危|
|Google TensorFlow 缓冲区错误漏洞|使用未经初始化的指针|[MPS-2021-31983](https://www.oscs1024.com/hd/MPS-2021-31983)|CVE-2021-41214|高危|
|Google TensorFlow 代码问题漏洞|空指针取消引用|[MPS-2021-31984](https://www.oscs1024.com/hd/MPS-2021-31984)|CVE-2021-41215|中危|
|Google TensorFlow 缓冲区错误漏洞|越界写入|[MPS-2021-31985](https://www.oscs1024.com/hd/MPS-2021-31985)|CVE-2021-41216|高危|
|Google TensorFlow 代码问题漏洞|空指针取消引用|[MPS-2021-31986](https://www.oscs1024.com/hd/MPS-2021-31986)|CVE-2021-41217|中危|
|Google TensorFlow 数字错误漏洞|除零错误|[MPS-2021-31987](https://www.oscs1024.com/hd/MPS-2021-31987)|CVE-2021-41218|中危|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2021-31988](https://www.oscs1024.com/hd/MPS-2021-31988)|CVE-2021-41219|高危|
|Google TensorFlow 缓冲区错误漏洞|越界写入|[MPS-2021-31990](https://www.oscs1024.com/hd/MPS-2021-31990)|CVE-2021-41221|高危|
|Google TensorFlow 安全漏洞|数值计算不正确|[MPS-2021-31991](https://www.oscs1024.com/hd/MPS-2021-31991)|CVE-2021-41222|中危|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2021-31992](https://www.oscs1024.com/hd/MPS-2021-31992)|CVE-2021-41223|高危|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2021-31993](https://www.oscs1024.com/hd/MPS-2021-31993)|CVE-2021-41224|高危|
|Google TensorFlow 安全漏洞|对未经初始化资源的使用|[MPS-2021-31994](https://www.oscs1024.com/hd/MPS-2021-31994)|CVE-2021-41225|高危|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2021-31995](https://www.oscs1024.com/hd/MPS-2021-31995)|CVE-2021-41226|高危|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2021-31996](https://www.oscs1024.com/hd/MPS-2021-31996)|CVE-2021-41227|中危|
|Google TensorFlow 代码注入漏洞|代码注入|[MPS-2021-31997](https://www.oscs1024.com/hd/MPS-2021-31997)|CVE-2021-41228|高危|
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|Google TensorFlow 数字错误漏洞|除零错误|[MPS-2021-37083](https://www.oscs1024.com/hd/MPS-2021-37083)|CVE-2022-21725|中危|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2021-37084](https://www.oscs1024.com/hd/MPS-2021-37084)|CVE-2022-21726|高危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-37085](https://www.oscs1024.com/hd/MPS-2021-37085)|CVE-2022-21727|高危|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2021-37086](https://www.oscs1024.com/hd/MPS-2021-37086)|CVE-2022-21728|高危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-37087](https://www.oscs1024.com/hd/MPS-2021-37087)|CVE-2022-21729|中危|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2021-37088](https://www.oscs1024.com/hd/MPS-2021-37088)|CVE-2022-21730|高危|
|Google TensorFlow 安全漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2021-37089](https://www.oscs1024.com/hd/MPS-2021-37089)|CVE-2022-21731|中危|
|Google TensorFlow 安全漏洞|不加限制或调节的资源分配|[MPS-2021-37090](https://www.oscs1024.com/hd/MPS-2021-37090)|CVE-2022-21732|中危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-37091](https://www.oscs1024.com/hd/MPS-2021-37091)|CVE-2022-21733|中危|
|Google TensorFlow 安全漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2021-37092](https://www.oscs1024.com/hd/MPS-2021-37092)|CVE-2022-21734|中危|
|Google TensorFlow 数字错误漏洞|除零错误|[MPS-2021-37093](https://www.oscs1024.com/hd/MPS-2021-37093)|CVE-2022-21735|中危|
|Google TensorFlow 代码问题漏洞|空指针取消引用|[MPS-2021-37094](https://www.oscs1024.com/hd/MPS-2021-37094)|CVE-2022-21736|中危|
|Google TensorFlow 代码问题漏洞|对因果或异常条件的不恰当检查|[MPS-2021-37095](https://www.oscs1024.com/hd/MPS-2021-37095)|CVE-2022-21737|中危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2021-37096](https://www.oscs1024.com/hd/MPS-2021-37096)|CVE-2022-21738|中危|
|Google TensorFlow 代码问题漏洞|空指针取消引用|[MPS-2021-37097](https://www.oscs1024.com/hd/MPS-2021-37097)|CVE-2022-21739|中危|
|Google TensorFlow 缓冲区错误漏洞|越界写入|[MPS-2021-37098](https://www.oscs1024.com/hd/MPS-2021-37098)|CVE-2022-21740|高危|
|Google TensorFlow 数字错误漏洞|除零错误|[MPS-2021-37099](https://www.oscs1024.com/hd/MPS-2021-37099)|CVE-2022-21741|中危|
|Google TensorFlow 输入验证错误漏洞|拒绝服务|[MPS-2021-6371](https://www.oscs1024.com/hd/MPS-2021-6371)|CVE-2021-29611|中危|
|Google TensorFlow 目录穿越漏洞|路径遍历|[MPS-2021-9211](https://www.oscs1024.com/hd/MPS-2021-9211)|CVE-2021-35958|严重|
|Google TensorFlow 数字错误漏洞|除零错误|[MPS-2022-1984](https://www.oscs1024.com/hd/MPS-2022-1984)|CVE-2022-23557|中危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2022-1985](https://www.oscs1024.com/hd/MPS-2022-1985)|CVE-2022-23558|高危|
|Google Tensorflow 输入验证错误漏洞|整数溢出或环绕|[MPS-2022-1986](https://www.oscs1024.com/hd/MPS-2022-1986)|CVE-2022-23559|高危|
|Google TensorFlow 缓冲区错误漏洞||[MPS-2022-1987](https://www.oscs1024.com/hd/MPS-2022-1987)|CVE-2022-23560|高危|
|Google TensorFlow 缓冲区错误漏洞|越界写入|[MPS-2022-1988](https://www.oscs1024.com/hd/MPS-2022-1988)|CVE-2022-23561|高危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2022-1989](https://www.oscs1024.com/hd/MPS-2022-1989)|CVE-2022-23562|高危|
|Google Tensorflow 安全漏洞|检查时间与使用时间(TOCTOU)的竞争条件|[MPS-2022-1990](https://www.oscs1024.com/hd/MPS-2022-1990)|CVE-2022-23563|中危|
|Google Tensorflow 安全漏洞|可达断言|[MPS-2022-1991](https://www.oscs1024.com/hd/MPS-2022-1991)|CVE-2022-23564|中危|
|Google Tensorflow 安全漏洞|可达断言|[MPS-2022-1992](https://www.oscs1024.com/hd/MPS-2022-1992)|CVE-2022-23565|中危|
|Google TensorFlow 缓冲区错误漏洞|越界写入|[MPS-2022-1993](https://www.oscs1024.com/hd/MPS-2022-1993)|CVE-2022-23566|高危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2022-1994](https://www.oscs1024.com/hd/MPS-2022-1994)|CVE-2022-23567|中危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2022-1995](https://www.oscs1024.com/hd/MPS-2022-1995)|CVE-2022-23568|中危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-1996](https://www.oscs1024.com/hd/MPS-2022-1996)|CVE-2022-23569|中危|
|Google TensorFlow 代码问题漏洞||[MPS-2022-1997](https://www.oscs1024.com/hd/MPS-2022-1997)|CVE-2022-23570|中危|
|Google Tensorflow 安全漏洞|可达断言|[MPS-2022-1998](https://www.oscs1024.com/hd/MPS-2022-1998)|CVE-2022-23571|中危|
|Google TensorFlow 代码问题漏洞|可达断言|[MPS-2022-1999](https://www.oscs1024.com/hd/MPS-2022-1999)|CVE-2022-23572|中危|
|Google Tensorflow 安全漏洞|对未经初始化资源的使用|[MPS-2022-2000](https://www.oscs1024.com/hd/MPS-2022-2000)|CVE-2022-23573|高危|
|Google TensorFlow 缓冲区错误漏洞||[MPS-2022-2001](https://www.oscs1024.com/hd/MPS-2022-2001)|CVE-2022-23574|高危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2022-2002](https://www.oscs1024.com/hd/MPS-2022-2002)|CVE-2022-23575|中危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2022-2003](https://www.oscs1024.com/hd/MPS-2022-2003)|CVE-2022-23576|中危|
|Google TensorFlow 代码问题漏洞|空指针取消引用|[MPS-2022-2004](https://www.oscs1024.com/hd/MPS-2022-2004)|CVE-2022-23577|中危|
|Google Tensorflow 安全漏洞|内存泄漏|[MPS-2022-2005](https://www.oscs1024.com/hd/MPS-2022-2005)|CVE-2022-23578|中危|
|Google Tensorflow 安全漏洞|可达断言|[MPS-2022-2006](https://www.oscs1024.com/hd/MPS-2022-2006)|CVE-2022-23579|中危|
|Google TensorFlow 资源管理错误漏洞|输入中指定数量的验证不当|[MPS-2022-2007](https://www.oscs1024.com/hd/MPS-2022-2007)|CVE-2022-23580|中危|
|Google Tensorflow 安全漏洞|可达断言|[MPS-2022-2008](https://www.oscs1024.com/hd/MPS-2022-2008)|CVE-2022-23581|中危|
|Google Tensorflow 安全漏洞|可达断言|[MPS-2022-2009](https://www.oscs1024.com/hd/MPS-2022-2009)|CVE-2022-23582|中危|
|Google TensorFlow 安全漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2022-2010](https://www.oscs1024.com/hd/MPS-2022-2010)|CVE-2022-23583|中危|
|Google TensorFlow 资源管理错误漏洞|UAF|[MPS-2022-2011](https://www.oscs1024.com/hd/MPS-2022-2011)|CVE-2022-23584|中危|
|Google Tensorflow 安全漏洞|内存泄漏|[MPS-2022-2012](https://www.oscs1024.com/hd/MPS-2022-2012)|CVE-2022-23585|中危|
|Google Tensorflow 安全漏洞|可达断言|[MPS-2022-2013](https://www.oscs1024.com/hd/MPS-2022-2013)|CVE-2022-23586|中危|
|Tensorflow 输入验证错误漏洞|整数溢出或环绕|[MPS-2022-2014](https://www.oscs1024.com/hd/MPS-2022-2014)|CVE-2022-23587|严重|
|Google Tensorflow 安全漏洞|可达断言|[MPS-2022-2015](https://www.oscs1024.com/hd/MPS-2022-2015)|CVE-2022-23588|中危|
|Google TensorFlow 代码问题漏洞|空指针取消引用|[MPS-2022-2016](https://www.oscs1024.com/hd/MPS-2022-2016)|CVE-2022-23589|中危|
|Google TensorFlow 资源管理错误漏洞|未经控制的递归|[MPS-2022-2018](https://www.oscs1024.com/hd/MPS-2022-2018)|CVE-2022-23591|高危|
|Google TensorFlow 代码问题漏洞|空指针取消引用|[MPS-2022-2022](https://www.oscs1024.com/hd/MPS-2022-2022)|CVE-2022-23595|中危|
|Google TensorFlow拒绝服务漏洞|可达断言|[MPS-2022-51448](https://www.oscs1024.com/hd/MPS-2022-51448)|CVE-2022-35934|高危|
|Google TensorFlow存在未明漏洞|可达断言|[MPS-2022-51449](https://www.oscs1024.com/hd/MPS-2022-51449)|CVE-2022-35935|高危|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2022-51451](https://www.oscs1024.com/hd/MPS-2022-51451)|CVE-2022-35937|严重|
|Google TensorFlow 缓冲区错误漏洞|越界读取|[MPS-2022-51452](https://www.oscs1024.com/hd/MPS-2022-51452)|CVE-2022-35938|严重|
|Google TensorFlow 缓冲区错误漏洞|越界写入|[MPS-2022-51453](https://www.oscs1024.com/hd/MPS-2022-51453)|CVE-2022-35939|严重|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2022-51454](https://www.oscs1024.com/hd/MPS-2022-51454)|CVE-2022-35940|高危|
|Google TensorFlow AvgPoolOp拒绝服务漏洞|可达断言|[MPS-2022-51455](https://www.oscs1024.com/hd/MPS-2022-51455)|CVE-2022-35941|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51466](https://www.oscs1024.com/hd/MPS-2022-51466)|CVE-2022-35952|高危|
|Google TensorFlow拒绝服务漏洞|可达断言|[MPS-2022-51473](https://www.oscs1024.com/hd/MPS-2022-51473)|CVE-2022-35959|高危|
|Google TensorFlow拒绝服务漏洞|可达断言|[MPS-2022-51474](https://www.oscs1024.com/hd/MPS-2022-51474)|CVE-2022-35960|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51477](https://www.oscs1024.com/hd/MPS-2022-51477)|CVE-2022-35963|高危|
|Google TensorFlow输入验证错误漏洞|拒绝服务|[MPS-2022-51478](https://www.oscs1024.com/hd/MPS-2022-51478)|CVE-2022-35964|高危|
|Google TensorFlow代码问题漏洞|空指针取消引用|[MPS-2022-51479](https://www.oscs1024.com/hd/MPS-2022-51479)|CVE-2022-35965|高危|
|Google TensorFlow 输入验证错误漏洞|拒绝服务|[MPS-2022-51480](https://www.oscs1024.com/hd/MPS-2022-51480)|CVE-2022-35966|高危|
|Google TensorFlow输入验证错误漏洞|拒绝服务|[MPS-2022-51481](https://www.oscs1024.com/hd/MPS-2022-51481)|CVE-2022-35967|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51482](https://www.oscs1024.com/hd/MPS-2022-51482)|CVE-2022-35968|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51483](https://www.oscs1024.com/hd/MPS-2022-51483)|CVE-2022-35969|高危|
|Google TensorFlow 输入验证错误漏洞|拒绝服务|[MPS-2022-51484](https://www.oscs1024.com/hd/MPS-2022-51484)|CVE-2022-35970|高危|
|Google TensorFlow拒绝服务漏洞|可达断言|[MPS-2022-51485](https://www.oscs1024.com/hd/MPS-2022-51485)|CVE-2022-35971|高危|
|Google TensorFlow 输入验证错误漏洞|拒绝服务|[MPS-2022-51486](https://www.oscs1024.com/hd/MPS-2022-51486)|CVE-2022-35972|高危|
|Google TensorFlow 输入验证错误漏洞|拒绝服务|[MPS-2022-51487](https://www.oscs1024.com/hd/MPS-2022-51487)|CVE-2022-35973|高危|
|Google TensorFlow 输入验证错误漏洞|拒绝服务|[MPS-2022-51488](https://www.oscs1024.com/hd/MPS-2022-51488)|CVE-2022-35974|高危|
|Google TensorFlow 输入验证错误漏洞|拒绝服务|[MPS-2022-51493](https://www.oscs1024.com/hd/MPS-2022-51493)|CVE-2022-35979|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51495](https://www.oscs1024.com/hd/MPS-2022-51495)|CVE-2022-35981|高危|
|Google TensorFlow 输入验证错误漏洞|拒绝服务|[MPS-2022-51496](https://www.oscs1024.com/hd/MPS-2022-51496)|CVE-2022-35982|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51497](https://www.oscs1024.com/hd/MPS-2022-51497)|CVE-2022-35983|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51498](https://www.oscs1024.com/hd/MPS-2022-51498)|CVE-2022-35984|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51499](https://www.oscs1024.com/hd/MPS-2022-51499)|CVE-2022-35985|高危|
|Google TensorFlow 安全漏洞|拒绝服务|[MPS-2022-51500](https://www.oscs1024.com/hd/MPS-2022-51500)|CVE-2022-35986|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51501](https://www.oscs1024.com/hd/MPS-2022-51501)|CVE-2022-35987|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51502](https://www.oscs1024.com/hd/MPS-2022-51502)|CVE-2022-35988|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51503](https://www.oscs1024.com/hd/MPS-2022-51503)|CVE-2022-35989|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51504](https://www.oscs1024.com/hd/MPS-2022-51504)|CVE-2022-35990|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51505](https://www.oscs1024.com/hd/MPS-2022-51505)|CVE-2022-35991|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51506](https://www.oscs1024.com/hd/MPS-2022-51506)|CVE-2022-35992|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51507](https://www.oscs1024.com/hd/MPS-2022-51507)|CVE-2022-35993|高危|
|Google TensorFlow CollectiveGather拒绝服务漏洞|可达断言|[MPS-2022-51508](https://www.oscs1024.com/hd/MPS-2022-51508)|CVE-2022-35994|高危|
|Google TensorFlow拒绝服务漏洞|可达断言|[MPS-2022-51509](https://www.oscs1024.com/hd/MPS-2022-51509)|CVE-2022-35995|高危|
|Google TensorFlow Conv2D拒绝服务漏洞|除零错误|[MPS-2022-51510](https://www.oscs1024.com/hd/MPS-2022-51510)|CVE-2022-35996|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51511](https://www.oscs1024.com/hd/MPS-2022-51511)|CVE-2022-35997|高危|
|Google TensorFlow EmptyTensorList拒绝服务漏洞|可达断言|[MPS-2022-51512](https://www.oscs1024.com/hd/MPS-2022-51512)|CVE-2022-35998|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51513](https://www.oscs1024.com/hd/MPS-2022-51513)|CVE-2022-35999|高危|
|Google TensorFlow 安全漏洞|空指针取消引用|[MPS-2022-51514](https://www.oscs1024.com/hd/MPS-2022-51514)|CVE-2022-36000|高危|
|Google TensorFlow DrawBoundingBoxes拒绝服务漏洞|可达断言|[MPS-2022-51515](https://www.oscs1024.com/hd/MPS-2022-51515)|CVE-2022-36001|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51516](https://www.oscs1024.com/hd/MPS-2022-51516)|CVE-2022-36002|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51517](https://www.oscs1024.com/hd/MPS-2022-51517)|CVE-2022-36003|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51518](https://www.oscs1024.com/hd/MPS-2022-51518)|CVE-2022-36004|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51519](https://www.oscs1024.com/hd/MPS-2022-51519)|CVE-2022-36005|高危|
|Google TensorFlow 代码问题漏洞|空指针取消引用|[MPS-2022-51525](https://www.oscs1024.com/hd/MPS-2022-51525)|CVE-2022-36011|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51526](https://www.oscs1024.com/hd/MPS-2022-51526)|CVE-2022-36012|高危|
|Google TensorFlow代码问题漏洞|空指针取消引用|[MPS-2022-51527](https://www.oscs1024.com/hd/MPS-2022-51527)|CVE-2022-36013|高危|
|Google TensorFlow 代码问题漏洞|空指针取消引用|[MPS-2022-51528](https://www.oscs1024.com/hd/MPS-2022-51528)|CVE-2022-36014|高危|
|Google TensorFlow 输入验证错误漏洞|整数溢出或环绕|[MPS-2022-51529](https://www.oscs1024.com/hd/MPS-2022-51529)|CVE-2022-36015|高危|
|Google TensorFlow存在未明漏洞|可达断言|[MPS-2022-51530](https://www.oscs1024.com/hd/MPS-2022-51530)|CVE-2022-36016|高危|
|Google TensorFlow 输入验证错误漏洞|输入验证不恰当|[MPS-2022-51531](https://www.oscs1024.com/hd/MPS-2022-51531)|CVE-2022-36017|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51532](https://www.oscs1024.com/hd/MPS-2022-51532)|CVE-2022-36018|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51533](https://www.oscs1024.com/hd/MPS-2022-51533)|CVE-2022-36019|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-51540](https://www.oscs1024.com/hd/MPS-2022-51540)|CVE-2022-36026|高危|
|Google TensorFlow 输入验证错误漏洞|输入验证不恰当|[MPS-2022-51541](https://www.oscs1024.com/hd/MPS-2022-51541)|CVE-2022-36027|高危|
|tensorflow 拒绝服务|拒绝服务|[MPS-2022-54907](https://www.oscs1024.com/hd/MPS-2022-54907)||高危|
|wandb 竞争条件|竞争条件|[MPS-2022-54910](https://www.oscs1024.com/hd/MPS-2022-54910)||中危|
|Google TensorFlow BaseCandidateSamplerOp缓冲区错误漏洞|越界读取|[MPS-2022-58517](https://www.oscs1024.com/hd/MPS-2022-58517)|CVE-2022-41880|严重|
|Google TensorFlow缓冲区溢出漏洞|越界读取|[MPS-2022-58520](https://www.oscs1024.com/hd/MPS-2022-58520)|CVE-2022-41883|高危|
|Google TensorFlow存在未明漏洞|控制流实现总是不正确|[MPS-2022-58521](https://www.oscs1024.com/hd/MPS-2022-58521)|CVE-2022-41884|高危|
|Google TensorFlow tf.raw_ops.FusedResizeAndPadConv2D缓冲区溢出漏洞|缓冲区大小计算不正确|[MPS-2022-58522](https://www.oscs1024.com/hd/MPS-2022-58522)|CVE-2022-41885|高危|
|Google TensorFlow tf.raw_ops.ImageProjectiveTransformV2缓冲区溢出漏洞|缓冲区大小计算不正确|[MPS-2022-58523](https://www.oscs1024.com/hd/MPS-2022-58523)|CVE-2022-41886|高危|
|Google TensorFlow tf.keras.losses.poisson缓冲区溢出漏洞|缓冲区大小计算不正确|[MPS-2022-58524](https://www.oscs1024.com/hd/MPS-2022-58524)|CVE-2022-41887|高危|
|Google TensorFlow 拒绝服务漏洞|拒绝服务|[MPS-2022-58525](https://www.oscs1024.com/hd/MPS-2022-58525)|CVE-2022-41888|高危|
|Google TensorFlow代码问题漏洞|空指针取消引用|[MPS-2022-58526](https://www.oscs1024.com/hd/MPS-2022-58526)|CVE-2022-41889|高危|
|Google TensorFlow缓冲区溢出漏洞|不正确的类型转换|[MPS-2022-58527](https://www.oscs1024.com/hd/MPS-2022-58527)|CVE-2022-41890|高危|
|Google TensorFlow 输入验证错误漏洞|输入验证不恰当|[MPS-2022-58528](https://www.oscs1024.com/hd/MPS-2022-58528)|CVE-2022-41891|高危|
|Google TensorFlow 安全漏洞|可达断言|[MPS-2022-58530](https://www.oscs1024.com/hd/MPS-2022-58530)|CVE-2022-41893|高危|
|Google TensorFlow存在未明漏洞|经典缓冲区溢出|[MPS-2022-58531](https://www.oscs1024.com/hd/MPS-2022-58531)|CVE-2022-41894|高危|
|Google TensorFlow 输入验证错误漏洞|输入中指定数量的验证不当|[MPS-2022-58533](https://www.oscs1024.com/hd/MPS-2022-58533)|CVE-2022-41896|高危|
|Google TensorFlow缓冲区溢出漏洞|越界读取|[MPS-2022-58534](https://www.oscs1024.com/hd/MPS-2022-58534)|CVE-2022-41897|高危|
|Google TensorFlow输入验证错误漏洞|输入验证不恰当|[MPS-2022-58535](https://www.oscs1024.com/hd/MPS-2022-58535)|CVE-2022-41898|高危|
|Google TensorFlow 输入验证错误漏洞|可达断言|[MPS-2022-58536](https://www.oscs1024.com/hd/MPS-2022-58536)|CVE-2022-41899|高危|
|Google TensorFlow缓冲区溢出漏洞||[MPS-2022-58537](https://www.oscs1024.com/hd/MPS-2022-58537)|CVE-2022-41900|严重|
|TensorFlow 存在越界写入漏洞|越界写入|[MPS-2022-58539](https://www.oscs1024.com/hd/MPS-2022-58539)|CVE-2022-41902|高危|
|Google TensorFlow缓冲区溢出漏洞|缓冲区大小计算不正确|[MPS-2022-58544](https://www.oscs1024.com/hd/MPS-2022-58544)|CVE-2022-41907|高危|
|Google TensorFlow输入验证错误漏洞|拒绝服务|[MPS-2022-58545](https://www.oscs1024.com/hd/MPS-2022-58545)|CVE-2022-41908|高危|
|Google TensorFlow 代码问题漏洞|空指针取消引用|[MPS-2022-58546](https://www.oscs1024.com/hd/MPS-2022-58546)|CVE-2022-41909|高危|
|TensorFlow 存在越界读取漏洞|越界读取|[MPS-2022-58547](https://www.oscs1024.com/hd/MPS-2022-58547)|CVE-2022-41910|中危|
|Google TensorFlow代码问题漏洞|不正确的类型转换|[MPS-2022-58548](https://www.oscs1024.com/hd/MPS-2022-58548)|CVE-2022-41911|高危|
|Jupyter Notebook 代码问题漏洞|对搜索路径元素未加控制|[MPS-2022-60830](https://www.oscs1024.com/hd/MPS-2022-60830)|CVE-2022-39286|高危|
|PyTorch 命令注入漏洞|代码注入|[MPS-2022-65270](https://www.oscs1024.com/hd/MPS-2022-65270)|CVE-2022-45907|严重|
|Google TensorFlow输入验证错误漏洞|拒绝服务|[MPS-2022-8592](https://www.oscs1024.com/hd/MPS-2022-8592)|CVE-2022-29191|中危|
|Google TensorFlow输入验证错误漏洞|拒绝服务|[MPS-2022-8593](https://www.oscs1024.com/hd/MPS-2022-8593)|CVE-2022-29192|中危|
|Google TensorFlow输入验证错误漏洞|拒绝服务|[MPS-2022-8594](https://www.oscs1024.com/hd/MPS-2022-8594)|CVE-2022-29193|中危|
|Google TensorFlow输入验证错误漏洞|拒绝服务|[MPS-2022-8595](https://www.oscs1024.com/hd/MPS-2022-8595)|CVE-2022-29194|中危|
|Google TensorFlow输入验证错误漏洞|拒绝服务|[MPS-2022-8596](https://www.oscs1024.com/hd/MPS-2022-8596)|CVE-2022-29195|中危|
|Google TensorFlow输入验证错误漏洞|输入中指定数量的验证不当|[MPS-2022-8597](https://www.oscs1024.com/hd/MPS-2022-8597)|CVE-2022-29196|中危|
|Google TensorFlow输入验证错误漏洞|拒绝服务|[MPS-2022-8598](https://www.oscs1024.com/hd/MPS-2022-8598)|CVE-2022-29197|中危|
|Google TensorFlow 输入验证错误漏洞|拒绝服务|[MPS-2022-8599](https://www.oscs1024.com/hd/MPS-2022-8599)|CVE-2022-29198|中危|
|Google TensorFlow 输入验证错误漏洞|拒绝服务|[MPS-2022-8600](https://www.oscs1024.com/hd/MPS-2022-8600)|CVE-2022-29199|中危|
|Google TensorFlow输入验证错误漏洞|输入中指定数量的验证不当|[MPS-2022-8601](https://www.oscs1024.com/hd/MPS-2022-8601)|CVE-2022-29200|中危|
|Google TensorFlow 代码问题漏洞||[MPS-2022-8602](https://www.oscs1024.com/hd/MPS-2022-8602)|CVE-2022-29201|中危|
|Google TensorFlow资源管理错误漏洞|输入中指定数量的验证不当|[MPS-2022-8603](https://www.oscs1024.com/hd/MPS-2022-8603)|CVE-2022-29202|中危|
|Google TensorFlow输入验证错误漏洞|整数溢出或环绕|[MPS-2022-8604](https://www.oscs1024.com/hd/MPS-2022-8604)|CVE-2022-29203|中危|
|Google TensorFlow 安全漏洞|超界折返|[MPS-2022-8605](https://www.oscs1024.com/hd/MPS-2022-8605)|CVE-2022-29204|中危|
|Google TensorFlow 安全漏洞||[MPS-2022-8606](https://www.oscs1024.com/hd/MPS-2022-8606)|CVE-2022-29205|中危|
|Google TensorFlow代码问题漏洞|空指针取消引用|[MPS-2022-8607](https://www.oscs1024.com/hd/MPS-2022-8607)|CVE-2022-29206|中危|
|Google TensorFlow安全漏洞|空指针取消引用|[MPS-2022-8608](https://www.oscs1024.com/hd/MPS-2022-8608)|CVE-2022-29207|中危|
|Google TensorFlow缓冲区错误漏洞|越界写入|[MPS-2022-8609](https://www.oscs1024.com/hd/MPS-2022-8609)|CVE-2022-29208|高危|
|Google TensorFlow安全漏洞|使用不兼容类型访问资源（类型混淆）|[MPS-2022-8610](https://www.oscs1024.com/hd/MPS-2022-8610)|CVE-2022-29209|中危|
|Google TensorFlow输入验证错误漏洞|输入验证不恰当|[MPS-2022-8612](https://www.oscs1024.com/hd/MPS-2022-8612)|CVE-2022-29211|中危|
|Google TensorFlow输入验证错误漏洞|输入验证不恰当|[MPS-2022-8613](https://www.oscs1024.com/hd/MPS-2022-8613)|CVE-2022-29212|中危|
|Google TensorFlow输入验证错误漏洞|可达断言|[MPS-2022-8614](https://www.oscs1024.com/hd/MPS-2022-8614)|CVE-2022-29213|中危|
|Google TensorFlow代码注入漏洞|代码注入|[MPS-2022-8617](https://www.oscs1024.com/hd/MPS-2022-8617)|CVE-2022-29216|高危|
|SciPy 资源管理错误漏洞|UAF|[MPS-2023-10196](https://www.oscs1024.com/hd/MPS-2023-10196)|CVE-2023-29824|严重|
|grpc不加限制或调节的资源分配漏洞||[MPS-7ht6-lm4j](https://www.oscs1024.com/hd/MPS-7ht6-lm4j)|CVE-2023-33953|高危|
|GitPython 代码问题漏洞|不可信的搜索路径|[MPS-efyw-rmlk](https://www.oscs1024.com/hd/MPS-efyw-rmlk)|CVE-2023-40590|高危|
|OpenSSL 安全漏洞|过度迭代|[MPS-n3pe-ljgc](https://www.oscs1024.com/hd/MPS-n3pe-ljgc)|CVE-2023-3817|中危|
|GitPython 路径遍历漏洞|路径遍历|[MPS-qhle-wjx0](https://www.oscs1024.com/hd/MPS-qhle-wjx0)|CVE-2023-41040|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|jupyter-core|4.6.3|4.11.2|间接依赖|强烈建议修复|C:0|H:1|M:0|L:0|
|tensorflow|2.4|2.11.1|间接依赖|强烈建议修复|C:7|H:112|M:79|L:1|
|psutil|5.6.6|5.6.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|torch|1.5.0|1.13.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|scipy|1.4.1|1.10.0rc1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|numpy|1.22.0|1.22.2|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|wandb|0.12.0|0.12.12|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|cryptography|41.0.2|41.0.3|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|grpcio|1.44.0|1.56.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|gitpython|3.1.32|3.1.33|间接依赖|可选修复|C:0|H:1|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|68|Low|
|Apache-2.0|62|Low|
|MIT|81|Low|
|ISC|6|Low|
|GPL-3.0|1|Medium|
|WTFPL|1|Low|
|BSD-3-Clause|26|Low|
|Apache-2.0 OR BSD-3-Clause|1|Low|
|MPL-2.0|2|Low|
|BSD-2-Clause|4|Low|
|Unlicense|1|Low|
|HPND|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|mccabe|0.6.1|间接依赖|pip|
|ElectraConfig||间接依赖|pip|
|retrying|1.3.3|间接依赖|pip|
|pytest-timeout|2.1.0|间接依赖|pip|
|requests-oauthlib|1.3.1|间接依赖|pip|
|jupyterlab-pygments|0.1.1|间接依赖|pip|
|stevedore|3.5.0|间接依赖|pip|
|XGLMConfig||间接依赖|pip|
|matplotlib|3.3.1|间接依赖|pip|
|redis|4.5.4|间接依赖|pip|
|pypng|0.0.21|间接依赖|pip|
|websocket-client|1.3.1|间接依赖|pip|
|uritemplate|4.1.1|间接依赖|pip|
|typing-extensions|4.1.1|间接依赖|pip|
|phonemizer|3.0.1|间接依赖|pip|
|ipaddr|2.2.0|间接依赖|pip|
|executing|0.8.3|间接依赖|pip|
|requests|2.31.0|间接依赖|pip|
|pyaml|20.4.0|间接依赖|pip|
|gast|0.5.3|间接依赖|pip|
|audioread|2.1.9|间接依赖|pip|
|CustomConfig||间接依赖|pip|
|onnx|1.13.0|间接依赖|pip|
|fugashi|1.1.2|间接依赖|pip|
|async-timeout|4.0.2|间接依赖|pip|
|TFAutoModelForSequenceClassification||间接依赖|pip|
|faiss-cpu|1.7.2|间接依赖|pip|
|TestCasePlus||间接依赖|pip|
|Dict||间接依赖|pip|
|TFAutoModel||间接依赖|pip|
|RagRetriever||间接依赖|pip|
|widgetsnbextension|3.5.1|间接依赖|pip|
|pytest-xdist|2.5.0|间接依赖|pip|
|wcwidth|0.2.5|间接依赖|pip|
|librosa|0.8.0|间接依赖|pip|
|AutoConfig||间接依赖|pip|
|webencodings|0.5.1|间接依赖|pip|
|TYPE_CHECKING||间接依赖|pip|
|sortedcontainers|2.4.0|间接依赖|pip|
|protobuf|3.19.5|间接依赖|pip|
|poyo|0.5.0|间接依赖|pip|
|segments|2.2.0|间接依赖|pip|
|sacremoses|0.0.43|间接依赖|pip|
|tokenizers|0.13.2|间接依赖|pip|
|cliff|3.10.1|间接依赖|pip|
|cmd2|2.4.0|间接依赖|pip|
|docker|4.4.4|间接依赖|pip|
|dm-tree|0.1.6|间接依赖|pip|
|is_tf_available||间接依赖|pip|
|dill|0.3.2|间接依赖|pip|
|argon2-cffi|20.1.0|间接依赖|pip|
|frozenlist|1.3.0|间接依赖|pip|
|lockfile|0.12.2|间接依赖|pip|
|pandas|1.1.2|间接依赖|pip|
|tzlocal|4.1|间接依赖|pip|
|ipadic|1.0.0|间接依赖|pip|
|backoff|1.11.1|间接依赖|pip|
|cffi|1.14.2|间接依赖|pip|
|jaxlib|0.1.59|间接依赖|pip|
|resampy|0.2.2|间接依赖|pip|
|black|22.1.0|间接依赖|pip|
|custom_to_pil||间接依赖|pip|
|scikit-learn|1.0.2|间接依赖|pip|
|HfArgumentParser||间接依赖|pip|
|torchvision|0.7.0|间接依赖|pip|
|nltk|3.7|间接依赖|pip|
|portalocker|2.0.0|间接依赖|pip|
|Any||间接依赖|pip|
|matplotlib-inline|0.1.3|间接依赖|pip|
|ModelCheckpoint||间接依赖|pip|
|pynvml|11.4.1|间接依赖|pip|
|parameterized_class||间接依赖|pip|
|llvmlite|0.38.0|间接依赖|pip|
|pyparsing|2.4.6|间接依赖|pip|
|cycler|0.10.0|间接依赖|pip|
|arrow|1.2.2|间接依赖|pip|
|google-pasta|0.2.0|间接依赖|pip|
|unidic|1.1.0|间接依赖|pip|
|tomli|2.0.1|间接依赖|pip|
|randint||间接依赖|pip|
|is_bitsandbytes_available||间接依赖|pip|
|pandocfilters|1.4.2|间接依赖|pip|
|Mako|1.2.2|间接依赖|pip|
|ipython-genutils|0.2.0|间接依赖|pip|
|kubernetes|12.0.1|间接依赖|pip|
|pyarrow|1.0.1|间接依赖|pip|
|./transformers/examples/pytorch/_test_requirements.txt||间接依赖|pip|
|colorlog|6.6.0|间接依赖|pip|
|TFGPT2LMHeadModel||间接依赖|pip|
|Pint|0.16.1|间接依赖|pip|
|msgpack|0.6.2|间接依赖|pip|
|appdirs|1.4.3|间接依赖|pip|
|tqdm|4.48.2|间接依赖|pip|
|cryptography|41.0.2|间接依赖|pip|
|pygtrie|2.4.2|间接依赖|pip|
|testpath|0.4.4|间接依赖|pip|
|rfc3986|1.5.0|间接依赖|pip|
|Session||间接依赖|pip|
|csvw|2.0.0|间接依赖|pip|
|CrossEntropyLoss||间接依赖|pip|
|tzdata|2022.1|间接依赖|pip|
|Accelerator||间接依赖|pip|
|SwinConfig||间接依赖|pip|
|CacheControl|0.12.6|间接依赖|pip|
|cloudpickle|2.0.0|间接依赖|pip|
|timm|0.5.4|间接依赖|pip|
|./torchdynamo/requirements.txt||间接依赖|pip|
|TrainingJobAnalytics||间接依赖|pip|
|hypothesis|6.39.4|间接依赖|pip|
|platformdirs|2.5.1|间接依赖|pip|
|wandb|0.12.0|间接依赖|pip|
|pluggy|1.0.0|间接依赖|pip|
|get_artifacts_links||间接依赖|pip|
|botocore|1.19.63|间接依赖|pip|
|execnet|1.9.0|间接依赖|pip|
|dash-html-components|2.0.0|间接依赖|pip|
|Markdown|3.3.6|间接依赖|pip|
|is_flax_available||间接依赖|pip|
|decorator|4.4.2|间接依赖|pip|
|BartTokenizer||间接依赖|pip|
|pathspec|0.9.0|间接依赖|pip|
|jupyter|1.0.0|间接依赖|pip|
|imageio|2.16.1|间接依赖|pip|
|git-python|1.0.3|间接依赖|pip|
|qtconsole|4.7.7|间接依赖|pip|
|prompt-toolkit|3.0.7|间接依赖|pip|
|onnxconverter-common|1.9.0|间接依赖|pip|
|pycodestyle|2.8.0|间接依赖|pip|
|alembic|1.7.7|间接依赖|pip|
|boto3|1.16.34|间接依赖|pip|
|wasabi|0.9.0|间接依赖|pip|
|numpy|1.22.0|间接依赖|pip|
|Deprecated|1.2.13|间接依赖|pip|
|tabulate|0.8.9|间接依赖|pip|
|jsonschema|3.2.0|间接依赖|pip|
|ipykernel|5.3.4|间接依赖|pip|
|Callable||间接依赖|pip|
|tensorboard|1.14.0|间接依赖|pip|
|Flask|2.3.2|间接依赖|pip|
|flatbuffers|2.0|间接依赖|pip|
|dash-table|5.0.0|间接依赖|pip|
|distro|1.4.0|间接依赖|pip|
|tornado|6.3.3|间接依赖|pip|
|absl-py|1.0.0|间接依赖|pip|
|gitdb|4.0.9|间接依赖|pip|
|QtPy|1.9.0|间接依赖|pip|
|MSELoss||间接依赖|pip|
|load_metric||间接依赖|pip|
|termcolor|1.1.0|间接依赖|pip|
|six|1.14.0|间接依赖|pip|
|py-cpuinfo|8.0.0|间接依赖|pip|
|colorama|0.4.3|间接依赖|pip|
|itsdangerous|2.1.1|间接依赖|pip|
|chex|0.1.1|间接依赖|pip|
|gym-notices|0.0.6|间接依赖|pip|
|loop_post_process||间接依赖|pip|
|jax_utils||间接依赖|pip|
|ray|1.11.0|间接依赖|pip|
|zipp|3.7.0|间接依赖|pip|
|pytz|2020.1|间接依赖|pip|
|contextlib2|0.6.0|间接依赖|pip|
|DataCollator||间接依赖|pip|
|filelock|3.0.12|间接依赖|pip|
|mujoco-py|2.1.2.14|间接依赖|pip|
|h5py|2.10.0|间接依赖|pip|
|pyzmq|19.0.2|间接依赖|pip|
|tenacity|8.0.1|间接依赖|pip|
|sentencepiece|0.1.91|间接依赖|pip|
|importlib-metadata|4.11.3|间接依赖|pip|
|pickleshare|0.7.5|间接依赖|pip|
|asttokens|2.0.5|间接依赖|pip|
|jupyter-client|6.1.7|间接依赖|pip|
|responses|0.18.0|间接依赖|pip|
|nbclient|0.5.0|间接依赖|pip|
|pytoml|0.1.21|间接依赖|pip|
|codecarbon|1.2.0|间接依赖|pip|
|yarl|1.7.2|间接依赖|pip|
|PIPELINE_INIT_ARGS||间接依赖|pip|
|load_dataset||间接依赖|pip|
|importlib-resources|5.4.0|间接依赖|pip|
|stack-data|0.2.0|间接依赖|pip|
|unflatten_dict||间接依赖|pip|
|ExplicitEnum||间接依赖|pip|
|cachetools|5.0.0|间接依赖|pip|
|timeout-decorator|0.5.0|间接依赖|pip|
|psutil|5.6.6|间接依赖|pip|
|nest-asyncio|1.4.0|间接依赖|pip|
|ClassLabel||间接依赖|pip|
|mypy-extensions|0.4.3|间接依赖|pip|
|unidic-lite|1.0.8|间接依赖|pip|
|dash-bootstrap-components|1.0.3|间接依赖|pip|
|pooch|1.6.0|间接依赖|pip|
|BartConfig||间接依赖|pip|
|tf-estimator-nightly|2.8.0.dev2021122109|间接依赖|pip|
|plac|1.3.4|间接依赖|pip|
|EarlyStopping||间接依赖|pip|
|tf2onnx|1.9.3|间接依赖|pip|
|PyYAML|5.4|间接依赖|pip|
|fasteners|0.17.3|间接依赖|pip|
|text-unidecode|1.3|间接依赖|pip|
|Pygments|2.7.4|间接依赖|pip|
|nbconvert|6.5.1|间接依赖|pip|
|reduce||间接依赖|pip|
|TextIO||间接依赖|pip|
|BaseTransformer||间接依赖|pip|
|AutoImageProcessor||间接依赖|pip|
|ipywidgets|7.5.1|间接依赖|pip|
|urllib3|1.26.5|间接依赖|pip|
|pycparser|2.20|间接依赖|pip|
|terminado|0.8.3|间接依赖|pip|
|rouge-score|0.0.4|间接依赖|pip|
|oauthlib|3.2.2|间接依赖|pip|
|BertConfig||间接依赖|pip|
|prometheus-client|0.8.0|间接依赖|pip|
|pyflakes|2.4.0|间接依赖|pip|
|nbformat|5.0.7|间接依赖|pip|
|add_start_docstrings||间接依赖|pip|
|chardet|3.0.4|间接依赖|pip|
|jinja2-time|0.2.0|间接依赖|pip|
|Brotli|1.0.9|间接依赖|pip|
|tensorflow-io-gcs-filesystem|0.24.0|间接依赖|pip|
|grpcio|1.44.0|间接依赖|pip|
|tensorboard-plugin-wit|1.8.1|间接依赖|pip|
|IterableDataset||间接依赖|pip|
|pyctcdecode|0.3.0|间接依赖|pip|
|threadpoolctl|3.1.0|间接依赖|pip|
|prettytable|3.2.0|间接依赖|pip|
|keras|2.8.0|间接依赖|pip|
|fire|0.4.0|间接依赖|pip|
|greenlet|1.1.2|间接依赖|pip|
|arguments||间接依赖|pip|
|traitlets|5.1.1|间接依赖|pip|
|sigopt|8.2.0|间接依赖|pip|
|plotly|5.6.0|间接依赖|pip|
|ptyprocess|0.6.0|间接依赖|pip|
|jax|0.2.8|间接依赖|pip|
|accelerate|0.12.0|间接依赖|pip|
|datasketch|1.5.7|间接依赖|pip|
|libclang|13.0.0|间接依赖|pip|
|optax|0.0.8|间接依赖|pip|
|notebook|6.4.12|间接依赖|pip|
|packaging|20.3|间接依赖|pip|
|DistributedType||间接依赖|pip|
|jupyter-console|6.2.0|间接依赖|pip|
|AutoModel||间接依赖|pip|
|smmap|5.0.0|间接依赖|pip|
|google-auth|2.6.2|间接依赖|pip|
|future|0.18.3|间接依赖|pip|
|click|7.1.2|间接依赖|pip|
|Sequence||间接依赖|pip|
|SoundFile|0.10.3.post1|间接依赖|pip|
|aiosignal|1.2.0|间接依赖|pip|
|Jinja2|2.11.3|间接依赖|pip|
|gitpython|3.1.32|间接依赖|pip|
|pyasn1-modules|0.2.8|间接依赖|pip|
|sacrebleu|1.5.1|间接依赖|pip|
|Flask-Compress|1.11|间接依赖|pip|
|py|1.11.0|间接依赖|pip|
|GitPython|3.1.32|间接依赖|pip|
|AutoModelForCausalLM||间接依赖|pip|
|flax|0.3.5|间接依赖|pip|
|jupyter-core|4.6.3|间接依赖|pip|
|Cython|0.29.28|间接依赖|pip|
|knockknock|0.1.8.1|间接依赖|pip|
|parso|0.7.1|间接依赖|pip|
|xxhash|2.0.0|间接依赖|pip|
|Features||间接依赖|pip|
|fonttools|4.31.1|间接依赖|pip|
|multiprocess|0.70.12.2|间接依赖|pip|
|choice||间接依赖|pip|
|certifi|2023.7.22|间接依赖|pip|
|is_accelerate_available||间接依赖|pip|
|flake8|4.0.1|间接依赖|pip|
|main||间接依赖|pip|
|defusedxml|0.6.0|间接依赖|pip|
|DatasetDict||间接依赖|pip|
|isodate|0.6.1|间接依赖|pip|
|fsspec|2022.2.0|间接依赖|pip|
|idna|2.8|间接依赖|pip|
|tensorboard-data-server|0.6.1|间接依赖|pip|
|wget|3.2|间接依赖|pip|
|toolz|0.11.2|间接依赖|pip|
|clldutils|3.11.1|间接依赖|pip|
|Werkzeug|2.2.3|间接依赖|pip|
|jmespath|0.10.0|间接依赖|pip|
|pep517|0.8.2|间接依赖|pip|
|ArgumentHandler||间接依赖|pip|
|Pillow|8.1.1|间接依赖|pip|
|MarkupSafe|1.1.1|间接依赖|pip|
|AutoTokenizer||间接依赖|pip|
|pytest-forked|1.4.0|间接依赖|pip|
|huggingface-hub|0.4.0|间接依赖|pip|
|distlib|0.3.0|间接依赖|pip|
|parameterized|0.8.1|间接依赖|pip|
|regex|2020.7.14|间接依赖|pip|
|google-auth-oauthlib|0.4.6|间接依赖|pip|
|pytz-deprecation-shim|0.1.0.post0|间接依赖|pip|
|html5lib|1.0.1|间接依赖|pip|
|transformers|4.26.1|间接依赖|pip|
|python-dateutil|2.8.1|间接依赖|pip|
|rsa|4.8|间接依赖|pip|
|mistune|2.0.3|间接依赖|pip|
|pytest|7.1.1|间接依赖|pip|
|pyOpenSSL|22.0.0|间接依赖|pip|
|Args||间接依赖|pip|
|pyperclip|1.8.2|间接依赖|pip|
|optuna|2.10.0|间接依赖|pip|
|SQLAlchemy|1.4.32|间接依赖|pip|
|CLIPConfig||间接依赖|pip|
|binaryornot|0.4.4|间接依赖|pip|
|astunparse|1.6.3|间接依赖|pip|
|cmaes|0.8.2|间接依赖|pip|
|backports.zoneinfo|0.2.1|间接依赖|pip|
|Keras-Preprocessing|1.1.2|间接依赖|pip|
|pexpect|4.8.0|间接依赖|pip|
|entrypoints|0.3|间接依赖|pip|
|flatten_dict||间接依赖|pip|
|numba|0.55.1|间接依赖|pip|
|AutoModelForSeq2SeqLM||间接依赖|pip|
|opencv-python|4.4.0.42|间接依赖|pip|
|wrapt|1.14.0|间接依赖|pip|
|joblib|1.2.0|间接依赖|pip|
|List||间接依赖|pip|
|pyasn1|0.4.8|间接依赖|pip|
|s3transfer|0.3.7|间接依赖|pip|
|Tuple||间接依赖|pip|
|ipython|8.10.0|间接依赖|pip|
|autopage|0.5.0|间接依赖|pip|
|lang-trans|0.6.0|间接依赖|pip|
|iniconfig|1.1.1|间接依赖|pip|
|NoSuperInitConfig||间接依赖|pip|
|glfw|2.5.1|间接依赖|pip|
|aiohttp|3.8.5|间接依赖|pip|
|XGLMForCausalLM||间接依赖|pip|
|pyrsistent|0.16.0|间接依赖|pip|
|SummarizationModule||间接依赖|pip|
|Union||间接依赖|pip|
|multidict|6.0.2|间接依赖|pip|
|datasets|1.8.0|间接依赖|pip|
|opt-einsum|3.3.0|间接依赖|pip|
|gym|0.23.1|间接依赖|pip|
|kiwisolver|1.2.0|间接依赖|pip|
|APScheduler|3.9.1|间接依赖|pip|
|partial||间接依赖|pip|
|isort|5.10.1|间接依赖|pip|
|add_generic_args||间接依赖|pip|
|python-slugify|6.1.1|间接依赖|pip|
|evaluate|0.2.2|间接依赖|pip|
|CLIPTextConfig||间接依赖|pip|
|async-generator|1.10|间接依赖|pip|
|backcall|0.2.0|间接依赖|pip|
|scipy|1.4.1|间接依赖|pip|
|Dataset||间接依赖|pip|
|add_end_docstrings||间接依赖|pip|
|pbr|5.8.1|间接依赖|pip|
|Optional||间接依赖|pip|
|Send2Trash|1.5.0|间接依赖|pip|
|attrs|20.2.0|间接依赖|pip|
|tensorflow|2.4|间接依赖|pip|
|jiwer|2.2.0|间接依赖|pip|
|tensorboardX|1.8|间接依赖|pip|
|pure-eval|0.2.2|间接依赖|pip|
|torch|1.5.0|间接依赖|pip|
|dash|2.3.0|间接依赖|pip|
|torchaudio|0.11.0|间接依赖|pip|
|field||间接依赖|pip|
|cookiecutter|2.1.1|间接依赖|pip|
|RagConfig||间接依赖|pip|
|get_gpu_count||间接依赖|pip|
|progress|1.5|间接依赖|pip|
|charset-normalizer|2.0.12|间接依赖|pip|
|jedi|0.17.2|间接依赖|pip|
|dataclass||间接依赖|pip|
|download_artifact||间接依赖|pip|
|dash-core-components|2.0.0|间接依赖|pip|
|dlinfo|1.2.1|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)