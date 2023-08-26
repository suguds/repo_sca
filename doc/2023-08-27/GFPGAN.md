# TencentARC/GFPGAN安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695502160342376449.svg)](https://www.murphysec.com/console/report/1694413535299067904/1695502160342376449)

仓库描述：GFPGAN aims at developing Practical Algorithms for Real-world Face Restoration.

仓库地址：[https://github.com/TencentARC/GFPGAN](https://github.com/TencentARC/GFPGAN)

| star：31648 | watch：463 | fork：5038 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-13 23:41:35 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-27 02:23:29 | 组件总数：17 | 漏洞总数：1 |

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
|Apache-2.0|2|Low|
|BSD-2-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|fused_leaky_relu||间接依赖|pip|
|imfrombytes||间接依赖|pip|
|GANLoss||间接依赖|pip|
|FacialComponentDiscriminator||间接依赖|pip|
|imwrite||间接依赖|pip|
|torch|1.7|间接依赖|pip|
|get_root_logger||间接依赖|pip|
|BasicBlock||间接依赖|pip|
|facexlib|0.2.5|间接依赖|pip|
|tensor2img||间接依赖|pip|
|FileClient||间接依赖|pip|
|Bottleneck||间接依赖|pip|
|GFPGANv1||间接依赖|pip|
|img2tensor||间接依赖|pip|
|basicsr|1.4.2|间接依赖|pip|
|FusedLeakyReLU||间接依赖|pip|
|L1Loss||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)