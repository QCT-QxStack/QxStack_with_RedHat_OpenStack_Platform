# QCT QxStack with Red Hat OpenStack Platform

## Overview

The QCT QxStack with Red Hat OpenStack Platform is an optimized appliance thoroughly validated by QCT based on Red Hat OpenStack Platform:

+ A robust, resilient, and high available OpenStack cloud environment for cloud services providers and enterprises.
+ QCT QxStack Auto-Deployment Tool for streamlined setup process.
+ Optimized configuration with high availability, functionality and performance.
<br>

This repository includes the solution deployment templates, the functionality verification result, and a comprehensive report for performance validation.
<br><br>

## Recommended Hardware

+ High Density Compute: [QuantaPlex T41S-2U](https://goo.gl/PSN7IS)
+ High computing Storage Server: [QuantaGrid D51PH-1ULH](https://goo.gl/HMs99p)
+ Management Switch: [QuantaMesh T1048-LB9](https://goo.gl/S9Y3vW)
+ Top-of-Rack (ToR) Switch: [QuantaMesh T3048-LY8](https://goo.gl/T7e79f)
<br><br>

## Solution Deployment 

### QCT One-Click Deployment Tool
+ Auto-generate Heat Orchestration Templates based on customers’ demands.
+ Fast deploy the QxStack with Red Hat OpenStack Platform without human intervention.
+ Deploy multiple cloud environments in a single run

For more information, please contact [QCT-QxStack@qct.io](mailto:QCT-QxStack@qct.io).
<br>

### Deployment Templates

The deployment templates for building QxStack with Red Hat OpenStack Platform are listed below:
 
+ [Red Hat OpenStack Platform director](./Deployment/ConfigFile/undercloud.conf)
+ [Network Environment Configurations](./Deployment/HeatTemplates/network-environment.yaml)
+ [Network Interface Configurations](./Deployment/HeatTemplates/nicConfig)
+ [Storage Environment Configurations](./Deployment/HeatTemplates/storage-environment.yaml)
+ [Other Customizations](./Deployment/Scripts)
<br><br>

## Solution Validation

Check the [Validation Report](./Validation/README.md) for QxStack with Red Hat OpenStack Platform

### Functionality Test
The Functionality of QxStack with Red Hat OpenStack Platform is validated with [OpenStack Tempest](https://docs.openstack.org/developer/tempest).<br>
For detailed results, please refer to [Tempest Test Report](https://qct-qxstack.github.io/QxStack_with_RedHat_OpenStack_Platform/v1.0/Validation/Tempest/QxStack-Tempest.html).
<br>

### Load Test
QCT conducted a comprehensive load test over QxStack with Red Hat OpenStack Platform to demonstrate the maximum capabilities, including:

+ [Authentication](./Validation/README.md#Authentication)
+ [Nova Compute Service](./Validation/README.md#Nova)
+ [Neutron Network Service](./Validation/README.md#Neutron)
+ [Glance Image Service](./Validation/README.md#Glance)
+ [Keystone Identity Service](./Validation/README.md#Keystone)
+ [Cinder Volume Service](./Validation/README.md#Cinder)
+ [Swift Object Storage Service](./Validation/README.md#Swift)
<br><br>

## References

+ [QCT QxStack with Red Hat OpenStack Platform](http://qct.io/solution/index/Compute-Virtualization/QxStack-with-Red-Hat-OpenStack-Platform)
+ [Red Hat Enterprise Linux 7 Product Documentation](https://access.redhat.com/documentation/en/red-hat-enterprise-linux/?version=7/)
+ [Red Hat OpenStack Platform](https://access.redhat.com/products/red-hat-openstack-platform/)
  * [Red Hat OpenStack Platform Life Cycle](https://access.redhat.com/support/policy/updates/openstack/platform)
  * [Red Hat OpenStack Platform Director Life Cycle](https://access.redhat.com/support/policy/updates/openstack/platform/director)
+ [Red Hat OpenStack Platform 10 Product Documentation](https://access.redhat.com/documentation/en/red-hat-openstack-platform/)
  * [Director Installation and Usage](https://access.redhat.com/documentation/en-us/red_hat_openstack_platform/10/html/director_installation_and_usage/)
  * [Red Hat Ceph Storage for the Overcloud](https://access.redhat.com/documentation/en-us/red_hat_openstack_platform/10/html/red_hat_ceph_storage_for_the_overcloud/)
+ [Red Hat Ceph Storage 2 Product Documentation](https://access.redhat.com/documentation/en/red-hat-ceph-storage?version=2/)
  * [Administration Guide](https://access.redhat.com/documentation/en-us/red_hat_ceph_storage/2/html/administration_guide/)
  * [Object Gateway Guide](https://access.redhat.com/documentation/en-us/red_hat_ceph_storage/2/html-single/object_gateway_guide_for_red_hat_enterprise_linux/)
