# Overview
This is Anomalous Trade Detection Project which is created on the Orcale Cloud Infrastructure(IaaS). This project detects a specific use case of Anomalous trades known as the Wash Trades in real time.
The trades data is produced and streamed continously , the streamed data is analysed in using a py-spark application and the detected wash trades information is notified to the user using E-mail.

# What is OCI 
Oracle Cloud Infrastructure (OCI) is a platform of cloud services that enable you to build and run a wide range of applications in a highly-available, consistently high-performance environment.

# Prerequisites
- Permission to `manage` the following  resources in your Oracle Cloud Infrastructure tenancy: `Vcn`, `Streaming`, `Object storage`, `Functions`, `Serviceconnectors`, `Data Flow`, and `Events`.

- Quota to create the following resources: 1 VCN, 1 subnets, 1 streaming, 1 events, 2 function, 2 service connector, 2 buckets.

If you don't have the required permissions and quota, contact your tenancy administrator. See [Policy Reference](https://docs.cloud.oracle.com/en-us/iaas/Content/Identity/Reference/policyreference.htm), [Service Limits](https://docs.cloud.oracle.com/en-us/iaas/Content/General/Concepts/servicelimits.htm), [Compartment Quotas](https://docs.cloud.oracle.com/iaas/Content/General/Concepts/resourcequotas.htm).

# Oci Services used 
* OCI Streaming
* OCI Service Connector Hub
* OCI Object Storage
* Oci Functions
* OCI Data Flow
* OCI Events

# Documentation
You can find the documentation of the OCI services at https://docs.oracle.com/en-us/iaas/Content/home.html

# Architecture Diagram
Comment - Add the architecture diagram here

# Instructions 
comment - write the instructions here

# Contributing
This project is open source.  Please submit your contributions by forking this repository and submitting a pull request!  Oracle appreciates any contributions that are made by the open source community.

# License
Copyright (c) 2021 Oracle and/or its affiliates.

Licensed under the Universal Permissive License (UPL), Version 1.0.

See [LICENSE](LICENSE) for more details.
