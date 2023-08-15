# coqui-ai/TTS安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691515368542982144.svg)](https://www.murphysec.com/console/report/1691515368299712512/1691515368542982144)

仓库描述：🐸💬 - a deep learning toolkit for Text-to-Speech, battle-tested in research and production

仓库地址：[https://github.com/coqui-ai/TTS](https://github.com/coqui-ai/TTS)

| star：14134 | watch：182 | fork：1850 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-15 15:19:44 | 许可证：- |
| 最近检测时间：2023-08-16 02:23:52 | 组件总数：106 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-2021-25101|经典缓冲区溢出|[MPS-2021-25101](https://www.oscs1024.com/hd/MPS-2021-25101)|CVE-2021-33430|中危|
|MPS-2021-25631|不充分的比较|[MPS-2021-25631](https://www.oscs1024.com/hd/MPS-2021-25631)|CVE-2021-34141|中危|
|MPS-2021-32278|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|MPS-2021-32279|经典缓冲区溢出|[MPS-2021-32279](https://www.oscs1024.com/hd/MPS-2021-32279)|CVE-2021-41496|中危|
|MPS-2022-65270|代码注入|[MPS-2022-65270](https://www.oscs1024.com/hd/MPS-2022-65270)|CVE-2022-45907|严重|
|MPS-2023-10196|UAF|[MPS-2023-10196](https://www.oscs1024.com/hd/MPS-2023-10196)|CVE-2023-29824|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|scipy|1.4.0|1.10.0rc1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|torch|1.7|1.13.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|numpy|1.17.0|1.22.2|间接依赖|可选修复|C:0|H:0|M:4|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|6|Low|
|MIT|1|Low|
|MPL-2.0|1|Low|
|BSD-3-Clause|2|Low|
|Apache-2.0|2|Low|
|GPL-2.0-or-later|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|get_tests_path||间接依赖|pip|
|generate_path||间接依赖|pip|
|GPTConfig||间接依赖|pip|
|remove_silence||间接依赖|pip|
|make_symbols||间接依赖|pip|
|Wavernn||间接依赖|pip|
|GE2ELoss||间接依赖|pip|
|RelativePositionBias||间接依赖|pip|
|Tuple||间接依赖|pip|
|_DEF_PUNCS||间接依赖|pip|
|rearrange||间接依赖|pip|
|LayerNorm||间接依赖|pip|
|CBHG||间接依赖|pip|
|MultiPeriodDiscriminator||间接依赖|pip|
|AngleProtoLoss||间接依赖|pip|
|get_device_id||间接依赖|pip|
|rmtree||间接依赖|pip|
|bangla|0.0.2|间接依赖|pip|
|Prenet||间接依赖|pip|
|optim||间接依赖|pip|
|Gruut||间接依赖|pip|
|DelightfulTtsArgs||间接依赖|pip|
|repeat||间接依赖|pip|
|run_cli||间接依赖|pip|
|GPT||间接依赖|pip|
|BCELossMasked||间接依赖|pip|
|BaseCharacters||间接依赖|pip|
|scipy|1.4.0|间接依赖|pip|
|Encoder||间接依赖|pip|
|AvgPool1d||间接依赖|pip|
|TTS||间接依赖|pip|
|inflect|5.6.0|间接依赖|pip|
|spectral_norm||间接依赖|pip|
|normalization||间接依赖|pip|
|Wav2Vec2CTCTokenizer||间接依赖|pip|
|Linear||间接依赖|pip|
|numpy|1.17.0|间接依赖|pip|
|FiLM||间接依赖|pip|
|load_voice||间接依赖|pip|
|BaseVocabulary||间接依赖|pip|
|ESpeak||间接依赖|pip|
|List||间接依赖|pip|
|Any||间接依赖|pip|
|g2pkk|0.1.1|间接依赖|pip|
|weight_norm||间接依赖|pip|
|nn||间接依赖|pip|
|bnunicodenormalizer|0.1.1|间接依赖|pip|
|requirements.txt||间接依赖|pip|
|phonemes||间接依赖|pip|
|mecab-python3|1.0.6|间接依赖|pip|
|ForwardTTS||间接依赖|pip|
|assertHasAttr||间接依赖|pip|
|Wavegrad||间接依赖|pip|
|BucketBatchSampler||间接依赖|pip|
|average_over_durations||间接依赖|pip|
|get_vad_model_and_utils||间接依赖|pip|
|umap-learn|0.5.1|间接依赖|pip|
|download_url||间接依赖|pip|
|Callable||间接依赖|pip|
|coqpit|0.0.16|间接依赖|pip|
|assertHasNotAttr||间接依赖|pip|
|torch|1.7|间接依赖|pip|
|WavegradArgs||间接依赖|pip|
|get_tests_data_path||间接依赖|pip|
|WavernnArgs||间接依赖|pip|
|InvConvNear||间接依赖|pip|
|DiscriminatorP||间接依赖|pip|
|WavLM||间接依赖|pip|
|VocoderConfig||间接依赖|pip|
|fsspec|2021.04.0|间接依赖|pip|
|download_kaggle_dataset||间接依赖|pip|
|ForwardTTSArgs||间接依赖|pip|
|Trainer||间接依赖|pip|
|jamo||间接依赖|pip|
|copyfile||间接依赖|pip|
|synthesis||间接依赖|pip|
|pylint|2.10.2|间接依赖|pip|
|Punctuation||间接依赖|pip|
|LayerNorm2||间接依赖|pip|
|transfer_voice||间接依赖|pip|
|Conv1dBNBlock||间接依赖|pip|
|Union||间接依赖|pip|
|get_tests_output_path||间接依赖|pip|
|field||间接依赖|pip|
|CouplingBlock||间接依赖|pip|
|denormalize_tacotron_mel||间接依赖|pip|
|bokeh|1.4.0|间接依赖|pip|
|Wav2Vec2FeatureExtractor||间接依赖|pip|
|DBlock||间接依赖|pip|
|Decoder||间接依赖|pip|
|Conv1d||间接依赖|pip|
|get_tests_input_path||间接依赖|pip|
|Outputnet||间接依赖|pip|
|TrainerArgs||间接依赖|pip|
|WavLMConfig||间接依赖|pip|
|unidic-lite|1.0.8|间接依赖|pip|
|AttentionBlock||间接依赖|pip|
|cython|0.29.30|间接依赖|pip|
|ContinuousTransformerWrapper||间接依赖|pip|
|Optional||间接依赖|pip|
|dataclass||间接依赖|pip|
|Dict||间接依赖|pip|
|L1LossMasked||间接依赖|pip|
|Conv1dBN||间接依赖|pip|
|Downsample||间接依赖|pip|
|PerfectBatchSampler||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)