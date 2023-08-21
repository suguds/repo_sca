# xinntao/Real-ESRGAN安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693689693354156032.svg)](https://www.murphysec.com/console/report/1693689692725010432/1693689693354156032)

仓库描述：Real-ESRGAN aims at developing Practical Algorithms for General Image/Video Restoration.

仓库地址：[https://github.com/xinntao/Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)

| star：22378 | watch：220 | fork：2784 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-07-30 03:39:44 | 许可证：BSD-3-Clause |
| 最近检测时间：2023-08-22 02:21:20 | 组件总数：12 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|PyTorch 命令注入漏洞|代码注入|[MPS-2022-65270](https://www.oscs1024.com/hd/MPS-2022-65270)|CVE-2022-45907|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|torch|1.7|1.13.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|3|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|torch|1.7|间接依赖|pip|
|basicsr|1.4.2|间接依赖|pip|
|random_add_poisson_noise_pt||间接依赖|pip|
|GANLoss||间接依赖|pip|
|L1Loss||间接依赖|pip|
|paired_paths_from_folder||间接依赖|pip|
|paired_paths_from_lmdb||间接依赖|pip|
|circular_lowpass_kernel||间接依赖|pip|
|facexlib|0.2.5|间接依赖|pip|
|random_mixed_kernels||间接依赖|pip|
|random_add_gaussian_noise_pt||间接依赖|pip|
|gfpgan|1.3.5|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)