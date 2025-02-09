# Table of contents

* [Github Open Source Repo](https://github.com/akto-api-security/community-edition)
* [What is Akto?](README.md)
* [AktoGPT](aktogpt.md)

## Getting Started

* [Akto Cloud](getting-started/quick-start-with-akto-cloud.md)
* [Akto Self Hosted](getting-started/quick-start-with-akto-self-hosted.md)
* [AWS deploy](getting-started/aws-deploy.md)
* [AWS multi-VPC deploy](getting-started/aws-multi-vpc-deploy.md)
* [AWS Cross-Region Cross-VPC deploy](getting-started/aws-cross-region-vpc-deploy.md)
* [Custom subdomain on Akto on AWS](getting-started/aws-ssl.md)
* [GCP Deploy](getting-started/gcp-deploy.md)
* [Local Deploy](getting-started/local-deploy.md)
* [Azure Deploy](getting-started/azure-deploy.md)
* [Helm Deploy](getting-started/helm-deploy.md)
* [Heroku](getting-started/heroku.md)
* [FAQs on data concerns](getting-started/faqs-on-data-concerns.md)

## Traffic Connections

* [API Traffic data connectors](traffic-connections/traffic-data-sources/README.md)
  * [Connect Akto with AWS Traffic Mirroring](traffic-connections/traffic-data-sources/amazon-aws.md)
  * [Connect Akto with AWS EKS](traffic-connections/traffic-data-sources/aws-eks.md)
  * [Connect Akto with AWS Fargate](traffic-connections/traffic-data-sources/aws-fargate.md)
  * [Connect Akto with AWS Beanstalk](traffic-connections/traffic-data-sources/aws-beanstalk.md)
  * [Connect Akto with Kubernetes in AWS](traffic-connections/traffic-data-sources/kubernetes.md)
  * [Connect Akto with AWS API Gateway](traffic-connections/traffic-data-sources/aws-api-gateway.md)
  * [Connect Akto with Kong](traffic-connections/traffic-data-sources/kong.md)
  * [Connect Akto with NGINX](traffic-connections/traffic-data-sources/nginx.md)
  * [Connect Akto with Envoy](traffic-connections/traffic-data-sources/envoy.md)
  * [Connect Akto with Istio](traffic-connections/traffic-data-sources/envoy-1.md)
  * [Connect Akto with Docker](traffic-connections/traffic-data-sources/docker.md)
  * [Connect Akto with TCP Agent](traffic-connections/traffic-data-sources/tcp-agent.md)
  * [Connect Akto with eBPF](traffic-connections/traffic-data-sources/ebpf.md)
  * [Add API traffic to Akto using HAR file upload](traffic-connections/traffic-data-sources/har-file-upload.md)
  * [Connect Akto with GCP Packet Mirroring](traffic-connections/traffic-data-sources/google-cloud-gcp.md)
  * [Connect Akto with Burp suite](traffic-connections/traffic-data-sources/burp-suite.md)
  * [Connect Akto with Postman](traffic-connections/traffic-data-sources/postman.md)
  * [Connect Akto with OpenAPI](traffic-connections/traffic-data-sources/openapi.md)
  * [Akto SDK](traffic-connections/traffic-data-sources/akto-sdk.md)

## API Inventory

* [Concepts](api-inventory/concepts/README.md)
  * [API Endpoints](api-inventory/concepts/api-endpoints.md)
  * [Meta Properties of API Endpoint](api-inventory/concepts/meta-properties-of-api-endpoint.md)
  * [API Collection](api-inventory/concepts/api-collection.md)
  * [Data Types](api-inventory/concepts/data-types.md)
  * [API Changes](api-inventory/concepts/api-changes.md)
  * [Sensitive Data](api-inventory/concepts/sensitive-data.md)
  * [Alerts](api-inventory/concepts/alerts.md)
  * [Risk Score](api-inventory/concepts/risk-score.md)
  * [Auth types](api-inventory/concepts/auth-types.md)
* [How-To](api-inventory/how-to/README.md)
  * [Export an API Collection to Postman](api-inventory/how-to/export-an-api-collection-to-postman.md)
  * [Export an API Collection to Burp](api-inventory/how-to/export-an-api-collection-to-burp.md)
  * [Create Swagger File Using Akto](api-inventory/how-to/create-swagger-file-using-akto.md)
  * [Copy API Endpoints Data](api-inventory/how-to/copy-api-endpoints-data.md)
  * [Add an API Collection](api-inventory/how-to/add-an-api-collection.md)
  * [Delete an API Collection](api-inventory/how-to/delete-an-api-collection.md)
  * [Create a Custom Data Type](api-inventory/how-to/create-a-custom-data-type.md)
  * [Set Sensitivity of a Data Type](api-inventory/how-to/set-sensitivity-of-a-data-type.md)
  * [De-activate a data type](api-inventory/how-to/de-activate-a-data-type.md)
  * [Add a Custom Auth Type](api-inventory/how-to/add-a-custom-auth-type.md)
  * [Reset an Auth Type](api-inventory/how-to/reset-an-auth-type.md)
  * [View New API Endpoint](api-inventory/how-to/view-new-api-endpoint.md)
  * [View New Parameters](api-inventory/how-to/view-new-parameters.md)
  * [Configure alerts on API changes](api-inventory/how-to/configure-alerts-on-api-changes.md)
  * [Create a custom collection](api-inventory/how-to/how-to-create-a-custom-collection.md)

## Test Editor

* [Overview](test-editor/overview.md)
* [Test Library](test-editor/test-library/README.md)
  * [Local File Inclusion with Akto](test-editor/test-library/local-file-inclusion-with-akto.md)
* [Test YAML Syntax (One pager)](test-editor/test-yaml-syntax-one-pager.md)
* [Test YAML Syntax (Detailed)](test-editor/test-yaml-syntax-detailed/README.md)
  * [ID](test-editor/test-yaml-syntax-detailed/id.md)
  * [Info](test-editor/test-yaml-syntax-detailed/info.md)
  * [API Selection Filters](test-editor/test-yaml-syntax-detailed/api-selection-filters.md)
  * [Execute](test-editor/test-yaml-syntax-detailed/execute.md)
  * [Auth](test-editor/test-yaml-syntax-detailed/auth.md)
  * [Validation](test-editor/test-yaml-syntax-detailed/validation.md)
* [Editing built in test](test-editor/editing-built-in-test.md)
* [Writing Custom Tests](test-editor/writing-custom-tests.md)

## TESTING

* [Run tests in CICD](testing/run-tests-in-cicd.md)
* [GitHub integration for CICD test reporting](testing/github\_integration\_testing/README.md)
  * [Github App creation and integration in Akto](testing/github\_integration\_testing/github\_app\_integration.md)
* [Run tests in CLI using Akto](testing/run-tests-in-cli-using-akto.md)
* [Run test](testing/run-test.md)
* [Create user config](testing/create-user-config.md)
* [Test results](testing/test-results.md)
* [Test library](testing/test-library.md)
* [Test roles](testing/user-roles.md)

## SSO

* [Azure AD SAML](sso/azureAd-saml.md)
* [Okta OIDC](sso/okta-oidc.md)
* [Github OIDC](sso/github-oidc.md)

***

* [Github contribution guide](github-contribution-guide.md)

## API reference

* [API reference](api-reference/api-reference.md)

## Components

* [Dashboard](components/dashboard.md)
* [Testing module](components/testing-module.md)
* [Traffic mirroring module](components/traffic-mirroring-module.md)
* [Runtime analyzer](components/runtime-analyzer.md)
* [Context analyzer](components/context-analyzer.md)
* [Puppeteer server](components/puppeteer-server.md)
* [Other OSS](components/other-oss.md)
* [robots.txt](components/robots.txt.md)

## Troubleshooting

* [How to get logs](troubleshooting/logs.md)

***

* [Support](support.md)
