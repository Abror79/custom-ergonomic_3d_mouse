# 🖱️ Ergonomic DIY Wireless Mouse

<img width="1100" height="710" alt="image" src="https://github.com/user-attachments/assets/1b3bca48-e36a-4a9c-abd8-16e30e6d255c" />


A fully custom-engineered, 3D-printable wireless mouse designed from scratch in Onshape. This project transforms a set of raw electronics into a functional, ergonomic device featuring precise mechanical tolerances and an optimized structural layout.

## ✨ Features
* **Custom Ergonomics:** Designed for a natural hand grip and long-term comfort.
* **Precision Clickers:** Integrated 1mm tolerance gaps designed to actuate microswitches perfectly while maintaining plastic flexibility.
* **Internal Pillar Support:** A reinforced rear column prevents shell deformation, ensuring the mouse feels solid during use.
* **Modular Assembly:** Two-part design (Top Shell + Base Plate) with precise screw pockets and a fingernail notch for easy battery access.

## 🛠️ Bill of Materials (BOM)
All prices are in USD. This design is optimized for the **Mellow/Bambu Lab Wireless Mouse Kit 002**.

| Item | Purpose | Cost | Source |
| :--- | :--- | :--- | :--- |
| **Bambu Kit 002** | PCB, Sensor, Switches, Wheel | $4.97 | [AliExpress](https://aliexpress.ru/item/1005008778644042.html) |
| **Delivery Fee** | Shipping to Uzbekistan | $4.80 | AliExpress |
| **Top Shell Print** | Main Body (3D Printed) | $5.00 | [Hack Club Print Legion](https://hackclub.com/print-legion/) |
| **Base Plate Print** | Bottom Floor (3D Printed) | $2.00 | [Hack Club Print Legion](https://hackclub.com/print-legion/) |
| **AA Battery** | Power Source | ~$0.50 | Local Store |

**💰 Total Project Cost: ~$17.27**

## 📐 The Engineering Process
This project was a deep dive into parametric 3D modeling. Key technical challenges included:
* **Mechanical Actuation:** Designing the clicker legs so they are rigid enough to press the switch but flexible enough to "spring" back.
* **Assembly Tolerances:** Using boolean operations and precise sketch offsets to ensure the PCB and battery housing snap into place without rattle.
* **Shell Integration:** Solving "non-manifold" geometry errors to merge the bottom rim into the main ergonomic dome for a clean, printable STL.

[**View the Original CAD in Onshape ↗**](https://cad.onshape.com/documents/097d8a45451faf35dc6d5726/w/ee41472c9fe61edef61676b1/e/4807f90e42e73941cf48a117)

## 📁 Files
* `Top_Shell.stl`: The main ergonomic housing (Print with supports).
* `Base_Plate.stl`: The bottom mounting plate for electronics.
* `Full_Assembly.step`: Complete CAD data for modifications and remixes.

## 🚀 How to Build
1. **Print:** Use a high-quality 3D printing service or your own printer (PLA/PETG, 0.16mm layers).
2. **Install Electronics:** Screw the PCB into the Base Plate using the M2 screws provided in the kit.
3. **Connect Shell:** Snap the Top Shell over the assembly.
4. **Power Up:** Insert one AA battery through the bottom access port.

---
*Created as part of a Hack Club project.*
