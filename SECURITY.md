# Security and Safety Policy

FSR is an embedded hardware and firmware repository. It does not expose a network service, authentication layer, or hosted application, but hardware projects can still create safety risks when connected to power, relays, sensors, or robotic actuators.

## Reporting Issues

Please report security or safety concerns through GitHub Issues unless a private reporting channel is added later.

Examples of useful reports:

- Unsafe relay behavior or unclear load limits.
- Power, grounding, or isolation concerns.
- Firmware behavior that could unexpectedly energize outputs.
- Documentation that may cause unsafe hardware use.
- Build artifacts that expose sensitive local information.

## Current Boundaries

- No formal vulnerability disclosure process is currently configured.
- No safety certification is claimed.
- No production readiness, compliance, or isolation guarantee is claimed.
- No secrets or environment variables are required by the repository.

## Hardware Safety Notes

- Validate the board with a current-limited bench supply before connecting external loads.
- Confirm relay ratings and isolation before switching motors, solenoids, or higher-power devices.
- Confirm ATmega8 clock and fuse settings before flashing firmware.
- Test pressure-sensing behavior on the bench before connecting to robotic motion.
- Treat the current firmware as a reference baseline, not safety-rated control software.

