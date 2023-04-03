---
title: Skapa återkommande och kontinuerliga e-postleveranser
description: Lär dig hur du ställer in en återkommande och kontinuerlig leverans och förstå skillnaderna mellan de två metoderna.
feature: Workflows
kt: 7982
thumbnail: 342637.jpg
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 469aecd7-4774-42c6-b07f-82792dfdc9c2
source-git-commit: b1b8d8a99a551239c445fb588cbd126b66a53c9b
workflow-type: tm+mt
source-wordcount: '232'
ht-degree: 94%

---

# Skapa återkommande och kontinuerliga e-postleveranser

I den här självstudiekursen beskrivs hur du ställer in en återkommande och kontinuerlig leverans och skillnaderna mellan de två metoderna.

## Återkommande och kontinuerlig leveransspårning {#recurring-and-continuous-delivery-tracking}

De återkommande och kontinuerliga leveranserna skiljer sig åt när det gäller hur kontaktdata hanteras:

* Med **kontinuerlig leverans** kan du lägga till nya mottagare till en befintlig leverans och undvika att du måste skapa en leverans varje gång en ny mottagare läggs till. Du kan uppdatera den kreativa informationen direkt i kampanjarbetsflödet och uppdatera mallen i leveransmallens resursmapp.

   En kontinuerlig leverans skapar en enskild leverans och leveransloggar (broadLog) och spårningsloggar, som refererar till denna leverans, läggs till varje gång den körs.

![Kontinuerlig leverans](/help/assets/delivery_continuous.jpg)

* En **återkommande leverans** skapar en leveransinstans varje gång den körs. Om arbetsflödet till exempel är schemalagt att köras en gång i veckan resulterar det i 52 leveranser efter ett år. Det innebär också att de breda loggarna och spårningsloggarna separeras av leveransinstansen.

![Återkommande leverans](/help/assets/delivery_recurring.jpg)

## Så ställer du in en återkommande leverans {#how-to-set-up-a-recurring-delivery}

Videon förklarar hur du konfigurerar en återkommande leverans och en schemalagd aktivitet.

>[!VIDEO](https://video.tv.adobe.com/v/342638?quality=12&learn=on)

## Så ställer du in en kontinuerlig leverans {#how-to-set-up-a-continuous-delivery}

Den här videon visar hur du konfigurerar en kontinuerlig leverans med en stegvis frågeställning.

>[!VIDEO](https://video.tv.adobe.com/v/342637?quality=12&learn=on)
