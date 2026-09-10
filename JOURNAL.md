| title       | Alper                            |
| ----------- | -------------------------------- |
| author      | Alpha_Dac                        |
| description | A DIY project for a first Drone. |
| created_at  | 2026-09-10                       |

# Day 1: Define the objective and research

Design and build from scratch a 3D‑printed electric pusher motorglider inspired by modern military surveillance UAVs, at reduced scale (around 1.80 m wingspan). This is not a kit: the airframe, aerodynamics and electronics are all being developed personally, with most structural parts produced by FDM 3D printing (optimized for low weight using LW‑PLA, PETG). The goal is a stable, lightweight, repairable aircraft with a clean nose for future payloads such as gimball cameras or sensors.

Research summary – 3D‑printed electric pusher UAV (≈1.80 m wingspan)

Objectives and flight envelope

Electric pusher motorglider with a clean nose for future sensors/camera.

Wingspan: ~1 800 mm.

Target mass: 1.8–2.2 kg (ideally under 2 kg).

Wing loading: 45–60 g/dm².

Speed: 8–18 m/s, stable and gentle flight, line‑of‑sight over a large open field.

Wing and aerodynamics

Mean chord: 200–220 mm (220–230 mm in a heavily 3D‑printed version).

Aspect ratio: ~8–9; wing area: 36–41 dm².

Airfoil: NACA 4412 or Clark Y (good lift, gentle stall, easy to build).

Dihedral: 3–5°; wing incidence: +1 to +2°.

CG: 25–30% of mean chord, first flights targeted at 28%.

Configuration and layout

Slender fuselage, pointed nose, “surveillance UAV” look (not an exact replica).

High or mid‑high wing; pusher propulsion at the rear.

Tail: conventional on the first prototype (simpler), V‑tail possible later.

Key stations from the nose:

Battery bay start: 120–150 mm.

Wing leading edge: 400 mm.

Target CG: 455–460 mm.

Wing trailing edge: 610 mm.

Empennage: 1 050–1 180 mm.

End of fuselage: ~1 250 mm.

Battery on an adjustable rail (130–330 mm) to fine‑tune the CG.

Materials and structure

Wings: XPS/EPP/Depron foam or 3D‑printed skins over internal ribs.

Spars: carbon tubes Ø10–12 mm (main) and Ø4–6 mm (anti‑torsion).

Fuselage: 3D‑printed PLA/PETG segments, demountable, with battery hatch.

Motor and battery mounts: PETG/ABS (heat + vibration resistance).

Modular and repairable structure (two‑piece wings, carbon pins).

3D printing strategy

Large skins: 1 perimeter, 0% infill, internal ribs every 35–50 mm.

Mechanical parts: 3–4 perimeters, 25–40% infill, inserts/epoxy for screws.

Filaments: LW‑PLA (wings/rear), PLA (nose/fairings), PETG (motor/loads), TPU (vibration isolation).

Half‑wings split into 4–5 segments assembled over continuous carbon spars.

Pre‑test: 200 mm wing segment to validate weight and settings before printing the full aircraft.

Mass and propulsion

Optimized target: 1.8–2.4 kg → motor 3542/4250, 700–900 KV, 4S, prop 11×6–12×6, ESC 40–60 A, battery 4S 3 000–5 000 mAh.

If > 2.5 kg: larger motor (4250/5055), ESC 60–80 A, battery 4S 4 000–6 000 mAh or 6S, prop 12×6–14×7.

Target static thrust: ≥ 0.5× weight (ideally 0.7×).

Estimated endurance: 10–20 min.

Avionics (phased approach)

Phase 1: 2.4 GHz receiver, 4–6 servos, ESC with BEC, battery alarm.

Phase 2 (after successful flights): GPS + flight controller (position/RTL), full battery telemetry, FPV camera, and optionally an ESP32‑type board for additional sensors.

Build phases

Concept and sizing. 2) CAD (segmented fuselage, wing jigs). 3) Half‑wing prototype. 4) Fuselage printing. 5) Dry assembly and CG check. 6) Ground tests. 7) First flights. 8) Add GPS/camera/sensors.

Regulatory context (France/EU, 2026)

~2 kg UAV → mandatory operator registration (AlphaTango portal), operator number marked on the aircraft.

Online A1/A3 training/exam required for any aircraft over 250 g.

Over 800 g → Remote ID (electronic identification) required.

Operations in Open category, subcategory A3: away from people and urban areas.

Max altitude 120 m, visual line‑of‑sight only, no flights over crowds.

Check no‑fly zones/aerodromes before each flight; RC liability insurance recommended.

I already hold an AlphaTango operator licence, so the registration and regulatory side is prepared.

Note: Nothing here is final. All values and choices may change at any time as further research is carried out and as the 3D design and prototyping progress.
first prototype is a piece of shit
![Image 1](images/img_1.png)
**Time Spent: 1.5 Hours**
