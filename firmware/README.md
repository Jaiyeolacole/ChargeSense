# Firmware (nRF54LM20 DK)

Built with the nRF Connect SDK.

Planned modules:

- **BMS driver**: read pack and cell data from a smart BMS over UART
- **Session manager**: detect charge start and end of charge
- **Features**: compute features incrementally as samples arrive
- **Inference**: run the quantised model at end of charge
- **BHI and alarms**: health index and threshold-based safety alerts
- **BLE health service**: send the health packet and alerts to the mobile app; receive configuration
