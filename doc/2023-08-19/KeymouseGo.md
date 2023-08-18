# taojy123/KeymouseGo安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692601439954427904.svg)](https://www.murphysec.com/console/report/1692601336649895936/1692601439954427904)

仓库描述：类似按键精灵的鼠标键盘录制和自动化操作 模拟点击和键入 | automate mouse clicks and keyboard input

仓库地址：[https://github.com/taojy123/KeymouseGo](https://github.com/taojy123/KeymouseGo)

| star：4098 | watch：45 | fork：686 |
| ----------- | -------------- | ------------ |
| 所有者：User | 更新时间：2023-06-15 21:31:58 | 许可证：GPL-2.0 |
| 最近检测时间：2023-08-19 02:16:56 | 组件总数：22 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|loguru 代码注入漏洞|代码注入|[MPS-2022-1393](https://www.oscs1024.com/hd/MPS-2022-1393)|CVE-2022-0329|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|loguru|0.6.0||间接依赖|建议修复|C:1|H:0|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|4|Low|
|自定义许可证|2|Low|
|BSD-2-Clause|1|Low|
|LGPL-3.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|mouse||间接依赖|pip|
|keyboard||间接依赖|pip|
|loguru|0.6.0|间接依赖|pip|
|QObject||间接依赖|pip|
|cpyHook||间接依赖|pip|
|abstractmethod||间接依赖|pip|
|pyperclip|1.8.0|间接依赖|pip|
|QFileDialog||间接依赖|pip|
|QDialog||间接依赖|pip|
|UIFunc||间接依赖|pip|
|QApplication||间接依赖|pip|
|pyautogui|0.9.53|间接依赖|pip|
|QWidget||间接依赖|pip|
|qt-material|2.11|间接依赖|pip|
|pywin32|302|间接依赖|pip|
|HookConstants||间接依赖|pip|
|pynput|1.7.6|间接依赖|pip|
|ABCMeta||间接依赖|pip|
|pyWinhook|1.6.2|间接依赖|pip|
|future|0.18.3|间接依赖|pip|
|Signal||间接依赖|pip|
|PySide6|6.4.3|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)