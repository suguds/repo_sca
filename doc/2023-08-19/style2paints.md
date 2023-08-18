# lllyasviel/style2paints安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692605848169107456.svg)](https://www.murphysec.com/console/report/1692605847359606784/1692605848169107456)

仓库描述：sketch + style = paints :art: (TOG2018/SIGGRAPH2018ASIA)

仓库地址：[https://github.com/lllyasviel/style2paints](https://github.com/lllyasviel/style2paints)

| star：17207 | watch：561 | fork：2093 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-01 10:02:00 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-19 02:48:34 | 组件总数：15 | 漏洞总数：12 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Bottle 安全漏洞|CRLF注入|[MPS-2016-6242](https://www.oscs1024.com/hd/MPS-2016-6242)|CVE-2016-9964|中危|
|OpenCV 数字错误漏洞|除零错误|[MPS-2019-11014](https://www.oscs1024.com/hd/MPS-2019-11014)|CVE-2019-15939|中危|
|OpenCV 缓冲区错误漏洞|越界读取|[MPS-2019-11421](https://www.oscs1024.com/hd/MPS-2019-11421)|CVE-2019-16249|中危|
|Android 缓冲区错误漏洞|越界写入|[MPS-2019-12353](https://www.oscs1024.com/hd/MPS-2019-12353)|CVE-2019-9423|高危|
|OpenCV 缓冲区错误漏洞|越界读取|[MPS-2019-9066](https://www.oscs1024.com/hd/MPS-2019-9066)|CVE-2019-14491|高危|
|OpenCV 缓冲区错误漏洞||[MPS-2019-9067](https://www.oscs1024.com/hd/MPS-2019-9067)|CVE-2019-14492|高危|
|OpenCV 缓冲区错误漏洞|越界写入|[MPS-2020-0084](https://www.oscs1024.com/hd/MPS-2020-0084)|CVE-2019-5063|高危|
|OpenCV 缓冲区错误漏洞|越界写入|[MPS-2020-0085](https://www.oscs1024.com/hd/MPS-2020-0085)|CVE-2019-5064|高危|
|Bottle 环境问题漏洞|HTTP请求走私|[MPS-2021-0650](https://www.oscs1024.com/hd/MPS-2021-0650)|CVE-2020-28473|中危|
|keras 存在反序列化漏洞|反序列化|[MPS-2022-14959](https://www.oscs1024.com/hd/MPS-2022-14959)||高危|
|scikit-learn 存在拒绝服务漏洞|拒绝服务|[MPS-2022-15126](https://www.oscs1024.com/hd/MPS-2022-15126)||低危|
|Bottle 安全特征问题漏洞|对异常条件的处理不恰当|[MPS-2022-16709](https://www.oscs1024.com/hd/MPS-2022-16709)|CVE-2022-31799|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|keras|2.2.5|2.6.0rc3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|bottle|0.12.10|0.12.20|间接依赖|建议修复|C:1|H:0|M:2|L:0|
|opencv-contrib-python|4.1.0.25|4.2.0.32|间接依赖|建议修复|C:0|H:5|M:2|L:0|
|scikit-learn|0.23.1|0.24.2|间接依赖|可选修复|C:0|H:0|M:0|L:1|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|4|Low|
|MIT|5|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|run||间接依赖|pip|
|scikit-image|0.14.5|间接依赖|pip|
|scikit-learn|0.23.1|间接依赖|pip|
|dilation||间接依赖|pip|
|llvmlite|0.36.0|间接依赖|pip|
|route||间接依赖|pip|
|config||间接依赖|pip|
|keras|2.2.5|间接依赖|pip|
|l0Smooth||间接依赖|pip|
|tensorflow_gpu|1.14.0|间接依赖|pip|
|createGuidedFilter||间接依赖|pip|
|disk||间接依赖|pip|
|opencv-contrib-python|4.1.0.25|间接依赖|pip|
|bottle|0.12.10|间接依赖|pip|
|numba|0.53.1|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)