---
title: Skapa ett exportarbetsflöde (del 1) – hitta datumet för senaste ändring för en lista över mottagare
description: I den här första delen av självstudiekursen Skapa ett exportarbetsflöde, får du lära dig hur du skapar ett arbetsflöde som hittar datumet för senaste ändring för en lista med mottagare som skapats från ett Experience Platform-segment.
feature: Data Import/Export, Workflows
kt: 8162
thumbnail: 336387.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: 6fd70eea-3be7-4589-a608-05b0a8de93a6
source-git-commit: b1b8d8a99a551239c445fb588cbd126b66a53c9b
workflow-type: tm+mt
source-wordcount: '120'
ht-degree: 100%

---

# Skapa ett exportarbetsflöde (del 1) – hitta datumet för senaste ändring för en lista över mottagare

I den här första delen av självstudiekursen Skapa ett exportarbetsflöde, får du lära dig hur du skapar ett arbetsflöde som hittar datumet för senaste ändring för en lista med mottagare som skapats från ett Experience Platform-segment.

>[!VIDEO](https://video.tv.adobe.com/v/336387?quality=12&learn=on)

## Resurser

JavaScript för att skapa datumintervall:

```java
 var DEFAULT_LOOKBACK_DAYS = 90;
 vars.OPTION_NAME = "BroadLog_CaptureTime";

 logInfo("=====================");
 logInfo("Starting Execution...");

 // Establish the last and next RunTimes
 var lastRunTime = getOption(vars.OPTION_NAME);
 var nextRunTime = getCurrentDate();

 //To reset and run through DEFAULT_LOOKBACK, uncomment the following line.
 //lastRunTime = null;

 logInfo("NEXT Run Date Set: [" + nextRunTime + "]");
 logInfo("LAST Run Date Retrieved (" + lastRunTime + ")");

 //Check for null so we can default the lastRunTime using the DEFAULT_LOOKBACK 
 if (lastRunTime == null || lastRunTime == "null" || lastRunTime == "") {

   logInfo("Empty Date Retrieved, setting to default lookback (-" + DEFAULT_LOOKBACK_DAYS + " days)");
   lastRunTime = new Date();
   lastRunTime.setDate(nextRunTime.getDate() - DEFAULT_LOOKBACK_DAYS);
   logInfo("LAST Run Date Set: [" + lastRunTime + "]");

 } 

 //Persist values through execution of this instance of the workflow.
 vars.lastRunTime = lastRunTime;
 vars.nextRunTime = nextRunTime;

 logInfo("Finished Execution.");
 logInfo("===================");
```

## Nästa video

[Skapa ett exportarbetsflöde (del 2) – extrahera, formatera och spara data till ett externt konto](extract-format-save-data-to-external-account.md)
