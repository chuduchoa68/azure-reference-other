---
title: "Error 0144 | Microsoft Docs"
titleSuffix: "Azure Machine Learning Studio"
ms.date: 07/19/2016
ms.service: "machine-learning"
ms.subservice: "studio"
ms.topic: "reference"


author: xiaoharper
ms.author: amlstudiodocs
manager: cgronlun
---
# Error 0144  
 User-provided GitHub url is missing the expected part.  
  
 This error in Azure Machine Learning occurs when you specify a GitHub file source using an invalid URL format.  
  
## Resolution  
 Check that the URL of the GitHub repository is valid and ends with \blob\ or \tree\\.  
  
|Exception Messages|  
|------------------------|  
|Cannot parse GitHub URL.|  
|Cannot parse GitHub URL (expecting '\blob\\' or '\tree\\' after the repository name): {0}|  
  
## See also  
 [Module error codes](../machine-learning-module-error-codes.md)
