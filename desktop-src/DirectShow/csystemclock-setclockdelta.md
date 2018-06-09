---
Description: The SetClockDelta method adjusts the clock time. This method implements the IAMClockAdjust::SetClockDelta method.
ms.assetid: 2bb9266f-3866-4b2e-92a8-cde31a501047
title: CSystemClock.SetClockDelta method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# CSystemClock.SetClockDelta method

The `SetClockDelta` method adjusts the clock time. This method implements the [**IAMClockAdjust::SetClockDelta**](/windows/desktop/api/Strmif/nf-strmif-iamclockadjust-setclockdelta) method.

## Syntax


```C++
HRESULT SetClockDelta(
   REFERENCE_TIME rtDelta
);
```



## Parameters

<dl> <dt>

*rtDelta* 
</dt> <dd>

Specifies the amount by which to adjust the clock, as a [**REFERENCE\_TIME**](reference-time.md) value. A positive value moves the clock forward, and a negative value moves the clock backward.

</dd> </dl>

## Return value

Returns S\_OK or an **HRESULT** error code.

## Remarks

This method simply calls [**CBaseReferenceClock::SetTimeDelta**](cbasereferenceclock-settimedelta.md).

The time values returned by [**IReferenceClock::GetTime**](/windows/desktop/api/Strmif/nf-strmif-ireferenceclock-gettime) are monotonically increasing. If you set the clock back, **GetTime** continues to report the old time until the internal clock catches up.

## Requirements



|                    |                                                                                                                                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Version<br/> | CSystemClock Class<br/>                                                                                                                                                              |
| Header<br/>  | <dl> <dt>Sysclock.h (include Streams.h)</dt> </dl>                                                                                  |
| Library<br/> | <dl> <dt>Strmbase.lib (retail builds); </dt> <dt>Strmbasd.lib (debug builds)</dt> </dl> |



 

 



