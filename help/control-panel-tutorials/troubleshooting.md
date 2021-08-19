---
title: Felsöka kontrollpanelen
description: Lär dig hur du felsöker Kontrollpanelen
feature: 'Kontrollpanelen  '
kt: 8520
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
source-git-commit: 4fc34f56e13c3df5f1c42c24c87a6c7c5caff04b
workflow-type: tm+mt
source-wordcount: '340'
ht-degree: 19%

---

# Felsökning [!UICONTROL Kontrollpanelen]

Lär dig hur du felsöker Kontrollpanelen.

## Logga in och hemsida

### Symptom: Det går inte att logga in i Experience Cloud

**Vad du ska göra:**
Användaren måste hitta sitt IMS-org-ID (xxx). Administratören måste lägga till användaren i produktprofilen&quot;Campaign-xxx-Admins&quot; för varje instans som han/hon vill hantera. Om användaren är administratör för alla instanser måste han eller hon lägga till sig själv som användare.

### Symptom: Länkar i startsidan för Experience Cloud som ger åtkomst till [!UICONTROL Kontrollpanelen] visas inte för en användare

**Orsak:**
Användare kan inte se länkarna förrän de har lagts till som användare i produktprofilen  _Campaign-xxx-Administrators/Admin_.

**Vad du ska göra:**
Administratören måste lägga till användaren i produktprofilen  _Campaign-xxx-_  Adminsför varje instans som han/hon vill hantera. Om användaren är administratör för alla instanser måste han eller hon lägga till sig själv som användare.

### Symptom: En instans visas inte i listan i [!UICONTROL Kontrollpanelen]

**Orsak:**
Den mest troliga användaren måste läggas till som en  ** userProduct Profile  _Campaign-xxx-Administrators/_ Adminfor den instans som saknas

**Vad du ska göra:**
Administratören måste lägga till användaren i produktprofilen  _Campaign-xxx-_  Adminsför varje instans som han/hon vill hantera. Om användaren är administratör för alla instanser måste han eller hon lägga till sig själv som&quot;användare&quot;.

### Användbara videor

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Kontrollera ett IMS-organisations-ID (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Så här lägger du till en administratör till produktprofiladministratörerna för att kunna använda  [!UICONTROL kontrollpanelen]  (01:03 min)*

### Användbar dokumentation

* [Lär känna kontrollpanelen](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=sv)
* [Hantera behörigheter till  [!UICONTROL Kontrollpanelen]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Upprätta en anslutning till en SFTP-server (klient eller API)

För anslutning till SFTP-servrar krävs:

* [!UICONTROL Tillåt ] att IP-adressen som du ansluter till SFTP-servern listas
* Privat/offentlig nyckel som måste registreras hos Adobe Campaign
* Om du vill ansluta till SFTP-servern direkt behöver du också SFTP-klientprogramvara

### Användbar dokumentation {#helpful-docs}

* [Logga in på SFTP-servern](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
