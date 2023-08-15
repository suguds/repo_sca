# go-skynet/LocalAI安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1691512983144652800.svg)](https://www.murphysec.com/console/report/1691512983085932544/1691512983144652800)

仓库描述：:robot: Self-hosted, community-driven, local OpenAI compatible API. Drop-in replacement for OpenAI running LLMs on consumer-grade hardware. Free Open Source OpenAI alternative. No GPU required. Runs ggml, GPTQ, onnx, TF compatible models: llama, gpt4all, rwkv, whisper, vicuna, koala, gpt4all-j, cerebras, falcon, dolly, starcoder, and many others

仓库地址：[https://github.com/go-skynet/LocalAI](https://github.com/go-skynet/LocalAI)

| star：9868 | watch：91 | fork：880 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-16 00:34:06 | 许可证：- |
| 最近检测时间：2023-08-16 02:11:45 | 组件总数：213 | 漏洞总数：10 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|MPS-2021-32278|空指针取消引用|[MPS-2021-32278](https://www.oscs1024.com/hd/MPS-2021-32278)|CVE-2021-41495|中危|
|MPS-2022-1918|对数据真实性的验证不充分|[MPS-2022-1918](https://www.oscs1024.com/hd/MPS-2022-1918)|CVE-2022-23491|中危|
|MPS-3udo-v1n0|注入|[MPS-3udo-v1n0](https://www.oscs1024.com/hd/MPS-3udo-v1n0)|CVE-2023-36188|严重|
|MPS-6i1z-gkra||[MPS-6i1z-gkra](https://www.oscs1024.com/hd/MPS-6i1z-gkra)|CVE-2023-34540|严重|
|MPS-84rc-nja1|代码注入|[MPS-84rc-nja1](https://www.oscs1024.com/hd/MPS-84rc-nja1)|CVE-2023-36095|严重|
|MPS-ck78-r6zg|对数据真实性的验证不充分|[MPS-ck78-r6zg](https://www.oscs1024.com/hd/MPS-ck78-r6zg)|CVE-2023-37920|严重|
|MPS-hr61-tzey|未授权敏感信息泄露|[MPS-hr61-tzey](https://www.oscs1024.com/hd/MPS-hr61-tzey)|CVE-2023-32681|中危|
|MPS-p829-6f3r|SQL注入|[MPS-p829-6f3r](https://www.oscs1024.com/hd/MPS-p829-6f3r)|CVE-2023-36189|高危|
|MPS-ptqs-e23v|HTTP请求走私|[MPS-ptqs-e23v](https://www.oscs1024.com/hd/MPS-ptqs-e23v)|CVE-2023-37276|高危|
|MPS-s5ul-own1||[MPS-s5ul-own1](https://www.oscs1024.com/hd/MPS-s5ul-own1)|CVE-2023-36258|严重|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|requests|2.29.0|2.31.0|间接依赖|建议修复|C:0|H:0|M:1|L:0|
|certifi|2022.12.7|2023.07.22|间接依赖|建议修复|C:1|H:0|M:1|L:0|
|langchain|0.0.159|0.0.236|间接依赖|建议修复|C:4|H:1|M:0|L:0|
|langchain|0.0.234|0.0.236|间接依赖|建议修复|C:3|H:1|M:0|L:0|
|langchain|0.0.160|0.0.236|间接依赖|建议修复|C:4|H:1|M:0|L:0|
|aiohttp|3.8.4|3.8.5|间接依赖|建议修复|C:0|H:1|M:0|L:0|
|numpy|1.24.3||间接依赖|可选修复|C:0|H:0|M:1|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|BSD-2-Clause|2|Low|
|Apache-2.0|10|Low|
|MIT|106|Low|
|BSD-3-Clause|4|Low|
|ISC|14|Low|
|自定义许可证|3|Low|
|CC0-1.0|1|Low|
|0BSD|1|Low|
|MPL-2.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|webidl-conversions|3.0.1|间接依赖|npm|
|yarl|1.9.2|间接依赖|pip|
|pydantic|1.10.7|间接依赖|pip|
|flat|5.0.2|间接依赖|npm|
|p-retry|4.6.2|间接依赖|npm|
|p-queue|6.6.2|间接依赖|npm|
|github.com/golang/snappy|v0.0.2|间接依赖|go|
|github.com/xrash/smetrics|v0.0.0-20201216005158-039620a65673|间接依赖|go|
|@types/node|18.16.4|直接依赖|npm|
|numpy|1.24.3|间接依赖|pip|
|ml-array-sum|1.1.6|间接依赖|npm|
|github.com/kr/text|v0.2.0|间接依赖|go|
|google.golang.org/protobuf|v1.31.0|直接依赖|go|
|browser-or-node|2.1.1|间接依赖|npm|
|any-promise|1.3.0|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|ieee754|1.2.1|间接依赖|npm|
|github.com/go-skynet/bloomz.cpp|v0.0.0-20230529155654-1834e77b83fa|直接依赖|go|
|tr46|0.0.3|间接依赖|npm|
|numexpr|2.8.4|间接依赖|pip|
|github.com/urfave/cli/v2|v2.25.7|直接依赖|go|
|google.golang.org/genproto/googleapis/rpc|v0.0.0-20230525234030-28d5490b6b19|间接依赖|go|
|escalade|3.1.1|间接依赖|npm|
|GPTVectorStoreIndex||间接依赖|pip|
|github.com/ulikunitz/xz|v0.5.9|间接依赖|go|
|github.com/go-audio/riff|v1.0.0|间接依赖|go|
|yargs|17.7.2|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|urllib3|1.26.15|间接依赖|pip|
|safe-buffer|5.2.1|间接依赖|npm|
|@sqltools/formatter|1.2.5|间接依赖|npm|
|zod|3.21.4|间接依赖|npm|
|thenify|3.3.1|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|@dqbd/tiktoken|1.0.7|间接依赖|npm|
|binary-extensions|2.2.0|间接依赖|npm|
|retry|0.13.1|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|y18n|5.0.8|间接依赖|npm|
|github.com/google/uuid|v1.3.0|直接依赖|go|
|aiosignal|1.3.1|间接依赖|pip|
|color-convert|2.0.1|直接依赖|npm|
|github.com/phayes/freeport|v0.0.0-20220201140144-74d24b5ae9f5|直接依赖|go|
|github.com/onsi/gomega|v1.27.10|直接依赖|go|
|LLMChain||间接依赖|pip|
|aiohttp|3.8.4|间接依赖|pip|
|ml-distance-euclidean|2.0.0|间接依赖|npm|
|mime-types|2.1.35|间接依赖|npm|
|chromadb|0.3.21|间接依赖|pip|
|frozenlist|1.3.3|间接依赖|pip|
|gopkg.in/check.v1|v1.0.0-20201130134442-10cb98267c6c|间接依赖|go|
|attrs|23.1.0|间接依赖|pip|
|follow-redirects|1.15.2|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|uuid|9.0.0|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|github.com/valyala/fasthttp|v1.48.0|直接依赖|go|
|github.com/nwaples/rardecode|v1.1.0|间接依赖|go|
|github.com/mattn/go-runewidth|v0.0.14|间接依赖|go|
|supports-color|7.2.0|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|langchain|0.0.159|间接依赖|pip|
|google.golang.org/grpc|v1.57.0|直接依赖|go|
|wrappy|1.0.2|间接依赖|npm|
|github.com/cpuguy83/go-md2man/v2|v2.0.2|间接依赖|go|
|github.com/mattn/go-colorable|v0.1.13|间接依赖|go|
|fs.realpath|1.0.0|间接依赖|npm|
|github.com/go-skynet/go-ggml-transformers.cpp|v0.0.0-20230714203132-ffb09d7dd71e|直接依赖|go|
|github.com/valyala/bytebufferpool|v1.0.0|间接依赖|go|
|minimatch|5.1.6|间接依赖|npm|
|langchain|0.0.160|间接依赖|pip|
|langchain||间接依赖|pip|
|packaging|23.1|间接依赖|pip|
|github.com/modern-go/concurrent|v0.0.0-20180228061459-e0a39a4cb421|间接依赖|go|
|sha.js|2.4.11|间接依赖|npm|
|github.com/pierrec/lz4/v4|v4.1.2|间接依赖|go|
|mime-db|1.52.0|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|thenify-all|1.6.0|间接依赖|npm|
|github.com/hpcloud/tail|v1.0.0|直接依赖|go|
|PyYAML|6.0|间接依赖|pip|
|marshmallow-enum|1.5.1|间接依赖|pip|
|dataclasses-json|0.5.7|间接依赖|pip|
|typing_extensions|4.5.0|间接依赖|pip|
|github.com/donomii/go-rwkv.cpp|v0.0.0-20230715075832-c898cd0f62df|直接依赖|go|
|charset-normalizer|3.1.0|间接依赖|pip|
|has-flag|4.0.0|间接依赖|npm|
|typing-inspect|0.8.0|间接依赖|pip|
|SQLAlchemy|2.0.12|间接依赖|pip|
|github.com/mudler/go-ggllm.cpp|v0.0.0-20230709223052-862477d16eef|直接依赖|go|
|github.com/klauspost/compress|v1.16.3|间接依赖|go|
|github.com/gofiber/fiber/v2|v2.48.0|直接依赖|go|
|color-name|1.1.4|间接依赖|npm|
|@fortaine/fetch-event-source|3.0.6|间接依赖|npm|
|yargs-parser|21.1.1|间接依赖|npm|
|openai|0.27.8|间接依赖|pip|
|expr-eval|2.0.2|间接依赖|npm|
|multidict|6.0.4|间接依赖|pip|
|github.com/go-audio/wav|v1.1.0|直接依赖|go|
|highlight.js|10.7.3|间接依赖|npm|
|github.com/imdario/mergo|v0.3.16|直接依赖|go|
|parse5-htmlparser2-tree-adapter|6.0.1|间接依赖|npm|
|dotenv|16.0.3|间接依赖|npm|
|github.com/go-skynet/go-llama.cpp|v0.0.0-20230814195654-18f25c21abf9|直接依赖|go|
|mkdirp|2.1.6|间接依赖|npm|
|inflight|1.0.6|间接依赖|npm|
|node-fetch|2.6.7|间接依赖|npm|
|ml-array-mean|1.1.6|间接依赖|npm|
|github.com/pkoukk/tiktoken-go|v0.1.2|间接依赖|go|
|colorama|0.4.6|间接依赖|pip|
|llama-index|0.6.2|间接依赖|pip|
|mz|2.7.0|间接依赖|npm|
|num-sort|2.1.0|间接依赖|npm|
|glob|8.1.0|间接依赖|npm|
|golang.org/x/text|v0.11.0|间接依赖|go|
|debugpy|1.6.7|间接依赖|pip|
|gopkg.in/yaml.v2|v2.4.0|直接依赖|go|
|axios|0.26.1|间接依赖|npm|
|github.com/dsnet/compress|v0.0.2-0.20210315054119-f66993602bf5|间接依赖|go|
|github.com/klauspost/pgzip|v1.2.5|间接依赖|go|
|delayed-stream|1.0.0|间接依赖|npm|
|PromptHelper||间接依赖|pip|
|github.com/hashicorp/errwrap|v1.0.0|间接依赖|go|
|form-data|4.0.0|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|eventemitter3|4.0.7|间接依赖|npm|
|app-root-path|3.1.0|间接依赖|npm|
|cross-fetch|3.1.5|间接依赖|npm|
|golang.org/x/tools|v0.9.3|间接依赖|go|
|gopkg.in/tomb.v1|v1.0.0-20141024135613-dd632973f1e7|间接依赖|go|
|object-hash|3.0.0|间接依赖|npm|
|tqdm|4.65.0|间接依赖|pip|
|PromptTemplate||间接依赖|pip|
|gopkg.in/fsnotify.v1|v1.4.7|间接依赖|go|
|mypy-extensions|1.0.0|间接依赖|pip|
|cliui|8.0.1|间接依赖|npm|
|LLMPredictor||间接依赖|pip|
|async-timeout|4.0.2|间接依赖|pip|
|require-directory|2.1.1|间接依赖|npm|
|github.com/mholt/archiver/v3|v3.5.1|直接依赖|go|
|asynckit|0.4.0|间接依赖|npm|
|binary-search|1.3.6|间接依赖|npm|
|tslib|2.5.0|间接依赖|npm|
|golang.org/x/net|v0.12.0|间接依赖|go|
|golang.org/x/sys|v0.10.0|间接依赖|go|
|langchain|0.0.67|直接依赖|npm|
|github.com/go-task/slim-sprig|v0.0.0-20230315185526-52ccab3ef572|间接依赖|go|
|github.com/onsi/ginkgo/v2|v2.11.0|直接依赖|go|
|github.com/google/pprof|v0.0.0-20210407192527-94a9f03dee38|间接依赖|go|
|brace-expansion|2.0.1|间接依赖|npm|
|reflect-metadata|0.1.13|间接依赖|npm|
|github.com/json-iterator/go|v1.1.12|直接依赖|go|
|chalk|4.1.2|间接依赖|npm|
|zod-to-json-schema|3.21.0|间接依赖|npm|
|requests|2.29.0|间接依赖|pip|
|emoji-regex|8.0.0|间接依赖|npm|
|github.com/golang/protobuf|v1.5.3|间接依赖|go|
|github.com/mudler/go-processmanager|v0.0.0-20220724164624-c45b5c61312d|直接依赖|go|
|greenlet|2.0.2|间接依赖|pip|
|typescript|5.0.4|直接依赖|npm|
|ml-tree-similarity|1.0.0|间接依赖|npm|
|ml-distance|4.0.0|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|SimpleDirectoryReader||间接依赖|pip|
|github.com/mattn/go-isatty|v0.0.19|间接依赖|go|
|github.com/sashabaranov/go-openai|v1.14.2|直接依赖|go|
|marshmallow|3.19.0|间接依赖|pip|
|github.com/rs/zerolog|v1.30.0|直接依赖|go|
|is-any-array|2.0.1|间接依赖|npm|
|openai|3.2.1|间接依赖|npm|
|github.com/go-audio/audio|v1.0.0|间接依赖|go|
|@types/retry|0.12.0|间接依赖|npm|
|gopkg.in/yaml.v3|v3.0.1|直接依赖|go|
|p-timeout|3.2.0|间接依赖|npm|
|certifi|2022.12.7|间接依赖|pip|
|github.com/ggerganov/whisper.cpp/bindings/go|v0.0.0-20230628193450-85ed71aaec8e|直接依赖|go|
|openapi-schema-pydantic|1.2.4|间接依赖|pip|
|github.com/hashicorp/go-multierror|v1.1.1|直接依赖|go|
|tenacity|8.2.2|间接依赖|pip|
|github.com/russross/blackfriday/v2|v2.1.0|间接依赖|go|
|requirements.txt||间接依赖|pip|
|yaml|2.2.2|间接依赖|npm|
|@anthropic-ai/sdk|0.4.3|间接依赖|npm|
|github.com/modern-go/reflect2|v1.0.2|间接依赖|go|
|idna|3.4|间接依赖|pip|
|ansi-styles|5.2.0|间接依赖|npm|
|langchain|0.0.234|间接依赖|pip|
|github.com/go-skynet/go-bert.cpp|v0.0.0-20230716133540-6abe312cded1|直接依赖|go|
|p-finally|1.0.0|间接依赖|npm|
|base64-js|1.5.1|间接依赖|npm|
|github.com/mudler/go-stable-diffusion|v0.0.0-20230605122230-d89260f598af|直接依赖|go|
|github.com/go-logr/logr|v1.2.4|间接依赖|go|
|github.com/otiai10/openaigo|v1.5.2|直接依赖|go|
|parse5|5.1.1|间接依赖|npm|
|cli-highlight|2.1.11|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|openai|0.27.6|间接依赖|pip|
|github.com/rivo/uniseg|v0.2.0|间接依赖|go|
|github.com/dlclark/regexp2|v1.8.1|间接依赖|go|
|inherits|2.0.4|间接依赖|npm|
|github.com/xi2/xz|v0.0.0-20171230120015-48954b6210f8|间接依赖|go|
|github.com/google/go-cmp|v0.5.9|间接依赖|go|
|github.com/nomic-ai/gpt4all/gpt4all-bindings/golang|v0.0.0-20230814164545-4e55940edf11|直接依赖|go|
|google.golang.org/genproto|v0.0.0-20230526161137-0005af68ea54|间接依赖|go|
|typeorm|0.3.15|直接依赖|npm|
|github.com/valyala/tcplisten|v1.0.0|间接依赖|go|
|github.com/mudler/go-piper|v0.0.0-20230621222733-56b8a81b4760|直接依赖|go|
|github.com/andybalholm/brotli|v1.0.5|间接依赖|go|
|whatwg-url|5.0.0|间接依赖|npm|
|buffer|6.0.3|间接依赖|npm|
|github.com/tmc/langchaingo|v0.0.0-20230811231558-fd8b7f099537|直接依赖|go|
|jsonpointer|5.0.1|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)