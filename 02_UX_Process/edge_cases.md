# Edge Cases Considered

Several real-world booking conflicts were considered during the UX process.

## Case 1 — Preferred Barber Unavailable

If a selected barber is unavailable at the chosen time:

The system recommends:

- Alternative available time slots
OR
- Another barber available for the same service

This prevents booking failure.

## Case 2 — Simultaneous Booking Conflict

If two users attempt to book the same barber and time slot simultaneously:

The system prioritizes the first successful booking and immediately recommends:

- Nearby available time slots
OR
- Alternative available barber

This reduces customer frustration.

## Case 3 — First-Time Users

If a customer does not know any barber:

The app recommends the best available barber based on:

- Selected service
- Availability
- Expertise
