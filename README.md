# Team Mott's RC Rover

A custom-designed remote-controlled rover built for **ENGR 7A: Introduction to Engineering** at the **University of California, Irvine (Fall 2023)**[cite: 2].

## System Overview

The Team Mott's Rover is an engineering prototype designed to traverse obstacles, navigate speed courses, and scale steep ramps[cite: 2]. The design features a custom Ackerman steering mechanism, high-torque gearing, custom wood chassis fabrication, and integrated safety covers[cite: 2].

## Key Specifications

| Specification | Value | Target Constraint |
| :--- | :--- | :--- |
| **Dimensions** | 13.94" L x 9.43" W[cite: 2] | < 16.0" L x 10.0" W[cite: 2] |
| **Vehicle Weight** | 1.20 kg[cite: 2] | Predicted: 1.39 kg[cite: 2] |
| **Total Build Cost** | $253.13 (incl. tax)[cite: 2] | < $275.00 limit[cite: 2] |
| **Power Source** | 7.2V 3600 mAh NiMH Battery[cite: 2] | ≥ 10 min operation[cite: 2] |
| **Drive Gear Ratio** | 4:1 (64T Spur / 16T Pinion)[cite: 2] | High-torque selection[cite: 2] |

---

## Subsystem Architecture

### Mechanical & Structural
* **Chassis:** Laser-cut 1/4" Baltic birch plywood featuring custom cutouts for central battery positioning and gear clearance[cite: 2].
* **Ackerman Steering:** Driven by a servo motor attached to a custom 3D-printed adapter horn that connects via rotating linkages to 2-inch D-shaft wheel pivots[cite: 2].
* **Drivetrain:** Features a 12V 4.4:1 metal gearmotor connected via a 64T spur gear to an 8-inch stainless steel rear D-shaft axle[cite: 2].
* **Wheels:** 85 mm rubber tires to maximize ground clearance over course obstacles[cite: 2].
* **Safety Integration:** Includes a transparent 3D-printed red gear guard covering moving drive teeth[cite: 2].

### Electrical & Controls
* **Power Distribution:** 7.2V 3600 mAh NiMH battery feeds directly to the Electronic Speed Controller (ESC) and Buck Converter[cite: 2].
* **Voltage Regulator:** 5A DC-DC Buck Converter steps down 7.2V input to a constant 5V output for the steering servo motor[cite: 2].
* **Radio Control:** 6-channel digital radio transmitter paired with a chassis-mounted receiver[cite: 2].

---

## Competition Performance

* **Preliminary Round:** Completed course in 26.75 seconds, ranking **8th out of 56 teams**[cite: 2].
* **Final Competition (Top 10):** Recorded a 36.00-second course run (+10s penalty for cone contact), securing **6th place overall**[cite: 2].

---

## Future Design Improvements

* **Steering Stabilization:** Replace glued joints with threaded M3 screw connections and shorten sleeve bearing hole depths to eliminate wheel wobble[cite: 2].
* **Friction Reduction:** Convert internal PLA-on-PLA linkage joints to M3 screw pivots[cite: 2].
* **Chassis Clearance:** Shorten overall chassis length or lower axle mount positions to clear ramp peaks without touching[cite: 2].

---

## Team Members

* **Alex M.** — Team Captain[cite: 2]
* **Brady C.** — Electronics Lead[cite: 2]
* **Bryant N.** — CAD Design Lead[cite: 2]
* **Christine R.** — Fabrication Lead[cite: 2]
* **Christine Y.** — Fabrication Lead[cite: 2]
* **Darcy M.** — Research Lead[cite: 2]
* **Emely B.** — Research Lead[cite: 2]
