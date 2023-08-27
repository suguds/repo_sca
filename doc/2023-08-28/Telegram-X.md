# TGX-Android/Telegram-X安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695862399092744192.svg)](https://www.murphysec.com/console/report/1695862398346158080/1695862399092744192)

仓库描述：The main repository of Telegram X — official alternative Telegram client for Android.

仓库地址：[https://github.com/TGX-Android/Telegram-X](https://github.com/TGX-Android/Telegram-X)

| star：2346 | watch：118 | fork：318 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-27 13:51:43 | 许可证：GPL-3.0 |
| 最近检测时间：2023-08-28 02:20:20 | 组件总数：35 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Play services 安全漏洞|MAID|[MPS-2022-51102](https://www.oscs1024.com/hd/MPS-2022-51102)|CVE-2022-2390|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.google.android.gms:play-services-basement|17.6.0|18.0.2|直接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|1|Low|
|Apache-2.0|10|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|androidx.camera:camera-camera2|1.2.3|直接依赖|maven|
|nl.dionsegijn:konfetti-xml|2.0.2|直接依赖|maven|
|com.google.android.gms:play-services-basement|17.6.0|直接依赖|maven|
|com.google.mlkit:language-id|16.1.1|直接依赖|maven|
|androidx.exifinterface:exifinterface|1.3.6|直接依赖|maven|
|androidx.recyclerview:recyclerview|1.3.0|直接依赖|maven|
|com.squareup.okhttp3:okhttp|4.9.3|直接依赖|maven|
|com.github.natario1:Transcoder|ba8f098c94|直接依赖|maven|
|androidx.palette:palette|1.0.0|直接依赖|maven|
|com.google.android.gms:play-services-maps|17.0.1|直接依赖|maven|
|com.google.zxing:core|3.4.1|直接依赖|maven|
|com.android.tools.build:gradle|8.0.2|直接依赖|maven|
|androidx.browser:browser|1.5.0|直接依赖|maven|
|androidx.viewpager:viewpager|1.0.0|直接依赖|maven|
|com.google.android.play:app-update|2.1.0|直接依赖|maven|
|androidx.camera:camera-lifecycle|1.2.3|直接依赖|maven|
|com.google.android.exoplayer:exoplayer-core|2.19.0|直接依赖|maven|
|androidx.camera:camera-view|1.2.3|直接依赖|maven|
|androidx.interpolator:interpolator|1.0.0|直接依赖|maven|
|androidx.collection:collection|1.2.0|直接依赖|maven|
|com.googlecode.mp4parser:isoparser|1.0.6|直接依赖|maven|
|com.google.firebase:firebase-appcheck-safetynet|16.1.2|直接依赖|maven|
|com.getkeepsafe.relinker:relinker|1.4.5|直接依赖|maven|
|com.google.gms:google-services|4.3.15|直接依赖|maven|
|com.google.android.gms:play-services-location|18.0.0|直接依赖|maven|
|com.google.firebase:firebase-messaging|22.0.0|直接依赖|maven|
|com.google.android.gms:play-services-base|17.6.0|直接依赖|maven|
|androidx.activity:activity|1.7.2|直接依赖|maven|
|com.beust:klaxon|5.6|直接依赖|maven|
|com.squareup.okhttp3:logging-interceptor|4.9.3|直接依赖|maven|
|com.google.android.gms:play-services-mlkit-barcode-scanning|16.2.1|直接依赖|maven|
|androidx.gridlayout:gridlayout|1.0.0|直接依赖|maven|
|androidx.work:work-runtime|2.8.1|直接依赖|maven|
|com.luckycatlabs:SunriseSunsetCalculator|1.2|直接依赖|maven|
|com.davemorrissey.labs:subsampling-scale-image-view-androidx|3.10.0|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)