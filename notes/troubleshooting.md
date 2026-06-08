\# Troubleshooting Notes



\## FC Not Detected



\### Symptoms



\* No connection in Mission Planner

\* No COM port appears



\### Checks



1\. Verify USB cable supports data.

2\. Verify drivers installed.

3\. Verify FC powered.

4\. Check Device Manager.



\---



\## FC Appears as DFU Device



\### Symptoms



STM32 DFU mode detected.



\### Resolution



Use:



\* STM32CubeProgrammer

\* Correct bootloader firmware



Flash bootloader if required.



\---



\## ELRS Receiver Not Working



\### Checks



\* Verify UART assignment

\* Verify CRSF protocol

\* Verify receiver binding

\* Verify TX/RX orientation



\---



\## PreArm: Compass Not Healthy



\### Checks



\* Verify compass enabled

\* Verify GPS/compass wiring

\* Perform calibration



\---



\## PreArm: Battery Failsafe



\### Checks



\* Battery monitor settings

\* Voltage scaling

\* Wiring to BAT input



\---



\## Motors Spin Incorrectly



\### Checks



\* Verify motor order

\* Verify ESC signal wiring

\* Verify motor direction



Use Mission Planner Motor Test before flight.



\---



\## General Rule



Do not change multiple settings simultaneously.



Change one variable at a time and document the result.



