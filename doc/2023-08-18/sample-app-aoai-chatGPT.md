# microsoft/sample-app-aoai-chatGPT安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1692240278671089664.svg)](https://www.murphysec.com/console/report/1692240278507511808/1692240278671089664)

仓库描述：[PREVIEW] Sample code for a simple web chat experience targeting chatGPT through AOAI.

仓库地址：[https://github.com/microsoft/sample-app-aoai-chatGPT](https://github.com/microsoft/sample-app-aoai-chatGPT)

| star：389 | watch：23 | fork：376 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-17 06:54:26 | 许可证：MIT |
| 最近检测时间：2023-08-18 02:21:45 | 组件总数：252 | 漏洞总数：2 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|LangChain SQL注入漏洞|SQL注入|[MPS-p829-6f3r](https://www.oscs1024.com/hd/MPS-p829-6f3r)|CVE-2023-36189|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|langchain|0.0.254||间接依赖|建议修复|C:0|H:1|M:0|L:0|
|semver|6.3.0|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|MIT|198|Low|
|BSD-3-Clause|4|Low|
|ISC|4|Low|
|自定义许可证|2|Low|
|Apache-2.0|4|Low|
|0BSD|1|Low|
|CC-BY-4.0|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|@types/lodash-es|4.17.7|直接依赖|npm|
|mdast-util-to-markdown|1.5.0|间接依赖|npm|
|@babel/helper-simple-access|7.20.2|间接依赖|npm|
|csstype|3.1.1|间接依赖|npm|
|@esbuild/linux-arm|0.16.17|间接依赖|npm|
|@griffel/core|1.10.0|间接依赖|npm|
|Response||间接依赖|pip|
|uvu|0.5.6|间接依赖|npm|
|rollup|3.14.0|间接依赖|npm|
|@types/mdast|3.0.11|间接依赖|npm|
|micromark-util-chunked|1.0.0|间接依赖|npm|
|@fluentui/keyboard-key|0.4.5|间接依赖|npm|
|@babel/types|7.20.7|间接依赖|npm|
|rtl-css-js|1.16.1|间接依赖|npm|
|@fluentui/font-icons-mdl2|8.5.8|间接依赖|npm|
|@esbuild/win32-arm64|0.16.17|间接依赖|npm|
|@babel/helper-module-imports|7.18.6|间接依赖|npm|
|langchain|0.0.254|间接依赖|pip|
|lodash-es|4.17.21|直接依赖|npm|
|trough|2.1.0|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.17|间接依赖|npm|
|micromark-util-types|1.0.2|间接依赖|npm|
|micromark-extension-gfm|2.0.2|间接依赖|npm|
|micromark-util-decode-numeric-character-reference|1.0.0|间接依赖|npm|
|diff|5.1.0|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|sade|1.8.1|间接依赖|npm|
|extend|3.0.2|间接依赖|npm|
|@babel/helper-function-name|7.19.0|间接依赖|npm|
|@griffel/react|1.5.5|间接依赖|npm|
|browserslist|4.21.5|间接依赖|npm|
|vite|4.1.5|直接依赖|npm|
|micromark-extension-gfm-footnote|1.1.0|间接依赖|npm|
|electron-to-chromium|1.4.286|间接依赖|npm|
|mdast-util-gfm|2.0.2|间接依赖|npm|
|react-refresh|0.14.0|间接依赖|npm|
|Markdown|3.4.3|间接依赖|pip|
|react|18.2.0|直接依赖|npm|
|@esbuild/linux-mips64el|0.16.17|间接依赖|npm|
|remark-rehype|9.1.0|间接依赖|npm|
|@fluentui/foundation-legacy|8.2.28|间接依赖|npm|
|micromark-factory-title|1.0.2|间接依赖|npm|
|@esbuild/android-arm|0.16.17|间接依赖|npm|
|@fluentui/dom-utilities|2.2.5|间接依赖|npm|
|mdast-util-to-string|3.2.0|间接依赖|npm|
|resolve|1.22.1|间接依赖|npm|
|hast-util-parse-selector|3.1.1|间接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|azure-identity|1.14.0b2|间接依赖|pip|
|@esbuild/darwin-x64|0.16.17|间接依赖|npm|
|mdast-util-phrasing|3.0.1|间接依赖|npm|
|@esbuild/linux-riscv64|0.16.17|间接依赖|npm|
|@fluentui/react-hooks|8.6.16|间接依赖|npm|
|@babel/helper-hoist-variables|7.18.6|间接依赖|npm|
|kleur|4.1.5|间接依赖|npm|
|@babel/plugin-transform-react-jsx-self|7.18.6|间接依赖|npm|
|path-parse|1.0.7|间接依赖|npm|
|@esbuild/win32-ia32|0.16.17|间接依赖|npm|
|@types/react|18.0.27|间接依赖|npm|
|picocolors|1.0.0|间接依赖|npm|
|is-buffer|2.0.5|间接依赖|npm|
|@esbuild/linux-arm64|0.16.17|间接依赖|npm|
|prettier|2.8.3|直接依赖|npm|
|micromark|3.1.0|间接依赖|npm|
|mdast-util-find-and-replace|2.2.2|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|openai|0.27.7|间接依赖|pip|
|@types/debug|4.1.7|间接依赖|npm|
|typescript|4.9.5|直接依赖|npm|
|stylis|4.1.3|间接依赖|npm|
|@babel/helper-compilation-targets|7.20.7|间接依赖|npm|
|@types/parse5|6.0.3|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|app||间接依赖|pip|
|unist-util-is|5.2.1|间接依赖|npm|
|hast-util-to-parse5|7.1.0|间接依赖|npm|
|is-plain-obj|4.1.0|间接依赖|npm|
|@esbuild/freebsd-arm64|0.16.17|间接依赖|npm|
|lodash|4.17.21|直接依赖|npm|
|azure-ai-formrecognizer|3.2.1|间接依赖|pip|
|micromark-factory-label|1.0.2|间接依赖|npm|
|@babel/helper-split-export-declaration|7.18.6|间接依赖|npm|
|micromark-util-encode|1.0.1|间接依赖|npm|
|micromark-util-decode-string|1.0.2|间接依赖|npm|
|tiktoken|0.4.0|间接依赖|pip|
|azure-search-documents|11.4.0b6|间接依赖|pip|
|python-dotenv|1.0.0|间接依赖|pip|
|markdown-table|3.0.3|间接依赖|npm|
|micromark-extension-gfm-task-list-item|1.0.4|间接依赖|npm|
|@babel/helper-validator-option|7.18.6|间接依赖|npm|
|space-separated-tokens|2.0.2|间接依赖|npm|
|unist-util-generated|2.0.1|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|@fluentui/date-time-utilities|8.5.5|间接依赖|npm|
|node-releases|2.0.10|间接依赖|npm|
|@jridgewell/gen-mapping|0.1.1|间接依赖|npm|
|semver|6.3.0|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|@vitejs/plugin-react|3.1.0|直接依赖|npm|
|@types/hast|2.3.4|间接依赖|npm|
|@esbuild/linux-ia32|0.16.17|间接依赖|npm|
|@esbuild/darwin-arm64|0.16.17|间接依赖|npm|
|@ampproject/remapping|2.2.0|间接依赖|npm|
|comma-separated-tokens|2.0.3|间接依赖|npm|
|vfile-location|4.1.0|间接依赖|npm|
|@fluentui/merge-styles|8.5.6|间接依赖|npm|
|nanoid|3.3.4|间接依赖|npm|
|@fluentui/set-version|8.2.5|间接依赖|npm|
|micromark-factory-space|1.0.0|间接依赖|npm|
|html-void-elements|2.0.1|间接依赖|npm|
|@babel/helper-string-parser|7.19.4|间接依赖|npm|
|character-entities|2.0.2|间接依赖|npm|
|micromark-util-subtokenize|1.0.2|间接依赖|npm|
|tslib|2.5.0|间接依赖|npm|
|property-information|6.2.0|间接依赖|npm|
|style-to-object|0.3.0|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|@microsoft/load-themed-styles|1.10.295|间接依赖|npm|
|@types/unist|2.0.6|间接依赖|npm|
|is-core-module|2.11.0|间接依赖|npm|
|react-is|17.0.2|间接依赖|npm|
|@babel/core|7.20.12|间接依赖|npm|
|react-router-dom|6.8.1|直接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|ccount|2.0.1|间接依赖|npm|
|web-namespaces|2.0.1|间接依赖|npm|
|micromark-util-normalize-identifier|1.0.0|间接依赖|npm|
|@types/scheduler|0.16.2|间接依赖|npm|
|mri|1.2.0|间接依赖|npm|
|micromark-extension-gfm-strikethrough|1.0.5|间接依赖|npm|
|@esbuild/linux-s390x|0.16.17|间接依赖|npm|
|mdast-util-definitions|5.1.2|间接依赖|npm|
|source-map-js|1.0.2|间接依赖|npm|
|yallist|3.1.1|间接依赖|npm|
|react-dom|18.2.0|直接依赖|npm|
|@esbuild/android-arm64|0.16.17|间接依赖|npm|
|micromark-factory-whitespace|1.0.0|间接依赖|npm|
|@esbuild/win32-x64|0.16.17|间接依赖|npm|
|esbuild|0.16.17|间接依赖|npm|
|hast-util-whitespace|2.0.1|间接依赖|npm|
|hast-util-from-parse5|7.1.2|间接依赖|npm|
|azure-storage-blob|12.17.0|间接依赖|pip|
|micromark-util-symbol|1.0.1|间接依赖|npm|
|inline-style-parser|0.1.1|间接依赖|npm|
|unist-builder|3.0.1|间接依赖|npm|
|@babel/parser|7.20.15|间接依赖|npm|
|@remix-run/router|1.3.2|间接依赖|npm|
|@types/prop-types|15.7.5|间接依赖|npm|
|rehype-raw|6.1.1|直接依赖|npm|
|@babel/traverse|7.20.13|间接依赖|npm|
|mdast-util-from-markdown|1.3.0|间接依赖|npm|
|micromark-extension-gfm-autolink-literal|1.0.4|间接依赖|npm|
|gensync|1.0.0-beta.2|间接依赖|npm|
|@babel/plugin-transform-react-jsx-source|7.19.6|间接依赖|npm|
|@esbuild/linux-ppc64|0.16.17|间接依赖|npm|
|@babel/compat-data|7.20.14|间接依赖|npm|
|@babel/helpers|7.20.13|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|update-browserslist-db|1.0.10|间接依赖|npm|
|@babel/helper-environment-visitor|7.18.9|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|mdast-util-gfm-strikethrough|1.0.3|间接依赖|npm|
|@fluentui/react-icons|2.0.195|直接依赖|npm|
|@esbuild/linux-loong64|0.16.17|间接依赖|npm|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|@types/mdurl|1.0.2|间接依赖|npm|
|supports-preserve-symlinks-flag|1.0.0|间接依赖|npm|
|prop-types|15.8.1|间接依赖|npm|
|dequal|2.0.3|间接依赖|npm|
|@fluentui/react-window-provider|2.2.6|间接依赖|npm|
|micromark-util-html-tag-name|1.1.0|间接依赖|npm|
|convert-source-map|1.9.0|间接依赖|npm|
|/usr/src/app/requirements.txt||间接依赖|pip|
|micromark-util-sanitize-uri|1.1.0|间接依赖|npm|
|json5|2.2.3|间接依赖|npm|
|requests|2.31.0|间接依赖|pip|
|mdast-util-gfm-task-list-item|1.0.2|间接依赖|npm|
|@types/ms|0.7.31|间接依赖|npm|
|parse5|6.0.1|间接依赖|npm|
|bs4|0.0.1|间接依赖|pip|
|hast-util-raw|7.2.3|间接依赖|npm|
|@esbuild/sunos-x64|0.16.17|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|postcss|8.4.21|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|@babel/helper-plugin-utils|7.20.2|间接依赖|npm|
|micromark-util-character|1.1.0|间接依赖|npm|
|@fluentui/utilities|8.13.6|间接依赖|npm|
|micromark-extension-gfm-tagfilter|1.0.2|间接依赖|npm|
|scheduler|0.23.0|间接依赖|npm|
|caniuse-lite|1.0.30001450|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|mdast-util-gfm-autolink-literal|1.0.3|间接依赖|npm|
|unist-util-stringify-position|3.0.3|间接依赖|npm|
|@babel/generator|7.20.14|间接依赖|npm|
|pytest|7.4.0|间接依赖|pip|
|lru-cache|5.1.1|间接依赖|npm|
|@fluentui/theme|2.6.22|间接依赖|npm|
|longest-streak|3.1.0|间接依赖|npm|
|mdast-util-gfm-table|1.0.7|间接依赖|npm|
|micromark-util-combine-extensions|1.0.0|间接依赖|npm|
|@fluentui/style-utilities|8.9.1|间接依赖|npm|
|bail|2.0.2|间接依赖|npm|
|@babel/code-frame|7.18.6|间接依赖|npm|
|micromark-extension-gfm-table|1.0.6|间接依赖|npm|
|mdast-util-to-hast|11.3.0|间接依赖|npm|
|unist-util-visit|4.1.2|间接依赖|npm|
|micromark-core-commonmark|1.0.6|间接依赖|npm|
|vfile|5.3.7|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.14|间接依赖|npm|
|remark-gfm|3.0.1|直接依赖|npm|
|decode-named-character-reference|1.0.2|间接依赖|npm|
|react-router|6.8.1|间接依赖|npm|
|@types/lodash|4.14.194|间接依赖|npm|
|Flask|2.3.2|间接依赖|pip|
|urllib3|2.0.4|间接依赖|pip|
|regenerator-runtime|0.13.11|间接依赖|npm|
|@fluentui/react-focus|8.8.14|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|@babel/helper-validator-identifier|7.19.1|间接依赖|npm|
|@esbuild/netbsd-x64|0.16.17|间接依赖|npm|
|micromark-util-resolve-all|1.0.0|间接依赖|npm|
|vfile-message|3.1.4|间接依赖|npm|
|@babel/template|7.20.7|间接依赖|npm|
|@emotion/hash|0.9.0|间接依赖|npm|
|@esbuild/linux-x64|0.16.17|间接依赖|npm|
|micromark-factory-destination|1.0.0|间接依赖|npm|
|@fluentui/react|8.105.4|直接依赖|npm|
|magic-string|0.27.0|间接依赖|npm|
|@esbuild/freebsd-x64|0.16.17|间接依赖|npm|
|@babel/highlight|7.18.6|间接依赖|npm|
|mdurl|1.0.1|间接依赖|npm|
|hastscript|7.2.0|间接依赖|npm|
|zwitch|2.0.4|间接依赖|npm|
|micromark-util-classify-character|1.0.0|间接依赖|npm|
|unified|10.1.2|间接依赖|npm|
|tqdm|4.65.0|间接依赖|pip|
|unist-util-visit-parents|5.1.3|间接依赖|npm|
|@types/react-dom|18.0.10|直接依赖|npm|
|@fluentui/react-portal-compat-context|9.0.4|间接依赖|npm|
|@babel/helper-module-transforms|7.20.11|间接依赖|npm|
|mdast-util-gfm-footnote|1.0.2|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|remark-parse|10.0.1|间接依赖|npm|
|@esbuild/openbsd-x64|0.16.17|间接依赖|npm|
|react-markdown|7.1.2|直接依赖|npm|
|@babel/runtime|7.21.0|间接依赖|npm|
|remark-supersub|1.0.0|直接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|@esbuild/android-x64|0.16.17|间接依赖|npm|
|unist-util-position|4.0.4|间接依赖|npm|
|fsevents|2.3.2|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)