---

copyright:
  years: 2016, 2019
lastupdated: "2019-05-01"

keywords: IBM Cloud, Activity Tracker, compliance

subcollection: cloud-activity-tracker

---

{:new_window: target="_blank"}
{:shortdesc: .shortdesc}
{:screen: .screen}
{:pre: .pre}
{:table: .aria-labeledby="caption"}
{:codeblock: .codeblock}
{:tip: .tip}
{:download: .download}
{:important: .important}
{:note: .note}
{:deprecated: .deprecated}


# Compliance
{: #compliance}

[The {{site.data.keyword.cloud_notm}} provides a Cloud platform and services that are built to IBM's stringent security standards](/docs/overview?topic=overview-security#compliance). The {{site.data.keyword.cloudaccesstraillong}} service is a DevOps service that is built for the {{site.data.keyword.cloud_notm}}. 
{:shortdesc}

{{site.data.keyword.cloudaccesstrailfull}} is deprecated. As of 9 May 2019, you cannot provision new {{site.data.keyword.cloudaccesstrailshort}} instances. Existing premium plan instances are supported until 9 October 2019. To continue monitoring the activity of your {{site.data.keyword.cloud_notm}} account, provision an instance of the [{{site.data.keyword.at_full}}](/docs/services/Activity-Tracker-with-LogDNA?topic=logdnaat-getting-started#getting-started).
{: deprecated}

## General Data Protection Regulation

The General Data Protection Regulation (GDPR) seeks to create a harmonized data protection law framework across the EU and aims to give citizens back the control of their personal data, whilst imposing strict rules on those hosting and ‘processing’ this data, anywhere in the world. The Regulation also introduces rules relating to the free movement of personal data within and outside the EU. 

**Disclaimer:** The {{site.data.keyword.cloudaccesstrailshort}} service stores and displays event records from Cloud resources that run in your account in the {{site.data.keyword.cloud_notm}}. Personal information (PI) must not be included in any of the event entries stored in {{site.data.keyword.cloudaccesstrailshort}} as this data is accessible to other users within your Enterprise, as well as to {{site.data.keyword.IBM_notm}} to be able to support the Cloud Service.

### Regions
{: #compliance_regions}

The {{site.data.keyword.cloudaccesstrailshort}} service is compliant with GDPR in the {{site.data.keyword.cloud_notm}} Public regions where the service is available.


### Data retention
{: #compliance_data_retention}

The {{site.data.keyword.cloudaccesstrailshort}} service includes 2 data repositories where your event data is stored: 

* One repository where event data is available for analysis through Kibana. The standard or lite plan only stores data in this repository. Data is kept for 3 days.
* One long-term storage repository that hosts the event data for the premium plan. Event data is stored until you either configure a retention policy or delete them manually. By default, events are kept indefinitely.


### Data deletion
{: #compliance_data_deletion}

Consider the following information:

* Events that are stored in the repository that provides the data for Kibana are deleted after 3 days.

* Events that are stored in the long-term repository are deleted after a number of days when you configure a retention policy, or when you delete them manually. 



If you change from a paid plan to the standard or lite plan, events that are in the long-term storage repository will be deleted in about one day.

At any time, you can open a support ticket and request that all your data is deleted. For information about opening an IBM support ticket, see [Getting support](/docs/get-support?topic=get-support-getting-customer-support#getting-customer-support).



### More information
{: #compliance_info}

For more information, see:

[{{site.data.keyword.cloud_notm}} security compliance](/docs/overview?topic=overview-security#compliance)

[GDPR - {{site.data.keyword.IBM_notm}} official page ![External link icon](../../icons/launch-glyph.svg "External link icon")](https://www.ibm.com/data-responsibility/gdpr/){:new_window}



