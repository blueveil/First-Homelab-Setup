# Compact 3-Tier Shelf Beginner Homelab 

## Overview
This project documents a **small 3-tier shelf setup** for home lab / mini PCs / networking devices.  
Goal: stable, open-airflow shelving for **2 mini PCs, switch, Raspberry Pi**, and optional **printed 10" patch panel**.  
Power management, cable routing, and device placement are included.

---
## Devices

### HP ProDesk 400 G4 DM
- **CPU:** Intel Core i5-8500T (6C/6T)
- **RAM:** 16GB (2x8GB Kingston DDR4 2666MHz)
- **SSD 1 (M.2):**  
- **SSD 2 (SATA):**  

### Dell OptiPlex 7060 Micro
- **CPU:** Intel Core i5-8500T (6C/6T)
- **RAM:** 16GB (2x8GB Samsung DDR4 2666MHz)
- **SSD 1 (M.2):**  
- **SSD 2 (SATA):**  

### Raspberry Pi 3B+  
- **OS / Image:** Raspberry Pi OS 32-bit / Pi-hole
- **MAC / Network:**  
- **Notes:**  

### Networking / Switch
- **Switch:** tp-link TL-SG108E
- **Ports used:**  
- **Notes:**  

### Power / Miscellaneous
- **Power Strip:** (e.g., TESSAN 5ft flat surge protector)  
- **Velcro / Rubber feet placement:**  
- **Patch Panel:** Printed 10” placeholder (keystones TBD)  

---

## SSDs Available
- 512GB Patriot P210 (2.5" SATA, new)  
- 500GB Samsung 870 EVO (2.5" SATA, new)   
- Planned future uture NVMe SSDs  

---

## Shelf Layout Plan

```

# ==================== Top Shelf ====================  
| |  
| Dell Mini PC (velcro/rubber feet) |  
| |

## ==================== Middle Shelf =================  
| Patch Panel (printed 10") mounted horizontally |  
| facing front, velcro or screws to shelf posts |

## | Switch + Raspberry Pi side by side |  
| velcro/rubber feet to secure |  
| Power Strip (TESSAN) behind devices, velcroed|

# ==================== Bottom Shelf =================  
| |  
| HP Mini PC (velcro/rubber feet) |  
| |

```

### Notes:
- ~1–2” gap above each device for airflow  
- Open front & back → natural convection cooling  
- Patch panel ports facing front → easy keystone access  
- Power strip behind middle shelf → flat, mountable  
- Velcro secures all devices, patch panel, and power strip  
- Cables routed along posts, tied neatly  

---

## Initial Setup & Testing

### Baseline Validation Log

| **Node**          | **MemTest86+**    | **Stress Temp (3m)** | **SSD Health** | **Status**    |
| ----------------- | ---------------- | -------------------- | -------------- | ------------- |
| **HP ProDesk**    | ✅ Pass (2 Cycles)| 74°C (Factory Paste) | 100%           | **Certified** |
| **Dell OptiPlex** | ✅ Pass (2 Cycles)| 71°C (Factory Paste) | "Good"         | **Certified** |
| **Raspberry Pi 3B+** | TBD           | TBD                  | TBD            | TBD           |
| **Switch**        | N/A              | Ambient              | N/A            | Operational   |

---
## Maintenance History

- **2026-02-01:** HP ProDesk and Dell OptiPlex RAM and CPU stress-tested successfully.
	- Updated BIOS on both machines.
- **2026-02-03:** 3D printed SSD mounting grommets for HP ProDesk.
- **TBD:** Patch panel printed, installed, keystones inserted.

---
## To-Do
- Repaste and clean both mini PCs with **PTM7950**  
- Install patch panel and mount above middle shelf  
- Velcro switch, Pi, and power strip into position  
- Route and tie cables along shelf posts  
- Test airflow and device temps under load  
- Optional: install mini fan for middle shelf  

---
## Bill of Materials (Placeholder)

| Item                      | Quantity | Notes                                |
| ------------------------- | -------- | ------------------------------------ |
| 3-Tier Shelf              | 1        | Open front/back, plastic/metal       |
| Velcro strips             | TBD      | Heavy duty for devices + patch panel |
| TESSAN 5 ft Power Strip   | 1        | Flat plug, mountable                 |
| Mini PCs                  | 2        | Dell + HP                            |
| Raspberry Pi 3B+          | 1        | MicroSD/USB power                    |
| Switch (SG108E / GS108E)  | 1        | 8 ports, managed/unmanaged           |
| Patch Panel (Printed 10”) | 1        | Mount vertically above switch/Pi     |
| SSDs                      | TBD      | see list above                       |
| Cable ties / Velcro ties  | TBD      | For neat cable routing               |

---
## Notes
- This setup avoids racks entirely — just simple shelves with vertical stacking  
- Keeps devices accessible, airflow optimized, and tidy  
