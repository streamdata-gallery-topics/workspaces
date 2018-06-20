---
name: AWS WorkSpaces
x-slug: aws-workspaces
description: Amazon WorkSpaces is a fully managed, secure desktop computing service
  which runs on the AWS cloud. Amazon WorkSpaces allows you to easily provision cloud-based
  virtual desktops and provide your users access to the documents, applications, and
  resources they need from any supported device, including Windows and Mac computers,
  Chromebooks, iPads, Fire tablets, Android tablets, and Chrome and Firefox web browsers.
  With just a few clicks in the AWS Management Console, you can deploy high-quality
  cloud desktops for any number of users. With Amazon WorkSpaces, you pay either monthly
  or hourly just for the Amazon WorkSpaces you launch, which helps you save money
  when compared to traditional desktops and on-premises Virtual Desktop Infrastructure
  (VDI) solutions.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkSpaces.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Workspaces
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/aws-workspaces/apis.md
specificationVersion: "0.14"
apis:
- name: AWS WorkSpaces Service API Describe Workspaces
  x-api-slug: aws-workspaces-service-api
  description: Obtains information about the specified WorkSpaces.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkSpaces.png
  humanURL: https://aws.amazon.com/workspaces/
  baseURL: ://///?Action=DescribeWorkspaces
  tags: Workspaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/aws-workspaces/actiondescribeworkspaces-get-openapi.md
- name: AWS WorkSpaces Service API Describe Workspaces Connection Status
  x-api-slug: aws-workspaces-service-api
  description: Describes the connection status of a specified WorkSpace.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkSpaces.png
  humanURL: https://aws.amazon.com/workspaces/
  baseURL: ://///?Action=DescribeWorkspacesConnectionStatus
  tags: Workspaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/aws-workspaces/actiondescribeworkspacesconnectionstatus-get-openapi.md
- name: AWS WorkSpaces Service API Modify Workspace Properties
  x-api-slug: aws-workspaces-service-api
  description: Modifies the WorkSpace properties, including the running mode and AutoStop
    time.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkSpaces.png
  humanURL: https://aws.amazon.com/workspaces/
  baseURL: ://///?Action=ModifyWorkspaceProperties
  tags: Workspaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/aws-workspaces/actionmodifyworkspaceproperties-get-openapi.md
- name: AWS WorkSpaces Service API Reboot Workspaces
  x-api-slug: aws-workspaces-service-api
  description: Reboots the specified WorkSpaces.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkSpaces.png
  humanURL: https://aws.amazon.com/workspaces/
  baseURL: ://///?Action=RebootWorkspaces
  tags: Workspaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/aws-workspaces/actionrebootworkspaces-get-openapi.md
- name: AWS WorkSpaces Service API Rebuild Workspaces
  x-api-slug: aws-workspaces-service-api
  description: Rebuilds the specified WorkSpaces.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkSpaces.png
  humanURL: https://aws.amazon.com/workspaces/
  baseURL: ://///?Action=RebuildWorkspaces
  tags: Workspaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/aws-workspaces/actionrebuildworkspaces-get-openapi.md
- name: AWS WorkSpaces Service API Start Workspaces
  x-api-slug: aws-workspaces-service-api
  description: Starts the specified WorkSpaces.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkSpaces.png
  humanURL: https://aws.amazon.com/workspaces/
  baseURL: ://///?Action=StartWorkspaces
  tags: Workspaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/aws-workspaces/actionstartworkspaces-get-openapi.md
- name: AWS WorkSpaces Service API Stop Workspaces
  x-api-slug: aws-workspaces-service-api
  description: Stops the specified WorkSpaces.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkSpaces.png
  humanURL: https://aws.amazon.com/workspaces/
  baseURL: ://///?Action=StopWorkspaces
  tags: Workspaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/aws-workspaces/actionstopworkspaces-get-openapi.md
- name: AWS WorkSpaces Service API Terminate Workspaces
  x-api-slug: aws-workspaces-service-api
  description: Terminates the specified WorkSpaces.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkSpaces.png
  humanURL: https://aws.amazon.com/workspaces/
  baseURL: ://///?Action=TerminateWorkspaces
  tags: Workspaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/aws-workspaces/actionterminateworkspaces-get-openapi.md
- name: AWS WorkSpaces Service API
  x-api-slug: aws-workspaces-service-api
  description: Amazon WorkSpaces is a fully managed, secure desktop computing service
    which runs on the AWS cloud. Amazon WorkSpaces allows you to easily provision
    cloud-based virtual desktops and provide your users access to the documents, applications,
    and resources they need from any supported device, including Windows and Mac computers,
    Chromebooks, iPads, Fire tablets, Android tablets, and Chrome and Firefox web
    browsers. With just a few clicks in the AWS Management Console, you can deploy
    high-quality cloud desktops for any number of users. With Amazon WorkSpaces, you
    pay either monthly or hourly just for the Amazon WorkSpaces you launch, which
    helps you save money when compared to traditional desktops and on-premises Virtual
    Desktop Infrastructure (VDI) solutions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Enterprise-Applications_AmazonWorkSpaces.png
  humanURL: https://aws.amazon.com/workspaces/
  baseURL: :///
  tags: Workspaces
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/workspaces/master/_listings/aws-workspaces/openapi.md
x-common:
- type: x-documentation
  url: http://docs.aws.amazon.com/workspaces/latest/api/api-reference.html
- type: x-faq
  url: https://aws.amazon.com/workspaces/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=164
- type: x-pricing
  url: https://aws.amazon.com/workspaces/pricing/
- type: x-testimonials
  url: https://aws.amazon.com/workspaces/testimonials/
- type: x-webinars
  url: https://aws.amazon.com/workspaces/resources/#webinars
- type: x-website
  url: https://aws.amazon.com/workspaces/
- type: x-white-papers
  url: https://aws.amazon.com/workspaces/resources/#whitepapers
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---