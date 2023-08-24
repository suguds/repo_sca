# aws/aws-sdk-go-v2安全风险及SBOM

## 基础信息

项目徽章：

[![Security Status](https://www.murphysec.com/platform3/v31/badge/1694775464421056512.svg)](https://www.murphysec.com/console/report/1694412476530909184/1694775464421056512)

仓库描述：AWS SDK for the Go programming language. 

仓库地址：[https://github.com/aws/aws-sdk-go-v2](https://github.com/aws/aws-sdk-go-v2)

| star：2109 | watch：49 | fork：554 |
| ----------- | -------------- | ------------ |
| 所有者：Organization | 更新时间：2023-08-25 00:34:20 | 许可证：Apache-2.0 |
| 最近检测时间：2023-08-25 02:32:01 | 组件总数：109 | 漏洞总数：1 |

> 点击徽章可查看详细项目安全报告



## 漏洞列表

| 漏洞名称 | 漏洞类型 | MPS编号 | CVE编号 | 漏洞等级 |
| ------- | ------ | ------- | ------ | ----- |
|Google Golang 资源管理错误漏洞|拒绝服务|[MPS-2022-58307](https://www.oscs1024.com/hd/MPS-2022-58307)|CVE-2022-41723|高危|




## 缺陷组件

| 组件名称 | 版本 | 最小修复版本 | 依赖关系 | 修复建议 |
| -------- | ---- | ------------ | -------- | -------- |
|golang.org/x/net|v0.1.0|0.7.0|直接依赖|建议修复|C:0|H:1|M:0|L:0|




## 许可证风险

| 许可证类型 | 相关组件 | 许可证风险 |
| ---------- | -------- | ---------- |
|Apache-2.0|107|Low|
|BSD-3-Clause|2|Low|




## SBOM清单

| 组件名称 | 组件版本 | 是否直接依赖 | 仓库 |
| -------- | -------- | ------------ | ---- |
|github.com/aws/aws-sdk-go-v2/aws/protocol/eventstream|v1.4.13|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/pinpointemail|v1.13.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/devicefarm|v1.16.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/batch|v1.26.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/route53domains|v1.17.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sts|v1.21.5|直接依赖|go|
|github.com/aws/smithy-go|v1.14.2|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/health|v1.18.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudsearch|v1.15.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/elasticsearchservice|v1.20.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/timestreamwrite|v1.18.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2|v1.21.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codecommit|v1.16.1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudwatch|v1.27.6|直接依赖|go|
|github.com/jmespath/go-jmespath|v0.4.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/wafregional|v1.14.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssm|v1.37.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/elasticloadbalancing|v1.16.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/applicationdiscoveryservice|v1.17.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudtrail|v1.28.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/route53|v1.29.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sqs|v1.24.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/autoscaling|v1.30.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/snowball|v1.21.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/route53resolver|v1.19.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ssooidc|v1.15.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/lexruntimeservice|v1.14.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/directoryservice|v1.18.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/marketplacecommerceanalytics|v1.13.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/polly|v1.31.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/support|v1.16.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/elasticache|v1.29.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codedeploy|v1.17.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/waf|v1.13.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/shield|v1.19.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/config|v1.18.37|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/iam|v1.22.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/glacier|v1.15.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/rekognition|v1.30.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/gamelift|v1.22.2|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/configsources|v1.1.41|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/apigateway|v1.18.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/feature/ec2/imds|v1.13.11|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudhsmv2|v1.15.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codebuild|v1.21.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/rds|v1.52.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/databasemigrationservice|v1.30.4|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/dynamodb|v1.21.5|直接依赖|go|
|github.com/aws/aws-sdk-go|v1.44.28|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/dynamodbstreams|v1.15.5|直接依赖|go|
|github.com/awslabs/aws-go-multi-module-repository-tools|v0.0.0-20210920212330-85c4889f37d1|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/elasticbeanstalk|v1.16.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cognitoidentityprovider|v1.25.4|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/ini|v1.3.42|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/s3shared|v1.15.4|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/transcribestreaming|v1.10.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/glue|v1.61.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ecs|v1.29.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ses|v1.16.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/schemas|v1.16.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/elasticloadbalancingv2|v1.21.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ec2|v1.114.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/v4a|v1.1.4|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/checksum|v1.1.36|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/presigned-url|v1.9.35|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/s3control|v1.32.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/s3|v1.38.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/configservice|v1.36.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/servicecatalog|v1.21.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/endpoint-discovery|v1.7.35|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/opsworks|v1.15.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/emr|v1.28.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/ecr|v1.19.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/iot|v1.39.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/lambda|v1.39.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/costandusagereportservice|v1.17.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/efs|v1.21.6|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/elastictranscoder|v1.15.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/kms|v1.24.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/acm|v1.18.5|直接依赖|go|
|github.com/google/go-cmp|v0.5.8|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/kinesis|v1.18.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sfn|v1.19.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/appstream|v1.22.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudfront|v1.28.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/credentials|v1.13.35|直接依赖|go|
|golang.org/x/net|v0.1.0|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/firehose|v1.17.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/secretsmanager|v1.21.3|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codestar|v1.14.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/feature/dynamodb/attributevalue|v1.10.39|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/athena|v1.31.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/lightsail|v1.28.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sns|v1.21.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/workspaces|v1.29.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/internal/endpoints/v2|v2.4.35|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/docdb|v1.23.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/redshift|v1.29.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/directconnect|v1.19.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/cloudformation|v1.34.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/codepipeline|v1.16.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/eventstreamtesting|v1.0.74|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/applicationautoscaling|v1.22.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/sso|v1.13.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/neptune|v1.21.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/eventbridge|v1.20.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/wafv2|v1.37.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/inspector|v1.14.5|直接依赖|go|
|github.com/aws/aws-sdk-go-v2/service/internal/accept-encoding|v1.9.14|直接依赖|go|


------

*此检测报告由墨菲安全提供*

[墨菲安全](www.murphysec.com)