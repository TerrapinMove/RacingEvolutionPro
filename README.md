# RacingEvolution Pro — Tuning & Track Guide

![Cover](assets/cover.png)

## Overview

Master RacingEvolution Pro with this complete tuning guide, track walkthroughs, and performance optimization reference. Covers all vehicle classes from street to hypercar.

## Vehicle Tuning Database

### Class A — Hypercar Tuning Template
```
Engine:
  Turbo: Stage 3+
  Intake: Carbon fiber
  Exhaust: Titanium racing system
  ECU: Sport mapping (+45hp, +60nm)

Suspension:
  Ride Height: 35mm front / 40mm rear
  Springs: 18kg/mm front / 22kg/mm rear
  Dampers: 2-way adjustable
  Camber: -2.0 front / -1.5 rear
  Toe: 0.0 front / -0.3 rear

Aerodynamics:
  Front Splitter: Race (+80kg downforce)
  Rear Wing: Race (+120kg downforce)
  Diffuser: Aggressive
```

### Tire Strategy by Track Type

| Track Type | Compound | Pressure F/R | Camber |
|------------|----------|-------------|--------|
| Street | Sport | 32/30 psi | -2.0/-1.5 |
| Mountain | Semi-Slick | 30/28 psi | -2.5/-2.0 |
| Circuit | Slick | 28/26 psi | -3.0/-2.5 |
| Drag | Drag radial | 35/50 psi | 0.0/0.0 |

## Track Guides

### Silverstone Circuit — Full Walkthrough
**Best Lap Time**: 1:44.213
**Difficulty**: Medium

Key Sections:
1. **Abbey** — Trail brake into T1, apex at 50m marker
2. **The Loop** — Flat on throttle, minimal steering
3. **Club** — Lift and rotate, exit at full throttle
4. **Maggotts/Becketts** — S-series, maintain momentum
5. **Stowe** — Late apex, 5th gear sweep

### Nurburgring Nordschleife
**Best Lap Time**: 7:32.450
**Difficulty**: Extreme

Critical Sections:
- Fuchsröhre: Stay left, car controlled slide
- Karussel: Trust the banking, no brakes
- Döttinger Höhe: Top speed run, 310+ km/h

## Performance Calculator

Use `tools/perf_calc.py` to estimate lap times based on your vehicle spec.

## License

MIT License
