# dromara/hutool安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1700571624897298432.svg)](https://www.murphysec.com/console/report/1700571623693533184/1700571624897298432)

仓库描述：🍬A set of tools that keep Java sweet.

仓库地址：[https://github.com/dromara/hutool](https://github.com/dromara/hutool)

| star：27015 | watch：607 | fork：7265 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-08 23:25:03 | 许可证：NOASSERTION |
| 最近检测时间：2023-09-10 02:11:26 | 组件总数：228 | 漏洞总数：43 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Guava 不可信数据的反序列化漏洞|不加限制或调节的资源分配|[MPS-2018-5515](https://www.oscs1024.com/hd/MPS-2018-5515)|CVE-2018-10237|中危|
|Apache Log4j SocketServer反序列化漏洞|反序列化|[MPS-2019-17271](https://www.oscs1024.com/hd/MPS-2019-17271)|CVE-2019-17571|严重|
|Google Guava 访问控制错误漏洞|关键资源权限分配不当|[MPS-2020-17429](https://www.oscs1024.com/hd/MPS-2020-17429)|CVE-2020-8908|低危|
|Apache Log4j2 SmtpAppender证书验证不当漏洞|证书验证不恰当|[MPS-2020-6684](https://www.oscs1024.com/hd/MPS-2020-6684)|CVE-2020-9488|低危|
|Apache Commons Compress 安存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10550](https://www.oscs1024.com/hd/MPS-2021-10550)|CVE-2021-35517|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10551](https://www.oscs1024.com/hd/MPS-2021-10551)|CVE-2021-35516|高危|
|Apache Commons Compress 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2021-10564](https://www.oscs1024.com/hd/MPS-2021-10564)|CVE-2021-36090|高危|
|Apache Commons Compress 无限循环漏洞|不可达退出条件的循环（无限循环）|[MPS-2021-10565](https://www.oscs1024.com/hd/MPS-2021-10565)|CVE-2021-35515|高危|
|JetBrains Kotlin <1.4.21 不正确的默认权限漏洞|缺省权限不正确|[MPS-2021-1082](https://www.oscs1024.com/hd/MPS-2021-1082)|CVE-2020-29582|中危|
|TwelveMonkeys ImageIO 3.7.1 XML 外部实体 注入漏洞|XXE|[MPS-2021-19831](https://www.oscs1024.com/hd/MPS-2021-19831)|CVE-2021-23792|严重|
|iText < 7.1.17存在命令注入漏洞|命令注入|[MPS-2021-34409](https://www.oscs1024.com/hd/MPS-2021-34409)|CVE-2021-43113|严重|
|Apache Log4j2 JDBC Appender远程代码执行漏洞|代码注入|[MPS-2021-38327](https://www.oscs1024.com/hd/MPS-2021-38327)|CVE-2021-44832|中危|
|Apache Log4j JMSAppender反序列化漏洞||[MPS-2021-38359](https://www.oscs1024.com/hd/MPS-2021-38359)|CVE-2021-4104|高危|
|Apache Log4j2 自引用拒绝服务漏洞|未经控制的递归|[MPS-2021-38752](https://www.oscs1024.com/hd/MPS-2021-38752)|CVE-2021-45105|中危|
|com.google.code.gson:gson 存在BigDecimal拒绝服务漏洞|反序列化|[MPS-2022-12287](https://www.oscs1024.com/hd/MPS-2022-12287)|CVE-2022-25647|高危|
|org.json:json 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13520](https://www.oscs1024.com/hd/MPS-2022-13520)||高危|
|Apache Log4j JDBCAppender SQL注入漏洞|SQL注入|[MPS-2022-1444](https://www.oscs1024.com/hd/MPS-2022-1444)|CVE-2022-23305|严重|
|Apache Log4j Chainsaw反序列化漏洞|反序列化|[MPS-2022-1445](https://www.oscs1024.com/hd/MPS-2022-1445)|CVE-2022-23307|高危|
|Apache Log4j 反序列化漏洞|反序列化|[MPS-2022-1446](https://www.oscs1024.com/hd/MPS-2022-1446)|CVE-2022-23302|高危|
|Apache Xalan 存在整数截断漏洞|数值截断错误|[MPS-2022-19461](https://www.oscs1024.com/hd/MPS-2022-19461)|CVE-2022-34169|中危|
|itextpdf < 7.2.2存在拒绝服务漏洞|越界写入|[MPS-2022-2944](https://www.oscs1024.com/hd/MPS-2022-2944)|CVE-2022-24197|中危|
|itextpdf < 7.2.4 存在拒绝服务漏洞|越界读取|[MPS-2022-2945](https://www.oscs1024.com/hd/MPS-2022-2945)|CVE-2022-24198|中危|
|itextpdf 存在拒绝服务漏洞|不加限制或调节的资源分配|[MPS-2022-2947](https://www.oscs1024.com/hd/MPS-2022-2947)|CVE-2022-24196|中危|
|JetBrains Kotlin <1.6.0 存在锁定不当漏洞|加锁机制不恰当|[MPS-2022-3233](https://www.oscs1024.com/hd/MPS-2022-3233)|CVE-2022-24329|中危|
|snakeYAML <1.31 存在拒绝服务漏洞|拒绝服务|[MPS-2022-5144](https://www.oscs1024.com/hd/MPS-2022-5144)|CVE-2022-25857|高危|
|Bouncy Castle <1.69 认证绕过漏洞|密码学问题|[MPS-2022-54305](https://www.oscs1024.com/hd/MPS-2022-54305)||中危|
|Apache Batik 信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-55649](https://www.oscs1024.com/hd/MPS-2022-55649)|CVE-2022-38398|中危|
|Apache Batik 存在 SSRF 漏洞|未授权敏感信息泄露|[MPS-2022-55890](https://www.oscs1024.com/hd/MPS-2022-55890)|CVE-2022-38648|中危|
|snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56040](https://www.oscs1024.com/hd/MPS-2022-56040)|CVE-2022-38751|中危|
|snakeYAML <1.32 存在基于堆栈的缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-56041](https://www.oscs1024.com/hd/MPS-2022-56041)|CVE-2022-38752|低危|
|snakeYAML <1.31 存在拒绝服务漏洞|栈缓冲区溢出|[MPS-2022-56051](https://www.oscs1024.com/hd/MPS-2022-56051)|CVE-2022-38750|中危|
| snakeYAML <1.31 存在基于堆栈的缓冲区溢出漏洞|拒绝服务|[MPS-2022-56081](https://www.oscs1024.com/hd/MPS-2022-56081)|CVE-2022-38749|中危|
|Apache Batik  DefaultScriptSecurity 函数存在 SSRF 漏洞|未授权敏感信息泄露|[MPS-2022-57733](https://www.oscs1024.com/hd/MPS-2022-57733)|CVE-2022-40146|中危|
|SnakeYAML <1.32 存在缓冲区溢出漏洞|栈缓冲区溢出|[MPS-2022-58478](https://www.oscs1024.com/hd/MPS-2022-58478)|CVE-2022-41854|中危|
|Apache Batik visibleToScripts 信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-59716](https://www.oscs1024.com/hd/MPS-2022-59716)|CVE-2022-42890|中危|
|Spring Expression 存在拒绝服务漏洞|拒绝服务|[MPS-2022-62835](https://www.oscs1024.com/hd/MPS-2022-62835)|CVE-2023-20863|高危|
|Spring Boot 欢迎页功能拒绝服务风险|拒绝服务|[MPS-2022-62855](https://www.oscs1024.com/hd/MPS-2022-62855)|CVE-2023-20883|高危|
|Apache XML Graphics Batik<1.17 存在SSRF漏洞|SSRF|[MPS-2022-63578](https://www.oscs1024.com/hd/MPS-2022-63578)|CVE-2022-44729|中危|
|Apache XML Graphics Batik 代码问题漏洞|SSRF|[MPS-2022-63579](https://www.oscs1024.com/hd/MPS-2022-63579)|CVE-2022-44730|中危|
|snakeYAML <2.0 存在反序列化漏洞|反序列化|[MPS-2022-9425](https://www.oscs1024.com/hd/MPS-2022-9425)|CVE-2022-1471|高危|
|Bouncy Castle 信任管理问题漏洞|证书验证不恰当|[MPS-i6w7-d48e](https://www.oscs1024.com/hd/MPS-i6w7-d48e)|CVE-2023-33201|中危|
|Guava<32.0.0 存在竞争条件漏洞|创建拥有不安全权限的临时文件|[MPS-mfku-xzh3](https://www.oscs1024.com/hd/MPS-mfku-xzh3)|CVE-2023-2976|中危|
|QLEpress<=3.3.1 任意代码执行漏洞|不完整的黑名单|[MPS-nsqf-18wp](https://www.oscs1024.com/hd/MPS-nsqf-18wp)||严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|org.apache.xmlgraphics:batik-transcoder|1.14|1.17|间接依赖|强烈建议修复|C:0|H:0|M:1|L:0|
|org.apache.xmlgraphics:batik-bridge|1.14|1.17|间接依赖|强烈建议修复|C:0|H:0|M:4|L:0|
|com.itextpdf:io|7.1.13|7.2.2|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|org.apache.logging.log4j:log4j-core|2.16.0|2.17.1|间接依赖|建议修复|C:0|H:0|M:2|L:0|
|xalan:xalan|2.7.2||间接依赖|建议修复|C:0|H:0|M:1|L:0|
|org.apache.commons:commons-compress|1.19|1.21|间接依赖|建议修复|C:0|H:4|M:0|L:0|
|org.yaml:snakeyaml|1.30|2.0|间接依赖|建议修复|C:0|H:2|M:4|L:1|
|com.alibaba:QLExpress|3.3.1||直接依赖|建议修复|C:1|H:0|M:0|L:0|
|log4j:log4j|1.2.17||直接依赖|建议修复|C:2|H:3|M:0|L:1|
|com.twelvemonkeys.imageio:imageio-metadata|3.5|3.7.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|org.springframework.boot:spring-boot-autoconfigure|2.7.10|3.0.7|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.guava:guava|19.0|32.0.0-jre|间接依赖|可选修复|C:0|H:0|M:2|L:1|
|org.springframework:spring-expression|5.3.26|6.0.8|直接依赖|可选修复|C:0|H:1|M:0|L:0|
|org.jetbrains.kotlin:kotlin-stdlib|1.3.50|1.6.0|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.json:json|20170516|20180130|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.google.code.gson:gson|2.8.5|2.8.9|间接依赖|可选修复|C:0|H:1|M:0|L:0|
|com.itextpdf:kernel|7.1.13|7.2.4|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.apache.xmlgraphics:batik-script|1.14|1.17|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.bouncycastle:bcprov-jdk15on|1.68|1.69|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|org.bouncycastle:bcprov-jdk15on|1.70||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|org.json:json|20141113|20180130|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|JSON|3|Low|
|Apache-2.0|146|Low|
|AGPL-3.0|5|High|
|MIT|7|Low|
|自定义许可证|56|Low|
|GPL-3.0|2|Medium|
|EPL-1.0|6|Low|
|BSD-3-Clause|1|Low|
|MPL-2.0|1|Low|
|LGPL-2.1|3|Medium|
|LGPL-3.0|1|Medium|
|MPL-1.1|1|Low|
|EPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|org.json:json|20220320|间接依赖|maven|
|org.apache.xmlbeans:xmlbeans|3.1.0|间接依赖|maven|
|org.mongodb:mongodb-driver-core|4.9.1|间接依赖|maven|
|org.ofdrw:ofdrw-core|2.0.5|间接依赖|maven|
|commons-lang:commons-lang|2.4|间接依赖|maven|
|com.itextpdf:kernel|7.1.13|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.30|间接依赖|maven|
|org.apache.xmlgraphics:batik-parser|1.14|间接依赖|maven|
|org.nlpcn:nlp-lang|1.7.7|间接依赖|maven|
|com.ibeetl:beetl-default-antlr4.9-support|3.15.3.RELEASE|间接依赖|maven|
|com.googlecode.aviator:aviator|5.3.3|直接依赖|maven|
|org.rythmengine:rythm-engine|1.4.2|直接依赖|maven|
|com.mayabot.mynlp.resource:mynlp-resource-coredict|1.0.0|间接依赖|maven|
|javax.activation:activation|1.1|间接依赖|maven|
|com.jcraft:jsch|0.1.55|直接依赖|maven|
|org.ofdrw:ofdrw-sign|2.0.5|间接依赖|maven|
|com.twelvemonkeys.common:common-image|3.5|间接依赖|maven|
|cn.hutool:hutool-captcha|5.8.21|直接依赖|maven|
|com.github.stuxuhai:jpinyin|1.1.8|直接依赖|maven|
|net.i2p.crypto:eddsa|0.3.0|间接依赖|maven|
|com.github.chris2018998:beecp|3.4.1|直接依赖|maven|
|org.jboss.logging:jboss-logging|3.4.3.Final|直接依赖|maven|
|org.hamcrest:hamcrest-junit|2.0.0.0|间接依赖|maven|
|com.github.subchen:jetbrick-template|2.1.10|直接依赖|maven|
|ch.ethz.ganymed:ganymed-ssh2|262|直接依赖|maven|
|com.ibeetl:beetl-ext|3.15.3.RELEASE|间接依赖|maven|
|cn.hutool:hutool-aop|5.8.21|直接依赖|maven|
|org.ofdrw:ofdrw-gm|2.0.5|间接依赖|maven|
|org.ofdrw:ofdrw-layout|2.0.5|间接依赖|maven|
|org.apache.pdfbox:jbig2-imageio|3.0.3|间接依赖|maven|
|org.ansj:ansj_seg|5.1.6|直接依赖|maven|
|org.apache.lucene:lucene-suggest|4.10.4|间接依赖|maven|
|com.hierynomus:sshj|0.35.0|直接依赖|maven|
|org.mozilla:rhino|1.7.14|直接依赖|maven|
|org.slf4j:jul-to-slf4j|1.7.36|间接依赖|maven|
|com.jfinal:enjoy|5.0.3|直接依赖|maven|
|com.hierynomus:asn-one|0.6.0|间接依赖|maven|
|org.dom4j:dom4j|2.1.3|间接依赖|maven|
|org.apache.mina:mina-core|2.1.6|间接依赖|maven|
|org.apache.xmlgraphics:batik-ext|1.14|间接依赖|maven|
|cn.hutool:hutool-extra|5.8.21|直接依赖|maven|
|com.mayabot.mynlp.resource:mynlp-resource-ner|1.0.0|间接依赖|maven|
|com.jfirer:jfireEl|1.0|直接依赖|maven|
|org.bouncycastle:bcutil-jdk18on|1.75|间接依赖|maven|
|com.sun.mail:javax.mail|1.6.2|直接依赖|maven|
|org.apache.xmlgraphics:batik-svg-dom|1.14|间接依赖|maven|
|org.febit.wit:wit-core|2.6.0|直接依赖|maven|
|cn.hutool:hutool-bloomFilter|5.8.21|直接依赖|maven|
|cn.hutool:hutool-system|5.8.21|直接依赖|maven|
|org.mongodb:mongodb-driver-sync|4.9.1|直接依赖|maven|
|com.twelvemonkeys.imageio:imageio-core|3.5|间接依赖|maven|
|com.jfirer:baseutil|1.0|间接依赖|maven|
|org.apache.ftpserver:ftpserver-core|1.2.0|直接依赖|maven|
|org.hamcrest:java-hamcrest|2.0.0.0|间接依赖|maven|
|org.apache.commons:commons-compress|1.22|直接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.70|间接依赖|maven|
|org.antlr:antlr4-runtime|4.9.3|间接依赖|maven|
|org.ofdrw:ofdrw-converter|2.0.5|间接依赖|maven|
|xalan:serializer|2.7.2|间接依赖|maven|
|com.alibaba:fastjson|1.2.83|间接依赖|maven|
|org.ujmp:ujmp-core|0.3.0|间接依赖|maven|
|com.zaxxer:SparseBitSet|1.2|间接依赖|maven|
|cn.hutool:hutool-json|5.8.21|直接依赖|maven|
|com.huaban:jieba-analysis|1.0.2|直接依赖|maven|
|ch.qos.logback:logback-core|1.4.6|间接依赖|maven|
|org.bouncycastle:bcpkix-jdk18on|1.75|直接依赖|maven|
|com.github.houbb:pinyin|0.3.1|直接依赖|maven|
|org.ofdrw:ofdrw-full|2.0.5|直接依赖|maven|
|org.lionsoul:jcseg-core|2.6.3|直接依赖|maven|
|org.springframework:spring-expression|5.3.26|直接依赖|maven|
|cn.hutool:hutool-jwt|5.8.21|直接依赖|maven|
|org.springframework:spring-beans|5.3.26|间接依赖|maven|
|org.ofdrw:ofdrw-gv|2.0.5|间接依赖|maven|
|org.apache.poi:poi|4.1.2|间接依赖|maven|
|org.tinylog:tinylog|1.3.6|直接依赖|maven|
|org.apdplat:word|1.3.1|直接依赖|maven|
|org.springframework:spring-aop|5.3.26|间接依赖|maven|
|org.apache.poi:poi-ooxml-schemas|4.1.2|间接依赖|maven|
|com.mayabot.mynlp.resource:mynlp-resource-pos|1.0.0|间接依赖|maven|
|ch.qos.logback:logback-classic|1.4.6|直接依赖|maven|
|org.freemarker:freemarker|2.3.32|直接依赖|maven|
|org.springframework:spring-jcl|5.3.27|间接依赖|maven|
|com.vdurmont:emoji-java|5.1.1|直接依赖|maven|
|com.google.guava:guava|19.0|间接依赖|maven|
|com.twelvemonkeys.imageio:imageio-metadata|3.5|间接依赖|maven|
|org.apache.lucene:lucene-analyzers-common|8.11.2|间接依赖|maven|
|ognl:ognl|3.3.4|间接依赖|maven|
|org.slf4j:slf4j-api|1.7.36|直接依赖|maven|
|org.apache.ftpserver:ftplet-api|1.2.0|间接依赖|maven|
|com.google.code.gson:gson|2.8.5|间接依赖|maven|
|org.apache.commons:commons-math3|3.6.1|间接依赖|maven|
|commons-io:commons-io|2.11.0|间接依赖|maven|
|org.springframework.boot:spring-boot-starter-logging|2.7.10|间接依赖|maven|
|com.github.subchen:jetbrick-commons|2.1.9|间接依赖|maven|
|com.mayabot.mynlp:mynlp-core|3.0.2|间接依赖|maven|
|org.apache.logging.log4j:log4j-to-slf4j|2.17.2|间接依赖|maven|
|org.apache.xmlgraphics:batik-script|1.14|间接依赖|maven|
|org.apache.xmlgraphics:batik-gvt|1.14|间接依赖|maven|
|org.jetbrains:annotations|21.0.1|间接依赖|maven|
|cn.hutool:hutool-cache|5.8.21|直接依赖|maven|
|com.twelvemonkeys.imageio:imageio-tiff|3.5|间接依赖|maven|
|org.springframework:spring-jcl|5.3.26|间接依赖|maven|
|com.mchange:c3p0|0.9.5.5|直接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.20.0|直接依赖|maven|
|com.twelvemonkeys.common:common-io|3.5|间接依赖|maven|
|org.springframework.boot:spring-boot-starter|2.7.10|直接依赖|maven|
|org.apache.xmlgraphics:batik-dom|1.14|间接依赖|maven|
|cn.hutool:hutool-cron|5.8.21|直接依赖|maven|
|com.mchange:mchange-commons-java|0.2.19|间接依赖|maven|
|org.apache.pdfbox:fontbox|2.0.27|间接依赖|maven|
|org.ow2.asm:asm|7.1|间接依赖|maven|
|com.chenlb.mmseg4j:mmseg4j-core|1.10.0|直接依赖|maven|
|org.bouncycastle:bcpkix-jdk15on|1.68|间接依赖|maven|
|org.apache.commons:commons-dbcp2|2.9.0|直接依赖|maven|
|jaxen:jaxen|1.2.0|间接依赖|maven|
|com.rnkrsoft.bopomofo4j:bopomofo4j|1.0.0|直接依赖|maven|
|org.apache.xmlgraphics:xmlgraphics-commons|2.6|间接依赖|maven|
|org.apache.commons:commons-collections4|4.4|间接依赖|maven|
|com.janeluo:ikanalyzer|2012_u6|直接依赖|maven|
|xml-apis:xml-apis|1.4.01|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.68|间接依赖|maven|
|com.google.zxing:core|3.5.1|直接依赖|maven|
|log4j:log4j|1.2.17|直接依赖|maven|
|org.slf4j:slf4j-api|1.7.25|间接依赖|maven|
|org.json:json|20141113|间接依赖|maven|
|org.apache.tomcat:tomcat-jdbc|10.0.23|直接依赖|maven|
|com.github.virtuald:curvesapi|1.06|间接依赖|maven|
|org.apache.pdfbox:pdfbox|2.0.27|间接依赖|maven|
|org.springframework:spring-core|5.3.27|直接依赖|maven|
|cglib:cglib|3.3.0|直接依赖|maven|
|org.ofdrw:ofdrw-font|2.0.5|间接依赖|maven|
|org.ofdrw:ofdrw-pkg|2.0.5|间接依赖|maven|
|org.osgl:osgl-ut|2.0.0-BETA-4-JAVA7|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.17.2|间接依赖|maven|
|cn.hutool:hutool-db|5.8.21|直接依赖|maven|
|org.jetbrains:annotations|13.0|间接依赖|maven|
|com.itextpdf:layout|7.1.13|间接依赖|maven|
|org.apache.lucene:lucene-misc|4.10.4|间接依赖|maven|
|org.springframework:spring-context|5.3.26|间接依赖|maven|
|com.mayabot.mynlp:mynlp-segment|3.0.2|直接依赖|maven|
|org.apache.poi:poi-ooxml|4.1.2|直接依赖|maven|
|org.apache.logging.log4j:log4j-slf4j-impl|2.16.0|间接依赖|maven|
|org.ahocorasick:ahocorasick|0.4.0|间接依赖|maven|
|com.stevesoft.pat:pat|1.5.3|间接依赖|maven|
|org.apache.xmlgraphics:batik-shared-resources|1.14|间接依赖|maven|
|org.apache.logging.log4j:log4j-api|2.16.0|间接依赖|maven|
|org.apache.xmlgraphics:batik-svggen|1.14|间接依赖|maven|
|org.osgl:osgl-version|2.0.0-BETA-4-JAVA7|间接依赖|maven|
|cn.hutool:hutool-crypto|5.8.21|直接依赖|maven|
|org.apache.xmlgraphics:batik-xml|1.14|间接依赖|maven|
|org.unbescape:unbescape|1.1.6.RELEASE|间接依赖|maven|
|org.json:json|20170516|间接依赖|maven|
|cn.hutool:hutool-dfa|5.8.21|直接依赖|maven|
|org.apache.lucene:lucene-core|8.11.2|间接依赖|maven|
|org.apache.xmlgraphics:batik-i18n|1.14|间接依赖|maven|
|commons-io:commons-io|2.8.0|间接依赖|maven|
|com.itextpdf:io|7.1.13|间接依赖|maven|
|org.bouncycastle:bcprov-jdk18on|1.75|间接依赖|maven|
|cn.hutool:hutool-setting|5.8.21|直接依赖|maven|
|org.apache.xmlgraphics:batik-constants|1.14|间接依赖|maven|
|org.apache.logging.log4j:log4j-core|2.16.0|间接依赖|maven|
|io.github.logtube:logtube|0.45.0|直接依赖|maven|
|org.apache.lucene:lucene-analyzers-smartcn|8.11.2|直接依赖|maven|
|org.apache.xmlgraphics:batik-transcoder|1.14|间接依赖|maven|
|com.itextpdf:font-asian|7.1.13|间接依赖|maven|
|cn.hutool:hutool-http|5.8.21|直接依赖|maven|
|com.google.code.gson:gson|2.8.9|间接依赖|maven|
|redis.clients:jedis|4.3.1|直接依赖|maven|
|com.github.houbb:heaven|0.1.154|间接依赖|maven|
|org.apache.velocity:velocity-engine-core|2.3|直接依赖|maven|
|commons-logging:commons-logging|1.2|直接依赖|maven|
|io.github.biezhi:TinyPinyin|2.0.3.RELEASE|直接依赖|maven|
|org.apache.commons:commons-lang3|3.11|间接依赖|maven|
|com.jcraft:jzlib|1.1.3|间接依赖|maven|
|commons-net:commons-net|3.9.0|直接依赖|maven|
|commons-codec:commons-codec|1.13|间接依赖|maven|
|com.hankcs:hanlp|portable-1.8.4|直接依赖|maven|
|org.apache.xmlgraphics:batik-util|1.14|间接依赖|maven|
|com.github.houbb:nlp-common|0.0.3|间接依赖|maven|
|org.mongodb:bson|4.9.1|间接依赖|maven|
|org.apache.commons:commons-compress|1.19|间接依赖|maven|
|org.springframework.boot:spring-boot|2.7.10|间接依赖|maven|
|cn.hutool:hutool-socket|5.8.21|直接依赖|maven|
|org.javassist:javassist|3.29.0-GA|间接依赖|maven|
|com.zaxxer:HikariCP|4.0.3|直接依赖|maven|
|org.ofdrw:ofdrw-tool|2.0.5|间接依赖|maven|
|org.yaml:snakeyaml|2.0|直接依赖|maven|
|org.springframework.boot:spring-boot-autoconfigure|2.7.10|间接依赖|maven|
|org.apache.tomcat:tomcat-juli|10.0.23|间接依赖|maven|
|com.twelvemonkeys.common:common-lang|3.5|间接依赖|maven|
|jakarta.validation:jakarta.validation-api|3.0.2|直接依赖|maven|
|org.thymeleaf:thymeleaf|3.1.1.RELEASE|直接依赖|maven|
|org.ofdrw:ofdrw-graphics2d|2.0.5|间接依赖|maven|
|org.apache.commons:commons-pool2|2.11.1|间接依赖|maven|
|com.mayabot.mynlp:mynlp-perceptron|3.0.2|间接依赖|maven|
|cn.hutool:hutool-log|5.8.21|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib-common|1.3.50|间接依赖|maven|
|org.apache.xmlgraphics:batik-awt-util|1.14|间接依赖|maven|
|net.lingala.zip4j:zip4j|2.11.3|间接依赖|maven|
|org.apache.xmlgraphics:batik-bridge|1.14|间接依赖|maven|
|org.eclipse.jdt.core.compiler:ecj|4.6.1|间接依赖|maven|
|org.bouncycastle:bcprov-jdk15on|1.70|间接依赖|maven|
|org.yaml:snakeyaml|1.30|间接依赖|maven|
|org.apache.commons:commons-jexl3|3.2.1|直接依赖|maven|
|org.mvel:mvel2|2.4.14.Final|直接依赖|maven|
|com.ibeetl:beetl-core|3.15.3.RELEASE|间接依赖|maven|
|xalan:xalan|2.7.2|间接依赖|maven|
|cn.hutool:hutool-core|5.8.21|直接依赖|maven|
|org.ofdrw:ofdrw-reader|2.0.5|间接依赖|maven|
|com.belerweb:pinyin4j|2.5.1|直接依赖|maven|
|cn.hutool:hutool-poi|5.8.21|直接依赖|maven|
|org.mongodb:bson-record-codec|4.9.1|间接依赖|maven|
|org.apache.xmlgraphics:batik-anim|1.14|间接依赖|maven|
|com.alibaba:QLExpress|3.3.1|直接依赖|maven|
|org.apache.lucene:lucene-queryparser|4.10.4|间接依赖|maven|
|org.apache.lucene:lucene-queries|4.10.4|间接依赖|maven|
|org.bouncycastle:bcutil-jdk15on|1.70|间接依赖|maven|
|cn.hutool:hutool-script|5.8.21|直接依赖|maven|
|xml-apis:xml-apis-ext|1.3.04|间接依赖|maven|
|com.alibaba:druid|1.2.16|直接依赖|maven|
|org.jetbrains.kotlin:kotlin-stdlib|1.3.50|间接依赖|maven|
|com.ibeetl:beetl|3.15.3.RELEASE|直接依赖|maven|
|org.apache.lucene:lucene-sandbox|4.10.4|间接依赖|maven|
|org.springframework:spring-core|5.3.26|间接依赖|maven|
|org.apache.xmlgraphics:batik-css|1.14|间接依赖|maven|
|org.tinylog:tinylog-api|2.6.1|直接依赖|maven|
|org.attoparser:attoparser|2.0.6.RELEASE|间接依赖|maven|
|jakarta.annotation:jakarta.annotation-api|1.3.5|间接依赖|maven|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)