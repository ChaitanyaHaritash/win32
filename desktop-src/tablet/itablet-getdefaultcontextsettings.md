---
Description: Retrieves the default context settings for the tablet.
ms.assetid: 59d1bab0-a8b8-4e23-9311-2921f9035dc4
title: ITablet::GetDefaultContextSettings method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# ITablet::GetDefaultContextSettings method

Retrieves the default context settings for the tablet.

## Syntax


```C++
HRESULT GetDefaultContextSettings(
  [out] TABLET_CONTEXT_SETTINGS **ppTCS
);
```



## Parameters

<dl> <dt>

*ppTCS* \[out\]
</dt> <dd>

The default context settings for the tablet.

</dd> </dl>

## Return value

This method can return one of these values.



| Return code                                                                            | Description                               |
|----------------------------------------------------------------------------------------|-------------------------------------------|
| <dl> <dt>**S\_OK**</dt> </dl>   | Success.<br/>                       |
| <dl> <dt>**E\_FAIL**</dt> </dl> | An unspecified error occurred.<br/> |



 

## Remarks

It is the caller's responsibility to free the memory returned from this method by using [**CoTaskMemFree**](https://msdn.microsoft.com/library/windows/desktop/ms680722).

## Requirements



|                                     |                                                                                        |
|-------------------------------------|----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows XP Tablet PC Edition \[desktop apps only\]<br/>                          |
| Minimum supported server<br/> | None supported<br/>                                                              |
| Library<br/>                  | <dl> <dt>Wisptis.exe</dt> </dl> |



## See also

<dl> <dt>

[**ITablet Interface**](itablet.md)
</dt> </dl>

 

 



