# roboflow/inference安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694776692571533312.svg)](https://www.murphysec.com/console/report/1694776692328263680/1694776692571533312)

仓库描述：An easy-to-use, production-ready inference server for computer vision supporting deployment of many popular model architectures and fine-tuned models.

仓库地址：[https://github.com/roboflow/inference](https://github.com/roboflow/inference)

| star：363 | watch：17 | fork：12 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-24 23:57:44 | 许可证：NOASSERTION |
| 最近检测时间：2023-08-25 02:25:29 | 组件总数：43 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|piexif 存在路径遍历漏洞|路径遍历|[MPS-2022-15029](https://www.oscs1024.com/hd/MPS-2022-15029)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|piexif|1.1.3||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|numpy|1.25.2||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|5|Low|
|ISC|2|Low|
|MIT|7|Low|
|Apache-2.0|3|Low|
|BSD-3-Clause|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|pillow|9.5.0|间接依赖|pip|
|sam_model_registry||间接依赖|pip|
|Pool||间接依赖|pip|
|rasterio|1.2.10|间接依赖|pip|
|field||间接依赖|pip|
|prometheus-fastapi-instrumentator|6.0.0|间接依赖|pip|
|fastapi-cprofile|0.0.2|间接依赖|pip|
|pymemcache|4.0.0|间接依赖|pip|
|onnxruntime|1.14.1|间接依赖|pip|
|wraps||间接依赖|pip|
|mkdocs-swagger-ui-tag|0.6.3|间接依赖|pip|
|InputMethodNotAllowed||间接依赖|pip|
|Any||间接依赖|pip|
|API_BASE_URL||间接依赖|pip|
|cpu_count||间接依赖|pip|
|dataclass||间接依赖|pip|
|sleep||间接依赖|pip|
|piexif|1.1.3|间接依赖|pip|
|cython|3.0.0|间接依赖|pip|
|perf_counter||间接依赖|pip|
|elasticache_auto_discovery|1.0.0|间接依赖|pip|
|rich|13.5.2|间接依赖|pip|
|inference||间接依赖|pip|
|shapely|2.0.1|间接依赖|pip|
|fastapi|0.85.1|间接依赖|pip|
|torchvision|0.15.2|间接依赖|pip|
|numpy|1.25.2|间接依赖|pip|
|opencv-python|4.8.0.76|间接依赖|pip|
|APScheduler|3.10.1|间接依赖|pip|
|mkdocs-material|9.2.1|间接依赖|pip|
|mkdocstrings|0.22.0|间接依赖|pip|
|requests|2.31.0|间接依赖|pip|
|mike|1.1.2|间接依赖|pip|
|MODEL_CACHE_DIR||间接依赖|pip|
|torch|2.0.1|间接依赖|pip|
|partial||间接依赖|pip|
|mkdocs|1.5.2|间接依赖|pip|
|SamPredictor||间接依赖|pip|
|python-multipart|0.0.6|间接依赖|pip|
|boto3|1.28.23|间接依赖|pip|
|onnxruntime-gpu|1.15.1|间接依赖|pip|
|Dict||间接依赖|pip|
|InvalidNumpyInput||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)