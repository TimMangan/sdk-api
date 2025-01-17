---
UID: NF:print3dmanagerinterop.IPrinting3DManagerInterop.ShowPrintUIForWindowAsync
tech.root: winrt
title: IPrinting3DManagerInterop::ShowPrintUIForWindowAsync
ms.date: 04/16/2021
targetos: Windows
description: Programmatically initiates the 3D printing user interface.
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: print3dmanagerinterop.h
req.idl: 
req.include-header: 
req.irql: 
req.kmdf-ver: 
req.lib: 
req.max-support: 
req.namespace: 
req.redist: 
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.target-type: 
req.type-library: 
req.umdf-ver: 
req.unicode-ansi: 
topic_type:
 - apiref
api_type:
 - COM
api_location:
 - print3dmanagerinterop.h
api_name:
 - IPrinting3DManagerInterop::ShowPrintUIForWindowAsync
f1_keywords:
 - IPrinting3DManagerInterop::ShowPrintUIForWindowAsync
 - print3dmanagerinterop/IPrinting3DManagerInterop::ShowPrintUIForWindowAsync
dev_langs:
 - c++
---

## -description

Programmatically initiates the 3D printing user interface.

## -parameters

### -param appWindow

Handle to the window of the active application.

### -param riid

The GUID for the resource interface.

The REFIID, or GUID, of the interface to the resource can be obtained by using the __uuidof() macro. For example: 

`__uuidof(IAsyncAction)` 

### -param asyncOperation

Address of a pointer to a [IAsyncAction](/uwp/api/Windows.Foundation.IAsyncAction) object that returns void upon completion.


## -returns

If this function succeeds, it returns S_OK. Otherwise, it returns an HRESULT error code.


## -remarks

## -see-also

