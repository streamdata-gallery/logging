---
name: AWS Identity and Access Management
x-slug: aws-identity-and-access-management
description: AWS Identity and Access Management (IAM) enables you to securely control
  access to AWS services and resources for your users. Using IAM, you can create and
  manage AWS users and groups, and use permissions to allow and deny their access
  to AWS resources.IAM is a feature of your AWS account offered at no additional charge.
  You will be charged only for use of other AWS services by your users.To get started
  using IAM, orif you have already registered with AWS, go to theAWS Management Consoleand
  get started with theseIAM Best Practices.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Logging
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/aws-identity-and-access-management/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Identity and Access Management API - Create Login Profile
  x-api-slug: actioncreateloginprofile-get
  description: |-
    Creates a password for the specified user, giving the user the ability to access AWS
          services through the AWS Management Console.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/aws-identity-and-access-management/actioncreateloginprofile-get-openapi.md
- name: AWS Identity and Access Management API - Delete Login Profile
  x-api-slug: actiondeleteloginprofile-get
  description: |-
    Deletes the password for the specified IAM user, which terminates the user's ability
          to access AWS services through the AWS Management Console.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/aws-identity-and-access-management/actiondeleteloginprofile-get-openapi.md
- name: AWS Identity and Access Management API - Get Login Profile
  x-api-slug: actiongetloginprofile-get
  description: Retrieves the user name and password-creation date for the specified
    IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/aws-identity-and-access-management/actiongetloginprofile-get-openapi.md
- name: AWS Identity and Access Management API - Update Login Profile
  x-api-slug: actionupdateloginprofile-get
  description: Changes the password for the specified IAM user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Security-Identity_AWSIAM.png
  humanURL: https://aws.amazon.com/iam/
  baseURL: :///
  tags: Amazon Web Services, Authentication, Stack Network, Security, API Service
    Provider, API Service Provider, API Provider, Identities, Profiles, Relative Data,
    Service API
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/logging/master/_listings/aws-identity-and-access-management/actionupdateloginprofile-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://aws.glacier.api.gallery.streamdata.io
- type: x-api-stack
  url: http://aws.identity.and.access.management.stack.network
- type: x-change-log
  url: http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=323
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/sts/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/IAM/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/iam/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=76
- type: x-getting-started
  url: https://aws.amazon.com/iam/getting-started/
- type: x-partners
  url: https://aws.amazon.com/iam/partners/
- type: x-tools
  url: http://aws.amazon.com/cli
- type: x-website
  url: https://aws.amazon.com/iam/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---