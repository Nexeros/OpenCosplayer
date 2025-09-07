# Project: Mechanical Exo-Tail

This folder contains all necessary files (3D models, etc.) to build a mechanical, segmented tail. The project was designed with modularity in mind and is available in two main versions.

![image_placeholder](https://via.placeholder.com/600x300.png?text=Insert+a+picture+of+your+project+here!)

---

## Project Versions

1.  **Inertial Version (Passive):** Simpler to build, requires no electronics. The tail moves naturally based on the wearer's body movement and inertia. Bearings ensure a smooth motion. This is a great starting point.
2.  **Motorized Version (Active):** A more advanced version where each segment (or selected segments) is controlled by servo motors. This allows for programmed movement sequences and remote control.

---

## Bill of Materials (BOM)

This list covers parts common to both versions. Additional components for the motorized version will be listed separately.

#### Non-Printed Parts (per segment):
*   **Self-Tapping Screw:** `2x` M3 (length 8-12 mm, **Important:** head diameter must be 6mm or less)

#### 3D Printed Parts (per segment):
*   `1x` Segment_A.stl
*   `1x` Segment_B.stl
*   `1x` Joint_Pin.stl

---

## Assembly Instructions (Inertial Version)

**Step 1: Prepare the Prints**
*   Ensure all parts are printed correctly. Remove all support material and clean up any holes, especially for the screws.

**Step 2: Connect the Segments**
*   Align `Segment_B` over `Segment_A` so that the holes in both parts and the bearing line up perfectly.
*   Slide the `Joint_Pin` through the holes of both segments and through the inner race of the bearing.

**Step 3: Secure the Connection**
*   Drive the `M3` self-tapping screws into the holes on the `Joint_Pin`. This will lock the pin in place and secure the entire joint. Do not overtighten, as this can damage the plastic.

**Step 4: Repeat the Process**
*   Repeat steps 2-4 for each subsequent segment until you achieve your desired tail length. Use a special `End_Cap.stl` for the final segment.

**Step 7: Mount the Base**
*   Attach the first segment to the `Mounting_Base.stl`, which is used to fasten the tail to a belt or harness.

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
