---
permalink: mapping-rackspace-resources-to-amazon-web-services-resources/
audit_date:
title: Mapping of Rackspace resources to Amazon Web Services resources
type: article
created_date: '2017-06-09'
created_by: Catherine Richardson
last_modified_date: '2017-06-09'
last_modified_by: Catherine Richardson
product: Rackspace Migration Manager
product_url: rackspace-migration-manager
noindex: true
---

This article helps you map Rackspace infrastructure products to Amazon Web Services (AWS) infrastructure as a service (IaaS) products. Being aware of this information should make your migration as seamless as possible.

In the initial release of the Rackspace Migration Manager, the products in the following table are supported for migration.

| Rackspace product | Corresponding AWS product |
| --- | --- |
| [Cloud Servers product](http://www.rackspace.com/cloud/servers)<br />[Cloud Servers API](https://developer.rackspace.com/docs/cloud-servers/v2/developer-guide/) | Amazon EC2 |
| [Cloud Networks product](https://www.rackspace.com/cloud/networks) | Amazon VPC |
| [Cloud Block Storage product](http://www.rackspace.com/cloud/block-storage)<br />[Cloud Block Storage API](https://developer.rackspace.com/docs/cloud-block-storage/v1/developer-guide/) | Amazon EBS |


### Mapping of Rackspace Cloud instance types to Amazon EC2 instance types

The following table maps Rackspace Cloud instance types to equivalent
Amazon EC2 instance types so that you can select an appropriate
instance size for your AWS Cloud.

| Rackspace instance type | EC2 instance type |
|---------------------|---------------------------|
| Standard: 512 MB RAM, 20 GB HDD, 1 vCPU<br />1 GB RAM, 40 GB HDD, 1 vCPU<br />Performance: 1 GB RAM, 20 GB SSD, 1 vCPU | Micro:<br />613 MB RAM, up to 2 ECUs, EBS storage, 64 bit |
| Standard: 2 GB RAM, 80 GB HDD, 2 vCPUs<br />Performance: 2 GB RAM, 40 GB and 20 GB SSDs, 2 vCPU | M1 Small:<br />1.7 GB RAM, 1 ECU, 160 GB local storage, 32 or 64 bit |
| Standard: 4 GB RAM, 160 GB HDD, 2 vCPUs<br />Performance: 4 GB RAM, 40 GB and 40 GB SSDs, 4 vCPU | M1 Medium:<br />3.75 GB RAM, 2 ECUs, 410 GB local storage, 32 or 64 bit |
| Standard: 8 GB RAM, 320 GB HDD, 4 vCPUs<br />Performance: 8 GB RAM, 40 GB and 80 GB SSDs, 8 vCPU | M1 Large:<br />7.5 GB RAM, 4 ECUs, 850 GB local storage, 64 bit |
| Standard: 15 GB RAM, 620 GB HDD, 6 vCPUs<br />Performance: 15 GB RAM, 40 GB and 150 GB SSDs, 4 vCPU | M1 Extra Large:<br />15 GB RAM, 8 ECUs, 1690 GB local storage, 64 bit |
| Standard: 15 GB RAM, 620 GB HDD, 6 vCPUs<br />Performance: 15 GB RAM, 40 GB and 150 GB SSDs, 4 vCPU | M3 Extra Large:<br />15 GB RAM, 13 ECUs, EBS storage, 64 bit |
| Standard: 30 GB RAM, 1200 GB HDD, 8 vCPUs<br />Performance: 30 GB RAM, 40 GB and 300 GB SSDs, 8 vCPU | M3 Extra Double Large:<br /> 30 GB RAM, 26 ECUs, EBS storage, 64 bit |
| Standard: 15 GB RAM, 620 GB HDD, 6 vCPUs<br />Performance: 15 GB RAM, 40 GB and 150 GB SSDs, 4 vCPU | High-Memory Extra Large:<br />17 GB RAM, 6.5 ECUs, 420 GB storage, 64 bit |
| Standard: 30 GB RAM, 1200 GB HDD, 8 vCPUs<br />Performance: 30 GB RAM, 40 GB and 300 GB SSDs, 8 vCPU | High-Memory Double Extra Large:<br />34 GB RAM, 13 ECUs, 850 GB local storage, 64 bit |

### Fanatical Support

[Rackspace Support](https://www.rackspace.com/support)
