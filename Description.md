# RLC Circuits Lab

An interactive **series RLC circuit calculator** that works out reactance, impedance, current, voltage drops, power and resonance, and shows every step of the working.

**Live site:** https://kandraeswithchowdary-cpu.github.io/RLC-Circuits-Lab/

**Created by:** K. Eswith Chowdary · CSE-D Section

---

## Pages

| Page | What it has |
| --- | --- |
| **Home** | Project overview, a basic series RLC circuit diagram and definitions of every term |
| **Calculator** | Inputs for V, f, R, L and C, result cards, step-by-step working for each variable, an animated circuit, live waveforms and a phasor diagram |
| **Explanation** | The theory behind reactance, impedance, phase, power and resonance, with all formulas and a symbols and units table |

## What it calculates

- Inductive reactance (X<sub>L</sub>), capacitive reactance (X<sub>C</sub>) and net reactance (X)
- Impedance (Z) and phase angle (φ)
- Current (I)
- Voltage across each part (V<sub>R</sub>, V<sub>L</sub>, V<sub>C</sub>)
- Active power (P), reactive power (Q), apparent power (S) and power factor
- Form factor
- Resonant frequency (f₀) and quality factor (Q)

## Formulas used

```
XL = 2πfL
XC = 1 / (2πfC)
X  = XL − XC
Z  = √(R² + X²)
φ  = tan⁻¹(X / R)
I  = V / Z
VR = I·R     VL = I·XL     VC = I·XC
P  = I²R     Q = I²X       S = V·I
PF = R / Z = cos φ
f₀ = 1 / (2π√(LC))
Q  = (1/R) · √(L/C)
```

## Features

- Results update live as you type
- Unit selectors for each input (for example mH, µF, kHz)
- "Set to resonance" button that jumps to f₀
- Expandable step-by-step working: formula, substitution, calculation and result
- Animated circuit, waveforms with toggleable traces, and a phasor diagram
- Works on phones, tablets and desktops

## Run it locally

No installation is needed. Download `index.html` and open it in any modern browser.

## Built with

HTML, CSS and JavaScript in a single file, with no libraries or frameworks.

## Author

**K. Eswith Chowdary**, CSE-D Section
