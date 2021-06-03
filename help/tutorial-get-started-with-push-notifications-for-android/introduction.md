---
title: Komma igång med push-meddelanden för Android – inledning
description: I den här självstudiekursen får du hjälp med att skicka push-meddelanden från Adobe Campaign och ta emot dessa meddelanden i din Android™-app.
feature: Tryck
kt: 6438
doc-type: article
activity: setup
team: TM
role: Administrator, Developer
level: Experienced
source-git-commit: 39bed2fe5fbe19101a9684b29d73f61026ad77b2
workflow-type: tm+mt
source-wordcount: '318'
ht-degree: 41%

---

# Komma igång med push-meddelanden för Android – inledning

Adobe Campaign låter dig skicka personaliserade och segmenterade [!DNL push]-meddelanden till mobila [!DNL iOS]- och [!DNL Android™]-enheter I den här självstudiekursen får du hjälp med att skicka [!DNL push]-meddelanden från Adobe Campaign till en [!DNL Android™]-app.

## Förhandskrav

Innan du kan börja måste du ha följande:

1) **Android™ Mobile-program**

   Den här självstudiekursen omfattar inte de detaljerade steg som krävs för att konfigurera den mobila appen. Du måste ha ett **[!DNL Android™]-mobilprogram med [!DNL Campaign SDK] integrerat**.

   Du hittar en detaljerad beskrivning över stegen som krävs i produktdokumentationen:

   [Integrera Campaign SDK i den mobila applikationen](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=sv)

2) **[!DNL Mobile App channel]-paket installerat**

   Paketet [!DNL Mobile App channel] måste vara installerat på din [!DNL Campaign]-instans. Följande video förklarar hur du kontrollerar om [!DNL Mobile App channel] är installerat på din instans och hur du installerar det om så inte är fallet.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Översikt över självstudiekurser

Målet är att skicka ett personligt kampanjmeddelande [!DNL push] till prenumeranterna på [!DNL Neotrip] [!DNL Android™]-mobilappen. Appen [!DNL Neotrip] är konfigurerad med [!DNL Campaign SDK] och [!DNL Mobile App channel] är aktiverad för instansen [!DNL Campaign].

Följande konfigurationssteg krävs:

### Steg 1: utöka appens prenumerationsschema för att anpassa [!DNL push]-meddelanden

Om du vill kunna anpassa [!DNL push]-meddelandet måste du först [utöka programmets prenumerationsschema](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md). Det gör att systemet kan lagra de personaliseringsvärden som tas emot från appen när användaren prenumererar på tjänsten.

### Steg 2: Konfigurera Android™-tjänsten och skapa mobilprogrammet i Campaign

Sedan [måste Android™-tjänsten vara konfigurerad och mobilprogrammet som skapas i Campaign](/help/tutorial-get-started-with-push-notifications-for-android/configure-an-android-service-in-campaign.md). I det här steget definieras [!DNL Neotrip]-appen som mål för push-meddelandet.

### Steg 3: konfigurera och skicka push-meddelandet

Nu är push-meddelandet klart att konfigureras och skickas[.](/help/tutorial-get-started-with-push-notifications-for-android/configure-and-send-push-notifications.md)

## Starta självstudiekursen

Steg 1: [utöka appens prenumerationsschema](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)
