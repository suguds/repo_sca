# api-platform/core安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1701664198760382464.svg)](https://www.murphysec.com/console/report/1696590499006996480/1701664198760382464)

仓库描述：The server component of API Platform: hypermedia and GraphQL APIs in minutes

仓库地址：[https://github.com/api-platform/core](https://github.com/api-platform/core)

| star：2273 | watch：74 | fork：792 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-09-12 20:26:43 | 许可证：MIT |
| 最近检测时间：2023-09-13 02:30:57 | 组件总数：594 | 漏洞总数：15 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|npm node-fetch 不加限制的资源分配漏洞|不加限制或调节的资源分配|[MPS-2020-12719](https://www.oscs1024.com/hd/MPS-2020-12719)|CVE-2020-15168|中危|
|GraphQL Playground 跨站脚本漏洞|XSS|[MPS-2021-32017](https://www.oscs1024.com/hd/MPS-2021-32017)|CVE-2021-41248|中危|
|GraphQL Playground 跨站脚本漏洞|XSS|[MPS-2021-32018](https://www.oscs1024.com/hd/MPS-2021-32018)|CVE-2021-41249|中危|
|Markdown-It 正则表达式拒绝服务漏洞|拒绝服务|[MPS-2021-37028](https://www.oscs1024.com/hd/MPS-2021-37028)|CVE-2022-21670|中危|
|marked 存在拒绝服务漏洞||[MPS-2021-37038](https://www.oscs1024.com/hd/MPS-2021-37038)|CVE-2022-21680|高危|
|marked 存在拒绝服务漏洞|过度严格的正则表达式|[MPS-2021-37039](https://www.oscs1024.com/hd/MPS-2021-37039)|CVE-2022-21681|高危|
|ejs < 3.1.6 存在代码注入漏洞|代码注入|[MPS-2022-13642](https://www.oscs1024.com/hd/MPS-2022-13642)||中危|
|markdown-it<10.0.0 存在拒绝服务漏洞|拒绝服务|[MPS-2022-13854](https://www.oscs1024.com/hd/MPS-2022-13854)||中危|
|marked<1.1.1 存在ReDoS漏洞|ReDoS|[MPS-2022-13864](https://www.oscs1024.com/hd/MPS-2022-13864)||中危|
|node-fetch 信息泄露漏洞|未授权敏感信息泄露|[MPS-2022-1461](https://www.oscs1024.com/hd/MPS-2022-1461)|CVE-2022-0235|中危|
|node-semver 安全漏洞|ReDoS|[MPS-2022-5166](https://www.oscs1024.com/hd/MPS-2022-5166)|CVE-2022-25883|高危|
|Github ejs 安全漏洞|注入|[MPS-2022-8391](https://www.oscs1024.com/hd/MPS-2022-8391)|CVE-2022-29078|严重|
|cross-fetch 安全漏洞|授权检查错误|[MPS-2022-8877](https://www.oscs1024.com/hd/MPS-2022-8877)|CVE-2022-1365|中危|
|ejs 存在服务端模板注入漏洞|注入|[MPS-2023-10199](https://www.oscs1024.com/hd/MPS-2023-10199)|CVE-2023-29827|严重|
|Braintree sanitize-url 跨站脚本漏洞|XSS|[MPS-2023-5609](https://www.oscs1024.com/hd/MPS-2023-5609)|CVE-2022-48345|中危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|ejs|2.7.4|3.1.7|间接依赖|建议修复|C:2|H:0|M:1|L:0|
|graphql-playground-react|1.7.26|1.7.28|直接依赖|可选修复|C:0|H:0|M:1|L:0|
|graphiql|0.17.5|1.4.7|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|@braintree/sanitize-url|6.0.0|6.0.1|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|markdown-it|10.0.0|12.3.2|间接依赖|可选修复|C:0|H:0|M:1|L:0|
|marked|0.8.2|4.0.10|间接依赖|可选修复|C:0|H:2|M:1|L:0|
|markdown-it|8.4.2|12.3.2|间接依赖|可选修复|C:0|H:0|M:2|L:0|
|node-fetch|1.7.3|3.2.10|间接依赖|可选修复|C:0|H:0|M:3|L:0|
|semver|5.7.1|7.5.2|间接依赖|可选修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|ISC|20|Low|
|MIT|480|Low|
|BSD-3-Clause|23|Low|
|BSD-2-Clause|7|Low|
|Apache-2.0|8|Low|
|0BSD|2|Low|
|Unlicense|1|Low|
|Python-2.0|1|Low|
|BSD|1|Low|
|自定义许可证|1|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|semver|5.7.1|间接依赖|npm|
|react-side-effect|1.2.0|间接依赖|npm|
|json-pointer|0.6.2|间接依赖|npm|
|axios|1.4.0|间接依赖|npm|
|oas-resolver|2.5.6|间接依赖|npm|
|@wry/equality|0.1.11|间接依赖|npm|
|@graphql-tools/executor-legacy-ws|0.0.11|间接依赖|npm|
|media-typer|0.3.0|间接依赖|npm|
|tiny-invariant|1.3.1|间接依赖|npm|
|redoc|2.0.0|直接依赖|npm|
|js-file-download|0.4.12|间接依赖|npm|
|fault|1.0.4|间接依赖|npm|
|minim|0.23.8|间接依赖|npm|
|symfony/serializer|^6.1|间接依赖|composer|
|content-disposition|0.5.4|间接依赖|npm|
|@babel/helper-module-imports|7.21.4|间接依赖|npm|
|@braintree/sanitize-url|6.0.0|间接依赖|npm|
|@swagger-api/apidom-ns-openapi-3-0|0.70.0|间接依赖|npm|
|form-data|4.0.0|间接依赖|npm|
|lowlight|1.20.0|间接依赖|npm|
|shallowequal|1.1.0|间接依赖|npm|
|@whatwg-node/fetch|0.8.8|间接依赖|npm|
|loose-envify|1.4.0|间接依赖|npm|
|zen-observable-ts|0.8.21|间接依赖|npm|
|ramda|0.29.0|间接依赖|npm|
|react-transition-group|2.9.0|间接依赖|npm|
|emoji-regex|8.0.0|间接依赖|npm|
|@swagger-api/apidom-ns-api-design-systems|0.70.0|间接依赖|npm|
|@swagger-api/apidom-ns-asyncapi-2|0.70.0|间接依赖|npm|
|color-name|1.1.3|间接依赖|npm|
|tr46|0.0.3|间接依赖|npm|
|ts-invariant|0.4.4|间接依赖|npm|
|deepmerge|4.3.1|间接依赖|npm|
|cryptiles|4.1.2|间接依赖|npm|
|set-value|4.1.0|间接依赖|npm|
|inherits|2.0.4|间接依赖|npm|
|eventemitter3|3.1.2|间接依赖|npm|
|object-assign|4.1.1|间接依赖|npm|
|should-util|1.0.1|间接依赖|npm|
|prettier|2.0.2|间接依赖|npm|
|dompurify|2.3.10|间接依赖|npm|
|webidl-conversions|3.0.1|间接依赖|npm|
|is-alphabetical|1.0.4|间接依赖|npm|
|markdown-it|10.0.0|间接依赖|npm|
|react-remove-scroll-bar|2.3.4|间接依赖|npm|
|side-channel|1.0.4|间接依赖|npm|
|is-dom|1.1.0|间接依赖|npm|
|backo2|1.0.2|间接依赖|npm|
|@fontsource/open-sans|5.0.1|直接依赖|npm|
|http2-client|1.3.5|间接依赖|npm|
|jsesc|2.5.2|间接依赖|npm|
|fetch|1.1.0|直接依赖|npm|
|simple-get|3.1.1|间接依赖|npm|
|react-virtualized|9.22.5|间接依赖|npm|
|codemirror|5.65.13|间接依赖|npm|
|@swagger-api/apidom-ns-json-schema-draft-6|0.70.0|间接依赖|npm|
|stampit|4.3.2|间接依赖|npm|
|dompurify|2.4.5|间接依赖|npm|
|react-copy-to-clipboard|5.0.4|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.14|间接依赖|npm|
|merge-descriptors|1.0.1|间接依赖|npm|
|punycode|2.3.0|间接依赖|npm|
|core-js-pure|3.30.2|间接依赖|npm|
|apollo-utilities|1.3.4|间接依赖|npm|
|get-caller-file|2.0.5|间接依赖|npm|
|is-object|1.0.2|间接依赖|npm|
|@graphql-tools/schema|9.0.19|间接依赖|npm|
|type-fest|0.20.2|间接依赖|npm|
|@swagger-api/apidom-ns-openapi-3-1|0.70.0|间接依赖|npm|
|react-codemirror|1.0.0|间接依赖|npm|
|eventemitter3|4.0.7|间接依赖|npm|
|tar-stream|2.2.0|间接依赖|npm|
|has|1.0.3|间接依赖|npm|
|iconv-lite|0.6.3|间接依赖|npm|
|markdown-it|8.4.2|间接依赖|npm|
|mobx-react-lite|3.4.3|间接依赖|npm|
|is-alphanumerical|1.0.4|间接依赖|npm|
|css-to-react-native|2.3.2|间接依赖|npm|
|@swagger-api/apidom-parser-adapter-api-design-systems-yaml|0.70.0|直接依赖|npm|
|@graphql-tools/url-loader|7.17.18|间接依赖|npm|
|symfony/property-info|^6.1|间接依赖|composer|
|@emotion/is-prop-valid|0.8.8|间接依赖|npm|
|redux-localstorage|1.0.0-rc5|间接依赖|npm|
|isobject|3.0.1|间接依赖|npm|
|uri-js|4.4.1|间接依赖|npm|
|short-unique-id|4.4.4|间接依赖|npm|
|colorette|1.4.0|间接依赖|npm|
|focus-lock|0.11.6|间接依赖|npm|
|oas-schema-walker|1.1.5|间接依赖|npm|
|xml|1.0.1|间接依赖|npm|
|@jridgewell/set-array|1.1.2|间接依赖|npm|
|punycode|1.3.2|间接依赖|npm|
|react-immutable-proptypes|2.2.0|间接依赖|npm|
|supports-color|5.5.0|间接依赖|npm|
|gzip-size|5.1.1|间接依赖|npm|
|@babel/helper-split-export-declaration|7.18.6|间接依赖|npm|
|subscriptions-transport-ws|0.9.19|间接依赖|npm|
|encoding|0.1.12|间接依赖|npm|
|path-to-regexp|1.8.0|间接依赖|npm|
|memoize-one|5.2.1|间接依赖|npm|
|space-separated-tokens|1.1.5|间接依赖|npm|
|mime-db|1.52.0|间接依赖|npm|
|strip-ansi|6.0.1|间接依赖|npm|
|@graphql-typed-document-node/core|3.2.0|间接依赖|npm|
|tiny-warning|1.0.3|间接依赖|npm|
|iterall|1.3.0|间接依赖|npm|
|@reach/tooltip|0.17.0|间接依赖|npm|
|@exodus/schemasafe|1.0.1|间接依赖|npm|
|markdown-it|12.3.2|间接依赖|npm|
|isarray|0.0.1|间接依赖|npm|
|ts-toolbelt|9.6.0|间接依赖|npm|
|on-finished|2.4.1|间接依赖|npm|
|redux-saga|1.2.3|间接依赖|npm|
|use-sidecar|1.1.2|间接依赖|npm|
|react-fast-compare|2.0.4|间接依赖|npm|
|set-blocking|2.0.0|间接依赖|npm|
|url|0.11.0|间接依赖|npm|
|content-type|1.0.5|间接依赖|npm|
|ms|2.1.2|间接依赖|npm|
|node-fetch|2.6.11|间接依赖|npm|
|@swagger-api/apidom-parser-adapter-openapi-yaml-3-1|0.70.0|直接依赖|npm|
|tunnel-agent|0.6.0|间接依赖|npm|
|array-flatten|1.1.1|间接依赖|npm|
|@babel/generator|7.21.9|间接依赖|npm|
|balanced-match|1.0.2|间接依赖|npm|
|ms|2.1.3|间接依赖|npm|
|classnames|2.3.2|间接依赖|npm|
|web-streams-polyfill|4.0.0-beta.3|间接依赖|npm|
|value-equal|1.0.1|间接依赖|npm|
|@reach/visually-hidden|0.17.0|间接依赖|npm|
|to-camel-case|1.0.0|间接依赖|npm|
|escalade|3.1.1|间接依赖|npm|
|swagger-ui|4.14.2|直接依赖|npm|
|@reach/auto-id|0.17.0|间接依赖|npm|
|parse-entities|2.0.0|间接依赖|npm|
|to-no-case|1.0.2|间接依赖|npm|
|whatwg-fetch|3.6.2|间接依赖|npm|
|json-schema-traverse|1.0.0|间接依赖|npm|
|has-symbols|1.0.3|间接依赖|npm|
|vary|1.1.2|间接依赖|npm|
|minimatch|5.1.6|间接依赖|npm|
|ipaddr.js|1.9.1|间接依赖|npm|
|decko|1.2.0|间接依赖|npm|
|finalhandler|1.2.0|间接依赖|npm|
|querystring|0.2.0|间接依赖|npm|
|forwarded|0.2.0|间接依赖|npm|
|@reach/descendants|0.17.0|间接依赖|npm|
|require-directory|2.1.1|间接依赖|npm|
|react|18.2.0|直接依赖|npm|
|@types/scheduler|0.16.3|间接依赖|npm|
|willdurand/negotiation|^3.0|间接依赖|composer|
|graphql-language-service-interface|2.10.2|间接依赖|npm|
|globals|11.12.0|间接依赖|npm|
|negotiator|0.6.3|间接依赖|npm|
|redux-immutable|4.0.0|间接依赖|npm|
|hastscript|6.0.0|间接依赖|npm|
|tree-sitter|0.20.1|间接依赖|npm|
|scheduler|0.19.1|间接依赖|npm|
|@types/node|14.18.47|间接依赖|npm|
|cookie-signature|1.0.6|间接依赖|npm|
|fast-safe-stringify|2.1.1|间接依赖|npm|
|resolve-pathname|3.0.0|间接依赖|npm|
|serve-static|1.15.0|间接依赖|npm|
|decode-uri-component|0.2.2|间接依赖|npm|
|wrap-ansi|7.0.0|间接依赖|npm|
|detect-libc|1.0.3|间接依赖|npm|
|jsonify|0.0.1|间接依赖|npm|
|isomorphic-ws|5.0.0|间接依赖|npm|
|redux-actions|2.6.5|间接依赖|npm|
|escape-html|1.0.3|间接依赖|npm|
|to-fast-properties|2.0.0|间接依赖|npm|
|@reach/observe-rect|1.2.0|间接依赖|npm|
|typescript-tuple|2.2.1|间接依赖|npm|
|mobx-react|7.6.0|间接依赖|npm|
|biskviit|1.0.1|间接依赖|npm|
|node-fetch|1.7.3|间接依赖|npm|
|simple-concat|1.0.1|间接依赖|npm|
|es6-promise|3.3.1|间接依赖|npm|
|regenerator-runtime|0.11.1|间接依赖|npm|
|foreach|2.0.6|间接依赖|npm|
|@swagger-api/apidom-ns-json-schema-draft-7|0.70.0|间接依赖|npm|
|cuid|1.3.8|间接依赖|npm|
|js-yaml|4.1.0|间接依赖|npm|
|graphql-language-service-types|1.8.7|间接依赖|npm|
|ieee754|1.2.1|间接依赖|npm|
|once|1.4.0|间接依赖|npm|
|zen-observable|0.8.15|间接依赖|npm|
|toggle-selection|1.0.6|间接依赖|npm|
|js-yaml|3.14.1|间接依赖|npm|
|react-redux|7.2.9|间接依赖|npm|
|property-information|5.6.0|间接依赖|npm|
|swagger-client|3.19.8|间接依赖|npm|
|path-browserify|1.0.1|间接依赖|npm|
|stylis|3.5.4|间接依赖|npm|
|typescript-compare|0.0.2|间接依赖|npm|
|react-style-singleton|2.2.1|间接依赖|npm|
|@redux-saga/core|1.2.3|间接依赖|npm|
|linkify-it|3.0.3|间接依赖|npm|
|core-js|2.6.12|间接依赖|npm|
|duplexer|0.1.2|间接依赖|npm|
|comma-separated-tokens|1.0.8|间接依赖|npm|
|unraw|2.0.1|间接依赖|npm|
|ansi-styles|4.3.0|间接依赖|npm|
|unpipe|1.0.0|间接依赖|npm|
|strict-uri-encode|1.1.0|间接依赖|npm|
|asynckit|0.4.0|间接依赖|npm|
|path-to-regexp|0.1.7|间接依赖|npm|
|fast-json-stable-stringify|2.1.0|间接依赖|npm|
|apollo-link-ws|1.0.20|间接依赖|npm|
|graphql-language-service-parser|1.10.4|间接依赖|npm|
|symfony/http-kernel|^6.1|间接依赖|composer|
|copy-to-clipboard|3.3.3|间接依赖|npm|
|use-callback-ref|1.3.0|间接依赖|npm|
|@types/lru-cache|4.1.3|间接依赖|npm|
|@reach/menu-button|0.17.0|间接依赖|npm|
|css-color-keywords|1.0.0|间接依赖|npm|
|parseurl|1.3.3|间接依赖|npm|
|symbol-observable|1.2.0|间接依赖|npm|
|highlight.js|10.7.3|间接依赖|npm|
|keycode|2.2.1|间接依赖|npm|
|graphql-language-service|5.1.6|间接依赖|npm|
|babel-plugin-syntax-jsx|6.18.0|间接依赖|npm|
|deep-extend|0.6.0|间接依赖|npm|
|@swagger-api/apidom-parser-adapter-api-design-systems-json|0.70.0|直接依赖|npm|
|pluralize|8.0.0|间接依赖|npm|
|unixify|1.0.0|间接依赖|npm|
|node-domexception|1.0.0|间接依赖|npm|
|@jridgewell/trace-mapping|0.3.18|间接依赖|npm|
|chalk|2.4.2|间接依赖|npm|
|proxy-from-env|1.1.0|间接依赖|npm|
|react-tabs|3.2.3|间接依赖|npm|
|is-stream|1.1.0|间接依赖|npm|
|@babel/helper-annotate-as-pure|7.18.6|间接依赖|npm|
|react-display-name|0.2.5|间接依赖|npm|
|react-debounce-input|3.3.0|间接依赖|npm|
|codemirror-graphql|0.11.6|间接依赖|npm|
|combined-stream|1.0.8|间接依赖|npm|
|tree-sitter-json|0.20.0|间接依赖|npm|
|warning|4.0.3|间接依赖|npm|
|isomorphic-fetch|2.2.1|间接依赖|npm|
|p-limit|3.1.0|间接依赖|npm|
|reftools|1.1.9|间接依赖|npm|
|escape-string-regexp|1.0.5|间接依赖|npm|
|type-is|1.6.18|间接依赖|npm|
|@babel/runtime-corejs3|7.21.5|间接依赖|npm|
|@babel/code-frame|7.21.4|间接依赖|npm|
|@reach/machine|0.17.0|间接依赖|npm|
|toidentifier|1.0.1|间接依赖|npm|
|graphql-playground-react|1.7.26|直接依赖|npm|
|stylis-rule-sheet|0.0.10|间接依赖|npm|
|graphql|15.8.0|间接依赖|npm|
|@graphql-tools/executor-graphql-ws|0.0.14|间接依赖|npm|
|psr/cache|^1.0 || ^2.0 || ^3.0|间接依赖|composer|
|is-plain-object|5.0.0|间接依赖|npm|
|linkify-it|2.2.0|间接依赖|npm|
|@types/react|18.2.7|间接依赖|npm|
|autolinker|3.16.2|间接依赖|npm|
|react-lifecycles-compat|3.0.4|间接依赖|npm|
|ini|1.3.8|间接依赖|npm|
|ansi-regex|5.0.1|间接依赖|npm|
|qs|6.11.0|间接依赖|npm|
|tree-sitter-yaml|0.5.0|间接依赖|npm|
|expand-template|2.0.3|间接依赖|npm|
|@graphql-tools/json-file-loader|7.4.18|间接依赖|npm|
|ansi-styles|3.2.1|间接依赖|npm|
|@types/ramda|0.29.1|间接依赖|npm|
|boom|7.3.0|间接依赖|npm|
|strip-json-comments|2.0.1|间接依赖|npm|
|sha.js|2.4.11|间接依赖|npm|
|react-remove-scroll|2.5.6|间接依赖|npm|
|@redux-saga/is|1.1.3|间接依赖|npm|
|react-is|16.13.1|间接依赖|npm|
|get-intrinsic|1.2.1|间接依赖|npm|
|react|17.0.2|间接依赖|npm|
|@graphql-tools/graphql-file-loader|7.5.17|间接依赖|npm|
|postcss-value-parser|3.3.1|间接依赖|npm|
|to-space-case|1.0.0|间接依赖|npm|
|uc.micro|1.0.6|间接依赖|npm|
|tar-fs|2.1.1|间接依赖|npm|
|babel-runtime|6.26.0|间接依赖|npm|
|body-parser|1.20.1|间接依赖|npm|
|pump|3.0.0|间接依赖|npm|
|follow-redirects|1.15.2|间接依赖|npm|
|immutable|3.8.2|间接依赖|npm|
|hoist-non-react-statics|3.3.2|间接依赖|npm|
|proxy-addr|2.0.7|间接依赖|npm|
|@graphql-tools/delegate|9.0.35|间接依赖|npm|
|is-fullwidth-code-point|3.0.0|间接依赖|npm|
|babel-plugin-styled-components|2.1.3|间接依赖|npm|
|randexp|0.5.3|间接依赖|npm|
|@jridgewell/resolve-uri|3.1.0|间接依赖|npm|
|lodash.debounce|3.1.1|间接依赖|npm|
|js-levenshtein|1.1.6|间接依赖|npm|
|form-data-encoder|1.9.0|间接依赖|npm|
|@swagger-api/apidom-parser-adapter-asyncapi-yaml-2|0.70.0|直接依赖|npm|
|globby|11.1.0|间接依赖|npm|
|just-curry-it|3.2.1|间接依赖|npm|
|hoopy|0.1.4|间接依赖|npm|
|@babel/helper-environment-visitor|7.21.5|间接依赖|npm|
|@reach/rect|0.17.0|间接依赖|npm|
|symfony/property-access|^6.1|间接依赖|composer|
|prismjs|1.29.0|间接依赖|npm|
|is-what|3.14.1|间接依赖|npm|
|call-bind|1.0.2|间接依赖|npm|
|meros|1.2.1|间接依赖|npm|
|xtend|4.0.2|间接依赖|npm|
|@babel/types|7.21.5|间接依赖|npm|
|color-convert|1.9.3|间接依赖|npm|
|@redux-saga/delay-p|1.2.1|间接依赖|npm|
|css.escape|1.5.1|间接依赖|npm|
|@redux-saga/symbols|1.1.3|间接依赖|npm|
|doctrine/inflector|^1.0 || ^2.0|间接依赖|composer|
|lodash|4.17.21|间接依赖|npm|
|tslib|1.14.1|间接依赖|npm|
|immutable|4.3.0|间接依赖|npm|
|@swagger-api/apidom-parser-adapter-json|0.70.0|间接依赖|npm|
|graphql-language-service-utils|2.7.1|间接依赖|npm|
|function-bind|1.1.1|间接依赖|npm|
|@graphiql/toolkit|0.8.4|间接依赖|npm|
|esprima|4.0.1|间接依赖|npm|
|@redocly/ajv|8.11.0|间接依赖|npm|
|symfony/deprecation-contracts|^3.1|间接依赖|composer|
|randombytes|2.1.0|间接依赖|npm|
|redux-localstorage-debounce|0.1.0|间接依赖|npm|
|@reach/utils|0.17.0|间接依赖|npm|
|safe-buffer|5.2.1|间接依赖|npm|
|etag|1.8.1|间接依赖|npm|
|apollo-link-http|1.5.17|间接依赖|npm|
|destroy|1.2.0|间接依赖|npm|
|base64-js|1.5.1|间接依赖|npm|
|argparse|1.0.10|间接依赖|npm|
|oas-linter|3.2.2|间接依赖|npm|
|string-env-interpolation|1.0.1|间接依赖|npm|
|react-dom|18.2.0|直接依赖|npm|
|redux|4.2.1|间接依赖|npm|
|ms|2.0.0|间接依赖|npm|
|parse-json|5.2.0|间接依赖|npm|
|codemirror-graphql|0.12.4|间接依赖|npm|
|entities|2.0.3|间接依赖|npm|
|prismjs|1.27.0|间接依赖|npm|
|graphql-config|4.5.0|间接依赖|npm|
|lunr|2.3.9|间接依赖|npm|
|cookie|0.5.0|间接依赖|npm|
|depd|2.0.0|间接依赖|npm|
|graphiql|2.4.5|直接依赖|npm|
|should|13.2.3|间接依赖|npm|
|@swagger-api/apidom-ns-json-schema-draft-4|0.70.0|间接依赖|npm|
|query-string|5.1.1|间接依赖|npm|
|openapi-sampler|1.3.1|间接依赖|npm|
|xml-but-prettier|1.0.1|间接依赖|npm|
|react-focus-lock|2.9.4|间接依赖|npm|
|react-addons-shallow-compare|15.6.3|间接依赖|npm|
|react-modal|3.16.1|间接依赖|npm|
|process|0.11.10|间接依赖|npm|
|setprototypeof|1.2.0|间接依赖|npm|
|web-tree-sitter|0.20.7|间接依赖|npm|
|should-type-adaptors|1.1.0|间接依赖|npm|
|safer-buffer|2.1.2|间接依赖|npm|
|range-parser|1.2.1|间接依赖|npm|
|cosmiconfig|8.0.0|间接依赖|npm|
|react-sortable-hoc|0.8.4|间接依赖|npm|
|yargs-parser|21.1.1|间接依赖|npm|
|react-clientside-effect|1.2.6|间接依赖|npm|
|symfony/web-link|^6.1|间接依赖|composer|
|entities|2.1.0|间接依赖|npm|
|@graphql-tools/utils|9.2.1|间接依赖|npm|
|brace-expansion|2.0.1|间接依赖|npm|
|psr/container|^1.0 || ^2.0|间接依赖|composer|
|utility-types|1.1.0|间接依赖|npm|
|@xstate/fsm|1.4.0|间接依赖|npm|
|zenscroll|4.0.2|间接依赖|npm|
|should-equal|2.0.0|间接依赖|npm|
|url-parse|1.5.10|间接依赖|npm|
|styled-components|4.4.1|间接依赖|npm|
|nullthrows|1.1.1|间接依赖|npm|
|browser-fingerprint|0.0.1|间接依赖|npm|
|is-decimal|1.0.4|间接依赖|npm|
|@redocly/openapi-core|1.0.0-beta.126|间接依赖|npm|
|utils-merge|1.0.1|间接依赖|npm|
|@swagger-api/apidom-json-pointer|0.70.0|直接依赖|npm|
|accepts|1.3.8|间接依赖|npm|
|@reach/dialog|0.17.0|间接依赖|npm|
|fast-deep-equal|3.1.3|间接依赖|npm|
|minimist|1.2.8|间接依赖|npm|
|express|4.18.2|间接依赖|npm|
|@types/json-schema|7.0.9|间接依赖|npm|
|calculate-size|1.1.1|间接依赖|npm|
|encoding|0.1.13|间接依赖|npm|
|is-plain-object|2.0.4|间接依赖|npm|
|path-type|4.0.0|间接依赖|npm|
|repeat-string|1.6.1|间接依赖|npm|
|mkdirp|0.5.6|间接依赖|npm|
|@graphql-tools/load|7.8.14|间接依赖|npm|
|@types/hast|2.3.4|间接依赖|npm|
|create-react-class|15.7.0|间接依赖|npm|
|argparse|2.0.1|间接依赖|npm|
|end-of-stream|1.4.4|间接依赖|npm|
|value-or-promise|1.0.12|间接依赖|npm|
|node-abi|2.30.1|间接依赖|npm|
|mime-types|2.1.35|间接依赖|npm|
|exenv|1.2.2|间接依赖|npm|
|apollo-link-http-common|0.2.16|间接依赖|npm|
|react-router|4.3.1|间接依赖|npm|
|@reach/popover|0.17.0|间接依赖|npm|
|js-tokens|4.0.0|间接依赖|npm|
|character-reference-invalid|1.1.4|间接依赖|npm|
|marked|4.3.0|间接依赖|npm|
|@babel/parser|7.21.9|间接依赖|npm|
|@types/json-schema|7.0.11|间接依赖|npm|
|@swagger-api/apidom-parser-adapter-openapi-yaml-3-0|0.70.0|直接依赖|npm|
|prop-types|15.8.1|间接依赖|npm|
|acorn-walk|7.2.0|间接依赖|npm|
|@redux-saga/types|1.2.1|间接依赖|npm|
|symfony/translation-contracts|^3.3|间接依赖|composer|
|vscode-languageserver-types|3.17.3|间接依赖|npm|
|@types/prop-types|15.7.5|间接依赖|npm|
|querystringify|2.2.0|间接依赖|npm|
|webpack-bundle-analyzer|3.9.0|间接依赖|npm|
|ws|6.2.2|间接依赖|npm|
|hoist-non-react-statics|2.5.5|间接依赖|npm|
|filesize|3.6.1|间接依赖|npm|
|requires-port|1.0.0|间接依赖|npm|
|@swagger-api/apidom-core|0.70.0|间接依赖|npm|
|cross-fetch|3.1.6|间接依赖|npm|
|character-entities-legacy|1.1.4|间接依赖|npm|
|acorn|7.4.1|间接依赖|npm|
|remarkable|2.0.1|间接依赖|npm|
|@graphql-tools/executor-http|0.1.10|间接依赖|npm|
|minimatch|7.4.6|间接依赖|npm|
|seamless-immutable|7.1.4|间接依赖|npm|
|check-types|8.0.3|间接依赖|npm|
|graphiql|0.17.5|间接依赖|npm|
|@emotion/unitless|0.7.5|间接依赖|npm|
|lodash.debounce|4.0.8|间接依赖|npm|
|csstype|3.1.2|间接依赖|npm|
|ramda-adjunct|4.0.0|间接依赖|npm|
|reduce-reducers|0.4.3|间接依赖|npm|
|core-js|1.2.7|间接依赖|npm|
|stickyfill|1.1.1|间接依赖|npm|
|invariant|2.2.4|间接依赖|npm|
|@swagger-api/apidom-ast|0.70.0|间接依赖|npm|
|encodeurl|1.0.2|间接依赖|npm|
|scheduler|0.23.0|间接依赖|npm|
|raw-body|2.5.1|间接依赖|npm|
|object-inspect|1.12.3|间接依赖|npm|
|bytes|3.1.2|间接依赖|npm|
|hoek|6.1.3|间接依赖|npm|
|mark.js|8.11.1|间接依赖|npm|
|pify|4.0.1|间接依赖|npm|
|@reach/dropdown|0.17.0|间接依赖|npm|
|are-we-there-yet|1.1.7|间接依赖|npm|
|merge-anything|2.4.4|间接依赖|npm|
|mime|1.6.0|间接依赖|npm|
|@babel/highlight|7.18.6|间接依赖|npm|
|commander|2.20.3|间接依赖|npm|
|regenerator-runtime|0.13.11|间接依赖|npm|
|send|0.18.0|间接依赖|npm|
|@types/hoist-non-react-statics|3.3.1|间接依赖|npm|
|@redux-saga/deferred|1.2.1|间接依赖|npm|
|@babel/runtime|7.21.5|间接依赖|npm|
|character-entities|1.2.4|间接依赖|npm|
|symfony/http-foundation|^6.1|间接依赖|composer|
|@reach/combobox|0.17.0|间接依赖|npm|
|gauge|2.7.4|间接依赖|npm|
|has-proto|1.0.1|间接依赖|npm|
|zen-observable|0.7.1|间接依赖|npm|
|string-width|4.2.3|间接依赖|npm|
|react-dom|17.0.2|间接依赖|npm|
|opener|1.5.2|间接依赖|npm|
|async-limiter|1.0.1|间接依赖|npm|
|url-template|2.0.8|间接依赖|npm|
|get-nonce|1.0.1|间接依赖|npm|
|tabbable|4.0.0|间接依赖|npm|
|tryer|1.0.1|间接依赖|npm|
|camelize|1.0.1|间接依赖|npm|
|whatwg-url|5.0.0|间接依赖|npm|
|json-stable-stringify|1.0.2|间接依赖|npm|
|@graphql-tools/merge|8.4.2|间接依赖|npm|
|marked|0.8.2|间接依赖|npm|
|is-primitive|3.0.1|间接依赖|npm|
|ws|7.5.9|间接依赖|npm|
|types-ramda|0.29.2|间接依赖|npm|
|tslib|2.5.2|间接依赖|npm|
|should-format|3.0.3|间接依赖|npm|
|react-helmet|5.2.1|间接依赖|npm|
|prebuild-install|6.1.4|间接依赖|npm|
|psl|1.9.0|间接依赖|npm|
|react-router-dom|4.3.1|间接依赖|npm|
|polished|4.2.2|间接依赖|npm|
|typescript-logic|0.0.0|间接依赖|npm|
|@reach/listbox|0.17.0|间接依赖|npm|
|bluebird|3.7.2|间接依赖|npm|
|node-fetch-h2|2.3.0|间接依赖|npm|
|@n1ru4l/push-pull-async-iterable-iterator|3.2.0|间接依赖|npm|
|dom-helpers|5.2.1|间接依赖|npm|
|history|4.10.1|间接依赖|npm|
|scheduler|0.20.2|间接依赖|npm|
|debug|2.6.9|间接依赖|npm|
|@graphiql/react|0.17.5|间接依赖|npm|
|@babel/helper-validator-identifier|7.19.1|间接依赖|npm|
|fast-json-patch|3.1.1|间接依赖|npm|
|react-inspector|5.1.1|间接依赖|npm|
|style-loader|3.3.3|间接依赖|npm|
|debug|4.3.4|间接依赖|npm|
|node-readfiles|0.2.0|间接依赖|npm|
|drange|1.1.1|间接依赖|npm|
|brace-expansion|1.1.11|间接依赖|npm|
|github-from-package|0.0.0|间接依赖|npm|
|react-copy-to-clipboard|5.1.0|间接依赖|npm|
|format|0.2.2|间接依赖|npm|
|@swagger-api/apidom-reference|0.70.0|间接依赖|npm|
|require-from-string|2.0.2|间接依赖|npm|
|ee-first|1.1.1|间接依赖|npm|
|react|16.13.1|间接依赖|npm|
|@swagger-api/apidom-parser-adapter-asyncapi-json-2|0.70.0|直接依赖|npm|
|call-me-maybe|1.0.2|间接依赖|npm|
|chownr|1.1.4|间接依赖|npm|
|iconv-lite|0.4.24|间接依赖|npm|
|ret|0.2.2|间接依赖|npm|
|perfect-scrollbar|1.5.5|间接依赖|npm|
|entities|2.2.0|间接依赖|npm|
|clsx|1.2.1|间接依赖|npm|
|@types/react-redux|7.1.25|间接依赖|npm|
|minimatch|4.2.3|间接依赖|npm|
|@swagger-api/apidom-parser-adapter-openapi-json-3-1|0.70.0|直接依赖|npm|
|jiti|1.17.1|间接依赖|npm|
|reselect|4.1.8|间接依赖|npm|
|mdurl|1.0.1|间接依赖|npm|
|is-window|1.0.2|间接依赖|npm|
|@jridgewell/sourcemap-codec|1.4.15|间接依赖|npm|
|traverse|0.6.7|间接依赖|npm|
|detect-node-es|1.1.0|间接依赖|npm|
|react-immutable-pure-component|2.2.2|间接依赖|npm|
|slugify|1.4.7|间接依赖|npm|
|entities|1.1.2|间接依赖|npm|
|@babel/helper-hoist-variables|7.18.6|间接依赖|npm|
|react-input-autosize|2.2.2|间接依赖|npm|
|nan|2.17.0|间接依赖|npm|
|lodash._getnative|3.9.1|间接依赖|npm|
|swagger2openapi|7.0.8|间接依赖|npm|
|fresh|0.5.2|间接依赖|npm|
|redux-localstorage-filter|0.1.1|间接依赖|npm|
|rc|1.2.8|间接依赖|npm|
|http-errors|2.0.0|间接依赖|npm|
|qs|6.11.2|间接依赖|npm|
|methods|1.1.2|间接依赖|npm|
|console-control-strings|1.1.0|间接依赖|npm|
|yargs|17.7.2|间接依赖|npm|
|oas-validator|5.0.8|间接依赖|npm|
|import-fresh|3.3.0|间接依赖|npm|
|@babel/traverse|7.21.5|间接依赖|npm|
|@babel/template|7.21.9|间接依赖|npm|
|node-fingerprint|0.0.2|间接依赖|npm|
|react-syntax-highlighter|15.5.0|间接依赖|npm|
|react-is|17.0.2|间接依赖|npm|
|oas-kit-common|1.0.8|间接依赖|npm|
|yaml-ast-parser|0.0.43|间接依赖|npm|
|serialize-error|8.1.0|间接依赖|npm|
|y18n|5.0.8|间接依赖|npm|
|has-flag|3.0.0|间接依赖|npm|
|@jridgewell/gen-mapping|0.3.3|间接依赖|npm|
|should-type|1.4.0|间接依赖|npm|
|@emotion/memoize|0.7.4|间接依赖|npm|
|@swagger-api/apidom-parser-adapter-openapi-json-3-0|0.70.0|直接依赖|npm|
|formdata-node|4.4.1|间接依赖|npm|
|npmlog|4.1.2|间接依赖|npm|
|apollo-link|1.2.14|间接依赖|npm|
|napi-build-utils|1.0.2|间接依赖|npm|
|@swagger-api/apidom-parser-adapter-yaml-1-2|0.70.0|间接依赖|npm|
|codemirror-graphql|2.0.8|间接依赖|npm|
|@types/ws|8.5.4|间接依赖|npm|
|@reach/portal|0.17.0|间接依赖|npm|
|@babel/helper-string-parser|7.21.5|间接依赖|npm|
|ws|8.13.0|间接依赖|npm|
|react-dom|16.14.0|间接依赖|npm|
|@ardatan/sync-fetch|0.0.1|间接依赖|npm|
|yaml|1.10.2|间接依赖|npm|
|refractor|3.6.0|间接依赖|npm|
|hast-util-parse-selector|2.2.5|间接依赖|npm|
|sprintf-js|1.0.3|间接依赖|npm|
|picomatch|2.3.1|间接依赖|npm|
|@graphql-tools/import|6.7.18|间接依赖|npm|
|dom-helpers|3.4.0|间接依赖|npm|
|@babel/helper-function-name|7.21.0|间接依赖|npm|
|@types/unist|2.0.6|间接依赖|npm|
|decompress-response|4.2.1|间接依赖|npm|
|is-hexadecimal|1.0.4|间接依赖|npm|
|cliui|8.0.1|间接依赖|npm|
|mkdirp-classic|0.5.3|间接依赖|npm|
|ejs|2.7.4|间接依赖|npm|
|lodash.isequal|4.5.0|间接依赖|npm|
|@graphql-tools/wrap|9.4.2|间接依赖|npm|
|statuses|2.0.1|间接依赖|npm|
|bfj|6.1.2|间接依赖|npm|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)