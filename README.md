#  Thermal Stress Analysis of Concrete and PBD (Performance Based Design) Solution for thermal Stresses| CVG 5150
### Advanced Concrete Technology | University of Ottawa | Nov – Dec 2024

---

## 📋 Project Overview

Analyzed thermal stress development and designed a performance-based construction strategy for a **20 m × 10 m × 8 m massive concrete foundation block** supporting the central pier of a cable-stayed bridge in Ottawa. The foundation is cast over the Fall season on rock (Erock = 40,000 MPa) and exposed to freeze-thaw cycles, de-icing salts, and very severe sulphate conditions.

| Parameter | Value |
|---|---|
| Foundation Dimensions | 20 m × 10 m × 8 m |
| Foundation Type | Rock (Erock = 40,000 MPa) |
| Binder Content | 405.94 kg/m³ (Cement + Fly Ash + Silica Fume) |
| 28-day Compressive Strength | 37.8 MPa |
| Aggregate Type | Limestone (Ec = 19,400 MPa per CEB-FIP) |

---

## 🔑 Key Work Completed

- Calculated placing temperature of 9.6°C using heat of hydration analysis incorporating ice and humidity corrections per ACI 207.2R-95
- Interpolated adiabatic temperature rise for 406 kg/m³ binder content over 28 days at 0.2 m intervals through the full 8 m block height
- Computed thermal restraint factors (Kr = 0.0715, Kf = 0.77, Ktotal = 0.055) accounting for rock foundation stiffness (Erock = 40,000 MPa) and plastic sheet insulation
- Demonstrated single-lift peak thermal stress of 0.82 MPa at 28 days — within safe limits due to controlled placing temperature and insulation
- Proposed a performance-based design using two 4 m lifts with a 1-day break, plastic sheet curing, and low placing temperature to eliminate thermal cracking risk
- Modelled time-dependent concrete strength development using the CEB-FIP / EN 1992-1-1 model (s = 0.38, slow-hardening cement) and verified thermal stresses remain below tensile capacity at all ages

---

## 🧮 Thermal Stress Analysis Summary

### Single Lift (8 m)
| Parameter | Value |
|---|---|
| L/H Ratio | 2.5 |
| Restraint Factor Kr | 0.0715 (with plastic sheet) |
| Foundation Stiffness Kf | 0.77 |
| Total Restraint Ktotal | 0.055 |
| Peak Thermal Stress (28 days) | **0.82 MPa** |
| Outcome | ✅ Safe — below tensile strength |

### Performance-Based Design (Two 4 m Lifts)
| Parameter | Value |
|---|---|
| L/H Ratio (each lift) | 5.0 |
| Restraint Factor Kr | 0.25 (with plastic sheet) |
| Foundation Stiffness Kf | 0.78 |
| Total Restraint Ktotal | 0.195 |
| Peak Stress – 1st Lift (28 days) | **1.807 MPa** |
| Peak Stress – 2nd Lift (28 days) | **1.837 MPa** |
| Concrete Tensile Strength (28 days) | **~3.78 MPa (ftm = fcm/10)** |
| Outcome | ✅ Safe — thermal stress below tensile capacity at all ages |

---

## 🏗️ Performance-Based Design Strategy

| Measure | Detail |
|---|---|
| Placing Temperature | 9.6°C (achieved using ice in mix water) |
| Number of Lifts | 2 lifts × 4 m each |
| Break Between Lifts | 1 day |
| Insulation | Plastic sheet (halves Kr) |
| Curing Method | Wet spray curing for 14 days |

---

## 📊 Strength Development (CEB-FIP / EN 1992-1-1)

| Age (days) | fcm (MPa) | Ec (MPa) |
|---|---|---|
| 1 | 7.40 | 17,548 |
| 7 | 25.85 | 26,625 |
| 14 | 32.30 | 28,676 |
| 28 | 37.80 | 30,220 |

> Cement classification: s = 0.38 (Class SL — slow hardening), limestone aggregate αE = 0.9

---

## ⚙️ Methods & Standards

- **Thermal Analysis:** ACI 207.2R-95 (adiabatic temperature rise interpolation)
- **Strength Development:** CEB-FIP Model Code / EN 1992-1-1
- **Restraint Factors:** ACI 207.2R (Kr, Kf methodology)
- **Stress Formula:** σ = E · α · ΔT · Kr · Kf · creep
- **Tools:** Microsoft Excel, ACI 207.2R-95 charts

---

*University of Ottawa – Faculty of Engineering, Department of Civil Engineering*
*Course Instructor: Dr. Leandro F. M. Sanchez*
