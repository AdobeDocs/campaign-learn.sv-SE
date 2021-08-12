---
title: Skapa valideringsarbetsflöden
description: Lär dig hur du konfigurerar olika arbetsflöden för godkännandevalidering.
feature: Arbetsflöden, godkännanden
kt: 7991
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: 02a6238163a7c8f887236e03b78673c57c836a45
workflow-type: ht
source-wordcount: '265'
ht-degree: 100%

---

# Skapa valideringsarbetsflöden

Adobe Campaign erbjuder flera alternativ för marknadsförare att granska och tillhandahålla leveransinnehåll, kampanjmål, dataextrahering och budgetgodkännanden.

Den här självstudiekursen beskriver hur du konfigurerar olika arbetsflöden för godkännandevalidering.

## Förutsättning {#prerequisite}

Innan man aktiverar godkännandestegen måste marknadsföringsteamet definiera enskilda granskare:

* Granskarrollen i Adobe Campaign inom en godkännandeaktivitet kan antingen vara en enskild granskare (operatör) eller en grupp med granskare (operatörsroll).
* För att kampanjutvecklare ska kunna välja granskarna som godkännare i en kampanj eller leverans, måste granskarna och granskningsgrupperna konfigureras i Adobe Campaign av en administratör.

## Konfigurera godkännanden för kampanjer   {#configuring-approvals-for-campaigns}

Om du har samma uppsättning granskare för alla leveranser i kampanjarbetsflödet, kan du använda funktionen för kampanjgodkännande genom att konfigurera godkännanden och granskare på kampanjnivå. Godkännandeaktiviteterna och granskarna överförs till varje leveransaktivitet i arbetsflödet när arbetsflödet har körts.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Konfigurera godkännanden för leveranser   {#configuring-approvals-for-deliveries}

Du kan också konfigurera godkännanden på leveransnivå. Leveransinställningarna åsidosätter kampanjinställningarna, om stegen och granskarna för leveransgodkännande skiljer sig från stegen och granskarna för kampanjgodkännande.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Konfigurera en godkännandeaktivitet   {#configuring-an-approval-activity}

Till skillnad från leverans- eller kampanjgodkännandena gör godkännandeaktiviteten det möjligt att skapa en godkännandeprocess i ett arbetsflöde. På så sätt kan logiken för målinriktningsvalen godkännas innan leveransen startas. Det möjliggör även godkännande på flera nivåer i arbetsflödet vid behov.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

Mer information finns i [Godkännandedokumentation](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=sv)
