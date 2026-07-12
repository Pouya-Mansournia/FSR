# Contributing to FSR

Thank you for taking the time to improve this project. FSR combines hardware design files and embedded firmware, so contributions should be careful, reproducible, and explicit about validation status.

## Before You Start

- Check the repository license status. No license file is currently present, so reuse and redistribution terms should be clarified before large contributions.
- Open an issue for substantial hardware, firmware, or documentation changes.
- Keep generated artifacts separate from source changes unless the generated output is the actual deliverable.

## Development Setup

The project currently uses proprietary design and firmware tools:

- Altium Designer for `FSR_Project/FSR_Project.PrjPcb`
- CodeVisionAVR/Atmel Studio project metadata for `FSR Board/FSRV1.cproj`

There is no scripted cross-platform build yet.

## Contribution Guidelines

- Keep schematic, PCB, firmware, and generated output changes in clearly separated commits when practical.
- Document the tool version used for hardware or firmware regeneration.
- Include bench-test notes for hardware-facing changes.
- Do not commit private manufacturing quotes, supplier credentials, or local machine paths unless they are already part of historical tool output and necessary for context.
- Avoid claiming hardware validation, calibration, or safety behavior unless you can provide evidence.

## Pull Request Checklist

- The README remains accurate after the change.
- Referenced file paths exist.
- Hardware outputs were regenerated from the current design files, when applicable.
- Firmware changes were rebuilt or clearly marked as not yet validated.
- Safety-sensitive behavior is documented, especially relay loads and sensor assumptions.
- Generated files are intentional and explained.

