# zauberzeug/nicegui安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695501236341399552.svg)](https://www.murphysec.com/console/report/1695501236303650816/1695501236341399552)

仓库描述：Create web-based user interfaces with Python. The nice way.

仓库地址：[https://github.com/zauberzeug/nicegui](https://github.com/zauberzeug/nicegui)

| star：4989 | watch：43 | fork：264 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-27 01:01:56 | 许可证：MIT |
| 最近检测时间：2023-08-27 02:22:27 | 组件总数：32 | 漏洞总数：13 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|OpenCV 数字错误漏洞|除零错误|[MPS-2019-11014](https://www.oscs1024.com/hd/MPS-2019-11014)|CVE-2019-15939|中危|
|OpenCV 缓冲区错误漏洞|越界读取|[MPS-2019-11421](https://www.oscs1024.com/hd/MPS-2019-11421)|CVE-2019-16249|中危|
|Android 缓冲区错误漏洞|越界写入|[MPS-2019-12353](https://www.oscs1024.com/hd/MPS-2019-12353)|CVE-2019-9423|高危|
|OpenCV 缓冲区错误漏洞|越界读取|[MPS-2019-15873](https://www.oscs1024.com/hd/MPS-2019-15873)|CVE-2019-19624|中危|
|OpenCV 缓冲区错误漏洞|越界写入|[MPS-2020-0085](https://www.oscs1024.com/hd/MPS-2020-0085)|CVE-2019-5064|高危|
|LangChain 注入漏洞|注入|[MPS-3udo-v1n0](https://www.oscs1024.com/hd/MPS-3udo-v1n0)|CVE-2023-36188|严重|
|Langchain 安全漏洞||[MPS-6i1z-gkra](https://www.oscs1024.com/hd/MPS-6i1z-gkra)|CVE-2023-34540|严重|
|langchain-0.0.194代码注入漏洞|代码注入|[MPS-84rc-nja1](https://www.oscs1024.com/hd/MPS-84rc-nja1)|CVE-2023-36095|严重|
|langchain-0.0.231代码注入漏洞|代码注入|[MPS-fv9p-y147](https://www.oscs1024.com/hd/MPS-fv9p-y147)|CVE-2023-38860|严重|
|LangChain SQL注入漏洞|SQL注入|[MPS-p829-6f3r](https://www.oscs1024.com/hd/MPS-p829-6f3r)|CVE-2023-36189|高危|
|LangChain 安全漏洞||[MPS-s5ul-own1](https://www.oscs1024.com/hd/MPS-s5ul-own1)|CVE-2023-36258|严重|
|langchain注入漏洞|注入|[MPS-vszg-p7q8](https://www.oscs1024.com/hd/MPS-vszg-p7q8)|CVE-2023-38896|严重|
|langchain注入漏洞|注入|[MPS-x9qb-uct8](https://www.oscs1024.com/hd/MPS-x9qb-uct8)|CVE-2023-39659|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|langchain|0.0.142|0.0.236|间接依赖|建议修复|C:7|H:1|M:0|L:0|
|opencv-python|4.0|4.2.0.32|间接依赖|建议修复|C:0|H:2|M:3|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|GPL-3.0-or-later|1|Low|
|Apache-2.0|1|Low|
|MIT|3|Low|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|date||间接依赖|pip|
|dataclass||间接依赖|pip|
|Awaitable||间接依赖|pip|
|app||间接依赖|pip|
|ui||间接依赖|pip|
|Request||间接依赖|pip|
|Optional||间接依赖|pip|
|events||间接依赖|pip|
|selenium||间接依赖|pip|
|langchain|0.0.142|间接依赖|pip|
|globals||间接依赖|pip|
|field||间接依赖|pip|
|elements||间接依赖|pip|
|Twist||间接依赖|pip|
|Generator||间接依赖|pip|
|background_tasks||间接依赖|pip|
|replicate|0.4|间接依赖|pip|
|Literal||间接依赖|pip|
|Callable||间接依赖|pip|
|Pose||间接依赖|pip|
|FastAPI||间接依赖|pip|
|List||间接依赖|pip|
|typing_extensions||间接依赖|pip|
|nicegui|1.2|间接依赖|pip|
|Dict||间接依赖|pip|
|Client||间接依赖|pip|
|tortoise||间接依赖|pip|
|APIRouter||间接依赖|pip|
|launch||间接依赖|pip|
|Any||间接依赖|pip|
|fastapi||间接依赖|pip|
|opencv-python|4.0|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)