---
-api-id: M:Windows.Globalization.Calendar.DayAsPaddedString(System.Int32)
-api-type: winrt method
---

<!-- Method syntax
public string DayAsPaddedString(System.Int32 minDigits)
-->

# Windows.Globalization.Calendar.DayAsPaddedString

## -description
Returns a string representation of the day, optionally zero-padded.

## -parameters
### -param minDigits
The minimum number of integer digits to be displayed. If the day does not have enough integer digits, it will be padded with zeros to the correct amount. For example, for the day 3, a parameter of 1 returns 3, and a parameter of 2 returns 03.

## -returns
A string representation of the day.

## -remarks

## -examples

## -see-also

[Calendar, date, and time controls](/windows/uwp/design/controls-and-patterns/date-and-time), [Calendar sample](https://github.com/Microsoft/Windows-universal-samples/tree/master/Samples/Calendar), [Date and time formatting sample](https://github.com/microsoft/Windows-universal-samples/tree/master/Samples/DateTimeFormatting)
