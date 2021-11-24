---
title: Skapa arbetsflöden för godkännanden och validering - introduktion
description: Lär dig hur du konfigurerar olika arbetsflöden för godkännandevalidering.
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: 806ecfd0c9377b82eef68e1f9499becfe67704eb
workflow-type: tm+mt
source-wordcount: '262'
ht-degree: 64%

---

# Skapa arbetsflöden för godkännanden och validering - introduktion

Adobe Campaign erbjuder flera alternativ för marknadsförare att granska och tillhandahålla leveransinnehåll, kampanjmål, dataextrahering och budgetgodkännanden. Lär dig hur [hantera godkännanden](/help/process-management/create-approvals-and-validation-workflows/manage-approvals.md).

## Förutsättning {#prerequisite}

Innan man aktiverar godkännandestegen måste marknadsföringsteamet definiera enskilda granskare:

* Granskarrollen i Adobe Campaign inom en godkännandeaktivitet kan antingen vara en enskild granskare (operatör) eller en grupp med granskare (operatörsroll).
* För att kampanjutvecklare ska kunna välja granskarna som godkännare i en kampanj eller leverans, måste granskarna och granskningsgrupperna konfigureras i Adobe Campaign av en administratör.

## Konfigurera godkännanden {#configuring-approvals}

1. [Konfigurera godkännanden för kampanjer](/help/process-management/create-validation-workflows/configure-approvals-for-campaigns.md): Om du har samma uppsättning granskare för alla leveranser i kampanjarbetsflödet kan du använda funktionen för kampanjgodkännande genom att konfigurera godkännanden och granskare på kampanjnivå. Godkännandeaktiviteterna och granskarna överförs till varje leveransaktivitet i arbetsflödet när arbetsflödet har körts.
2. [Konfigurera godkännanden för leveranser](/help/process-management/create-validation-workflows/configure-approvals-for-deliveries.md): Du kan också konfigurera godkännanden på leveransnivå. Leveransinställningarna åsidosätter kampanjinställningarna, om stegen och granskarna för leveransgodkännande skiljer sig från stegen och granskarna för kampanjgodkännande.
3. [Skapa en godkännandeprocess i ett arbetsflöde](/help/process-management/create-validation-workflows/create-approval-process-in-a-workflow.md): Godkännandeaktiviteten gör det möjligt att skapa en godkännandeprocess i ett arbetsflöde. På så sätt kan logiken för målinriktningsvalen godkännas innan leveransen startas. Det möjliggör även godkännande på flera nivåer i arbetsflödet vid behov.

Mer information finns i [dokumentation](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=sv).