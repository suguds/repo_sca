# openemr/openemr安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700938627752263680.svg)](https://www.murphysec.com/console/report/1700938627492216832/1700938627752263680)

仓库描述：The most popular open source electronic health records and medical practice management solution.

仓库地址：[https://github.com/openemr/openemr](https://github.com/openemr/openemr)

| star：2350 | watch：125 | fork：1779 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-10 05:08:15 | 许可证：GPL-3.0 |
| 最近检测时间：2023-09-11 02:28:04 | 组件总数：216 | 漏洞总数：12 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|jszip 原型污染漏洞|原型污染|[MPS-2021-11050](https://www.oscs1024.com/hd/MPS-2021-11050)|CVE-2021-23413|中危|
|angular  <=1.8.3 存在ReDoS漏洞|ReDoS|[MPS-2022-12542](https://www.oscs1024.com/hd/MPS-2022-12542)|CVE-2022-25844|中危|
|i18next 存在原型污染漏洞|原型污染|[MPS-2022-13771](https://www.oscs1024.com/hd/MPS-2022-13771)||高危|
|i18next 存在内存缓冲区边界内操作的限制不恰当漏洞|缓冲区溢出|[MPS-2022-13772](https://www.oscs1024.com/hd/MPS-2022-13772)||中危|
|i18next 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13773](https://www.oscs1024.com/hd/MPS-2022-13773)||中危|
|dompdf/dompdf 存在代码注入漏洞|代码注入|[MPS-2022-14193](https://www.oscs1024.com/hd/MPS-2022-14193)||高危|
|Angular 存在XSS漏洞|XSS|[MPS-2022-5154](https://www.oscs1024.com/hd/MPS-2022-5154)|CVE-2022-25869|中危|
|JSZip目录穿越漏洞|相对路径遍历|[MPS-2023-3073](https://www.oscs1024.com/hd/MPS-2023-3073)|CVE-2022-48285|高危|
|angular 安全漏洞|ReDoS|[MPS-2023-5110](https://www.oscs1024.com/hd/MPS-2023-5110)|CVE-2023-26117|中危|
|Angular 安全漏洞|ReDoS|[MPS-2023-5111](https://www.oscs1024.com/hd/MPS-2023-5111)|CVE-2023-26116|中危|
|Angular 安全漏洞|ReDoS|[MPS-2023-5112](https://www.oscs1024.com/hd/MPS-2023-5112)|CVE-2023-26118|中危|
|oauth2-server 安全漏洞|通过错误消息导致的信息暴露|[MPS-acjs-y501](https://www.oscs1024.com/hd/MPS-acjs-y501)|CVE-2023-37260|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|i18next|12.1.0|19.8.5|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|jszip|3.2.2|3.8.0|间接依赖|建议修复|C:0|H:1|M:1|L:0|
|league/oauth2-server|8.4.1|8.5.3|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|dompdf/dompdf|v2.0.3||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|angular|1.8.3||间接依赖|可选修复|C:0|H:0|M:5|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|GPL-3.0|2|Medium|
|MIT|139|Low|
|BSD-3-Clause|46|Low|
|BSD-2-Clause|1|Low|
|BSD-4-Clause|4|Low|
|Apache-2.0|7|Low|
|LGPL-2.1|4|Medium|
|CC0-1.0|1|Low|
|LGPL-2.0|3|Medium|
|LGPL-3.0|4|Medium|
|GPL-3.0-or-later|1|Low|
|ISC|1|Low|
|GPL-2.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|dwv|0.27.1|间接依赖|npm|
|symfony/dependency-injection|v5.4.21|间接依赖|composer|
|laminas/laminas-zendframework-bridge|1.7.0|间接依赖|composer|
|ramsey/collection|1.3.0|间接依赖|composer|
|angular|1.8.3|间接依赖|npm|
|core-util-is|1.0.3|间接依赖|npm|
|fflate|0.4.8|间接依赖|npm|
|sortablejs|1.15.0|间接依赖|npm|
|jquery-datetimepicker|2.5.21|间接依赖|npm|
|laminas/laminas-i18n|2.22.1|间接依赖|composer|
|laminas/laminas-hydrator|4.13.0|间接依赖|composer|
|moneyphp/money|v3.3.3|间接依赖|composer|
|paragonie/random_compat|v9.99.100|间接依赖|composer|
|datatables.net|1.13.4|间接依赖|npm|
|checklist-model|1.0.0|间接依赖|npm|
|symfony/property-access|v4.4.44|间接依赖|composer|
|i18next-browser-languagedetector|7.0.1|间接依赖|npm|
|interactjs|1.10.17|间接依赖|npm|
|dasprid/enum|1.0.4|间接依赖|composer|
|symfony/polyfill-intl-grapheme|v1.27.0|间接依赖|composer|
|string_decoder|1.1.1|间接依赖|npm|
|numeral|2.0.6|间接依赖|npm|
|php-http/client-implementation||间接依赖|composer|
|laminas/laminas-inputfilter|2.24.0|间接依赖|composer|
|laminas/laminas-modulemanager|2.14.0|间接依赖|composer|
|myclabs/deep-copy|1.11.1|间接依赖|composer|
|masterminds/html5|2.7.6|间接依赖|composer|
|psr/http-client|1.0.2|间接依赖|composer|
|datatables.net-scroller-jqui|2.1.1|间接依赖|npm|
|league/uri-interfaces|2.3.0|间接依赖|composer|
|nyholm/psr7-server|1.0.2|间接依赖|composer|
|laminas/laminas-config|3.8.0|间接依赖|composer|
|datatables.net-colreorder-dt|1.6.2|间接依赖|npm|
|symfony/polyfill-mbstring|v1.27.0|间接依赖|composer|
|defuse/php-encryption|v2.3.1|间接依赖|composer|
|knplabs/knp-snappy|v1.4.2|间接依赖|composer|
|league/uri|6.7.2|间接依赖|composer|
|datatables.net-dt|1.13.4|间接依赖|npm|
|ramsey/uuid|4.7.3|间接依赖|composer|
|laminas/laminas-soap|2.12.0|间接依赖|composer|
|markbaker/complex|3.0.2|间接依赖|composer|
|steverhoades/oauth2-openid-connect-server|v2.5.0|间接依赖|composer|
|datatables.net-bs4|1.13.4|间接依赖|npm|
|twig/twig|v3.5.1|间接依赖|composer|
|ckeditor4|4.20.2|间接依赖|npm|
|league/omnipay|v3.2.1|间接依赖|composer|
|setimmediate|1.0.5|间接依赖|npm|
|atob|2.1.2|间接依赖|npm|
|lie|3.3.0|间接依赖|npm|
|symfony/yaml|v5.4.21|间接依赖|composer|
|symfony/http-client-contracts|v2.5.2|间接依赖|composer|
|laminas/laminas-math|3.6.0|间接依赖|composer|
|@interactjs/types|1.10.17|间接依赖|npm|
|symfony/service-contracts|v2.5.2|间接依赖|composer|
|google/apiclient|v2.13.0|间接依赖|composer|
|laminas/laminas-view|2.27.0|间接依赖|composer|
|mobiledetect/mobiledetectlib|3.74.0|间接依赖|composer|
|symfony/event-dispatcher|v5.4.21|间接依赖|composer|
|process-nextick-args|2.0.1|间接依赖|npm|
|psr/http-factory|1.0.2|间接依赖|composer|
|symfony/http-client|v5.4.21|间接依赖|composer|
|lcobucci/clock|2.2.0|间接依赖|composer|
|phpmailer/phpmailer|v6.8.0|间接依赖|composer|
|academe/omnipay-authorizenetapi|3.1.2|间接依赖|composer|
|laminas/laminas-eventmanager|3.10.0|间接依赖|composer|
|laminas/laminas-form|3.8.0|间接依赖|composer|
|jszip|3.10.1|间接依赖|npm|
|jquery|3.6.4|间接依赖|npm|
|jquery-mousewheel|3.1.13|间接依赖|npm|
|symfony/polyfill-php80|v1.27.0|间接依赖|composer|
|laminas/laminas-stdlib|3.16.1|间接依赖|composer|
|digitickets/lalit|3.3.0|间接依赖|composer|
|brick/math|0.10.2|间接依赖|composer|
|bootstrap|4.6.2|间接依赖|npm|
|graham-campbell/result-type|v1.1.1|间接依赖|composer|
|monolog/monolog|2.9.1|间接依赖|composer|
|isarray|1.0.0|间接依赖|npm|
|symfony/deprecation-contracts|v2.5.2|间接依赖|composer|
|phpseclib/phpseclib|2.0.42|间接依赖|composer|
|chart.js|4.2.1|间接依赖|npm|
|datatables.net-scroller|2.1.1|间接依赖|npm|
|purecss|3.0.0|间接依赖|npm|
|firebase/php-jwt|v6.4.0|间接依赖|composer|
|pear/console_getopt|v1.4.3|间接依赖|composer|
|symfony/polyfill-php73|v1.27.0|间接依赖|composer|
|php-http/discovery|1.14.3|间接依赖|composer|
|laminas/laminas-router|3.11.1|间接依赖|composer|
|nyholm/psr7|1.5.1|间接依赖|composer|
|maennchen/zipstream-php|v2.4.0|间接依赖|composer|
|guzzlehttp/promises|1.5.2|间接依赖|composer|
|i18next-browser-languagedetector|3.0.3|间接依赖|npm|
|backbone|1.4.1|间接依赖|npm|
|webimpress/safe-writer|2.2.0|间接依赖|composer|
|ezyang/htmlpurifier|v4.16.0|间接依赖|composer|
|phpoption/phpoption|1.9.1|间接依赖|composer|
|symfony/polyfill-php81|v1.27.0|间接依赖|composer|
|@fortawesome/fontawesome-free|6.3.0|间接依赖|npm|
|twilio/sdk|6.44.3|间接依赖|composer|
|immediate|3.0.6|间接依赖|npm|
|pako|1.0.11|间接依赖|npm|
|jspdf|2.5.1|间接依赖|npm|
|symfony/event-dispatcher-contracts|v2.5.2|间接依赖|composer|
|symfony/filesystem|v5.4.21|间接依赖|composer|
|symfony/http-foundation|v5.4.21|间接依赖|composer|
|dropzone|5.9.3|间接依赖|npm|
|robthree/twofactorauth|1.8.2|间接依赖|composer|
|laminas/laminas-xmlrpc|2.15.0|间接依赖|composer|
|laminas/laminas-servicemanager|3.20.0|间接依赖|composer|
|league/oauth2-server|8.4.1|间接依赖|composer|
|psr/log|1.1.4|间接依赖|composer|
|google/apiclient-services|v0.296.0|间接依赖|composer|
|league/event|2.2.0|间接依赖|composer|
|@babel/runtime|7.21.0|间接依赖|npm|
|laminas/laminas-code|4.7.1|间接依赖|composer|
|i18next-xhr-backend|3.2.2|间接依赖|npm|
|symfony/console|v5.4.21|间接依赖|composer|
|waryway/php-traits-library|1.0.4|间接依赖|composer|
|psr/cache|3.0.0|间接依赖|composer|
|php-http/message|1.14.0|间接依赖|composer|
|php-http/httplug|2.4.0|间接依赖|composer|
|laminas/laminas-uri|2.10.0|间接依赖|composer|
|phenx/php-font-lib|0.5.4|间接依赖|composer|
|laminas/laminas-xml|1.5.0|间接依赖|composer|
|webmozart/assert|1.11.0|间接依赖|composer|
|vlucas/phpdotenv|v5.5.0|间接依赖|composer|
|util-deprecate|1.0.2|间接依赖|npm|
|guzzlehttp/psr7|2.5.0|间接依赖|composer|
|laminas/laminas-mvc-i18n|1.7.0|间接依赖|composer|
|html2text/html2text|4.3.1|间接依赖|composer|
|moment|2.29.4|间接依赖|npm|
|jquery-validation|1.19.5|间接依赖|npm|
|nikic/php-parser|v4.15.4|间接依赖|composer|
|knockout|3.5.1|间接依赖|npm|
|markbaker/matrix|3.0.1|间接依赖|composer|
|pear/pear-core-minimal|v1.10.11|间接依赖|composer|
|angular-sanitize|1.8.3|间接依赖|npm|
|symfony/string|v5.4.22|间接依赖|composer|
|psr/container|1.1.2|间接依赖|composer|
|guzzlehttp/guzzle|7.5.0|间接依赖|composer|
|dompdf/dompdf|v2.0.3|间接依赖|composer|
|ralouphie/getallheaders|3.0.3|间接依赖|composer|
|phpoffice/phpspreadsheet|1.28.0|间接依赖|composer|
|symfony/finder|v5.4.21|间接依赖|composer|
|set-immediate-shim|1.0.1|间接依赖|npm|
|laminas/laminas-db|2.17.0|间接依赖|composer|
|psr/clock|1.0.0|间接依赖|composer|
|konva|8.4.2|间接依赖|npm|
|regenerator-runtime|0.13.11|间接依赖|npm|
|myclabs/php-enum|1.8.4|间接依赖|composer|
|container-interop/container-interop||间接依赖|composer|
|laminas/laminas-server|2.15.0|间接依赖|composer|
|symfony/inflector|v5.4.21|间接依赖|composer|
|symfony/config|v5.4.21|间接依赖|composer|
|openemr/mustache|v2.15.2|间接依赖|composer|
|konva|2.6.0|间接依赖|npm|
|stella-maris/clock|0.1.7|间接依赖|composer|
|omnipay/stripe|v3.2.0|间接依赖|composer|
|bacon/bacon-qr-code|2.0.7|间接依赖|composer|
|datatables.net-jqui|1.13.4|间接依赖|npm|
|bootswatch|4.6.2|间接依赖|npm|
|php-http/promise|1.1.0|间接依赖|composer|
|symfony/process|v5.4.22|间接依赖|composer|
|yubico/u2flib-server|1.0.2|间接依赖|composer|
|i18next|22.4.11|间接依赖|npm|
|i18next-xhr-backend|2.0.1|间接依赖|npm|
|laminas/laminas-filter|2.31.0|间接依赖|composer|
|phenx/php-svg-lib|0.5.0|间接依赖|composer|
|php-http/message-factory|1.1.0|间接依赖|composer|
|validate.js|0.13.1|间接依赖|npm|
|psr/http-message|1.1|间接依赖|composer|
|aranyasen/hl7|3.0.0|间接依赖|composer|
|php-date-formatter|1.3.6|间接依赖|npm|
|laminas/laminas-json|3.5.0|间接依赖|composer|
|underscore|1.13.6|间接依赖|npm|
|@eastdesire/jscolor|2.5.1|间接依赖|npm|
|pear/pear_exception|v1.0.2|间接依赖|composer|
|psr/simple-cache|3.0.0|间接依赖|composer|
|pear/archive_tar|1.4.14|间接依赖|composer|
|datatables.net-colreorder|1.6.2|间接依赖|npm|
|@kurkle/color|0.3.2|间接依赖|npm|
|setasign/fpdi|v2.3.7|间接依赖|composer|
|btoa|1.2.1|间接依赖|npm|
|php-http/guzzle7-adapter|1.0.0|间接依赖|composer|
|google/auth|v1.26.0|间接依赖|composer|
|academe/authorizenet-objects|0.7.3|间接依赖|composer|
|laminas/laminas-escaper|2.12.0|间接依赖|composer|
|laminas/laminas-loader|2.9.0|间接依赖|composer|
|php81_bc/strftime|0.5.0|间接依赖|composer|
|lcobucci/jwt|4.2.1|间接依赖|composer|
|psr/event-dispatcher|1.0.0|间接依赖|composer|
|readable-stream|2.3.8|间接依赖|npm|
|safe-buffer|5.1.2|间接依赖|npm|
|adodb/adodb-php|v5.22.5|间接依赖|composer|
|hotkeys-js|3.10.1|间接依赖|npm|
|omnipay/common|v3.2.0|间接依赖|composer|
|smarty/smarty|v4.3.1|间接依赖|composer|
|rospdf/pdf-php|0.12.65|间接依赖|composer|
|laminas/laminas-validator|2.30.1|间接依赖|composer|
|inherits|2.0.4|间接依赖|npm|
|i18next|12.1.0|间接依赖|npm|
|stripe/stripe-php|v7.128.0|间接依赖|composer|
|flot|4.2.3|间接依赖|npm|
|particle/validator|v2.3.5|间接依赖|composer|
|kamermans/guzzle-oauth2-subscriber|v1.0.12|间接依赖|composer|
|symfony/polyfill-ctype|v1.27.0|间接依赖|composer|
|magic-wand-js|1.0.0|间接依赖|npm|
|clue/stream-filter|v1.6.0|间接依赖|composer|
|brick/varexporter|0.3.8|间接依赖|composer|
|select2|4.0.13|间接依赖|npm|
|sabberworm/php-css-parser|8.4.0|间接依赖|composer|
|mpdf/mpdf|v8.1.4|间接依赖|composer|
|laminas/laminas-mvc|3.6.0|间接依赖|composer|
|jszip|3.2.2|间接依赖|npm|
|laminas/laminas-http|2.18.0|间接依赖|composer|
|symfony/polyfill-intl-normalizer|v1.27.0|间接依赖|composer|
|laminas/laminas-json-server|3.7.0|间接依赖|composer|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)