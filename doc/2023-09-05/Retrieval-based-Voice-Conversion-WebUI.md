# RVC-Project/Retrieval-based-Voice-Conversion-WebUI安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698762982598426624.svg)](https://www.murphysec.com/console/report/1698400589763444736/1698762982598426624)

仓库描述：Voice data <= 10 mins can also be used to train a good VC model!

仓库地址：[https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)

| star：10866 | watch：91 | fork：1665 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-04 23:11:45 | 许可证：MIT |
| 最近检测时间：2023-09-05 02:20:45 | 组件总数：52 | 漏洞总数：4 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|joblib 安全漏洞||[MPS-2022-5059](https://www.oscs1024.com/hd/MPS-2022-5059)|CVE-2022-21797|严重|
|facebookresearch fairseq库存在任意代码执行漏洞|代码注入|[MPS-2022-65070](https://www.oscs1024.com/hd/MPS-2022-65070)||高危|
|Tornado 输入验证错误漏洞|跨站重定向|[MPS-84aj-mebq](https://www.oscs1024.com/hd/MPS-84aj-mebq)|CVE-2023-28370|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|fairseq|0.12.2||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|joblib|1.1.0|1.1.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|numpy|1.23.5||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|tornado|6.1|6.3.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|9|Low|
|ISC|2|Low|
|BSD-3-Clause|6|Low|
|MIT|8|Low|
|BSD-2-Clause|2|Low|
|Apache-2.0|3|Low|
|HPND|1|Low|
|GPL-3.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|fastapi|0.88|间接依赖|pip|
|conv1d||间接依赖|pip|
|numba|0.56.4|间接依赖|pip|
|randint||间接依赖|pip|
|resampy|0.4.2|间接依赖|pip|
|conv2d||间接依赖|pip|
|fsspec|2022.11.0|间接依赖|pip|
|Jinja2|3.1.2|间接依赖|pip|
|ffmpy|0.3.1|间接依赖|pip|
|Conv1d||间接依赖|pip|
|numpy|1.23.5|间接依赖|pip|
|colorama|0.4.5|间接依赖|pip|
|pyasn1|0.4.8|间接依赖|pip|
|uvicorn|0.21.1|间接依赖|pip|
|uc-micro-py|1.0.1|间接依赖|pip|
|fairseq|0.12.2|间接依赖|pip|
|python-dotenv|1.0.0|间接依赖|pip|
|pyworld|0.3.2|间接依赖|pip|
|modules||间接依赖|pip|
|faiss-cpu|1.7.3|间接依赖|pip|
|requirements.txt||间接依赖|pip|
|soundfile|0.12.1|间接依赖|pip|
|ffmpeg-python|0.2.0|间接依赖|pip|
|AudioPreDeEcho||间接依赖|pip|
|AvgPool1d||间接依赖|pip|
|llvmlite|0.39.0|间接依赖|pip|
|tornado|6.1|间接依赖|pip|
|librosa|0.9.1|间接依赖|pip|
|sympy|1.11.1|间接依赖|pip|
|Werkzeug|2.2.3|间接依赖|pip|
|pyasn1-modules|0.2.8|间接依赖|pip|
|Queue||间接依赖|pip|
|torchcrepe|0.0.20|间接依赖|pip|
|absl-py|1.2.0|间接依赖|pip|
|Pillow|9.1.1|间接依赖|pip|
|shuffle||间接依赖|pip|
|tabulate|0.8.10|间接依赖|pip|
|gradio|3.34.0|间接依赖|pip|
|load_audio||间接依赖|pip|
|PyYAML|6.0|间接依赖|pip|
|cpu_count||间接依赖|pip|
|matplotlib-inline|0.1.3|间接依赖|pip|
|load_wav_to_torch||间接依赖|pip|
|load_filepaths_and_text||间接依赖|pip|
|joblib|1.1.0|间接依赖|pip|
|praat-parselmouth|0.4.2|间接依赖|pip|
|wav2||间接依赖|pip|
|AudioPre||间接依赖|pip|
|commons||间接依赖|pip|
|matplotlib|3.7.0|间接依赖|pip|
|tqdm|4.63.1|间接依赖|pip|
|pydub|0.25.1|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)