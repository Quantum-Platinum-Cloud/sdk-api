---
UID: NF:vidcap.IVideoProcAmp.getRange_Contrast
title: IVideoProcAmp::getRange_Contrast (vidcap.h)
description: The getRange_Contrast method returns the range of contrast settings supported by the camera.
helpviewer_keywords: ["IVideoProcAmp interface [DirectShow]","getRange_Contrast method","IVideoProcAmp.getRange_Contrast","IVideoProcAmp::getRange_Contrast","IVideoProcAmpgetRange_Contrast","dshow.ivideoprocamp_getrange_contrast","getRange_Contrast","getRange_Contrast method [DirectShow]","getRange_Contrast method [DirectShow]","IVideoProcAmp interface","vidcap/IVideoProcAmp::getRange_Contrast"]
old-location: dshow\ivideoprocamp_getrange_contrast.htm
tech.root: dshow
ms.assetid: 3eb160f4-c3e6-4c74-a091-72c55416a81e
ms.date: 4/26/2023
ms.keywords: IVideoProcAmp interface [DirectShow],getRange_Contrast method, IVideoProcAmp.getRange_Contrast, IVideoProcAmp::getRange_Contrast, IVideoProcAmpgetRange_Contrast, dshow.ivideoprocamp_getrange_contrast, getRange_Contrast, getRange_Contrast method [DirectShow], getRange_Contrast method [DirectShow],IVideoProcAmp interface, vidcap/IVideoProcAmp::getRange_Contrast
req.header: vidcap.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP2 [desktop apps only]
req.target-min-winversvr: Windows Server 2003 R2 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IVideoProcAmp::getRange_Contrast
 - vidcap/IVideoProcAmp::getRange_Contrast
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Vidcap.h
api_name:
 - IVideoProcAmp.getRange_Contrast
---

# IVideoProcAmp::getRange_Contrast


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>getRange_Contrast</code> method returns the range of contrast settings supported by the camera.

## -parameters

### -param pMin [out]

Receives the minimum contrast setting.

### -param pMax [out]

Receives the maximum contrast setting.

### -param pSteppingDelta [out]

Receives the smallest step between settings.

### -param pDefault [out]

Receives the default contrast setting.

### -param pCapsFlag [out]

Receives one or more flags. See <a href="/windows/win32/api/strmif/ne-strmif-videoprocampflags">VideoProcAmpFlags</a>.

## -returns

Returns an <b>HRESULT</b> value.

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/vidcap/nn-vidcap-ivideoprocamp">IVideoProcAmp Interface</a>