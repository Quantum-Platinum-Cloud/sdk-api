---
UID: NF:strmif.IVMRWindowlessControl.RepaintVideo
title: IVMRWindowlessControl::RepaintVideo (strmif.h)
description: The RepaintVideo method repaints the current video frame.
helpviewer_keywords: ["IVMRWindowlessControl interface [DirectShow]","RepaintVideo method","IVMRWindowlessControl.RepaintVideo","IVMRWindowlessControl::RepaintVideo","IVMRWindowlessControlRepaintVideo","RepaintVideo","RepaintVideo method [DirectShow]","RepaintVideo method [DirectShow]","IVMRWindowlessControl interface","dshow.ivmrwindowlesscontrol_repaintvideo","strmif/IVMRWindowlessControl::RepaintVideo"]
old-location: dshow\ivmrwindowlesscontrol_repaintvideo.htm
tech.root: dshow
ms.assetid: 16ef3bc1-1781-44f7-a997-ae9b1b3c405c
ms.date: 4/26/2023
ms.keywords: IVMRWindowlessControl interface [DirectShow],RepaintVideo method, IVMRWindowlessControl.RepaintVideo, IVMRWindowlessControl::RepaintVideo, IVMRWindowlessControlRepaintVideo, RepaintVideo, RepaintVideo method [DirectShow], RepaintVideo method [DirectShow],IVMRWindowlessControl interface, dshow.ivmrwindowlesscontrol_repaintvideo, strmif/IVMRWindowlessControl::RepaintVideo
req.header: strmif.h
req.include-header: Dshow.h
req.target-type: Windows
req.target-min-winverclnt: Windows XP with SP1 [desktop apps only]
req.target-min-winversvr: Windows Server 2003 [desktop apps only]
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
 - IVMRWindowlessControl::RepaintVideo
 - strmif/IVMRWindowlessControl::RepaintVideo
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
 - IVMRWindowlessControl.RepaintVideo
---

# IVMRWindowlessControl::RepaintVideo


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>RepaintVideo</code> method repaints the current video frame.

## -parameters

### -param hwnd [in]

Specifies the handle of the window in which the repainting should occur.

### -param hdc [in]

Specifies the handle to the device context for the window.

## -returns

If the method succeeds, it returns S_OK. If it fails, it returns an error code.

<table>
<tr>
<th>Return code</th>
<th>Description</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>VFW_E_WRONG_STATE</b></dt>
</dl>
</td>
<td width="60%">
The VMR is not in windowless mode.

</td>
</tr>
</table>

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/strmif/nn-strmif-ivmrwindowlesscontrol">IVMRWindowlessControl Interface</a>



<a href="/windows/desktop/DirectShow/using-the-video-mixing-renderer">Using the Video Mixing Renderer</a>