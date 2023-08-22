# Qiskit/qiskit安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694052348258508800.svg)](https://www.murphysec.com/console/report/1694052347935547392/1694052348258508800)

仓库描述：Qiskit is an open-source SDK for working with quantum computers at the level of extended quantum circuits, operators, and algorithms.

仓库地址：[https://github.com/Qiskit/qiskit](https://github.com/Qiskit/qiskit)

| star：3760 | watch：209 | fork：2018 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-23 02:16:00 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-23 02:22:29 | 组件总数：25 | 漏洞总数：44 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Pillow 安全漏洞|不加限制或调节的资源分配|[MPS-2019-12652](https://www.oscs1024.com/hd/MPS-2019-12652)|CVE-2019-16865|高危|
|psutil 资源管理错误漏洞|双重释放|[MPS-2019-14454](https://www.oscs1024.com/hd/MPS-2019-14454)|CVE-2019-18874|高危|
|Pillow 输入验证错误漏洞|整数溢出或环绕|[MPS-2020-0059](https://www.oscs1024.com/hd/MPS-2020-0059)|CVE-2020-5310|高危|
|Pillow 缓冲区错误漏洞|经典缓冲区溢出|[MPS-2020-0060](https://www.oscs1024.com/hd/MPS-2020-0060)|CVE-2020-5311|严重|
|Pillow 缓冲区错误漏洞|经典缓冲区溢出|[MPS-2020-0061](https://www.oscs1024.com/hd/MPS-2020-0061)|CVE-2020-5312|严重|
|Pillow 缓冲区错误漏洞|越界读取|[MPS-2020-0062](https://www.oscs1024.com/hd/MPS-2020-0062)|CVE-2020-5313|高危|
|Pillow 输入验证错误漏洞|整数溢出或环绕|[MPS-2020-0120](https://www.oscs1024.com/hd/MPS-2020-0120)|CVE-2019-19911|高危|
|Pillow 缓冲区错误漏洞|越界读取|[MPS-2020-9466](https://www.oscs1024.com/hd/MPS-2020-9466)|CVE-2020-10177|中危|
|Pillow 缓冲区错误漏洞|越界读取|[MPS-2020-9467](https://www.oscs1024.com/hd/MPS-2020-9467)|CVE-2020-10378|中危|
|Pillow 缓冲区错误漏洞|经典缓冲区溢出|[MPS-2020-9468](https://www.oscs1024.com/hd/MPS-2020-9468)|CVE-2020-10379|高危|
|Pillow 缓冲区错误漏洞|越界读取|[MPS-2020-9469](https://www.oscs1024.com/hd/MPS-2020-9469)|CVE-2020-10994|中危|
|Pillow 缓冲区错误漏洞|越界读取|[MPS-2020-9470](https://www.oscs1024.com/hd/MPS-2020-9470)|CVE-2020-11538|高危|
|Pillow 缓冲区错误漏洞|越界读取|[MPS-2021-0176](https://www.oscs1024.com/hd/MPS-2021-0176)|CVE-2020-35653|高危|
|Pillow 资源管理错误漏洞|拒绝服务|[MPS-2021-2478](https://www.oscs1024.com/hd/MPS-2021-2478)|CVE-2021-27921|高危|
|Pillow 资源管理错误漏洞|拒绝服务|[MPS-2021-2479](https://www.oscs1024.com/hd/MPS-2021-2479)|CVE-2021-27922|高危|
|Pillow 资源管理错误漏洞|拒绝服务|[MPS-2021-2480](https://www.oscs1024.com/hd/MPS-2021-2480)|CVE-2021-27923|高危|
|NumPy 缓冲区错误漏洞|经典缓冲区溢出|[MPS-2021-25101](https://www.oscs1024.com/hd/MPS-2021-25101)|CVE-2021-33430|中危|
|NumPy 安全漏洞|不充分的比较|[MPS-2021-25631](https://www.oscs1024.com/hd/MPS-2021-25631)|CVE-2021-34141|中危|
|Pillow 缓冲区错误漏洞|越界读取|[MPS-2021-3070](https://www.oscs1024.com/hd/MPS-2021-3070)|CVE-2021-25293|高危|
|Pillow 缓冲区错误漏洞|越界写入|[MPS-2021-3074](https://www.oscs1024.com/hd/MPS-2021-3074)|CVE-2021-25290|高危|
|Pillow 安全漏洞|ReDoS|[MPS-2021-3075](https://www.oscs1024.com/hd/MPS-2021-3075)|CVE-2021-25292|中危|
|Pillow 缓冲区错误漏洞|越界读取|[MPS-2021-3076](https://www.oscs1024.com/hd/MPS-2021-3076)|CVE-2021-25291|高危|
|Pillow 缓冲区错误漏洞|越界写入|[MPS-2021-3077](https://www.oscs1024.com/hd/MPS-2021-3077)|CVE-2021-25289|严重|
|Red Hat Ansible Automation 安全漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-3169](https://www.oscs1024.com/hd/MPS-2021-3169)|CVE-2021-20270|高危|
|Matthäus G. Chajdas pygments 安全漏洞|ReDoS|[MPS-2021-3204](https://www.oscs1024.com/hd/MPS-2021-3204)|CVE-2021-27291|高危|
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|NumPy 安全漏洞|经典缓冲区溢出|[MPS-2021-32279](https://www.oscs1024.com/hd/MPS-2021-32279)|CVE-2021-41496|中危|
|Pillow 缓冲区错误漏洞|越界读取|[MPS-2021-7529](https://www.oscs1024.com/hd/MPS-2021-7529)|CVE-2021-25287|严重|
|Pillow 安全漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-7530](https://www.oscs1024.com/hd/MPS-2021-7530)|CVE-2021-28676|高危|
|Pillow 缓冲区错误漏洞|越界读取|[MPS-2021-7538](https://www.oscs1024.com/hd/MPS-2021-7538)|CVE-2021-25288|严重|
|Pillow 输入验证错误漏洞|拒绝服务|[MPS-2021-7618](https://www.oscs1024.com/hd/MPS-2021-7618)|CVE-2021-28677|高危|
|Pillow 数据伪造问题漏洞|对数据真实性的验证不充分|[MPS-2021-7765](https://www.oscs1024.com/hd/MPS-2021-7765)|CVE-2021-28678|中危|
|Pillow 资源管理错误漏洞|未加检查的返回值|[MPS-2021-7768](https://www.oscs1024.com/hd/MPS-2021-7768)|CVE-2021-28675|中危|
|Pillow 缓冲区错误漏洞|经典缓冲区溢出|[MPS-2021-9796](https://www.oscs1024.com/hd/MPS-2021-9796)|CVE-2021-34552|严重|
|Pillow 安全漏洞|初始化不恰当|[MPS-2022-0817](https://www.oscs1024.com/hd/MPS-2022-0817)|CVE-2022-22815|中危|
|Pillow 缓冲区错误漏洞|越界读取|[MPS-2022-0818](https://www.oscs1024.com/hd/MPS-2022-0818)|CVE-2022-22816|中危|
|Pillow 安全漏洞|命令注入|[MPS-2022-0819](https://www.oscs1024.com/hd/MPS-2022-0819)|CVE-2022-22817|严重|
|networkx 存在反序列化漏洞|反序列化|[MPS-2022-15000](https://www.oscs1024.com/hd/MPS-2022-15000)||高危|
|pillow 存在拒绝服务漏洞|拒绝服务|[MPS-2022-15032](https://www.oscs1024.com/hd/MPS-2022-15032)||中危|
|scikit-learn 存在拒绝服务漏洞|拒绝服务|[MPS-2022-15126](https://www.oscs1024.com/hd/MPS-2022-15126)||低危|
|Pillow 输入验证错误漏洞|输入验证不恰当|[MPS-2022-3208](https://www.oscs1024.com/hd/MPS-2022-3208)|CVE-2022-24303|严重|
|Matthäus G. Chajdas pygments 代码问题漏洞|任意文件上传|[MPS-2022-57237](https://www.oscs1024.com/hd/MPS-2022-57237)|CVE-2022-40896|中危|
|Pillow 安全漏洞|拒绝服务|[MPS-2022-64228](https://www.oscs1024.com/hd/MPS-2022-64228)|CVE-2022-45198|高危|
|SciPy 资源管理错误漏洞|UAF|[MPS-2023-10196](https://www.oscs1024.com/hd/MPS-2023-10196)|CVE-2023-29824|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|scipy|1.5|1.10.0rc1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|psutil|5|5.6.7|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|pillow|4.2.1|9.3.0|间接依赖|建议修复|C:8|H:16|M:9|L:0|
|networkx|2.3|2.6|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|pygments|2.4|2.15.0|间接依赖|建议修复|C:0|H:2|M:1|L:0|
|scikit-learn|0.20.0|0.24.2|间接依赖|可选修复|C:0|H:0|M:0|L:1|
|numpy|1.17|1.22.2|间接依赖|可选修复|C:0|H:0|M:4|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|5|Low|
|MPL-2.0|1|Low|
|MIT|2|Low|
|自定义许可证|7|Low|
|Apache-2.0|3|Low|
|GPL-2.0-or-later|1|Low|
|LGPL-2.1-or-later|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|sphinx-design|0.2.0|间接依赖|pip|
|numpy|1.17|间接依赖|pip|
|hypothesis|4.24.3|间接依赖|pip|
|z3-solver|4.7|间接依赖|pip|
|pylatexenc|1.4|间接依赖|pip|
|ruff|0.0.267|间接依赖|pip|
|seaborn|0.9.0|间接依赖|pip|
|python-constraint|1.4|间接依赖|pip|
|scipy|1.5|间接依赖|pip|
|coverage|4.4.0|间接依赖|pip|
|scikit-learn|0.20.0|间接依赖|pip|
|psutil|5|间接依赖|pip|
|dill|0.3|间接依赖|pip|
|rustworkx|0.13.0|间接依赖|pip|
|pillow|4.2.1|间接依赖|pip|
|python-dateutil|2.8.0|间接依赖|pip|
|stevedore|3.0.0|间接依赖|pip|
|ipywidgets|7.3.0|间接依赖|pip|
|ply|3.10|间接依赖|pip|
|pylint|2.16.2|间接依赖|pip|
|astroid|2.14.2|间接依赖|pip|
|pygments|2.4|间接依赖|pip|
|matplotlib|3.3|间接依赖|pip|
|networkx|2.3|间接依赖|pip|
|sympy|1.3|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)