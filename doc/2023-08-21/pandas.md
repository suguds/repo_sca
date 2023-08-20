# pandas-dev/pandas安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1693327830769491968.svg)](https://www.murphysec.com/console/report/1693327830450724864/1693327830769491968)

仓库描述：Flexible and powerful data analysis / manipulation library for Python, providing labeled data structures similar to R data.frame objects, statistical functions, and much more

仓库地址：[https://github.com/pandas-dev/pandas](https://github.com/pandas-dev/pandas)

| star：39428 | watch：1122 | fork：16591 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-21 00:36:23 | 许可证：BSD-3-Clause |
| 最近检测时间：2023-08-21 02:23:40 | 组件总数：45 | 漏洞总数：5 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Jupyter Notebook 输入验证错误漏洞|跨站重定向|[MPS-2020-16692](https://www.oscs1024.com/hd/MPS-2020-16692)|CVE-2020-26215|中危|
|Jupyter Notebook 跨站脚本漏洞|XSS|[MPS-2021-16957](https://www.oscs1024.com/hd/MPS-2021-16957)|CVE-2021-32798|严重|
|Jupyter Notebook 日志信息泄露漏洞|日志敏感信息泄露|[MPS-2022-3725](https://www.oscs1024.com/hd/MPS-2022-3725)|CVE-2022-24758|高危|
|lxml 和 libxml2 代码问题漏洞|空指针取消引用|[MPS-2022-46661](https://www.oscs1024.com/hd/MPS-2022-46661)|CVE-2022-2309|高危|
|Jupyter Notebook 安全漏洞|直接请求（强制性浏览）|[MPS-2022-8639](https://www.oscs1024.com/hd/MPS-2022-8639)|CVE-2022-29238|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|notebook|6.0.3|6.4.12|间接依赖|建议修复|C:1|H:1|M:2|L:0|
|lxml|4.8.0|4.9.1|间接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|11|Low|
|自定义许可证|12|Low|
|BSD-3-Clause|4|Low|
|Apache-2.0|5|Low|
|MPL-2.0|1|Low|
|LGPL-3.0-or-later|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|pre-commit|2.15.0|间接依赖|pip|
|tzdata|2022.1|间接依赖|pip|
|lxml|4.8.0|间接依赖|pip|
|fsspec|2022.05.0|间接依赖|pip|
|cython|0.29.33|间接依赖|pip|
|scripts||间接依赖|pip|
|numexpr|2.8.0|间接依赖|pip|
|gcsfs|2022.05.0|间接依赖|pip|
|odfpy|1.4.1|间接依赖|pip|
|pyarrow|7.0.0|间接依赖|pip|
|pytest-xdist|2.2.0|间接依赖|pip|
|as||间接依赖|pip|
|matplotlib|3.6.1|间接依赖|pip|
|beautifulsoup4|4.11.1|间接依赖|pip|
|pyreadstat|1.1.5|间接依赖|pip|
|numba|0.55.2|间接依赖|pip|
|xlsxwriter|3.0.3|间接依赖|pip|
|xlrd|2.0.1|间接依赖|pip|
|dataframe-api-compat|0.1.7|间接依赖|pip|
|openpyxl|3.0.10|间接依赖|pip|
|mypy|1.4.1|间接依赖|pip|
|meson-python|0.13.1|间接依赖|pip|
|SQLAlchemy|1.4.36|间接依赖|pip|
|pandas||间接依赖|pip|
|scipy|1.8.1|间接依赖|pip|
|zstandard|0.17.0|间接依赖|pip|
|pytest-asyncio|0.17.0|间接依赖|pip|
|tables|3.7.0|间接依赖|pip|
|fastparquet|0.8.1|间接依赖|pip|
|notebook|6.0.3|间接依赖|pip|
|xarray|2022.03.0|间接依赖|pip|
|hypothesis|6.46.1|间接依赖|pip|
|pytest|7.3.2|间接依赖|pip|
|pyxlsb|1.0.9|间接依赖|pip|
|tabulate|0.8.10|间接依赖|pip|
|pymysql|1.0.2|间接依赖|pip|
|nbconvert|6.4.5|间接依赖|pip|
|jinja2|3.1.2|间接依赖|pip|
|psycopg2-binary|2.9.3|间接依赖|pip|
|flake8|6.0.0|间接依赖|pip|
|numpy||间接依赖|pip|
|asv|0.5.1|间接依赖|pip|
|bottleneck|1.3.4|间接依赖|pip|
|s3fs|2022.05.0|间接依赖|pip|
|html5lib|1.1|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)