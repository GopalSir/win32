---
Description: Raised by the audio renderer when the audio session display name changes.
ms.assetid: d180b145-88e1-4f85-b001-b76140ca39d8
title: MEAudioSessionNameChanged event
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# MEAudioSessionNameChanged event

Raised by the audio renderer when the audio session display name changes.

The Media Session forwards this event to the application.

## Event values

Possible values retrieved from [**IMFMediaEvent::GetValue**](/windows/desktop/api/mfobjects/nf-mfobjects-imfmediaevent-getvalue) include the following.



| VARTYPE                | Description                                                                               |
|------------------------|-------------------------------------------------------------------------------------------|
| VT\_UNKNOWN<br/> | Pointer to the [**IMFAudioPolicy**](/windows/desktop/api/mfidl/nn-mfidl-imfaudiopolicy) interface.<br/> <br/> |



## Remarks

This event is sent by the audio renderer's stream sink. The event is triggered when the audio renderer receives an [**IAudioSessionEvents::OnDisplayNameChanged**](https://msdn.microsoft.com/65d21f0c-b6f1-4506-975c-6d0308b3fc2f) event from the audio session.

To get the new display name, call [**IMFAudioPolicy::GetDisplayName**](/windows/desktop/api/mfidl/nf-mfidl-imfaudiopolicy-getdisplayname).

## Requirements



|                                     |                                                                                                          |
|-------------------------------------|----------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows Vista \[desktop apps only\]<br/>                                                           |
| Minimum supported server<br/> | Windows Server 2008 \[desktop apps only\]<br/>                                                     |
| Header<br/>                   | <dl> <dt>Mfobjects.h (include Mfidl.h)</dt> </dl> |



## See also

<dl> <dt>

[**IMFAudioPolicy::GetDisplayName**](/windows/desktop/api/mfidl/nf-mfidl-imfaudiopolicy-getdisplayname)
</dt> <dt>

[Media Foundation Events](media-foundation-events.md)
</dt> <dt>

[Streaming Audio Renderer](streaming-audio-renderer.md)
</dt> </dl>

 

 



