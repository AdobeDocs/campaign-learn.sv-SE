---
title: Konfigurera återkommande och kontinuerliga e-postkampanjer
description: Lär dig hur du ställer in en återkommande och kontinuerlig leverans och förstå skillnaderna mellan de två metoderna.
feature: Arbetsflöden
kt: 7982
doc-type: feature video
activity: use
team: TM
role: Business Practitioner
level: Beginner
source-git-commit: 7609aa35dba225a05c8f5e3d3f75f4b6023772a0
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 100%

---


# Konfigurera återkommande och kontinuerliga e-postkampanjer

I den här självstudiekursen beskrivs hur du ställer in en återkommande och kontinuerlig leverans och skillnaderna mellan de två metoderna.

## Spårning av återkommande och kontinuerlig leverans {#recurring-and-continuous-delivery-tracking}

De återkommande och kontinuerliga leveranserna skiljer sig åt när det gäller hur kontaktdata hanteras:

* Med **kontinuerlig leverans** kan du lägga till nya mottagare till en befintlig leverans och undvika att du måste skapa en leverans varje gång en ny mottagare läggs till. Du kan uppdatera den kreativa informationen direkt i kampanjarbetsflödet och uppdatera mallen i leveransmallens resursmapp.

   En kontinuerlig leverans skapar en enskild leverans och leveransloggar (broadLog) och spårningsloggar, som refererar till denna leverans, läggs till varje gång den körs.

![Kontinuerlig leverans](/help/assets/delivery_continuous.jpg)

* En **återkommande leverans** skapar en leveransinstans varje gång den körs. Om arbetsflödet till exempel är schemalagt att köras en gång i veckan resulterar det i 52 leveranser efter ett år. Det innebär också att de breda loggarna och spårningsloggarna separeras av leveransinstansen.

![Återkommande leverans](/help/assets/delivery_recurring.jpg)

## Så ställer du in en återkommande leverans {#how-to-set-up-a-recurring-delivery}

I videon förklaras hur du konfigurerar en återkommande leverans och en schemalagd aktivitet.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Så ställer du in en kontinuerlig leverans {#how-to-set-up-a-continuous-delivery}

I den här videon visas hur du konfigurerar en kontinuerlig leverans med en stegvis frågeställning.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)
