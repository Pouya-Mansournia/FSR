# FSR Roadmap

This roadmap tracks repository maturity work that would make the project easier to reuse, fabricate, and maintain.

## Completed

- Altium PCB project committed.
- Schematic and PCB source documents committed.
- ATmega8 firmware source committed.
- CodeVisionAVR/Atmel Studio project metadata committed.
- Historical firmware build artifacts committed.
- Root README rewritten with architecture, setup, usage, limitations, and GitHub metadata recommendations.
- Basic issue and pull-request templates added.

## In Progress

- Repository presentation cleanup.
- Documentation of verified behavior versus planned or unvalidated behavior.

## Planned

- Add a license file.
- Add a board pinout table.
- Add a BOM or documented BOM-generation process.
- Add fabrication outputs or documented Altium output-generation steps.
- Add photos, screenshots, or rendered board previews for the README.
- Document sensor interface assumptions and calibration workflow.
- Extend firmware to read, filter, and publish FSR/ADC values.
- Add a reproducible firmware build path or AVR-GCC port.
- Decide whether generated debug artifacts and Altium history archives should stay in the main branch or move to release assets.

## Requires Validation

- Current PCB manufacturing readiness.
- Current firmware rebuild status in CodeVisionAVR.
- Relay load limits and isolation.
- ADC scaling, noise, and pressure calibration.
- Hardware behavior on a physical board.
