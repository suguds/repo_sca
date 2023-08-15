# signalapp/Signal-Android安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691511267816923136.svg)](https://www.murphysec.com/console/report/1691511267770785792/1691511267816923136)

仓库描述：A private messenger for Android.

仓库地址：[https://github.com/signalapp/Signal-Android](https://github.com/signalapp/Signal-Android)

| star：23919 | watch：901 | fork：5864 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-15 04:35:25 | 许可证：- |
| 最近检测时间：2023-08-16 02:58:07 | 组件总数：10 | 漏洞总数：7 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-2014-2456|输入验证不恰当|[MPS-2014-2456](https://www.oscs1024.com/hd/MPS-2014-2456)|CVE-2014-3146|中危|
|MPS-2018-15340|XSS|[MPS-2018-15340](https://www.oscs1024.com/hd/MPS-2018-15340)|CVE-2018-19787|中危|
|MPS-2020-17664|XSS|[MPS-2020-17664](https://www.oscs1024.com/hd/MPS-2020-17664)|CVE-2020-27783|中危|
|MPS-2021-3272|XSS|[MPS-2021-3272](https://www.oscs1024.com/hd/MPS-2021-3272)|CVE-2021-28957|中危|
|MPS-2021-36943||[MPS-2021-36943](https://www.oscs1024.com/hd/MPS-2021-36943)|CVE-2021-43818|高危|
|MPS-2022-14974|路径遍历|[MPS-2022-14974](https://www.oscs1024.com/hd/MPS-2022-14974)||中危|
|MPS-2022-46661|空指针取消引用|[MPS-2022-46661](https://www.oscs1024.com/hd/MPS-2022-46661)|CVE-2022-2309|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|lxml|3.3.3|4.9.1|间接依赖|建议修复|C:0|H:2|M:5|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|2|Low|
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|progressbar-latest|2.4|间接依赖|pip|
|libdl.so||间接依赖||
|Counter||间接依赖|pip|
|libm.so||间接依赖||
|androidx.recyclerview:recyclerview|1.2.1|直接依赖|maven|
|argparse|1.2.1|间接依赖|pip|
|androidx.appcompat:appcompat|1.4.1|直接依赖|maven|
|lxml|3.3.3|间接依赖|pip|
|libc.so||间接依赖||
|ProgressBar||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)