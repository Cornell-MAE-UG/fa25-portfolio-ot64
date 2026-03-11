---
layout: project
title: Thermal Bearing Coating (TBC) Performance Analysis
description: Modeling turbine blade heat protection systems
technologies: []
image: /assets/images/echo-dot-speaker.jpg
---

### **Selected Problem: Thermal Barrier Coatings (TBC) on Turbine Blades**
In this problem, we analyzed a **superalloy turbine blade** (k_b=25 **W/(mK)**) exposed to hot gases at **1616 K**. We first calculated the surface temperature of the blade without any protection and found it reached **1236 K**, which exceeded the maximum allowable limit (**T_max**) of **1200 K**. We then re-evaluated the system after adding a thin **0.5 mm Thermal Barrier Coating** (**k_TBC = 1 W/(mK)**) and accounting for an interfacial thermal resistance of **10⁻⁴ m² K/W**.

### **Reflection**
This problem was the most educational for me because it demonstrated the practical power of the **Thermal Resistance Network**. Before this, "thermal resistence" felt like an abstract mathematical convenience, but seeing how a **0.5 mm** coating could drop the blade's temperature by **132 K**, bringing it from a point of structural failure (**1236**) to a safe operating temperature of **1104 K**, was eye-opening. 

It taught me that in engineering, the **"weakest link"** in a heat flow path (the highest resistance) is often the most critical tool for design. By adding a material with very low thermal conductivity, we fundamentally **throttled the heat flux (q")** from **380,000 W/m²** to **320,000 W/m²**, which made all the difference.