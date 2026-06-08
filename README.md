# MANTIS UAV

A modular quadcopter project focused on learning UAV systems, ArduPilot, GPS navigation, tactical mapping integration, and eventually onboard autonomy.

## Project Goals

- Build and document a functional quadcopter platform
- Configure ArduPilot using Mission Planner
- Integrate GPS and telemetry
- Add camera/video capability
- Explore TAK/BFT integration
- Eventually add companion-computer autonomy

## Current Hardware

- Flight Controller: TAKER H743 BT
- Firmware: ArduPilot Copter 4.6.3
- Receiver: ELRS 2.4GHz Nano
- Transmitter: RadioMaster Pocket ELRS
- Battery: 3S 11.1V 5000mAh LiPo
- GPS: HGLRC M100-5883
- VTX: JHEMCU Crossover 5.8GHz
- Props: 8 inch
- Frame: Custom quad frame

## Current Status

- Flight controller flashed
- Receiver bound
- Motors tested
- Arming configured
- Basic hover testing in progress
- GPS, VTX, and camera integration pending

## Planned Features
- GPS-assisted flight modes
- Battery voltage/current monitoring
- Telemetry logging
- Video downlink
- TAK/WinTAK integration
- Click-to-mark GPS workflow
- Companion computer experimentation

## Disclaimer

This is an experimental educational UAV project. All testing should be conducted safely, legally, and away from people, aircraft, property, and restricted airspace.

## Repo Structure

```text
mantis-uav/
├── README.md
├── docs/
│   ├── build-log.md
│   ├── wiring.md
│   ├── ardupilot-setup.md
│   ├── flight-test-log.md
│   └── future-features.md
├── images/
├── parameters/
│   └── ardupilot-params.param
├── notes/
│   └── troubleshooting.md
└── scripts/

