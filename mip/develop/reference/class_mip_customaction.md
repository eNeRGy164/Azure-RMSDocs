---
title: class mip::CustomAction 
description: Documents the mip::customaction class of the Microsoft Information Protection (MIP) SDK.
author: msmbaldwin
ms.service: information-protection
ms.topic: reference
ms.author: mbaldwin
ms.date: 08/27/2019
---

# class mip::CustomAction 
[CustomAction](class_mip_customaction.md) is a generic action class that captures all the sub-properties of the action as a property bag. The caller is responsible to understand the meaning of the action.
  
## Summary
 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
public const std::string& GetName() const  |  Get action name.
public const std::vector\<std::pair\<std::string, std::string\>\>& GetProperties() const  |  Get the properties key value pair list.
  
## Members
  
### GetName function
Get action name.

  
**Returns**: An action name if one exists else an empty string.
  
### GetProperties function
Get the properties key value pair list.

  
**Returns**: A key value pair list.