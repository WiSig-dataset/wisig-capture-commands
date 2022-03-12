## Overview

These commands were used to capture the [WiSig dataset](https://cores.ee.ucla.edu/downloads/datasets/wisig).

## Citation
If you use this code in your research please cite
> S. Hanna, S. Karunaratne and D. Cabric, "WiSig: A Large-Scale WiFi Signal Dataset for Receiver and Channel Agnostic RF Fingerprinting," in IEEE Access, vol. 10, pp. 22808-22818, 2022, doi: 10.1109/ACCESS.2022.3154790.

## Steps

You need to configure the WiFi Tx, Rx, and AP.

After configuration:
Run the WiFi AP command (enable the udp server)
Run the WiFi Tx command (Connect to the WiFi AP and send random data to the udp server)

Run the USRP Rx command (capture the signals)

Close everything.


