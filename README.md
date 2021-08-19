<br/>
<div align="center">

A curated list of awesome cloud security related resources.

</div>
<br/>

# Awesome Cloud Security
🛡️ Awesome Cloud Security Resources ⚔️

# Contents
- [Standards](#standards)
- [Tools](#tools)
- [Reading materials](#reading-materials)
- [Resource](#resource)
- [Contributing](#contributing)

# Standards
- [Compliances](#compliances)
- [Benchmarks](#benchmarks)

## Compliances
* [CSA STAR](https://cloudsecurityalliance.org/star/)
* [ISO/IEC 27017:2015](https://www.iso.org/standard/43757.html)
* [ISO/IEC 27018:2019](https://www.iso.org/standard/76559.html)
* [MTCS SS 584](https://www.imda.gov.sg/regulations-and-licensing-listing/ict-standards-and-quality-of-service/IT-Standards-and-Frameworks/ComplianceAndCertification)

## Benchmarks
* [CIS Benchmark](https://www.cisecurity.org/cis-benchmarks/)

# Tools
- [Infrastrcture](#infrastrcture)
- [Container](#container)
- [SaaS](#saas)
- [Cross service type](#cross service type): TBD
- [Native tools](#nativetools)

## Infrastrcture
* [aws_pwn](https://github.com/dagrz/aws_pwn): A collection of AWS penetration testing junk
* [aws_ir](https://github.com/ThreatResponse/aws_ir): Python installable command line utility for mitigation of instance and key compromises.
* [aws-vault](https://github.com/99designs/aws-vault): A vault for securely storing and accessing AWS credentials in development environments.
* [awspx](https://github.com/FSecureLABS/awspx): A graph-based tool for visualizing effective access and resource relationships within AWS.
* [azucar](https://github.com/nccgroup/azucar): A security auditing tool for Azure environments
* [checkov](https://github.com/bridgecrewio/checkov): A static code analysis tool for infrastructure-as-code.
* [CloudBrute](https://github.com/0xsha/CloudBrute): A multiple cloud enumerator.
* [cloud-forensics-utils]([https://github.com/google/cloud-forensics-utils): A python lib for DF & IR on the cloud.
* [Cloud-Katana](https://github.com/Azure/Cloud-Katana): Automate the execution of simulation steps in multi-cloud and hybrid cloud environments.
* [cloudlist](https://github.com/projectdiscovery/cloudlist): Listing Assets from multiple Cloud Providers.
* [Cloud Sniper](https://github.com/cloud-sniper/cloud-sniper): A platform designed to manage Cloud Security Operations.
* [cloudgoat](https://github.com/RhinoSecurityLabs/cloudgoat): "Vulnerable by Design" AWS deployment tool.
* [Cloudmapper](https://github.com/duo-labs/cloudmapper): Analyze your AWS environments.
* [cloudsplaining](https://github.com/salesforce/cloudsplaining): An AWS IAM Security Assessment tool that identifies violations of least privilege and generates a risk-prioritized report.
* [Cloudsploit Scans](https://github.com/cloudsploit/scans): Cloud security configuration checks.
* [Cloud-custodian](https://github.com/cloud-custodian/cloud-custodian): Rules engine for cloud security, cost optimization, and governance.
* [cs suite](https://github.com/SecurityFTW/cs-suite): Tool for auditing the security posture of AWS/GCP/Azure.
* [dftimewolf](https://github.com/log2timeline/dftimewolf): A multi-cloud framework for orchestrating forensic collection, processing and data export.
* [diffy](https://github.com/Netflix-Skunkworks/diffy): Diffy is a digital forensics and incident response (DFIR) tool developed by Netflix.
* [ElectricEye](https://github.com/jonrau1/ElectricEye): Continuously monitor AWS services for configurations.
* [Forseti security](https://github.com/forseti-security/forseti-security): GCP inventory monitoring and policy enforcement tool.
* [Hammer](https://github.com/dowjones/hammer): A multi-account cloud security tool for AWS. It identifies misconfigurations and insecure data exposures within most popular AWS resources.
* [kics](https://github.com/Checkmarx/kics): Find security vulnerabilities, compliance issues, and infrastructure misconfigurations early in the development cycle of your infrastructure-as-code.
* [Leonidas](https://github.com/FSecureLABS/leonidas): A framework for executing attacker actions in the cloud.
* [Open policy agent](https://www.openpolicyagent.org/): Policy-based control tool.
* [pacbot](https://github.com/tmobile/pacbot): Policy as Code Bot.
* [pacu](https://github.com/RhinoSecurityLabs/pacu): The AWS exploitation framework.
* [Prowler](https://github.com/toniblyx/prowler): Command line tool for AWS Security Best Practices Assessment, Auditing, Hardening and Forensics Readiness Tool.
* [Sadcloud](https://github.com/nccgroup/sadcloud): Tool for spinning up insecure AWS infrastructure with Terraform.
* [ScoutSuite](https://github.com/nccgroup/ScoutSuite): Multi-cloud security auditing tool.
* [Security Monkey](https://github.com/Netflix/security_monkey): Monitors AWS, GCP, OpenStack, and GitHub orgs for assets and their changes over time.
* [SkyArk](https://github.com/cyberark/SkyArk): Tool to helps to discover, assess and secure the most privileged entities in Azure and AWS.
* [SkyWrapper](https://github.com/cyberark/SkyWrapper): Tool helps to discover suspicious creation forms and uses of temporary tokens in AWS.
* [Smogcloud](https://github.com/BishopFox/smogcloud): Find cloud assets that no one wants exposed.
* [TerraGoat](https://github.com/bridgecrewio/terragoat): Bridgecrew's "Vulnerable by Design" Terraform repository.
* [Terrascan](https://github.com/accurics/terrascan): Detect compliance and security violations across Infrastructure as Code to mitigate risk before provisioning cloud native infrastructure.
* [tfsec](https://github.com/liamg/tfsec): Static analysis powered security scanner for Terraform code.
* [Zeus](https://github.com/DenizParlak/Zeus): AWS Auditing & Hardening Tool.

## Container
* [auditkube](https://github.com/opszero/auditkube): Audit for for EKS, AKS and GKE for HIPAA/PCI/SOC2 compliance and cloud security.
* [ccat](https://github.com/RhinoSecurityLabs/ccat): Cloud Container Attack Tool.
* [Falco](https://github.com/falcosecurity/falco): Container runtime security.
* [mkit](https://github.com/darkbitio/mkit): Managed kubernetes inspection tool.
* [Open policy agent](https://www.openpolicyagent.org/): Policy-based control tool.

## SaaS
* [binaryalert](https://github.com/airbnb/binaryalert): Serverless S3 yara scanner.
* [Function Shield](https://github.com/puresec/FunctionShield): Protection/destection lib of aws lambda and gcp function.
* [FestIN](https://github.com/cr0hn/festin): S3 bucket finder and content discover.
* [GCPBucketBrute](https://github.com/RhinoSecurityLabs/GCPBucketBrute): A script to enumerate Google Storage buckets.
* [Lambda Guard](https://github.com/Skyscanner/LambdaGuard): AWS Lambda auditing tool.
* [Policy Sentry](https://github.com/salesforce/policy_sentry): IAM Least Privilege Policy Generator.
* [S3 Inspector](https://github.com/kromtech/s3-inspector): Tool to check AWS S3 bucket permissions.
* [Serverless Goat](https://github.com/OWASP/Serverless-Goat): A serverless application demonstrating common serverless security flaws

## Native tools
* AWS
  * [Artifact](https://aws.amazon.com/artifact/): Compliance report selfservice.
  * [Certificate Manager](https://aws.amazon.com/certificate-manager/): Private CA and certificate management service.
  * [CloudTrail](https://aws.amazon.com/cloudtrail/): Record and log API call on AWS.
  * [Config](https://aws.amazon.com/config/): Configuration and resources relationship monitoring.
  * [Detective](https://aws.amazon.com/detective/): Analyze and visualize security data and help security investigations.
  * [Firewall Manager](https://aws.amazon.com/firewall-manager/): Firewall management service.
  * [GuardDuty](https://aws.amazon.com/guardduty/): IDS service
  * [CloudHSM](https://aws.amazon.com/cloudhsm/): HSM service.
  * [Inspector](https://aws.amazon.com/inspector/): Vulnerability discover and assessment service.
  * [KMS](https://aws.amazon.com/kms/): KMS service
  * [Macie](https://aws.amazon.com/macie/): Fully managed data security and data privacy service for S3.
  * [Network Firewall](https://aws.amazon.com/network-firewall/): Network firewall service.
  * [Secret Manager](https://aws.amazon.com/secrets-manager/): Credential management service.
  * [Security Hub](https://aws.amazon.com/security-hub/): Integration service for other AWS and third-party security service. 
  * [Shield](https://aws.amazon.com/shield/): DDoS protection service.
  * [VPC Flowlog](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html): Log of network traffic.
  * [WAF](https://aws.amazon.com/waf/): Web application firewall service.
* Azure
  * [Application Gateway](https://azure.microsoft.com/en-us/services/application-gateway/): L7 load balancer with optional WAF function.
  * [DDoS Protection](https://azure.microsoft.com/en-us/services/ddos-protection/): DDoS protection service.
  * [Dedicated HSM](https://azure.microsoft.com/en-us/services/azure-dedicated-hsm/): HSM service.
  * [Key Vault](https://azure.microsoft.com/en-us/services/key-vault/): KMS service
  * [Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/): API log and monitoring related service.
  * [Security Center](https://azure.microsoft.com/en-us/services/security-center/): Integration service for other Azure and third-party security service.
  * [Sentinel](https://azure.microsoft.com/zh-tw/services/azure-sentinel/): SIEM service.
* GCP
  * [Access Transparency](https://cloud.google.com/access-transparency): Transparency log and control of GCP.
  * [Apigee Sense](https://cloud.google.com/apigee/api-management/apigee-sense): API security monitoring, detection, mitigation.
  * [Armor](https://cloud.google.com/armor): DDoS protection and WAF service
  * [Asset Inventory](https://cloud.google.com/asset-inventory): Asset monitoring service.
  * [Audit Logs](https://cloud.google.com/audit-logs): API logs.
  * [Cloud HSM](https://cloud.google.com/hsm): HSM service
  * [Context-aware Access](https://cloud.google.com/context-aware-access): Enable zero trust access to applications and infrastructure.
  * [DLP](https://cloud.google.com/dlp): DLP service:
  * [EKM](https://cloud.google.com/ekm): External key management service
  * [Identity-Aware Proxy](https://cloud.google.com/iap): Identity-Aware Proxy for protect the internal service.
  * [KMS](https://cloud.google.com/kms): KMS service
  * [Policy Intelligence](https://cloud.google.com/policy-intelligence): Detect the policy related risk.
  * [Security Command Center](https://cloud.google.com/security-command-center): Integration service for other GCP security service.
  * [Security Scanner](https://cloud.google.com/security-scanner): Application security scanner for GAE, GCE, GKE.
  * [Event Threat Detection](https://cloud.google.com/event-threat-detection): Threat dection service.
  * [VPC Service Controls](https://cloud.google.com/vpc-service-controls): GCP service security perimeter control.

# Reading Materials
- [AWS](#aws)
- [Azure](#azure)
- [GCP](#gcp)
- [Others](#others)

## AWS
1. [Overiew of AWS Security](https://aws.amazon.com/security/)
2. [AWS-IAM-Privilege-Escalation by RhinoSecurityLabs](https://github.com/RhinoSecurityLabs/AWS-IAM-Privilege-Escalation): A centralized source of all AWS IAM privilege escalation methods.
3. [MITRE ATT&CK Matrices of AWS](https://attack.mitre.org/matrices/enterprise/cloud/aws/)
4. [AWS security workshops](https://github.com/aws-samples/aws-security-workshops)
## Azure
1. [Overiew of Azure Security](https://azure.microsoft.com/en-us/overview/security/)
2. [Azure security fundamentals](https://docs.microsoft.com/en-us/azure/security/fundamentals/)
3. [MicroBurst by NetSPI](https://github.com/NetSPI/MicroBurst): A collection of scripts for assessing Microsoft Azure security
4. [MITRE ATT&CK Matrices of Azure](https://attack.mitre.org/matrices/enterprise/cloud/azure/)
5. [Azure security center workflow automation](https://github.com/Azure/Azure-Security-Center/tree/master/Workflow%20automation)
## GCP
1. [Overiew of GCP Security](https://cloud.google.com/security)
2. [GKE security scenarios demo](https://github.com/GoogleCloudPlatform/gke-security-scenarios-demo)
3. [MITRE ATT&CK Matrices of GCP](https://attack.mitre.org/matrices/enterprise/cloud/gcp/)
4. [Security response automation](https://github.com/GoogleCloudPlatform/security-response-automation)
## Others
1. [Cloud Security Research by RhinoSecurityLabs](https://github.com/RhinoSecurityLabs/Cloud-Security-Research) 
2. [CSA cloud security guidance v4](https://cloudsecurityalliance.org/artifacts/security-guidance-v4/)
3. [Appsecco provides training](https://github.com/appsecco/breaking-and-pwning-apps-and-servers-aws-azure-training)

# Resource
- [AWS](#aws-1)
- [Others](#others-1)
## AWS
1. [Bucket search by grayhatwarfare](https://buckets.grayhatwarfare.com/)

## Others
1. [Mapping of On-Premises Security Controls vs. Major Cloud Providers Services](https://www.eventid.net/docs/onprem_to_cloud.asp)

# Contributing
See [contributing](https://github.com/4ndersonLin/awesome-cloud-security/blob/master/CONTRIBUTING.md)
