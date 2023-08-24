# carbon-design-system/carbon安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694781334655688704.svg)](https://www.murphysec.com/console/report/1694781334060097536/1694781334655688704)

仓库描述：A design system built by IBM

仓库地址：[https://github.com/carbon-design-system/carbon](https://github.com/carbon-design-system/carbon)

| star：6943 | watch：86 | fork：1629 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-25 01:39:40 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-25 03:58:41 | 组件总数：35 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Go 权限许可和访问控制问题漏洞|权限管理不当|[MPS-2022-9049](https://www.oscs1024.com/hd/MPS-2022-9049)|CVE-2022-29526|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/sys|v0.0.0-20220715151400-c0bba94af5f8|0.1.0|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|KERNEL32.dll||间接依赖||
|ole32.dll||间接依赖||
|libc.musl-x86_64.so.1||间接依赖||
|/System/Library/Frameworks/AppKit.framework/Versions/C/AppKit||间接依赖||
|/System/Library/Frameworks/CoreFoundation.framework/Versions/A/CoreFoundation||间接依赖||
|/usr/lib/libiconv.2.dylib||间接依赖||
|USER32.dll||间接依赖||
|/System/Library/Frameworks/CoreServices.framework/Versions/A/CoreServices||间接依赖||
|/usr/lib/libc++.1.dylib||间接依赖||
|api-ms-win-core-winrt-string-l1-1-0.dll||间接依赖||
|PSAPI.DLL||间接依赖||
|VERSION.dll||间接依赖||
|/System/Library/Frameworks/Foundation.framework/Versions/C/Foundation||间接依赖||
|/System/Library/Frameworks/Security.framework/Versions/A/Security||间接依赖||
|librt.so.1||间接依赖||
|/usr/lib/libresolv.9.dylib||间接依赖||
|/System/Library/Frameworks/Cocoa.framework/Versions/A/Cocoa||间接依赖||
|/usr/lib/libSystem.B.dylib||间接依赖||
|libm.so.6||间接依赖||
|ld-linux-x86-64.so.2||间接依赖||
|/usr/lib/libobjc.A.dylib||间接依赖||
|ADVAPI32.dll||间接依赖||
|/System/Library/Frameworks/ScriptingBridge.framework/Versions/A/ScriptingBridge||间接依赖||
|libc.so.6||间接依赖||
|libpthread.so.0||间接依赖||
|libX11||间接依赖||
|api-ms-win-core-winrt-error-l1-1-0.dll||间接依赖||
|libdl.so.2||间接依赖||
|api-ms-win-core-winrt-l1-1-0.dll||间接依赖||
|libstdc++.so.6||间接依赖||
|golang.org/x/sys|v0.0.0-20220715151400-c0bba94af5f8|间接依赖|go|
|dbghelp.dll||间接依赖||
|libgcc_s.so.1||间接依赖||
|msvcrt.dll||间接依赖||
|SHELL32.dll||间接依赖||


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)