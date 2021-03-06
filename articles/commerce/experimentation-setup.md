---
# required metadata

title: Set up an experiment
description: This topic describes how to set up an experiment in a third-party service.
author:  sushma-rao 
manager: AnnBe
ms.date: 10/01/2020
ms.topic: article
ms.prod: 
ms.service: dynamics-365-retail
ms.technology: 

# optional metadata

# ms.search.form: 
# ROBOTS: 
audience: Application User
# ms.devlang: 
ms.reviewer: josaw
ms.search.scope: Core, Operations, Retail
# ms.tgt_pltfrm: 
ms.custom: 
ms.assetid: 
ms.search.region: global
ms.search.industry: Retail
ms.author: sushmar
ms.search.validFrom: 2020-09-30
ms.dyn365.ops.version: AX 10.0.13
---

# Set up an experiment

After you [define a hypothesis and determine what success metrics you want to use](experimentation-identify.md), you'll need to set up your experiment in the third-party service. The following diagram shows all of the steps involved in setting up and running an experiment on an e-Commerce website in Dynamics 365 Commerce. Additional steps are covered in separate topics.

[ ![Experimentation user journey - Setup](./media/experimentation_setup.svg) ](./media/experimentation_setup.svg#lightbox)


## Set up your experiment in the third-party service
By now you should have chosen your third-party service to run and monitor your experiment, and set up the experimentation connector. These prerequisites are listed in  [Experimentation in Dynamics 365 Commerce](experimentation-overview.md).

Follow the steps required to create your experiment in the third-party service. If the connector is configured properly, the complete list of experiments you set up in the third-party service will surface in site builder within about 5 minutes.

## Set up your success metrics
Every experiment needs metrics to measure the impact of the variations and to validate the hypothesis. Follow the steps below to enable the computation of metrics in the third-party service using live telemetry events from Dynamics 365 Commerce.

1. In site builder, select the **Pages** tab in the left navigation pane and then select the page that you want to collect metrics on. 
1. Go to the **Event IDs to track** section in the right property pane of the page or module you want to track.
1. Select **View**. A list of all event IDs is displayed. Copy the event you want to track, and paste the event key into the designated location in the third-party service. If you need more than one event, copy the keys one at a time. 
    - To learn how to view all of the available events and attributes, including page views and revenue tracking, see [Commerce component events for diagnostics and troubleshooting](dev-itpro/retail-component-events-diagnostics-troubleshooting.md).
1. Take any other steps for tracking metrics as required in the third-party service.

## Previous step
[Identify a hypothesis and determine metrics for an experiment](experimentation-identify.md) 


## Next step
[Connect and edit an experiment](experimentation-connect-edit.md)
