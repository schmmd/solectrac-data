# solectrac-can-data

This repository contains readings that were taken from the [CAN bus](https://en.wikipedia.org/wiki/CAN_bus) on a Solectrac electric tractor.  Readings were taken with a cheap [USB to CAN converter](https://www.amazon.com/dp/B0CRB8KXWL?ref=ppx_yo2ov_dt_b_fed_asin_title).  I updated the firmware on the device using the [canable.io updater](https://canable.io/updater/) and selecting `slcan 9fddea4`.  I bought a [cheap cable](https://www.amazon.com/dp/B07F16GPMB?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1) so I could plug the CAN reader into the ODB-2 port under the hood of the tractor.

The Solectrac CAN bus runs at a baud rate of 250,000.  I was able to record CAN data using a variety of tools (SavvyCan, canviz, python-can) on my M4 Macbook Pro.
