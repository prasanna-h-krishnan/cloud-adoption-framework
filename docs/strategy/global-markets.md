---
title: Impact of global market decisions
description: Use the Cloud Adoption Framework for Azure to understand how global market decisions can affect the transformation journey to the cloud.
author: martinekuan
ms.author: martinek
ms.date: 04/04/2019
ms.topic: conceptual
ms.service: cloud-adoption-framework
ms.subservice: strategy
ms.custom: internal, UpdateFrequency2
---

# How will global market decisions affect the transformation journey?

The cloud opens new opportunities to perform on a global scale. Barriers to global operations are significantly reduced, by empowering companies to deploy assets in their markets, without the need to invest heavily in new datacenters. Unfortunately, this also adds a great deal of complexity from technical and legal perspectives.

## Data sovereignty

Many geopolitical regions have established data sovereignty regulations. Those regulations restrict where data can be stored, what data can leave the country/region of origin, and what data can be collected about citizens of that region. Before operating any cloud-based solution in a foreign geography, you should understand how that cloud provider handles data sovereignty. For more information about Azure's approach for each region, see [Azure geographies](https://azure.microsoft.com/global-infrastructure/geographies/). For more information about compliance in Azure, see [Privacy at Microsoft](https://www.microsoft.com/trust-center/privacy) in the Microsoft Trust Center.

The remainder of this article assumes legal counsel has reviewed and approved operations in a foreign geopolitical region.

## Business units

It is important to understand which business units operate in foreign locales and which countries/regions are affected. This information will be used to design solutions for hosting, billing, and deployments to the cloud provider.

## Employee usage patterns

It is important to understand how global users access applications that are not hosted in the same country/region as the user. Global wide-area networks (WANs) route users based on existing networking agreements. In a traditional on-premises world, some constraints limit WAN design. Those constraints can lead to poor user experiences if not properly understood before cloud adoption.

In a cloud model, commodity internet opens up many new options as well. Communicating the spread of employees across multiple geographies can help the cloud adoption team design WAN solutions that create positive user experiences **and** potential reduce networking costs.

## External user usage patterns

It is equally important to understand the usage patterns of external users, like customers or partners. Much like employee usage patterns, external user usage patterns can negatively affect performance of cloud deployments. When a large or mission-critical user base resides in a foreign country/region, it could be wise to include a global deployment strategy into the overall solution design.

## Next steps

Learn about the [skills needed during the strategizing phase](./suggested-skills.md) of your cloud adoption journey.

> [!div class="nextstepaction"]
> [Skills needed during the strategizing phase](./suggested-skills.md)
