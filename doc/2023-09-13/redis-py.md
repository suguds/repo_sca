# redis/redis-py安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1701662073154224128.svg)](https://www.murphysec.com/console/report/1701662072919343104/1701662073154224128)

仓库描述：Redis Python Client

仓库地址：[https://github.com/redis/redis-py](https://github.com/redis/redis-py)

| star：11736 | watch：324 | fork：2431 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-12 20:18:08 | 许可证：MIT |
| 最近检测时间：2023-09-13 02:20:39 | 组件总数：94 | 漏洞总数：6 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|UltraJSON 安全漏洞|越界写入|[MPS-2021-40089](https://www.oscs1024.com/hd/MPS-2021-40089)|CVE-2021-45958|中危|
|UltraJSON 安全漏洞|控制流实现总是不正确|[MPS-2022-11146](https://www.oscs1024.com/hd/MPS-2022-11146)|CVE-2022-31116|高危|
|UltraJSON 资源管理错误漏洞|双重释放|[MPS-2022-11147](https://www.oscs1024.com/hd/MPS-2022-11147)|CVE-2022-31117|中危|
|Python 安全漏洞|ReDoS|[MPS-2022-57239](https://www.oscs1024.com/hd/MPS-2022-57239)|CVE-2022-40898|高危|
|redis-py 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2023-8854](https://www.oscs1024.com/hd/MPS-2023-8854)|CVE-2023-28858|中危|
|redis-py 存在信息泄露漏洞|未授权敏感信息泄露|[MPS-2023-8855](https://www.oscs1024.com/hd/MPS-2023-8855)|CVE-2023-28859|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|ujson|4.2.0|5.4.0|间接依赖|建议修复|C:0|H:1|M:2|L:0|
|redis|4.3.4|4.5.3|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|wheel|0.30.0|0.38.0|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|9|Low|
|MIT|10|Low|
|BSD-3-Clause|1|Low|
|Apache-2.0|2|Low|
|GPL-3.0-or-later|2|Low|
|GPL-2.0|1|Medium|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|opentelemetry-instrumentation-redis|0.35b0|间接依赖|pip|
|IndexType||间接依赖|pip|
|packaging|20.4|间接依赖|pip|
|Tuple||间接依赖|pip|
|uptrace|1.14.0|间接依赖|pip|
|mock|4.0.3|间接依赖|pip|
|node||间接依赖|pip|
|LifoQueue||间接依赖|pip|
|AsyncIterator||间接依赖|pip|
|Node||间接依赖|pip|
|random_string||间接依赖|pip|
|pytest-timeout|2.1.0|间接依赖|pip|
|urljoin||间接依赖|pip|
|docutils|0.18|间接依赖|pip|
|TimeoutError||间接依赖|pip|
|LockNotOwnedError||间接依赖|pip|
|StrictRedis||间接依赖|pip|
|IncompleteReadError||间接依赖|pip|
|NumericField||间接依赖|pip|
|Redis||间接依赖|pip|
|skip_if_server_version_lt||间接依赖|pip|
|ConnectionPool||间接依赖|pip|
|Edge||间接依赖|pip|
|ABC||间接依赖|pip|
|click|8.0.4|间接依赖|pip|
|EMPTY_RESPONSE||间接依赖|pip|
|_AsyncRESP2Parser||间接依赖|pip|
|get_protocol_version||间接依赖|pip|
|urllib3|2|间接依赖|pip|
|wait_for_command||间接依赖|pip|
|black|22.3.0|间接依赖|pip|
|ParseResult||间接依赖|pip|
|_AsyncHiredisParser||间接依赖|pip|
|wheel|0.30.0|间接依赖|pip|
|base||间接依赖|pip|
|flake8|5.0.4|间接依赖|pip|
|exceptions||间接依赖|pip|
|edge||间接依赖|pip|
|LockError||间接依赖|pip|
|Dict||间接依赖|pip|
|GeoField||间接依赖|pip|
|pytest-asyncio|0.20.2|间接依赖|pip|
|the||间接依赖|pip|
|pytest-cov|4.0.0|间接依赖|pip|
|to_bool||间接依赖|pip|
|IndexDefinition||间接依赖|pip|
|abstractmethod||间接依赖|pip|
|Awaitable||间接依赖|pip|
|loads||间接依赖|pip|
|assert_resp_response||间接依赖|pip|
|RedisClusterException||间接依赖|pip|
|AsyncCommandsParser||间接依赖|pip|
|urlparse||间接依赖|pip|
|Union||间接依赖|pip|
|_HiredisParser||间接依赖|pip|
|skip_ifmodversion_lt||间接依赖|pip|
|TypeVar||间接依赖|pip|
|Iterable||间接依赖|pip|
|ujson|4.2.0|间接依赖|pip|
|UnixDomainSocketConnection||间接依赖|pip|
|Empty||间接依赖|pip|
|List||间接依赖|pip|
|TYPE_CHECKING||间接依赖|pip|
|Queue||间接依赖|pip|
|SSLConnection||间接依赖|pip|
|parse_qs||间接依赖|pip|
|StreamReader||间接依赖|pip|
|NEVER_DECODE||间接依赖|pip|
|_RESP2Parser||间接依赖|pip|
|flake8-isort|6.0.0|间接依赖|pip|
|RedisError||间接依赖|pip|
|Full||间接依赖|pip|
|async-timeout|4.0.2|间接依赖|pip|
|skip_ifnot_redis_enterprise||间接依赖|pip|
|Any||间接依赖|pip|
|Protocol||间接依赖|pip|
|quote_string||间接依赖|pip|
|Encoder||间接依赖|pip|
|vulture|2.3.0|间接依赖|pip|
|is_resp2_connection||间接依赖|pip|
|SimpleNamespace||间接依赖|pip|
|Optional||间接依赖|pip|
|Connection||间接依赖|pip|
|_get_client||间接依赖|pip|
|invoke|1.7.3|间接依赖|pip|
|TypedDict||间接依赖|pip|
|ConnectionError||间接依赖|pip|
|redis|4.3.4|间接依赖|pip|
|TracebackType||间接依赖|pip|
|JSONDecodeError||间接依赖|pip|
|skip_if_redis_enterprise||间接依赖|pip|
|parse_to_list||间接依赖|pip|
|Callable||间接依赖|pip|
|pytest|7.2.0|间接依赖|pip|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)