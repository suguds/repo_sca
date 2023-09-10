# sensity-ai/dot安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700937833056616448.svg)](https://www.murphysec.com/console/report/1700937832976924672/1700937833056616448)

仓库描述：The Deepfake Offensive Toolkit

仓库地址：[https://github.com/sensity-ai/dot](https://github.com/sensity-ai/dot)

| star：3438 | watch：31 | fork：307 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-07 18:18:51 | 许可证：BSD-3-Clause |
| 最近检测时间：2023-09-11 02:24:24 | 组件总数：100 | 漏洞总数：3 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 安全漏洞|不充分的比较|[MPS-2021-25631](https://www.oscs1024.com/hd/MPS-2021-25631)|CVE-2021-34141|中危|
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|mpmath 存在ReDoS漏洞|ReDoS|[MPS-2022-14993](https://www.oscs1024.com/hd/MPS-2022-14993)||中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|numpy|1.22.0|1.22.2|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|mpmath|1.3.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|39|Low|
|自定义许可证|25|Low|
|Unlicense|1|Low|
|Apache-2.0|7|Low|
|BSD-3-Clause|7|Low|
|BSD-2-Clause|1|Low|
|MPL-2.0|1|Low|
|ISC|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|pillow|9.3.0|间接依赖|pip|
|isort|5.12.0|间接依赖|pip|
|mccabe|0.6.1|间接依赖|pip|
|distlib|0.3.4|间接依赖|pip|
|filelock|3.12.2|间接依赖|pip|
|face-alignment|1.3.3|间接依赖|pip|
|networkx|2.8.4|间接依赖|pip|
|packaging|21.3|间接依赖|pip|
|absl-py|1.1.0|间接依赖|pip|
|typing-extensions|4.3.0|间接依赖|pip|
|six|1.16.0|间接依赖|pip|
|jinja2|3.1.2|间接依赖|pip|
|tifffile|2022.5.4|间接依赖|pip|
|pefile|2023.2.7|间接依赖|pip|
|pure-eval|0.2.2|间接依赖|pip|
|numba|0.55.2|间接依赖|pip|
|ipdb|0.13.9|间接依赖|pip|
|pyparsing|3.0.9|间接依赖|pip|
|cffi|1.15.1|间接依赖|pip|
|urllib3|1.26.10|间接依赖|pip|
|click|8.0.2|间接依赖|pip|
|backcall|0.2.0|间接依赖|pip|
|imageio|2.19.3|间接依赖|pip|
|scikit-image|0.19.1|间接依赖|pip|
|pycodestyle|2.7.0|间接依赖|pip|
|altgraph|0.17.3|间接依赖|pip|
|wcwidth|0.2.5|间接依赖|pip|
|exceptiongroup|1.1.2|间接依赖|pip|
|pywin32-ctypes|0.2.2|间接依赖|pip|
|decorator|5.1.1|间接依赖|pip|
|onnxruntime|1.9.0|间接依赖|pip|
|iniconfig|2.0.0|间接依赖|pip|
|types-pyyaml|6.0.10|间接依赖|pip|
|parso|0.8.3|间接依赖|pip|
|protobuf|3.20.2|间接依赖|pip|
|idna|2.10|间接依赖|pip|
|pycparser|2.21|间接依赖|pip|
|opencv-contrib-python|4.5.5.62|间接依赖|pip|
|scipy|1.10.0|间接依赖|pip|
|sounddevice|0.4.6|间接依赖|pip|
|torch|2.0.1|间接依赖|pip|
|mediapipe|0.10.3|间接依赖|pip|
|coverage|6.4.2|间接依赖|pip|
|jedi|0.18.1|间接依赖|pip|
|stack-data|0.3.0|间接依赖|pip|
|virtualenv|20.15.1|间接依赖|pip|
|pluggy|1.2.0|间接依赖|pip|
|bumpversion|0.6.0|间接依赖|pip|
|matplotlib|3.5.2|间接依赖|pip|
|matplotlib-inline|0.1.3|间接依赖|pip|
|fonttools|4.34.4|间接依赖|pip|
|atomicwrites|1.4.1|间接依赖|pip|
|requests|2.31.0|间接依赖|pip|
|pyyaml|5.4.1|间接依赖|pip|
|toml|0.10.2|间接依赖|pip|
|colorama|0.4.6|间接依赖|pip|
|bump2version|1.0.1|间接依赖|pip|
|pathspec|0.9.0|间接依赖|pip|
|dlib|19.19.0|间接依赖|pip|
|llvmlite|0.38.1|间接依赖|pip|
|attrs|21.4.0|间接依赖|pip|
|flatbuffers|2.0|间接依赖|pip|
|kornia|0.6.5|间接依赖|pip|
|pygments|2.15.0|间接依赖|pip|
|platformdirs|2.5.2|间接依赖|pip|
|darkdetect|0.8.0|间接依赖|pip|
|certifi|2023.7.22|间接依赖|pip|
|customtkinter|5.2.0|间接依赖|pip|
|asttokens|2.0.5|间接依赖|pip|
|pyinstaller-hooks-contrib|2023.5|间接依赖|pip|
|cfgv|3.3.1|间接依赖|pip|
|tqdm|4.64.0|间接依赖|pip|
|executing|0.8.3|间接依赖|pip|
|markupsafe|2.1.3|间接依赖|pip|
|pickleshare|0.7.5|间接依赖|pip|
|cycler|0.11.0|间接依赖|pip|
|numpy|1.22.0|间接依赖|pip|
|torchvision|0.15.2|间接依赖|pip|
|pre-commit|2.19.0|间接依赖|pip|
|mypy-extensions|0.4.3|间接依赖|pip|
|traitlets|5.3.0|间接依赖|pip|
|tomli|2.0.1|间接依赖|pip|
|identify|2.5.1|间接依赖|pip|
|charset-normalizer|3.2.0|间接依赖|pip|
|prompt-toolkit|3.0.30|间接依赖|pip|
|black|22.3.0|间接依赖|pip|
|pyinstaller|5.13.0|间接依赖|pip|
|pytest-cov|3.0.0|间接依赖|pip|
|pyflakes|2.3.1|间接依赖|pip|
|pytest|7.4.0|间接依赖|pip|
|kiwisolver|1.4.3|间接依赖|pip|
|py|1.11.0|间接依赖|pip|
|ipython|8.10.0|间接依赖|pip|
|nodeenv|1.7.0|间接依赖|pip|
|pywavelets|1.3.0|间接依赖|pip|
|mpmath|1.3.0|间接依赖|pip|
|python-dateutil|2.8.2|间接依赖|pip|
|flake8|3.9.2|间接依赖|pip|
|opencv-python|4.5.5.62|间接依赖|pip|
|sympy|1.12|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)