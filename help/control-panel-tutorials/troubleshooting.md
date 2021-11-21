---
title: Felsöka kontrollpanelen
description: Lär dig hur du felsöker Kontrollpanelen
feature: Control Panel
kt: 8520
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 0dca4676-2d5e-411b-9fdf-fbfd1081cb0e
source-git-commit: f7cb6c57d9cd6b00def9f0a4ccbcc94267f0d593
workflow-type: tm+mt
source-wordcount: '338'
ht-degree: 100%

---

# Felsöka [!UICONTROL Kontrollpanelen]

Lär dig hur du felsöker Kontrollpanelen.

## Inloggning och hemsida

### Symptom: Det går inte att logga in på Experience Cloud

**Gör så här:**
Användaren måste hitta sitt IMS-organisations-ID (xxx). Administratören måste lägga till användaren i produktprofilen &quot;Campaign-xxx-Admins&quot; för varje instans som denne vill hantera. Om användaren är en administratör för alla instanser kan denne fortfarande behöva lägga till sig själv som användare.

### Symptom: Länkar i Experience Cloud Home för åtkomst till [!UICONTROL Kontrollpanelen] visas inte för en användare

**Orsak:**
Användare ser inte länkarna förrän de läggs till som användare i produktprofilen _Campaign-xxx-Administrators/Admin_.

**Gör så här:**
Administratören måste lägga till användaren i Product Profile _Campaign-xxx-Admins_ för varje instans som de ska hantera. Om användaren är en administratör för alla instanser kan denne fortfarande behöva lägga till sig själv som användare.

### Symptom: En instans visas inte i [!UICONTROL Kontrollpanelen]

**Orsak:**
Sannolikt måste användaren läggas till som *användare* Produktprofil _Campaign-xxx-Administrators/Admin_ för instansen som saknas

**Gör så här:**
Administratören måste lägga till användaren i Produktprofil _Campaign-xxx-Admins_  för varje instans som ska hanteras. Om användaren är en administratör för alla instanser kan denne fortfarande behöva lägga till sig själv som &quot;användare&quot;.

### Användbara videor

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Kontrollera ett IMS-organisations-ID (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Så här läggs en administratör till i produktprofiladministratörer som ska kunna använda [!UICONTROL Kontrollpanelen] (01:03 min)*

### Användbar dokumentation

* [Lär känna kontrollpanelen](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=sv)
* [Hantera behörigheter till [!UICONTROL Kontrollpanelen]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Upprätta en anslutning till en SFTP-server (klient eller API)

För anslutning till SFTP-servrar krävs:

* [!UICONTROL Tillåt listning av]IP-adressen från vilken du ansluter till SFTP-servern
* Ett privat/offentligt nyckelpar som måste registreras i Adobe Campaign
* Om du ansluter till SFTP-servern direkt behöver du även en SFTP-klientprogramvara

### Användbar dokumentation {#helpful-docs}

* [Logga in på SFTP-servern](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
