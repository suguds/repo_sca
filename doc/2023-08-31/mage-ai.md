# mage-ai/mage-ai安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1696951712227946496.svg)](https://www.murphysec.com/console/report/1696951711703658496/1696951712227946496)

仓库描述：🧙 The modern replacement for Airflow. Build, run, and manage data pipelines for integrating and transforming data.

仓库地址：[https://github.com/mage-ai/mage-ai](https://github.com/mage-ai/mage-ai)

| star：5443 | watch：53 | fork：471 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-31 01:08:56 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-31 02:30:41 | 组件总数：240 | 漏洞总数：21 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|NumPy 缓冲区错误漏洞|经典缓冲区溢出|[MPS-2021-25101](https://www.oscs1024.com/hd/MPS-2021-25101)|CVE-2021-33430|中危|
|NumPy 安全漏洞|不充分的比较|[MPS-2021-25631](https://www.oscs1024.com/hd/MPS-2021-25631)|CVE-2021-34141|中危|
|NumPy 代码问题漏洞|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|NumPy 安全漏洞|经典缓冲区溢出|[MPS-2021-32279](https://www.oscs1024.com/hd/MPS-2021-32279)|CVE-2021-41496|中危|
|httpx 存在输入验证不恰当漏洞|输入验证不恰当|[MPS-2022-14944](https://www.oscs1024.com/hd/MPS-2022-14944)||中危|
|joblib 安全漏洞||[MPS-2022-5059](https://www.oscs1024.com/hd/MPS-2022-5059)|CVE-2022-21797|严重|
|snowflake-connector-python 安全漏洞|ReDoS|[MPS-2022-59892](https://www.oscs1024.com/hd/MPS-2022-59892)|CVE-2022-42965|高危|
|OpenSSL 安全漏洞|加锁机制不恰当|[MPS-2022-64591](https://www.oscs1024.com/hd/MPS-2022-64591)|CVE-2022-3996|高危|
|OpenSSL 缓冲区错误漏洞|越界读取|[MPS-2022-65756](https://www.oscs1024.com/hd/MPS-2022-65756)|CVE-2022-4203|中危|
|OpenSSL 安全漏洞|通过差异性导致的信息暴露|[MPS-2022-66954](https://www.oscs1024.com/hd/MPS-2022-66954)|CVE-2022-4304|中危|
|OpenSSL 资源管理错误漏洞|双重释放|[MPS-2022-67892](https://www.oscs1024.com/hd/MPS-2022-67892)|CVE-2022-4450|高危|
|OpenSSL 资源管理错误漏洞|UAF|[MPS-2023-1276](https://www.oscs1024.com/hd/MPS-2023-1276)|CVE-2023-0215|高危|
|OpenSSL 代码问题漏洞|空指针取消引用|[MPS-2023-1277](https://www.oscs1024.com/hd/MPS-2023-1277)|CVE-2023-0216|高危|
|OpenSSL 代码问题漏洞|空指针取消引用|[MPS-2023-1278](https://www.oscs1024.com/hd/MPS-2023-1278)|CVE-2023-0217|高危|
|OpenSSL 代码问题漏洞|空指针取消引用|[MPS-2023-2153](https://www.oscs1024.com/hd/MPS-2023-2153)|CVE-2023-0401|高危|
|cryptography 代码问题漏洞|对因果或异常条件的不恰当检查|[MPS-2023-2194](https://www.oscs1024.com/hd/MPS-2023-2194)|CVE-2023-23931|中危|
|Interactive Python 操作系统命令注入漏洞|OS命令注入|[MPS-2023-3322](https://www.oscs1024.com/hd/MPS-2023-3322)|CVE-2023-24816|高危|
|Tornado 输入验证错误漏洞|跨站重定向|[MPS-84aj-mebq](https://www.oscs1024.com/hd/MPS-84aj-mebq)|CVE-2023-28370|中危|
|Requests Proxy-Authorization 标头泄露漏洞|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|
|OpenSSL 安全漏洞|过度迭代|[MPS-n3pe-ljgc](https://www.oscs1024.com/hd/MPS-n3pe-ljgc)|CVE-2023-3817|中危|
|python-cryptography 信任管理问题漏洞|证书验证不恰当|[MPS-sj5m-20tf](https://www.oscs1024.com/hd/MPS-sj5m-20tf)|CVE-2023-38325|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|ipython|7.34.0|8.10.0|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|joblib|1.1.0|1.1.1|间接依赖|建议修复|C:1|H:0|M:0|L:0|
|requests|2.27.1|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|snowflake-connector-python|2.7.9|3.0.2|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|cryptography|36.0.2|41.0.3|间接依赖|建议修复|C:0|H:7|M:4|L:0|
|numpy|1.21.0|1.22.2|间接依赖|可选修复|C:0|H:0|M:4|L:0|
|httpx|0.23.1||间接依赖|可选修复|C:0|H:0|M:1|L:0|
|tornado|6.1|6.3.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|自定义许可证|22|Low|
|Apache-2.0|33|Low|
|MIT|31|Low|
|BSD-3-Clause|8|Low|
|GPL-2.0|1|Medium|
|0BSD|1|Low|
|LGPL-3.0|1|Medium|
|GPL-3.0-or-later|1|Low|
|Apache-2.0 OR BSD-3-Clause|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|DEFAULT_LOCALHOST_URL||间接依赖|pip|
|parse_cookie_header||间接依赖|pip|
|tap_zendesk||间接依赖|pip|
|metrics||间接依赖|pip|
|read_sql||间接依赖|pip|
|ipykernel|6.15.0|间接依赖|pip|
|utils||间接依赖|pip|
|Ads||间接依赖|pip|
|HOSTNAME||间接依赖|pip|
|IPython||间接依赖|pip|
|PyGithub|1.59.0|间接依赖|pip|
|runner||间接依赖|pip|
|dbt-trino|1.4.0|间接依赖|pip|
|MAGE_DATA_DIR_ENV_VAR||间接依赖|pip|
|abstractmethod||间接依赖|pip|
|SENTRY_DSN||间接依赖|pip|
|SSHException||间接依赖|pip|
|tap_sftp||间接依赖|pip|
|alembic|1.7.5|间接依赖|pip|
|ENABLE_NEW_RELIC||间接依赖|pip|
|BaseFile||间接依赖|pip|
|aws-secretsmanager-caching|1.1.1.5|间接依赖|pip|
|generate_salt||间接依赖|pip|
|parse_source_from_url||间接依赖|pip|
|clickhouse-connect|0.5.20|间接依赖|pip|
|mage_integrations||间接依赖|pip|
|Mock||间接依赖|pip|
|replace_base_path||间接依赖|pip|
|pendulum|2.1.0|间接依赖|pip|
|newrelic|8.8.0|间接依赖|pip|
|Group||间接依赖|pip|
|numpy|1.21.0|间接依赖|pip|
|sqlalchemy||间接依赖|pip|
|snowflake||间接依赖|pip|
|DEFAULT_MAGE_DATA_DIR||间接依赖|pip|
|pymongo|4.3.3|间接依赖|pip|
|elasticsearch|8.9.0|间接依赖|pip|
|Parameter||间接依赖|pip|
|six|1.15.0|间接依赖|pip|
|pytz|2022.1|间接依赖|pip|
|Oauth2Application||间接依赖|pip|
|react-is|16.13.1|间接依赖|npm|
|ipython|7.34.0|间接依赖|pip|
|db-dtypes|1.0.5|间接依赖|pip|
|google-cloud-run|0.5.0|间接依赖|pip|
|QUERY_ROW_LIMIT||间接依赖|pip|
|botocore|1.29.60|间接依赖|pip|
|Oauth2AccessToken||间接依赖|pip|
|tap_tester||间接依赖|pip|
|redirect_stderr||间接依赖|pip|
|deltalake|0.7.0|间接依赖|pip|
|tzlocal|4.2|间接依赖|pip|
|google-cloud-storage|2.5.0|间接依赖|pip|
|zenpy|2.0.25|间接依赖|pip|
|REDIS_URL||间接依赖|pip|
|get_repo_name||间接依赖|pip|
|extract||间接依赖|pip|
|pyspark||间接依赖|pip|
|Union||间接依赖|pip|
|thefuzz||间接依赖|pip|
|Any||间接依赖|pip|
|azure-identity|1.11.0|间接依赖|pip|
|write_schema||间接依赖|pip|
|Catalog||间接依赖|pip|
|dbt-core|1.4.6|间接依赖|pip|
|bcrypt|4.0.1|间接依赖|pip|
|dbt-snowflake|1.4.0|间接依赖|pip|
|object-assign|4.1.1|间接依赖|npm|
|streams||间接依赖|pip|
|dataclass||间接依赖|pip|
|tslib|2.5.0|间接依赖|npm|
|jupyter_client|7.3.4|间接依赖|pip|
|Role||间接依赖|pip|
|pymongo_schema|0.4.1|间接依赖|pip|
|python-magic|0.4.27|间接依赖|pip|
|List||间接依赖|pip|
|faker||间接依赖|pip|
|TEST_DB||间接依赖|pip|
|dask|2022.2.0|间接依赖|pip|
|Pipeline||间接依赖|pip|
|dbt-sqlserver|1.3.1|间接依赖|pip|
|great_expectations|0.15.50|间接依赖|pip|
|metadata||间接依赖|pip|
|tornado|6.1|间接依赖|pip|
|facebook_business|17.0.2|间接依赖|pip|
|AdCreative||间接依赖|pip|
|ruamel.yaml|0.17.17|间接依赖|pip|
|ldap3|2.9.1|间接依赖|pip|
|xlsx2csv|0.8.1|间接依赖|pip|
|Timeout||间接依赖|pip|
|sentry-sdk|1.19.1|间接依赖|pip|
|httpx|0.23.1|间接依赖|pip|
|Dict||间接依赖|pip|
|PipelineRun||间接依赖|pip|
|ExportWritePolicy||间接依赖|pip|
|GitPython|3.1.31|间接依赖|pip|
|google-cloud-pubsub|2.16.0|间接依赖|pip|
|Jinja2|3.1.2|间接依赖|pip|
|NEW_RELIC_CONFIG_PATH||间接依赖|pip|
|get_streams_to_sync||间接依赖|pip|
|attr-accept|2.2.2|间接依赖|npm|
|dbt-clickhouse|1.4.0|间接依赖|pip|
|python-dateutil|2.8.2|间接依赖|pip|
|ActionType||间接依赖|pip|
|ConnectionError||间接依赖|pip|
|azure-eventhub|5.11.2|间接依赖|pip|
|get_repo_path||间接依赖|pip|
|has_at_least_editor_role||间接依赖|pip|
|scikit-learn|1.0|间接依赖|pip|
|azure-keyvault-secrets|4.6.0|间接依赖|pip|
|jupyter-server|1.23.5|间接依赖|pip|
|datadog|0.44.0|间接依赖|pip|
|tap_pipedrive||间接依赖|pip|
|twitter_ads||间接依赖|pip|
|attrs|17.4.0|间接依赖|pip|
|DataFrame||间接依赖|pip|
|CatalogEntry||间接依赖|pip|
|backoff|2.0.0|间接依赖|pip|
|call||间接依赖|pip|
|redshift-connector|2.0.909|间接依赖|pip|
|IO||间接依赖|pip|
|mage_ai||间接依赖|pip|
|tables|3.7.0|间接依赖|pip|
|safe_db_query||间接依赖|pip|
|requests|2.27.1|间接依赖|pip|
|psycopg2-binary|2.9.3|间接依赖|pip|
|oracledb|1.3.1|间接依赖|pip|
|isfunction||间接依赖|pip|
|azure||间接依赖|pip|
|snowflake-connector-python|2.7.9|间接依赖|pip|
|patch||间接依赖|pip|
|MAGE_PUBLIC_HOST||间接依赖|pip|
|drop_all_collections||间接依赖|pip|
|dbt-redshift|1.4.0|间接依赖|pip|
|ABC||间接依赖|pip|
|ignore_keys||间接依赖|pip|
|openai|0.27.8|间接依赖|pip|
|google-cloud-iam|2.9.0|间接依赖|pip|
|couchbase|4.1.1|间接依赖|pip|
|tap_hubspot||间接依赖|pip|
|opensearch-py|2.0.0|间接依赖|pip|
|initialize_reports||间接依赖|pip|
|BlockRun||间接依赖|pip|
|pyodbc|4.0.35|间接依赖|pip|
|get_test_connection||间接依赖|pip|
|gnupg|2.3.1|间接依赖|pip|
|field||间接依赖|pip|
|mysql-connector-python|8.0.31|间接依赖|pip|
|pandas|1.3.0|间接依赖|pip|
|dbt-bigquery|1.4.3|间接依赖|pip|
|kubernetes|25.3.0|间接依赖|pip|
|SENTRY_TRACES_SAMPLE_RATE||间接依赖|pip|
|describe_cluster||间接依赖|pip|
|loose-envify|1.4.0|间接依赖|npm|
|quote_plus||间接依赖|pip|
|list_clusters||间接依赖|pip|
|redirect_stdout||间接依赖|pip|
|sshtunnel|0.4.0|间接依赖|pip|
|typing_extensions||间接依赖|pip|
|stripe|4.2.0|间接依赖|pip|
|ENV_DEV||间接依赖|pip|
|dbt-spark|1.4.0|间接依赖|pip|
|BlockType||间接依赖|pip|
|singer_sdk|0.30.0|间接依赖|pip|
|trino|0.321.0|间接依赖|pip|
|db_connection||间接依赖|pip|
|AuthenticationException||间接依赖|pip|
|VariableType||间接依赖|pip|
|Generator||间接依赖|pip|
|google-api-core|2.11.0|间接依赖|pip|
|google-analytics-data|0.14.2|间接依赖|pip|
|parse_qs||间接依赖|pip|
|pydruid|0.6.5|间接依赖|pip|
|Block||间接依赖|pip|
|terminado|0.17.1|间接依赖|pip|
|Tuple||间接依赖|pip|
|react-dropzone|14.2.3|直接依赖|npm|
|Callable||间接依赖|pip|
|sklearn||间接依赖|pip|
|inflection|0.5.1|间接依赖|pip|
|requests_aws4auth|1.1.2|间接依赖|pip|
|timezone||间接依赖|pip|
|ensure_file_is_in_project||间接依赖|pip|
|freezegun|1.2.2|间接依赖|pip|
|RequestException||间接依赖|pip|
|flask||间接依赖|pip|
|dbt-postgres|1.4.6|间接依赖|pip|
|Faker|4.14.0|间接依赖|pip|
|requests_mock|1.10.0|间接依赖|pip|
|xmltodict|0.13.0|间接依赖|pip|
|write_state||间接依赖|pip|
|simplejson|3.17.6|间接依赖|pip|
|create_bcrypt_hash||间接依赖|pip|
|ENV_PROD||间接依赖|pip|
|prop-types|15.8.1|间接依赖|npm|
|MagicMock||间接依赖|pip|
|SingerSyncError||间接依赖|pip|
|Organization||间接依赖|pip|
|date||间接依赖|pip|
|cryptography|36.0.2|间接依赖|pip|
|kafka-python|2.0.2|间接依赖|pip|
|connections||间接依赖|pip|
|LOGGER||间接依赖|pip|
|google||间接依赖|pip|
|github||间接依赖|pip|
|asdict||间接依赖|pip|
|singer||间接依赖|pip|
|initialize_core_streams||间接依赖|pip|
|google-cloud-bigquery-storage|2.16.2|间接依赖|pip|
|menagerie||间接依赖|pip|
|timedelta||间接依赖|pip|
|jupyter-server-proxy|3.2.1|间接依赖|pip|
|Leads||间接依赖|pip|
|pyarrow|10.0.1|间接依赖|pip|
|boto3|1.26.60|间接依赖|pip|
|typing-extensions|4.5.0|间接依赖|pip|
|azure-storage-blob|12.14.1|间接依赖|pip|
|pool||间接依赖|pip|
|pymssql|2.2.8|间接依赖|pip|
|google-api-python-client|2.70.0|间接依赖|pip|
|engine_from_config||间接依赖|pip|
|Transformer||间接依赖|pip|
|PyJWT|2.6.0|间接依赖|pip|
|azure-mgmt-containerinstance|10.1.0|间接依赖|pip|
|make_app||间接依赖|pip|
|terminaltables|3.1.10|间接依赖|pip|
|File||间接依赖|pip|
|aiofiles|22.1.0|间接依赖|pip|
|croniter|1.3.7|间接依赖|pip|
|raise_or_log_zenpy_apiexception||间接依赖|pip|
|joblib|1.1.0|间接依赖|pip|
|merge_dict||间接依赖|pip|
|pika|1.3.1|间接依赖|pip|
|InvalidPipelineError||间接依赖|pip|
|azure-keyvault-certificates|4.6.0|间接依赖|pip|
|twitter-ads|11.0.0|间接依赖|pip|
|authenticate_client_and_token||间接依赖|pip|
|psycopg2|2.9.3|间接依赖|pip|
|js-tokens|4.0.0|间接依赖|npm|
|file-selector|0.6.0|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)