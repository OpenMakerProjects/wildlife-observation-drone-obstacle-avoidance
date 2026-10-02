# Wildlife Observation Drone Obstacle Avoidance

Build a drones prototype that uses battery monitor, IMU, optical flow sensor to avoid nearby obstacles during slow flight. Include setup instructions, a circuit diagram, tested firmware, and sample output.

> Build and test at safe low voltage. Real machinery, vehicles, aircraft, pumps, and power systems require qualified engineering review and certified safeguards.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 852 |
| Category | Drones |
| Platform | ESP32 |
| Difficulty | Intermediate |
| Estimated build time | 28 hours |
| Connectivity | LoRa |
| Core components | battery monitor, IMU, optical flow sensor |
| Control mode | interactive monitor |

## Repository layout

- `firmware/wildlife-observation-drone-obstacle-avoidance/wildlife-observation-drone-obstacle-avoidance.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/wildlife-observation-drone-obstacle-avoidance/wildlife-observation-drone-obstacle-avoidance.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **ESP32**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Obstacle Avoidance demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
