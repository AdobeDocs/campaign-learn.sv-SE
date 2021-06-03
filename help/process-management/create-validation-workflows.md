---
title: Skapa valideringsarbetsflöden
description: Lär dig konfigurera olika arbetsflöden för godkännandevalidering.
feature: Arbetsflöden, godkännanden
kt: 7991
doc-type: feature video
activity: setup
team: TM
role: Business Practitioner
level: Experienced
source-git-commit: f6bb16306773a4b6ff7aa390a514e9b31fe047d6
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---


# Skapa valideringsarbetsflöden

Adobe Campaign erbjuder flera alternativ för marknadsförare att granska och tillhandahålla leveransinnehåll, kampanjmål, dataextrahering och budgetgodkännanden.

I den här självstudiekursen beskrivs hur du konfigurerar olika arbetsflöden för godkännandevalidering.

## Förutsättning {#prerequisite}

Innan man aktiverar godkännandestegen måste marknadsföringsteamet definiera enskilda granskare:

* Adobe Campaign granskarroll inom en godkännandeaktivitet kan antingen vara en enskild granskare (Operator) eller en grupp med granskare (Operator role).
* För att kampanjutvecklare ska kunna välja granskarna som godkännare i en kampanj eller leverans måste granskarna och granskningsgrupperna konfigureras i Adobe Campaign av en administratör.

## Konfigurera godkännanden för kampanjer {#configuring-approvals-for-campaigns}

Om du har samma uppsättning granskare för alla leveranser i kampanjarbetsflödet kan du använda funktionen för kampanjgodkännande genom att konfigurera godkännanden och granskare på kampanjnivå. Godkännandeaktiviteterna och granskarna överförs till varje leveransaktivitet i arbetsflödet när arbetsflödet har körts.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Konfigurerar godkännanden för leveranser {#configuring-approvals-for-deliveries}

Du kan också konfigurera godkännanden på leveransnivå. Om steg och granskare för leveransgodkännande skiljer sig från stegen för kampanjgodkännande och granskarna åsidosätter leveransinställningarna kampanjinställningarna.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Konfigurera en godkännandeaktivitet {#configuring-an-approval-activity}

Till skillnad från leverans- eller kampanjgodkännandena gör godkännandeaktiviteten det möjligt att skapa en godkännandeprocess i ett arbetsflöde. På så sätt kan logiken för målval godkännas innan leveransen startas. Det tillåter även godkännande på flera nivåer i arbetsflödet vid behov.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

Mer information finns i [Godkännandedokumentationen](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
