# amperage-readings/

Operator-confirmed dashboard-amperage ground truth (2026-05-09) for the
F100F3 pack-current decode. Each filename's number is the approximate
dashboard-displayed current at the time of recording:

| Capture       | Dashboard current             |
|---------------|-------------------------------|
| `amp-1.asc`   | ~1 A (true idle, in neutral)  |
| `amp-18.asc`  | ~18 A                         |
| `amp-35.asc`  | ~35 A                         |
| `amp-42.asc`  | ~42 A                         |
| `amp-58.asc`  | ~58 A                         |

These were the captures that finally pinned down the high-byte /
low-byte rollover behavior across the 25.5 / 51.1 / 76.7 A boundaries,
and are the cleanest cross-validation set for the F100F3 decode (see
the F100F3 section in `NOTES.txt`).
