---
name: Google Cloud DNS
x-slug: google-cloud-dns
description: Google Cloud DNS is a scalable, reliable and managed authoritative Domain
  Name System (DNS) service running on the same infrastructure as Google. It has low
  latency, high availability and is a cost-effective way to make your applications
  and services available to your users. Cloud DNS translates requests for domain names
  like www.google.com into IP addresses like 74.125.29.101. Cloud DNS is programmable.
  You can easily publish and manage millions of DNS zones and records using our simple
  user interface, command-line interface or API.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-dns-network.png
x-kinRank: "9"
x-alexaRank: ""
tags: Google Cloud DNS
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dns/master/_listings/google-cloud-dns/apis.md
specificationVersion: "0.14"
apis:
- name: Google Cloud DNS API Get Project
  x-api-slug: google-cloud-dns-api
  description: Fetch the representation of an existing Project.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-dns-network.png
  humanURL: https://cloud.google.com/dns/
  baseURL: ://www.googleapis.com//dns/v1/projects//{project}
  tags: Project
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dns/master/_listings/google-cloud-dns/project-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dns/master/_listings/google-cloud-dns/project-get-openapi.md
- name: Google Cloud DNS API Get Managed Zones
  x-api-slug: google-cloud-dns-api
  description: Enumerate ManagedZones that have been created but not yet deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-dns-network.png
  humanURL: https://cloud.google.com/dns/
  baseURL: ://www.googleapis.com//dns/v1/projects//{project}/managedZones
  tags: Managed Zone
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dns/master/_listings/google-cloud-dns/projectmanagedzones-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dns/master/_listings/google-cloud-dns/projectmanagedzones-get-openapi.md
- name: Google Cloud DNS API Create Managed Zone
  x-api-slug: google-cloud-dns-api
  description: Create a new ManagedZone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-dns-network.png
  humanURL: https://cloud.google.com/dns/
  baseURL: ://www.googleapis.com//dns/v1/projects//{project}/managedZones
  tags: Managed Zone
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dns/master/_listings/google-cloud-dns/projectmanagedzones-post-openapi.md
- name: Google Cloud DNS API Delete Managed Zone
  x-api-slug: google-cloud-dns-api
  description: Delete a previously created ManagedZone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-dns-network.png
  humanURL: https://cloud.google.com/dns/
  baseURL: ://www.googleapis.com//dns/v1/projects//{project}/managedZones/{managedZone}
  tags: Managed Zone
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dns/master/_listings/google-cloud-dns/projectmanagedzonesmanagedzone-delete-openapi.md
- name: Google Cloud DNS API Get Managed Zone
  x-api-slug: google-cloud-dns-api
  description: Fetch the representation of an existing ManagedZone.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-dns-network.png
  humanURL: https://cloud.google.com/dns/
  baseURL: ://www.googleapis.com//dns/v1/projects//{project}/managedZones/{managedZone}
  tags: Managed Zone
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dns/master/_listings/google-cloud-dns/projectmanagedzonesmanagedzone-get-openapi.md
- name: Google Cloud DNS API List Managed Zone Changes
  x-api-slug: google-cloud-dns-api
  description: Enumerate Changes to a ResourceRecordSet collection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-dns-network.png
  humanURL: https://cloud.google.com/dns/
  baseURL: ://www.googleapis.com//dns/v1/projects//{project}/managedZones/{managedZone}/changes
  tags: Managed Zone
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dns/master/_listings/google-cloud-dns/projectmanagedzonesmanagedzonechanges-get-openapi.md
- name: Google Cloud DNS API Create Managed Zone Change
  x-api-slug: google-cloud-dns-api
  description: Atomically update the ResourceRecordSet collection.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-dns-network.png
  humanURL: https://cloud.google.com/dns/
  baseURL: ://www.googleapis.com//dns/v1/projects//{project}/managedZones/{managedZone}/changes
  tags: Managed Zone
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dns/master/_listings/google-cloud-dns/projectmanagedzonesmanagedzonechanges-post-openapi.md
- name: Google Cloud DNS API Get Managed Zone Change
  x-api-slug: google-cloud-dns-api
  description: Fetch the representation of an existing Change.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-dns-network.png
  humanURL: https://cloud.google.com/dns/
  baseURL: ://www.googleapis.com//dns/v1/projects//{project}/managedZones/{managedZone}/changes/{changeId}
  tags: Managed Zone
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dns/master/_listings/google-cloud-dns/projectmanagedzonesmanagedzonechangeschangeid-get-openapi.md
- name: Google Cloud DNS API Get Managed Zone Resources
  x-api-slug: google-cloud-dns-api
  description: Enumerate ResourceRecordSets that have been created but not yet deleted.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-dns-network.png
  humanURL: https://cloud.google.com/dns/
  baseURL: ://www.googleapis.com//dns/v1/projects//{project}/managedZones/{managedZone}/rrsets
  tags: Managed Zone
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dns/master/_listings/google-cloud-dns/projectmanagedzonesmanagedzonerrsets-get-openapi.md
- name: Google Cloud DNS API
  x-api-slug: google-cloud-dns-api
  description: Google Cloud DNS is a scalable, reliable and managed authoritative
    Domain Name System (DNS) service running on the same infrastructure as Google.
    It has low latency, high availability and is a cost-effective way to make your
    applications and services available to your users. Cloud DNS translates requests
    for domain names like www.google.com into IP addresses like 74.125.29.101. Cloud
    DNS is programmable. You can easily publish and manage millions of DNS zones and
    records using our simple user interface, command-line interface or API.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/global-dns-network.png
  humanURL: https://cloud.google.com/dns/
  baseURL: ://www.googleapis.com//dns/v1/projects
  tags: Google Cloud DNS
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-cloud-dns/master/_listings/google-cloud-dns/openapi.md
x-common:
- type: x-documentation
  url: https://cloud.google.com/dns/docs/
- type: x-forum
  url: https://groups.google.com/forum/#!forum/cloud-dns-discuss
- type: x-getting-started
  url: https://cloud.google.com/dns/quickstart
- type: x-guides
  url: https://cloud.google.com/dns/docs/how-to
- type: x-pricing
  url: https://cloud.google.com/dns/pricing
- type: x-rate-limits
  url: https://cloud.google.com/dns/quota
- type: x-service-level-agreements
  url: https://cloud.google.com/dns/sla
- type: x-website
  url: https://cloud.google.com/dns/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---