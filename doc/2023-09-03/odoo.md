# odoo/odoo安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1698041842402721792.svg)](https://www.murphysec.com/console/report/1698041842364973056/1698041842402721792)

仓库描述：Odoo. Open Source Apps To Grow Your Business.

仓库地址：[https://github.com/odoo/odoo](https://github.com/odoo/odoo)

| star：30445 | watch：1502 | fork：19768 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-02 22:02:02 | 许可证：NOASSERTION |
| 最近检测时间：2023-09-03 02:38:05 | 组件总数：66 | 漏洞总数：10 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|OpenSSL 安全漏洞|加锁机制不恰当|[MPS-2022-64591](https://www.oscs1024.com/hd/MPS-2022-64591)|CVE-2022-3996|高危|
|OpenSSL 缓冲区错误漏洞|越界读取|[MPS-2022-65756](https://www.oscs1024.com/hd/MPS-2022-65756)|CVE-2022-4203|中危|
|OpenSSL 安全漏洞|通过差异性导致的信息暴露|[MPS-2022-66954](https://www.oscs1024.com/hd/MPS-2022-66954)|CVE-2022-4304|中危|
|OpenSSL 资源管理错误漏洞|双重释放|[MPS-2022-67892](https://www.oscs1024.com/hd/MPS-2022-67892)|CVE-2022-4450|高危|
|OpenSSL 资源管理错误漏洞|UAF|[MPS-2023-1276](https://www.oscs1024.com/hd/MPS-2023-1276)|CVE-2023-0215|高危|
|OpenSSL 代码问题漏洞|空指针取消引用|[MPS-2023-1277](https://www.oscs1024.com/hd/MPS-2023-1277)|CVE-2023-0216|高危|
|OpenSSL 代码问题漏洞|空指针取消引用|[MPS-2023-1278](https://www.oscs1024.com/hd/MPS-2023-1278)|CVE-2023-0217|高危|
|OpenSSL 代码问题漏洞|空指针取消引用|[MPS-2023-2153](https://www.oscs1024.com/hd/MPS-2023-2153)|CVE-2023-0401|高危|
|cryptography 代码问题漏洞|对因果或异常条件的不恰当检查|[MPS-2023-2194](https://www.oscs1024.com/hd/MPS-2023-2194)|CVE-2023-23931|中危|
|OpenSSL 安全漏洞|过度迭代|[MPS-n3pe-ljgc](https://www.oscs1024.com/hd/MPS-n3pe-ljgc)|CVE-2023-3817|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|cryptography|3.4.8|41.0.3|间接依赖|建议修复|C:0|H:6|M:4|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|18|Low|
|CDDL-1.0|1|Low|
|Libpng OR Zlib|1|Low|
|MIT|6|Low|
|Apache-2.0|2|Low|
|Apache-2.0 OR BSD-3-Clause|1|Low|
|LGPL-3.0|1|Medium|
|BSD-2-Clause|1|Low|
|BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|decorator|4.4.2|间接依赖|pip|
|ebaysdk|2.1.5|间接依赖|pip|
|pysmb|1.2.9.1|间接依赖|pip|
|dateutil||间接依赖|pip|
|chardet|4.0.0|间接依赖|pip|
|checkers||间接依赖|pip|
|get_modules||间接依赖|pip|
|pyserial|3.5|间接依赖|pip|
|cryptocode|0.1|间接依赖|pip|
|canceling||间接依赖|pip|
|PIPE||间接依赖|pip|
|b64decode||间接依赖|pip|
|ghostscript|0.7|间接依赖|pip|
|run||间接依赖|pip|
|PyKCS11|1.5.12|间接依赖|pip|
|get_extension||间接依赖|pip|
|get_module_path||间接依赖|pip|
|TransactionCase||间接依赖|pip|
|config||间接依赖|pip|
|pydot|1.4.2|间接依赖|pip|
|openerp||间接依赖|pip|
|python-stdnum|1.16|间接依赖|pip|
|idna|2.10|间接依赖|pip|
|call||间接依赖|pip|
|_||间接依赖|pip|
|format_date||间接依赖|pip|
|guess_mimetype||间接依赖|pip|
|python-dateutil|2.8.1|间接依赖|pip|
|common||间接依赖|pip|
|docutils|0.16|间接依赖|pip|
|api||间接依赖|pip|
|qrcode|6.1|间接依赖|pip|
|fields||间接依赖|pip|
|MissingError||间接依赖|pip|
|patch||间接依赖|pip|
|interfaces||间接依赖|pip|
|format_datetime||间接依赖|pip|
|odoo||间接依赖|pip|
|HttpCase||间接依赖|pip|
|Form||间接依赖|pip|
|vobject|0.9.6.1|间接依赖|pip|
|Request||间接依赖|pip|
|deque||间接依赖|pip|
|pyopenssl|20.0.1|间接依赖|pip|
|libsass|0.20.1|间接依赖|pip|
|UserError||间接依赖|pip|
|timedelta||间接依赖|pip|
|cryptography|3.4.8|间接依赖|pip|
|defaultdict||间接依赖|pip|
|netifaces|0.11.0|间接依赖|pip|
|polib|1.1.0|间接依赖|pip|
|mute_logger||间接依赖|pip|
|Command||间接依赖|pip|
|zeep|4.0.0|间接依赖|pip|
|psycopg2||间接依赖|pip|
|b64encode||间接依赖|pip|
|Response||间接依赖|pip|
|models||间接依赖|pip|
|werkzeug||间接依赖|pip|
|XlsxWriter|1.1.2|间接依赖|pip|
|freezegun||间接依赖|pip|
|main||间接依赖|pip|
|date||间接依赖|pip|
|lxml||间接依赖|pip|
|num2words|0.5.9|间接依赖|pip|
|tagged||间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)