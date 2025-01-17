---
title: Release Notes for Cloud Manager 2023.4.0 in Adobe Experience Manager as a Cloud Service
description: These are the release notes for Cloud Manager 2023.4.0 in AEM as a Cloud Service.
feature: Release Information
exl-id: 9c73d7ab-c2c2-4803-a07b-e9054220c6b2
---

# Release Notes for Cloud Manager 2023.4.0 in Adobe Experience Manager as a Cloud Service {#release-notes}

This page documents the release notes for Cloud Manager release 2023.4.0 in AEM as a Cloud Service.

>[!NOTE]
>
>Refer to [this page](/help/release-notes/release-notes-cloud/release-notes-current.md) for the current release notes for Adobe Experience Manager as a Cloud Service.

## Release Date {#release-date}

The release date for Cloud Manager release 2023.4.0 in AEM as a Cloud Service is 13 April 2023. The next release is planned for 11 May 2023.

## What's New {#what-is-new}

* [The AEM Project Archetype](https://experienceleague.adobe.com/docs/experience-manager-core-components/using/developing/archetype/overview.html) has been updated to version 41.

## Bug Fixes {#bug-fixes}

* When a [certificate](/help/implementing/cloud-manager/managing-ssl-certifications/introduction.md) expires, [domain names](/help/implementing/cloud-manager/custom-domain-names/introduction.md) and [IP allow lists](/help/implementing/cloud-manager/ip-allow-lists/introduction.md) associated with the certificate will no longer be removed from the CDN.  In such cases, the site will continue to be reachable.
* The Cloud Manager UI will provide more visible advance warnings that the [SSL certificate](/help/implementing/cloud-manager/managing-ssl-certifications/introduction.md) is about to expire.
* A rare situation was fixed where customers were unable to create a new environment or delete an environment.
