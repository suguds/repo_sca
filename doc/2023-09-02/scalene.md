# plasma-umass/scalene安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1697678608323706880.svg)](https://www.murphysec.com/console/report/1697316247686701056/1697678608323706880)

仓库描述：Scalene: a high-performance, high-precision CPU, GPU, and memory profiler for Python with AI-powered optimization proposals

仓库地址：[https://github.com/plasma-umass/scalene](https://github.com/plasma-umass/scalene)

| star：9515 | watch：85 | fork：323 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-01 02:33:28 | 许可证：Apache-2.0 |
| 最近检测时间：2023-09-02 02:33:19 | 组件总数：28 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Interactive Python 操作系统命令注入漏洞|OS命令注入|[MPS-2023-3322](https://www.oscs1024.com/hd/MPS-2023-3322)|CVE-2023-24816|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|ipython|8.10|8.10.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|5|Low|
|自定义许可证|2|Low|
|MIT|3|Low|
|Apache-2.0|1|Low|
|MPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|cloudpickle|2.2.1|间接依赖|pip|
|List||间接依赖|pip|
|packaging|20.9|间接依赖|pip|
|Generic||间接依赖|pip|
|HTTPServer||间接依赖|pip|
|pyperf|2.0.0|间接依赖|pip|
|NewType||间接依赖|pip|
|rich|10.7.0|间接依赖|pip|
|expand||间接依赖|pip|
|Jinja2|3.0.3|间接依赖|pip|
|cast||间接依赖|pip|
|pyproj||间接依赖|pip|
|ipython|8.10|间接依赖|pip|
|Dict||间接依赖|pip|
|Cython|0.29.28|间接依赖|pip|
|defaultdict||间接依赖|pip|
|sleep||间接依赖|pip|
|hypothesis||间接依赖|pip|
|lxml|4.9.1|间接依赖|pip|
|flask||间接依赖|pip|
|BaseHTTPRequestHandler||间接依赖|pip|
|perf_counter||间接依赖|pip|
|OrderedDict||间接依赖|pip|
|setuptools|65.5.1|间接依赖|pip|
|symbols||间接依赖|pip|
|Any||间接依赖|pip|
|Optional||间接依赖|pip|
|psutil|5.9.2|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)