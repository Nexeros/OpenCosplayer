# Project: Mechanical Exo-Tail

This folder contains all necessary files (3D models, etc.) to build a mechanical, segmented tail. The project was designed with modularity in mind and is available in two main versions.

<img width="955" height="774" alt="obraz" src="https://github.com/user-attachments/assets/9ea27135-10e0-42fb-9533-77b2b6252d73" />




---

## Project Versions

1.  **Inertial Version (Passive):** Simpler to build, requires no electronics. The tail moves naturally based on the wearer's body movement and inertia. Bearings ensure a smooth motion. This is a great starting point.
2.  **Motorized Version (Active):** A more advanced version where each segment (or selected segments) is controlled by servo motors. This allows for programmed movement sequences and remote control.

---

## Bill of Materials (BOM)

This list covers parts common to both versions. Additional components for the motorized version will be listed separately.

#### Non-Printed Parts (per segment):
*   **Self-Tapping Screw:** `2x` M3 (length 8-12 mm, **Important:** head diameter must be 6mm or less)
*   **Steel Rope:** `3x` 1,5mm (length 10cm times number of modules. **Not necessary for Inertial version, but can help to align tail**)
*   **PTFE tube:** `3x` 4mm (length 42mm times number of modules + 28mm for base module + 67mm for end module)
*   **Springs:** `4x` 15mm (recommended, max 30, min 10mm as you want to stiffen your tail)

#### 3D Printed Parts (per segment):
*   `1x` spine_module.3mf
*   `4x` distancer.3mf
*   `1x` rubber_bushing.3mf

---

## Assembly Instructions (Inertial Version)

**Step 1: Prepare the Prints**
*   Ensure all parts are printed correctly. Remove all support material and clean up any holes, especially for the screws.

**Step 2: Connect the Segments**
*   Align `spine_module` over next `spine_module` at 90 degrees and slide in bearing hole, then align them so that the holes in both parts and the bearing line up perfectly.
*   Slide the `distancer`.

**Step 3: Secure the Connection**
*   Drive the `M3` self-tapping screws into the holes on the `distancer`. This will secure the entire joint by locking the pin in place. Do not overtighten, as this can damage the plastic.

**Step 4: Repeat the Process**
*   Repeat steps 2-4 for each subsequent segment until you achieve your desired tail length. Use a special `end_module.3mf` for the final segment.

**Step 7: Mount the Base**
*   Attach the first segment to the `base_module.3mf` with mounted `*_mount.3mf` (based on version), which is used to fasten the tail to a belt or harness.

**Step 8: Install ropes (not necessary for Inertial version)** 
*   Cut 4mm (1.7mm inner) PTFE tube and slide it into the holes in the segments.
*   Drag steel rope through segments, including `end_module.3mf` and `base_module.3mf`.
*   Lock with srews at ends and in segments you want.

**Step 9: Install springs**
*   Tension the springs and attach them to the mounting holes in the segments.
---

## Recommendations and Tips

#### 3D Printing Tips
*   **Material:** **PETG** or **ABS/ASA** are recommended over PLA for their superior strength and durability.
*   **Infill:** A minimum of **25-30%** is suggested to ensure adequate rigidity. For critical parts like the pins, consider increasing this to 50% or more.
*   **Layer Height:** 0.2 mm is a good balance between quality and print time.
*   **Supports:** Supports may be necessary depending on the model's orientation. Use tree supports if possible for easier removal.

#### Assembly Tips
*   **Test Fit:** Before final assembly, check that all parts fit together smoothly. Some light sanding may be required.
*   **Lubrication:** For even smoother movement, apply a small amount of silicone-based grease to the bearings and pins.
*   **Do Not Overtighten:** Self-tapping screws can easily strip the plastic. Tighten them gently until you feel resistance, and then stop.

---

*This project is a work in progress. Suggestions and improvements are welcome!*
