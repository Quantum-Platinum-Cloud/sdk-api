---
UID: NF:control.IDeferredCommand.Postpone
title: IDeferredCommand::Postpone (control.h)
description: The Postpone method specifies a new invocation time for the command.
helpviewer_keywords: ["IDeferredCommand interface [DirectShow]","Postpone method","IDeferredCommand.Postpone","IDeferredCommand::Postpone","IDeferredCommandPostpone","Postpone","Postpone method [DirectShow]","Postpone method [DirectShow]","IDeferredCommand interface","control/IDeferredCommand::Postpone","dshow.ideferredcommand_postpone"]
old-location: dshow\ideferredcommand_postpone.htm
tech.root: dshow
ms.assetid: 184370db-95df-45a8-b1a0-e399923f866e
ms.date: 4/26/2023
ms.keywords: IDeferredCommand interface [DirectShow],Postpone method, IDeferredCommand.Postpone, IDeferredCommand::Postpone, IDeferredCommandPostpone, Postpone, Postpone method [DirectShow], Postpone method [DirectShow],IDeferredCommand interface, control/IDeferredCommand::Postpone, dshow.ideferredcommand_postpone
req.header: control.h
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
 - IDeferredCommand::Postpone
 - control/IDeferredCommand::Postpone
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
 - IDeferredCommand.Postpone
---

# IDeferredCommand::Postpone


## -description

\[The feature associated with this page, [DirectShow](/windows/win32/directshow/directshow), is a legacy feature. It has been superseded by [MediaPlayer](/uwp/api/Windows.Media.Playback.MediaPlayer) and [IMFMediaEngine](/windows/win32/api/mfmediaengine/nn-mfmediaengine-imfmediaengine). **MediaPlayer** and **IMFMediaEngine** have been optimized for Windows 10 and Windows 11. Microsoft strongly recommends that new code use **MediaPlayer** and **IMFMediaEngine** instead of **DirectShow**, when possible. Microsoft suggests that existing code that uses the legacy APIs be rewritten to use the new APIs if possible.\]

The <code>Postpone</code> method specifies a new invocation time for the command.

## -parameters

### -param newtime

New time at which to invoke the command.

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
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
Success.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>VFW_E_TIME_ALREADY_PASSED</b></dt>
</dl>
</td>
<td width="60%">
The specified time has already passed.

</td>
</tr>
</table>

## -see-also

<a href="/windows/desktop/DirectShow/error-and-success-codes">Error and Success Codes</a>



<a href="/windows/desktop/api/control/nn-control-ideferredcommand">IDeferredCommand Interface</a>