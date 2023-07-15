# Data

## Visits table (server logs with data on website visits):
- *Uid* — user's unique identifier.
- *Device* — user's device.
- *Start Ts* — session start date and time.
- *End Ts* — session end date and time.
- *Source Id* — identifier of the ad source the user came from.

## Orders table (data on orders):
- *Uid* — unique identifier of the user making an order.
- *Buy Ts* — order date and time.
- *Revenue* — Company's revenue from the order.

## Costs table (data on marketing expenses):
- *source_id* — ad source identifier.
- *dt* — date.
- *costs* — expenses on this ad source on this day.
