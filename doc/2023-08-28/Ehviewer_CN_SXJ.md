# xiaojieonly/Ehviewer_CN_SXJ安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1695860120818114560.svg)](https://www.murphysec.com/console/report/1695860120620982272/1695860120818114560)

仓库描述：ehviewer，用爱发电，快乐前行

仓库地址：[https://github.com/xiaojieonly/Ehviewer_CN_SXJ](https://github.com/xiaojieonly/Ehviewer_CN_SXJ)

| star：7220 | watch：139 | fork：269 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-08-25 21:19:28 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-28 02:14:50 | 组件总数：48 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Fastjson < 1.2.83 任意代码执行漏洞|反序列化|[MPS-2022-11320](https://www.oscs1024.com/hd/MPS-2022-11320)|CVE-2022-25845|高危|
|jsoup <1.15.3 存在反射型 XSS 漏洞|XSS|[MPS-2022-51547](https://www.oscs1024.com/hd/MPS-2022-51547)|CVE-2022-36033|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|com.alibaba:fastjson|1.2.73|1.2.83|直接依赖|建议修复|C:0|H:1|M:0|L:0|
|org.jsoup:jsoup|1.14.2|1.15.3|直接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|10|Low|
|GPL-3.0|1|Medium|
|libpng-2.0|1|Low|
|EPL-1.0|2|Low|
|MIT|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|com.squareup.okhttp3:okhttp|3.14.7|直接依赖|maven|
|com.github.seven332:refreshlayout|0.1.0|直接依赖|maven|
|org.greenrobot:greendao-generator|3.0.0|直接依赖|maven|
|androidx.cardview:cardview|1.0.0|直接依赖|maven|
|androidx.appcompat:appcompat|1.0.2|直接依赖|maven|
|androidx.preference:preference|1.0.0|直接依赖|maven|
|com.github.seven332:image|0.1.12|直接依赖|maven|
|com.github.amlcurran.showcaseview:library|5.4.3|直接依赖|maven|
|com.github.seven332:android-resource|0.1.0|直接依赖|maven|
|com.alibaba:fastjson|1.2.73|直接依赖|maven|
|com.h6ah4i.android.widget.advrecyclerview:advrecyclerview|1.0.0|直接依赖|maven|
|com.github.seven332:tuxiang|0.1.6|直接依赖|maven|
|com.github.seven332:ripple|0.1.2|直接依赖|maven|
|com.github.seven332:drawerlayout|ea2bb388f0|直接依赖|maven|
|com.github.seven332:yorozuya-thread|0.1.1|直接依赖|maven|
|com.github.seven332:beerbelly|0.1.4|直接依赖|maven|
|androidx.fragment:fragment|1.3.0-rc01|直接依赖|maven|
|com.github.seven332:yorozuya-collect|0.1.4|直接依赖|maven|
|com.github.seven332:glview-image|0.1.0|直接依赖|maven|
|androidx.activity:activity|1.2.4|直接依赖|maven|
|androidx.recyclerview:recyclerview|1.2.0|直接依赖|maven|
|com.squareup.okhttp3:okhttp-dnsoverhttps|3.14.7|直接依赖|maven|
|org.ccil.cowan.tagsoup:tagsoup|1.2.1|直接依赖|maven|
|com.github.seven332.a7zip:extract-lite|1b21783|直接依赖|maven|
|org.greenrobot:greendao|3.0.0|直接依赖|maven|
|com.fpliu.ndk.pkg.prefab.android.21:libpng|1.6.37|直接依赖|maven|
|com.github.seven332:unifile|9ec57bcd8f|直接依赖|maven|
|com.getkeepsafe.relinker:relinker|1.4.4|直接依赖|maven|
|com.google.firebase:firebase-analytics|21.3.0|直接依赖|maven|
|com.github.seven332:easyrecyclerview|0.1.1|直接依赖|maven|
|com.github.seven332:android-recaptcha|2bbb3459a8|直接依赖|maven|
|androidx.biometric:biometric|1.2.0-alpha01|直接依赖|maven|
|com.github.seven332:glview|0.1.0|直接依赖|maven|
|org.jboss.forge.roaster:roaster-jdt|2.22.2.Final|直接依赖|maven|
|com.github.seven332:conaco|0.1.5-eh|直接依赖|maven|
|org.greenrobot:eventbus|3.1.1|直接依赖|maven|
|com.github.seven332:streampipe|0.1.0|直接依赖|maven|
|androidx.browser:browser|1.3.0|直接依赖|maven|
|org.jsoup:jsoup|1.14.2|直接依赖|maven|
|androidx.constraintlayout:constraintlayout|1.1.3|直接依赖|maven|
|androidx.appcompat:appcompat|1.2.0|直接依赖|maven|
|com.github.seven332:glgallery|0.1.2|直接依赖|maven|
|com.github.seven332:animator|0.1.0|直接依赖|maven|
|org.conscrypt:conscrypt-android|2.5.1|直接依赖|maven|
|com.google.android.material:material|1.4.0|直接依赖|maven|
|com.github.seven332:hotspot|0.1.0|直接依赖|maven|
|com.github.seven332:yorozuya|0.1.2|直接依赖|maven|
|org.jboss.forge.roaster:roaster-api|2.22.2.Final|直接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)