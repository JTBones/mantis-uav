\# ArduPilot Setup Notes



\## Firmware



\* ArduPilot Copter 4.6.3

\* Installed through Mission Planner



\## Initial Configuration



\### Accelerometer Calibration



Completed successfully.



\### Radio Calibration



Completed using RadioMaster Pocket ELRS transmitter.



\### Flight Modes



Channel 5 (SA Switch)



Planned Modes:



\* Stabilize

\* Alt Hold

\* Loiter



\### Arming



Channel 6 (SB Switch)



Arming position:



\* SB fully away from operator



\## Receiver Protocol



CRSF



Receiver:



\* ELRS 2.4GHz Nano



\## Motor Testing



Completed through Mission Planner.



Verified:



\* Motor order

\* Motor direction

\* Throttle response



\## Issues Encountered



\### PreArm Errors



Observed:



\* Compass not healthy

\* Battery failsafe

\* Logging failed



Resolved through parameter review and hardware verification.



\### Smoke Stopper Issue



Motor test initially stopped at approximately 10% throttle.



Root cause:



\* Voltage drop through smoke stopper.



Resolved by direct battery connection.



\## Future Configuration



\* GPS integration

\* Compass calibration

\* Battery monitoring

\* RTL testing

\* Loiter testing

\* Telemetry integration



