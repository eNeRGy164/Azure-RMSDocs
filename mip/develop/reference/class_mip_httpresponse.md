---
title: class mip::HttpResponse 
description: Documents the mip::httpresponse class of the Microsoft Information Protection (MIP) SDK.
author: msmbaldwin
ms.service: information-protection
ms.topic: reference
ms.author: mbaldwin
ms.date: 08/27/2019
---

# class mip::HttpResponse 
Interface that describes a single HTTP response, implemented by client app when overriding [HttpDelegate](class_mip_httpdelegate.md).
  
## Summary
 Members                        | Descriptions                                
--------------------------------|---------------------------------------------
public const std::string& GetId() const  |  Gets response ID.
public int32_t GetStatusCode() const  |  Get response status code.
public const std::vector\<uint8_t\>& GetBody() const  |  Get request body.
public const std::map\<std::string, std::string, CaseInsensitiveComparator\>& GetHeaders() const  |  Get request headers.
  
## Members
  
### GetId function
Gets response ID.

  
**Returns**: Response ID
The corresponding HttpRequest will have had the same ID
  
### GetStatusCode function
Get response status code.

  
**Returns**: Status code
  
### GetBody function
Get request body.

  
**Returns**: Request body
  
### GetHeaders function
Get request headers.

  
**Returns**: Request headers