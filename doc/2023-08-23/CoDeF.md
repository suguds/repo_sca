# qiuyu96/CoDeF安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694050765038772224.svg)](https://www.murphysec.com/console/report/1692963726990135297/1694050765038772224)

仓库描述：Official PyTorch implementation of CoDeF: Content Deformation Fields for Temporally Consistent Video Processing

仓库地址：[https://github.com/qiuyu96/CoDeF](https://github.com/qiuyu96/CoDeF)

| star：2447 | watch：51 | fork：174 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-22 16:08:54 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-23 02:16:51 | 组件总数：21 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|numpy|1.24.3||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|4|Low|
|自定义许可证|5|Low|
|Apache-2.0|2|Low|
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|rearrange||间接依赖|pip|
|einops|0.6.1|间接依赖|pip|
|easydict|1.10|间接依赖|pip|
|SGD||间接依赖|pip|
|Adam||间接依赖|pip|
|tqdm|4.65.0|间接依赖|pip|
|torch||间接依赖|pip|
|tensorboard|2.13.0|间接依赖|pip|
|reduce||间接依赖|pip|
|PyYAML|6.0|间接依赖|pip|
|pytorch_lightning|2.0.2|间接依赖|pip|
|opencv-python-headless|4.5.5.62|间接依赖|pip|
|sk-video|1.1.10|间接依赖|pip|
|Trainer||间接依赖|pip|
|numpy|1.24.3|间接依赖|pip|
|LightningModule||间接依赖|pip|
|kornia|0.5.10|间接依赖|pip|
|scipy|1.10.1|间接依赖|pip|
|ipdb|0.13.13|间接依赖|pip|
|scikit-image|0.21.0|间接依赖|pip|
|torch_optimizer|0.3.0|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)