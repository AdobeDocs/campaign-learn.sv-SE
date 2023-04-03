---
title: Skapa ett exportarbetsflöde (del 2) – extrahera, formatera och spara data till ett externt konto
description: I den andra delen av självstudiekursen Skapa ett exportarbetsflöde får du lära dig hur du formaterar data för export och hur du sparar data till ett externt konto.
feature: Data Import/Export, Workflows
kt: 8160
thumbnail: 336391.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: ac29b75c-a838-4183-8ec5-034281290725
source-git-commit: b1b8d8a99a551239c445fb588cbd126b66a53c9b
workflow-type: ht
source-wordcount: '0'
ht-degree: 100%

---

# Skapa ett exportarbetsflöde (del 2): extrahera, formatera och spara data till ett externt konto

I den andra delen av självstudiekursen Skapa ett exportarbetsflöde får du lära dig hur du formaterar data för export och hur du sparar data till ett externt konto.

>[!VIDEO](https://video.tv.adobe.com/v/336391?quality=12&learn=on)

## Resurser

JavaScript: spara datum

```java
 logInfo("=====================")
 logInfo("Starting Execution...")

 optionName = vars.OPTION_NAME;
 logInfo("optionName: " + optionName);
 logInfo("NEXT Run Date: " + vars.nextRunTime);
 
 //Make sure we have valid values before saving for next run
 if (vars.nextRunTime == null || optionName == null){

   logInfo("Unable to find non-null values for optionName/nextRunTime! Throwing Error.")
   throw new Error('Unable to find non-null values for optionName/nextRunTime!  Ending Execution.');

 } else {

   // Save the nextRunTime to the database to establish starting point for next run.
   setOption(optionName, vars.nextRunTime);
   logInfo("Date Saved. [" + optionName + "] = [" + vars.lastRunTime + "]")

 }

 logInfo("Finished Execution.") 
 logInfo("===================")
```
