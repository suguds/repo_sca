# zhayujie/chatgpt-on-wechat安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695866372205473792.svg)](https://www.murphysec.com/console/report/1695866371198840832/1695866372205473792)

仓库描述：Wechat robot based on ChatGPT,  which using OpenAI api and itchat library. 使用ChatGPT搭建微信聊天机器人，基于 GPT3.5/GPT4.0/文心一言/讯飞星火 模型，支持个人微信、公众号、企业微信部署，能处理文本、语音和图片，访问操作系统和互联网，支持基于知识库定制专属机器人。

仓库地址：[https://github.com/zhayujie/chatgpt-on-wechat](https://github.com/zhayujie/chatgpt-on-wechat)

| star：15297 | watch：129 | fork：4552 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-28 02:08:49 | 许可证：MIT |
| 最近检测时间：2023-08-28 02:30:29 | 组件总数：32 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|requests|2.28.2|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|numpy|1.24.2||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|7|Low|
|MIT|2|Low|
|Apache-2.0|3|Low|
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|wechaty_puppet|0.4.23|间接依赖|pip|
|generate||间接依赖|pip|
|_reset_logger||间接依赖|pip|
|ReplyType||间接依赖|pip|
|openai|0.27.8|间接依赖|pip|
|plugin_config||间接依赖|pip|
|qrcode|7.4.2|间接依赖|pip|
|common||间接依赖|pip|
|logger||间接依赖|pip|
|requirements.txt||间接依赖|pip|
|ThreadPoolExecutor||间接依赖|pip|
|set_api_key||间接依赖|pip|
|bot||间接依赖|pip|
|config||间接依赖|pip|
|Reply||间接依赖|pip|
|utils||间接依赖|pip|
|Future||间接依赖|pip|
|pconf||间接依赖|pip|
|PyQRCode|1.2.1|间接依赖|pip|
|chardet|5.1.0|间接依赖|pip|
|requirements-optional.txt||间接依赖|pip|
|ImageReply||间接依赖|pip|
|websocket-client|1.2.0|间接依赖|pip|
|wechaty|0.10.7|间接依赖|pip|
|conf||间接依赖|pip|
|numpy|1.24.2|间接依赖|pip|
|requests|2.28.2|间接依赖|pip|
|chatgpt_tool_hub|0.4.6|间接依赖|pip|
|wechatpy||间接依赖|pip|
|subscribe_msg||间接依赖|pip|
|HTMLParser|0.0.2|间接依赖|pip|
|VoiceReply||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)