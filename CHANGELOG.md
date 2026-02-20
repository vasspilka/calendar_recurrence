# CHANGELOG

## Unreleased

- [CalendarRecurrence.RRULE](https://hexdocs.pm/calendar_recurrence/CalendarRecurrence.RRULE.html) add monthly `BYDAY` support with optional ordinal prefixes (#13). Enables rules like `FREQ=MONTHLY;BYDAY=1MO` (first Monday of every month) and `FREQ=MONTHLY;BYDAY=-1FR` (last Friday of every month). Plain `BYDAY` in monthly context (e.g., `BYDAY=MO` — every Monday of every month) is also supported (#19).

## v0.2.0 (2025-11-12)

- [CalendarRecurrence.RRULE](https://hexdocs.pm/calendar_recurrence/CalendarRecurrence.RRULE.html) add `String.Chars` protocol (#16)
- [CalendarRecurrence.RRULE](https://hexdocs.pm/calendar_recurrence/CalendarRecurrence.RRULE.html) allow optional UTC suffix in UNTIL rule (#8)

This is potentially a **breaking change** as before we would coerce the UNTIL rule to a UTC DateTime

## v0.1.0 (2025-05-12)

- Initial release
