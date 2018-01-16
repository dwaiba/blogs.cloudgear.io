---
title: "Queries and Integration Decisions"
date: 2018-01-16T15:22:57+01:00
draft: false
---

# Queries:
## The Oracle E-Business Suite (EBS) for the Oracle Financial Services Release would help - Latest is 12.1

## The Biztalk Server version would assist - Latest is BTS2016

## SAP Modules other than HR (Sf) that needs to be integrated especially IDOC Integrations besides SAP MM and SAP SD in INT 16a and INT 20a.

## What is the Innserve System that is in INT 26.

## What are the 3rd Party Systems in INT 14 and INT 15.

## The Oracle Service Cloud Version would help

##  Setup of Biztalk Topology if not done already: 5 Days excluding delays in Server Provisioning (on prem or cloud) and testing of the same.

## For Successfactors API :

### Notes and Connectivity Options:
Availability of cData's OData BizTalk Adapter [https://www.cdata.com/drivers/odata/download/biztalk/] eases using the robust OData API for the workflow integrations.

The new OData API: A newer option provided by SuccessFactors to integrate with the external systems . OData is built on HTTP at its core and the OData API is based on REST architecture.

- It is also the direction where SuccessFactors is focusing their investment which makes it a suitable candidate for your upcoming integrations making it future proof.

- MDF objects are also exposed through this OData API. E.g. Position data can be extracted using OData API.


This is the best for Odata REST Calls to sf.

It is a powerful BizTalk Adapter that allow you to easily connect BizTalk Server with live OData feeds through standard orchestrations. Use the OData Data Adapters to synchronize with OData Services. Perfect for data synchronization, local back-ups, workflow automation, and especially for Successfactors OData !

1) Similar to the BizTalk Adapter for SQL Server but for OData Services.
2) Supports meta-data discovery and schema generation for OData entities.
3) Includes a Receive Adapter and a two-way Send Adapter with support for updategrams, stored procedures, and queries.

#### Activities for all interfaces involving Sf if above design choice of Odata Integration and availability of the stated Odata Adpter is there (one time):
1. Connectivity Setup and Check from Biztalk - 5 days 

## For the source and Targets - Oracle Service Cloud:
### Setting up of Two-way WCF-WebHttp Send Port from Biztalk for interacting with the Oracle Service Cloud Rest Interface

### Connectivity Requirements: 
Connect REST API allows customers and partners to integrate with the Oracle Service Cloud platform using representational state transfer (REST) web services. Connect REST API is a public API that leverages the Connect Common Object Model version 1.4.

#### Activities for all interfaces involving Oracle Service Cloud (one time):
1. Connectivity Setup and Check from Biztalk - 5 days 

## For the Source and Targets - Oracle Service Cloud:

The following key facets for connectivity would be required for Biztalk interacting with OFS especially staging and interface tables:
### Binding Properties for Setting Application Context For Various Artifacts
### BizTalk Adapter for Oracle E-Business Suite binding properties

Besides the above which would set the integrations in place and the components are required.


