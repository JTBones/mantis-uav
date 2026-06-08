\# Wiring Diagram \& Connections



\## Flight Controller



\* FC: TAKER H743 BT

\* Firmware: ArduPilot Copter 4.6.3



\## Power Distribution



\### Battery



\* 3S LiPo Battery

\* XT60 Connector



\### Power Path



Battery → Matek PDB-XT60 → ESCs + Flight Controller



\### Flight Controller Power



\* 5V from PDB connected to FC 5V input

\* Ground from PDB connected to FC Ground

\* Battery voltage monitoring connected to BAT pad



\## ESC Connections



| Motor       | FC Output |

| ----------- | --------- |

| Front Right | M1        |

| Rear Right  | M2        |

| Rear Left   | M3        |

| Front Left  | M4        |



\### ESC Wiring



\* Signal wire → Motor output pad

\* Ground wire → FC Ground

\* Red 5V wire not used



\## Receiver



\### ELRS Nano Receiver



UART2



| Receiver | Flight Controller |

| -------- | ----------------- |

| TX       | RX2               |

| RX       | TX2               |

| 5V       | 5V                |

| GND      | GND               |



Protocol: CRSF



\## GPS



\### HGLRC M100-5883



UART configuration pending.



Expected connections:



| GPS | FC  |

| --- | --- |

| TX  | RX  |

| RX  | TX  |

| 5V  | 5V  |

| GND | GND |



\## VTX



JHEMCU Crossover 5.8GHz



Connections pending.



\## Notes



Always verify polarity before applying power.



Use a smoke stopper during first power-on after any major wiring changes.



