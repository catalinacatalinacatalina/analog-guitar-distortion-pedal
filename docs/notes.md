# Project Notes

## Current Status

- Breadboard prototype is fully working and validated.
- PCB design is complete and fabrication files are generated.
- PCB fabrication and assembly are complete, and the finished pedal has been tested.

## Design Phase

- **Reference**: Brian Wampler - Basic Distortion Circuit Tutorial (Aug 2024)
- **Design Approach**: Breadboard first, then PCB if satisfied with tone
- **Result**: Breadboard tone validated, then moved to PCB design stage.

## Breadboard Build Checklist

### Pre-Build
- [x] All components sourced
- [x] Breadboard layout sketched
- [x] Power supply tested (should output 9V)
- [x] Multimeter available for testing

### Power Supply Stage
- [x] 9V battery or regulated supply connected
- [x] Vref (virtual ground) at approximately 4.5V
- [x] Decoupling capacitors placed
- [x] No voltage drops on ground rail

### Input Stage
- [x] Input capacitor functional
- [x] Gain potentiometer responds smoothly
- [x] Signal amplification confirmed
- [x] No oscillation

### Inverting Stage with Clipping
- [x] Diodes installed (start with LEDs)
- [x] Clipping threshold achievable
- [x] Distortion is smooth, not harsh
- [x] Low-pass filter in place

## PCB Readiness Checklist

- [x] Schematic and footprints finalized in KiCad
- [x] PCB layout completed
- [x] DRC completed with no blocking errors
- [x] Gerber and drill files generated
- [x] PCB ordered, assembled, and validated

## References

- **Main Tutorial**: https://www.wamplerpedals.com/blog/lifestyle-hobby/2024/08/how-to-design-a-basic-distortion-pedal-circuit/
- **Parts bought at**: https://www.electronicaembajadores.com/es/