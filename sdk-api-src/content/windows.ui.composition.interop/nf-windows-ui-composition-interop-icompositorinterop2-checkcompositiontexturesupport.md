---
UID: NF:windows.ui.composition.interop.ICompositorInterop2.CheckCompositionTextureSupport
title: ICompositorInterop2::CheckCompositionTextureSupport
description: TBD
tech.root: winrt
ms.date: 06/15/2023
targetos: Windows
prerelease: true
req.assembly: 
req.construct-type: function
req.ddi-compliance: 
req.dll: 
req.header: windows.ui.composition.interop.h
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
 - windows.ui.composition.interop.h
api_name:
 - ICompositorInterop2::CheckCompositionTextureSupport
f1_keywords:
 - ICompositorInterop2::CheckCompositionTextureSupport
 - windows.ui.composition.interop/ICompositorInterop2::CheckCompositionTextureSupport
dev_langs:
 - c++
helpviewer_keywords:
 - CheckCompositionTextureSupport
---

## -description

Queries whether the Direct3D device that you're using to render supports composition textures (without having to first allocate a Direct3D texture on that device). Before you attempt to create composition textures for D3D textures backed by a given Direct3D device, you should call **CheckCompositionTextureSupport**, passing that backing device.

## -parameters

### -param renderingDevice

Type: \_In\_ **[IUnknown](/windows/win32/api/unknwn/nn-unknwn-iunknown)\***

The backing Direct3D device.

### -param supportsCompositionTextures

Type: \_Out\_ **[BOOL](/windows/win32/winprog/windows-data-types)\***

Points to a value of `true` if *renderingDevice* supports composition textures; otherwise 'false`.

## -returns

Type: **[HRESULT](/windows/win32/winprog/windows-data-types)**

If the function succeeds, it returns **S_OK**. Otherwise, it returns an [HRESULT](/windows/win32/winprog/windows-data-types) error code.

## -remarks

## -see-also

* [ICompositorInterop2 interface](./nn-windows-ui-composition-interop-icompositorinterop2.md)
