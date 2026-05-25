# bms-error-codes/

Captures taken while the dashboard was cycling through specific BMS
fault codes. The matched-mode pair (`bms-124-140-142-143-144-146.asc`
vs. `idle-no-bms.asc`, both 2026-05-09) localized the fault encoding to
F108 byte 7 and is what enabled the byte-7 decode. A subsequent
full-charge capture extends F108 evidence to bytes outside byte 7.

See the F108F3 section in `NOTES.txt`. Per-capture details live in the
sidecar `.txt` files next to each `.asc`.
