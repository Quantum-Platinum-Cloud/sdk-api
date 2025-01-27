---
UID: NF:vidcap.IVideoProcAmp.put_ColorEnable
title: IVideoProcAmp::put_ColorEnable (vidcap.h)
description: The put_ColorEnable method sets the camera's color-enable setting.
helpviewer_keywords: ["IVideoProcAmp interface [DirectShow]","put_ColorEnable method","IVideoProcAmp.put_ColorEnable","IVideoProcAmp::put_ColorEnable","IVideoProcAmpput_ColorEnable","dshow.ivideoprocamp_put_colorenable","put_ColorEnable","put_ColorEnable method [DirectShow]","put_ColorEnable method [DirectShow]","IVideoProcAmp interface","vidcap/IVideoProcAmp::put_ColorEnable"]
old-location: dshow\ivideoprocamp_put_colorenable.htm
tech.root: dshow
ms.assetid: 6a1caa3f-e591-4176-90b9-80a4bd71533b
ms.date: 4/26/2023
ms.keywords: IVideoProcAmp interface [DirectShow],put_ColorEnable method, IVideoProcAmp.put_ColorEnable, IVideoProcAmp::put_ColorEnable, IVideoProcAmpput_ColorEnable, dshow.ivideoprocamp_put_colorenable, put_ColorEnable, put_ColorEnable method [DirectShow], put_ColorEnable method [DirectShow],IVideoProcAmp interface, vidcap/IVideoProcAmp::put_ColorEnable
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
 - IVideoProcAmp::put_ColorEnable
 - vidcap/IVideoProcAmp::put_ColorEnable
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
 - IVideoProcAmp.put_ColorEnable
---

# IVideoProcAmp::put_ColorEnable


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>put_ColorEnable</code> method sets the camera's color-enable setting.

## -parameters

### -param Value [in]

Specifies one of the following values.

<table>
<tr>
<th>Value
                </th>
<th>Description
                </th>
</tr>
<tr>
<td>0</td>
<td>Color disabled.</td>
</tr>
<tr>
<td>1</td>
<td>Color enabled.</td>
</tr>
</table>

### -param Flags [in]

Zero or more flags. See <a href="/windows/win32/api/strmif/ne-strmif-videoprocampflags">VideoProcAmpFlags</a>. If the VideoProcAmp_Flags_Auto flag is used, the <i>Value</i> parameter is ignored and the camera sets the default value.

## -returns

Returns an <b>HRESULT</b> value.

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/vidcap/nn-vidcap-ivideoprocamp">IVideoProcAmp Interface</a>