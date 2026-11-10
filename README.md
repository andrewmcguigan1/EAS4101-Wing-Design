# Wing Design Project — EAS 4101

Andrew McGuigan and Jovan Rojas | University of Florida | April 2026

Preliminary design of a tapered wing for a 10,231.8 N aircraft, for EAS 4101 (Dr. Bruce Carroll). The wing had to give a high lift-to-drag ratio, keep the root bending moment under 11,000 N·m, and have zero sweep at the quarter chord.

- [Project report](Wing_Design_Project.pdf): design discussion, final wing parameters, operating conditions, and wing polars.

## Design process

1. **Airfoils:** NACA 4412 at the root and NACA 2412 at the tip. The tip's lower camber reduces tip drag and bending moment.
2. **Planform area:** sized from level flight (L = W) at the minimum speed with a maximum lift coefficient of 1.4, giving S ≈ 8 m².
3. **Taper:** a taper ratio of 0.4 gives a near-elliptic lift distribution.
4. **Bending moment check:** an 11 m span exceeded the root bending moment limit at this taper ratio, so the span was cut to 9 m. That left margin under the 11,000 N·m limit.
5. **Sweep and twist:** the tip was offset spanwise to keep the quarter chord unswept. A −2° twist (washout) keeps the tips, and the control surfaces on them, effective at higher angles of attack.

## Final wing

| Span | Root chord | Tip chord | Area | Aspect ratio | Dihedral | Quarter-chord sweep | Twist |
| ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| 9.00 m | 1.270 m | 0.508 m | 8.00 m² | 10.12 | 1.72° | 0.0° | −2.00° |

## Results at the three design speeds

| Condition | Airspeed | Angle of attack | Root Re | CL | L/D | Root bending moment |
| --- | ---: | ---: | ---: | ---: | ---: | ---: |
| Max speed | 72 m/s | 2.62° | 6.10 × 10⁶ | 0.400 | 38.0 | 8,723 N·m |
| Cruise | 56 m/s | 5.65° | 4.74 × 10⁶ | 0.666 | 34.1 | 8,778 N·m |
| Min speed | 39 m/s | 13.96° | 3.30 × 10⁶ | 1.373 | 19.2 | 8,646 N·m |

The lift curve slope is 4.926 per radian. The root bending moment stays below the 11,000 N·m limit at all three speeds.
