# jackfrued/Python-100-Days安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694051424894611456.svg)](https://www.murphysec.com/console/report/1692964517050208256/1694051424894611456)

仓库描述：Python - 100天从新手到大师

仓库地址：[https://github.com/jackfrued/Python-100-Days](https://github.com/jackfrued/Python-100-Days)

| star：139049 | watch：6176 | fork：49672 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-14 14:13:11 | 许可证：- |
| 最近检测时间：2023-08-23 02:28:15 | 组件总数：42 | 漏洞总数：17 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Lxml 跨站脚本漏洞|XSS|[MPS-2020-17664](https://www.oscs1024.com/hd/MPS-2020-17664)|CVE-2020-27783|中危|
|NumPy 缓冲区错误漏洞|经典缓冲区溢出|[MPS-2021-25101](https://www.oscs1024.com/hd/MPS-2021-25101)|CVE-2021-33430|中危|
|NumPy 安全漏洞|不充分的比较|[MPS-2021-25631](https://www.oscs1024.com/hd/MPS-2021-25631)|CVE-2021-34141|中危|
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|NumPy 安全漏洞|经典缓冲区溢出|[MPS-2021-32279](https://www.oscs1024.com/hd/MPS-2021-32279)|CVE-2021-41496|中危|
|Lxml 跨站脚本漏洞|XSS|[MPS-2021-3272](https://www.oscs1024.com/hd/MPS-2021-3272)|CVE-2021-28957|中危|
|lxml  注入漏洞||[MPS-2021-36943](https://www.oscs1024.com/hd/MPS-2021-36943)|CVE-2021-43818|高危|
|Interactive Python 安全漏洞||[MPS-2021-37057](https://www.oscs1024.com/hd/MPS-2021-37057)|CVE-2022-21699|高危|
|urllib3 资源管理错误漏洞|拒绝服务|[MPS-2021-9054](https://www.oscs1024.com/hd/MPS-2021-9054)|CVE-2021-33503|高危|
|pylint 存在拒绝服务漏洞|拒绝服务|[MPS-2022-15071](https://www.oscs1024.com/hd/MPS-2022-15071)||中危|
|pylint 存在代码注入漏洞|代码注入|[MPS-2022-15072](https://www.oscs1024.com/hd/MPS-2022-15072)||中危|
|pylint 存在拒绝服务漏洞|拒绝服务|[MPS-2022-15073](https://www.oscs1024.com/hd/MPS-2022-15073)||高危|
|Certifi 存在数据真实性验证不充分漏洞|对数据真实性的验证不充分|[MPS-2022-1918](https://www.oscs1024.com/hd/MPS-2022-1918)|CVE-2022-23491|中危|
|lxml 和 libxml2 代码问题漏洞|空指针取消引用|[MPS-2022-46661](https://www.oscs1024.com/hd/MPS-2022-46661)|CVE-2022-2309|高危|
|Interactive Python 操作系统命令注入漏洞|OS命令注入|[MPS-2023-3322](https://www.oscs1024.com/hd/MPS-2023-3322)|CVE-2023-24816|高危|
|Certifi 数据伪造问题漏洞|对数据真实性的验证不充分|[MPS-ck78-r6zg](https://www.oscs1024.com/hd/MPS-ck78-r6zg)|CVE-2023-37920|严重|
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|ipython|7.13.0|8.10.0|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|urllib3|1.25.9|1.26.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|requests|2.23.0|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|pylint|2.4.4|2.7.0|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|certifi|2020.4.5.1|2023.7.22|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|lxml|4.5.0|4.9.1|间接依赖|建议修复|C:0|H:2|M:2|L:0|
|numpy|1.18.3|1.22.2|间接依赖|可选修复|C:0|H:0|M:4|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|8|Low|
|BSD-3-Clause|6|Low|
|MIT|10|Low|
|Apache-2.0|3|Low|
|GPL-2.0-or-later|1|Low|
|LGPL-2.1-or-later|1|Low|
|BSD-2-Clause|2|Low|
|MPL-2.0|1|Low|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|wrapt|1.11.2|间接依赖|pip|
|example12||间接依赖|pip|
|lxml|4.5.0|间接依赖|pip|
|urllib3|1.25.9|间接依赖|pip|
|six|1.14.0|间接依赖|pip|
|isort|4.3.21|间接依赖|pip|
|prompt-toolkit|3.0.5|间接依赖|pip|
|Thread||间接依赖|pip|
|wcwidth|0.1.9|间接依赖|pip|
|ipython-genutils|0.2.0|间接依赖|pip|
|traitlets|4.3.3|间接依赖|pip|
|jedi|0.17.0|间接依赖|pip|
|ipython|7.13.0|间接依赖|pip|
|pickleshare|0.7.5|间接依赖|pip|
|backcall|0.1.0|间接依赖|pip|
|requests|2.23.0|间接依赖|pip|
|memory-profiler|0.57.0|间接依赖|pip|
|mccabe|0.6.1|间接依赖|pip|
|Lock||间接依赖|pip|
|appnope|0.1.0|间接依赖|pip|
|chardet|3.0.4|间接依赖|pip|
|typed-ast|1.4.1|间接依赖|pip|
|beautifulsoup4|4.9.0|间接依赖|pip|
|pylint|2.4.4|间接依赖|pip|
|pytz|2019.3|间接依赖|pip|
|decorator|4.4.2|间接依赖|pip|
|line-profiler|3.0.2|间接依赖|pip|
|psutil|5.7.0|间接依赖|pip|
|python-dateutil|2.8.1|间接依赖|pip|
|astroid|2.3.3|间接依赖|pip|
|soupsieve|2.0|间接依赖|pip|
|django||间接依赖|pip|
|ptyprocess|0.6.0|间接依赖|pip|
|pandas|1.0.3|间接依赖|pip|
|parso|0.7.0|间接依赖|pip|
|idna|2.9|间接依赖|pip|
|numpy|1.18.3|间接依赖|pip|
|Pygments|2.6.1|间接依赖|pip|
|certifi|2020.4.5.1|间接依赖|pip|
|PIL||间接依赖|pip|
|pexpect|4.8.0|间接依赖|pip|
|lazy-object-proxy|1.4.3|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)