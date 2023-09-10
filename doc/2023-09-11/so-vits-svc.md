# svc-develop-team/so-vits-svc安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700937175583555584.svg)](https://www.murphysec.com/console/report/1700937175340285952/1700937175583555584)

仓库描述：SoftVC VITS Singing Voice Conversion

仓库地址：[https://github.com/svc-develop-team/so-vits-svc](https://github.com/svc-develop-team/so-vits-svc)

| star：18918 | watch：144 | fork：3680 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-09 09:37:10 | 许可证：AGPL-3.0 |
| 最近检测时间：2023-09-11 02:20:05 | 组件总数：50 | 漏洞总数：8 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|facebookresearch fairseq库存在任意代码执行漏洞|代码注入|[MPS-2022-65070](https://www.oscs1024.com/hd/MPS-2022-65070)||高危|
|SciPy 资源管理错误漏洞|UAF|[MPS-2023-10196](https://www.oscs1024.com/hd/MPS-2023-10196)|CVE-2023-29824|严重|
|Gradio 信任管理问题漏洞|使用硬编码的凭证|[MPS-2023-4699](https://www.oscs1024.com/hd/MPS-2023-4699)|CVE-2023-25823|严重|
|Starlette 路径遍历漏洞|路径遍历|[MPS-4hcz-v0db](https://www.oscs1024.com/hd/MPS-4hcz-v0db)|CVE-2023-29159|高危|
|Starlette 安全漏洞|拒绝服务|[MPS-er5l-vnyh](https://www.oscs1024.com/hd/MPS-er5l-vnyh)|CVE-2023-30798|高危|
|Gradio 输入验证错误漏洞||[MPS-f8mu-5xwo](https://www.oscs1024.com/hd/MPS-f8mu-5xwo)|CVE-2023-34239|严重|
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|gradio|3.7.0|3.34.0|间接依赖|建议修复|C:2|H:0|M:0|L:0|
|requests|2.28.1|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|scipy|1.7.3|1.10.0rc1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|fairseq|0.12.2||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|starlette|0.19.1|0.27.0|间接依赖|建议修复|C:0|H:2|M:0|L:0|
|numpy|1.23.0||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|ISC|1|Low|
|自定义许可证|3|Low|
|MIT|5|Low|
|BSD-3-Clause|2|Low|
|Apache-2.0|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|librosa|0.9.1|间接依赖|pip|
|starlette|0.19.1|间接依赖|pip|
|sounddevice|0.4.5|间接依赖|pip|
|load_model||间接依赖|pip|
|to_viterbi_cents||间接依赖|pip|
|Optional||间接依赖|pip|
|load_config||间接依赖|pip|
|KMeans||间接依赖|pip|
|SoundFile|0.10.3.post1|间接依赖|pip|
|MiniBatchKMeans||间接依赖|pip|
|WavLMConfig||间接依赖|pip|
|DetectorFactory||间接依赖|pip|
|numpy|1.23.0|间接依赖|pip|
|List||间接依赖|pip|
|PyAudio|0.2.12|间接依赖|pip|
|requests|2.28.1|间接依赖|pip|
|detect||间接依赖|pip|
|pad_or_trim||间接依赖|pip|
|WavLM||间接依赖|pip|
|remove_weight_norm||间接依赖|pip|
|request||间接依赖|pip|
|torchaudio|0.13.1|间接依赖|pip|
|fairseq|0.12.2|间接依赖|pip|
|to_local_average_cents||间接依赖|pip|
|pydub|0.25.1|间接依赖|pip|
|rearrange||间接依赖|pip|
|torch|1.13.1|间接依赖|pip|
|GradScaler||间接依赖|pip|
|Conv1d||间接依赖|pip|
|Conv2d||间接依赖|pip|
|playsound|1.3.0|间接依赖|pip|
|Tuple||间接依赖|pip|
|autocast||间接依赖|pip|
|scipy|1.7.3|间接依赖|pip|
|get_padding||间接依赖|pip|
|init_weights||间接依赖|pip|
|load_wav_to_torch||间接依赖|pip|
|Mish||间接依赖|pip|
|pyworld|0.3.0|间接依赖|pip|
|gradio|3.7.0|间接依赖|pip|
|tqdm|4.63.0|间接依赖|pip|
|AvgPool1d||间接依赖|pip|
|TextIO||间接依赖|pip|
|repeat||间接依赖|pip|
|Flask_Cors|3.0.10|间接依赖|pip|
|Flask|2.1.2|间接依赖|pip|
|log_mel_spectrogram||间接依赖|pip|
|Callable||间接依赖|pip|
|load_filepaths_and_text||间接依赖|pip|
|weight_norm||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)