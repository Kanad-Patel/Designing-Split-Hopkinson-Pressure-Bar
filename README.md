# Mini Split Hopkinson Pressure Bar (SHPB) Project

## Overview

This repository documents the design, manufacturing, and assembly of a **Mini Split Hopkinson Pressure Bar (SHPB)**. The Mini SHPB is a critical apparatus used to characterize material properties under high strain rates, making it ideal for applications in aerospace, automotive, and defense industries.

The project includes:
- CAD designs of all components.
- Detailed manufacturing steps for each part.
- Quality control procedures and assembly instructions.
- Analysis of variations observed during manufacturing and their impacts on performance.

---

## Features
- **Compact Design**: A space-efficient Mini SHPB setup that retains high precision for material testing.
- **Material Testing Range**: Capable of testing materials at strain rates of **1000–5000 s⁻¹**.
- **Customizable Setup**: Modular design to allow modifications for different experimental needs.
- **Cost-Effective**: Manufactured using a combination of laser cutting, CNC machining, and manual processes to optimize costs.

---

## Project Structure
This repository contains the following sections:

| Folder/File           | Description                                                                                                                                       |
|-----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| `SHPB_Drawings`       | Contains all CAD drawings for individual components and the final assembly.                                                                     |                                                                                                 |
| `/SHPB_Group_Design_File`      | Comprehensive project report covering the design process, manufacturing, quality control, and testing.                                           |

---

## Design Components

Below are the main components of the Mini SHPB, along with their materials and manufacturing processes:

| **Component**         | **Material**         | **Manufacturing Process**                                                                                                           |
|-----------------------|----------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| **Base Slab**          | Mild Steel (MS)      | Cutting, CNC drilling, deburring, and anti-corrosion treatment.                                                                   |
| **Pressure Bars**      | SS304 Stainless Steel| Cutting, centerless grinding, and polishing.                                                                                      |
| **Barrel**             | SS304 Stainless Steel| Threading and cleaning.                                                                                                           |
| **Strikers**           | SS304 Stainless Steel| Cutting, centerless grinding, and polishing.                                                                                      |
| **Top Part 1**         | Mild Steel (10 mm)   | Laser cutting and deburring.                                                                                                      |
| **Support Plates**     | Mild Steel (10 mm)   | Laser cutting and deburring.                                                                                                      |
| **Bushings**           | Delrin (POM)         | Cutting, CNC turning, drilling, and deburring.                                                                                    |
| **Square Pipe Legs**   | Mild Steel           | Cutting, drilling, rotary cutting (windows), and deburring.                                                                       |
| **Support Brackets**   | Mild Steel (10 mm)   | Laser cutting, deburring, and inspection.                                                                                         |

---

## Assembly Instructions
The assembly of the Mini SHPB follows a **bottom-to-top** approach:

1. **Base Slab and Legs:**
   - Attach the square pipe legs to the slab using M5 bolts, washers, and nuts.
2. **Support Brackets:**
   - Fix support brackets to the slab using M4 bolts and washers.
3. **Pressure Bars and Bushings:**
   - Slide bushings onto the pressure bars and secure the bars on the support brackets.
4. **Barrel:**
   - Align the barrel between the pressure bars and fix it using M5 bolts.
5. **Strikers and Top Part:**
   - Insert the striker into the barrel and mount the top parts onto the structure.

Refer to the `/Assembly` folder for detailed CAD illustrations and step-by-step images.

---

## Manufacturing Variations
Despite stringent quality controls, some variations were observed during manufacturing:
1. **Holes for Square Pipe Feet:**
   - Manual center punching caused slight misalignments, which were adjusted during assembly.
2. **Window Cutting for Square Pipes:**
   - Rotary cutting introduced minor inaccuracies, affecting aesthetic uniformity.
3. **Base Width Inconsistencies:**
   - Machining variations in the base slab (width reduced to 63 mm in some areas instead of 65 mm) required smaller nut bolts during assembly.

**Mitigation Steps:**
- Improved CNC precision for hole marking and drilling.
- Standardized machining processes for critical components.

For a detailed analysis, refer to the `/Analysis` folder.

---

## Testing and Functionality
Once assembled, the Mini SHPB was tested to verify:
- Proper wave propagation along the pressure bars.
- Accurate material testing data using strain gauges and data acquisition systems.
- Stability and repeatability under high strain-rate conditions.

**Results:**
The apparatus met the expected performance criteria, with minor adjustments made during testing to align the pressure bars and supports.

---

## How to Use This Repository
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/Mini-SHPB.git
