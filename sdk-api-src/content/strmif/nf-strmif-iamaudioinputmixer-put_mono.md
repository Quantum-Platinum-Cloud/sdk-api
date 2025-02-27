---
UID: NF:strmif.IAMAudioInputMixer.put_Mono
title: IAMAudioInputMixer::put_Mono (strmif.h)
description: The put_Mono method combines all channels into a mono signal.
helpviewer_keywords: ["IAMAudioInputMixer interface [DirectShow]","put_Mono method","IAMAudioInputMixer.put_Mono","IAMAudioInputMixer::put_Mono","IAMAudioInputMixerput_Mono","dshow.iamaudioinputmixer_put_mono","put_Mono","put_Mono method [DirectShow]","put_Mono method [DirectShow]","IAMAudioInputMixer interface","strmif/IAMAudioInputMixer::put_Mono"]
old-location: dshow\iamaudioinputmixer_put_mono.htm
tech.root: dshow
ms.assetid: fb45a1ad-b6d8-4129-97f3-a9c99053c0f0
ms.date: 4/26/2023
ms.keywords: IAMAudioInputMixer interface [DirectShow],put_Mono method, IAMAudioInputMixer.put_Mono, IAMAudioInputMixer::put_Mono, IAMAudioInputMixerput_Mono, dshow.iamaudioinputmixer_put_mono, put_Mono, put_Mono method [DirectShow], put_Mono method [DirectShow],IAMAudioInputMixer interface, strmif/IAMAudioInputMixer::put_Mono
req.header: strmif.h
req.include-header: Dshow.h
req.target-type: Windows
req.target-min-winverclnt: Windows 2000 Professional [desktop apps only]
req.target-min-winversvr: Windows 2000 Server [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Strmiids.lib
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
f1_keywords:
 - IAMAudioInputMixer::put_Mono
 - strmif/IAMAudioInputMixer::put_Mono
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - Strmiids.lib
 - Strmiids.dll
api_name:
 - IAMAudioInputMixer.put_Mono
---

# IAMAudioInputMixer::put_Mono


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>put_Mono</code> method combines all channels into a mono signal.

## -parameters

### -param fMono [in]

Specifies mono or multichannel. Use one of the following values.

<table>
<tr>
<th>Value
                </th>
<th>Description
                </th>
</tr>
<tr>
<td><b>TRUE</b></td>
<td>Mono</td>
</tr>
<tr>
<td><b>FALSE</b></td>
<td>Multichannel</td>
</tr>
</table>

## -returns

Returns an <b>HRESULT</b> value. Possible values include the following.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_FAIL</b></dt>
</dl>
</td>
<td width="60%">
Error setting mono control.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
Success.

</td>
</tr>
</table>

## -remarks

In mono mode, a stereo recording of this input will have the same data in both channels. The result will be a mixture of the left and right signals.

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/strmif/nn-strmif-iamaudioinputmixer">IAMAudioInputMixer Interface</a>



<a href="/windows/desktop/api/strmif/nf-strmif-iamaudioinputmixer-get_mono">IAMAudioInputMixer::get_Mono</a>