---
layout: page
title: Research
permalink: /research/
---

## Visuo–Tactile Sensing for Robust Contact Perception  <span class="badge">CMU · Safe AI Lab</span>
- Designed a **new** vision–tactile sensor that renders frames **completely black before touch**, making perception robust to ambient lighting.
- On contact, captures **tactile deformation** *and* overlaid **color/text** cues, providing richer information than prior baselines.
- Demonstrated robust contact detection/feature extraction on **very soft materials** (water droplets, facial cream, thin plastic film).
- Integrated with a VLM to **sort resistors by color codes**, achieving **82%** end-to-end accuracy.

---

## [LocoTouch: Learning Dynamic Quadrupedal Transport with Tactile Sensing](https://linchangyi1.github.io/LocoTouch/)  <span class="badge">CMU · Safe AI Lab · CoRL ’25</span>
- Designed and fabricated a **221-taxel** piezoresistive back pad; now improving **manufacturing repeatability/yield** and updating the **low-noise PCB** for faster assembly.
- Developed a tactile-aware transport policy with a **teacher–student** pipeline (**PPO → DAgger**) and reliable **PD** tracking.
- Demonstrated **zero-shot** sim-to-real transport of unsecured objects over long distances and varied terrain.
- Contributions: sensor design & calibration, sensing bring-up, policy evaluation/ablations, and real-world trials.

---

## Vine-Robot Anchors for Mars Rover Locks & Drilling  <span class="badge">UCSB · Hawkes Lab</span>
- Designed compliant **vine-robot “locks”** to secure and stabilize tooling on sand–pebble–dust (Mars-regolith analog) surfaces.
- Built a **3 × 3 × 2 m** granular-media testbed with regolith analogs; Raspberry-Pi sensing/control and CV evaluation.
- Control: **LQI** pose regulation (integrators on x–y–yaw) with **MRAC** adaptation for gusts and soil/contact changes; validated under friction/lateral-load variations.
