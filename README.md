# Leaf-spring-suspension-system
A repository exploring the design, analysis, and modeling of leaf spring suspension systems for trucks.


This project focuses on the **design, modeling, and optimization** of a leaf spring suspension system.  
The workflow includes:
- Mathematical calculation of key parameters  
- 3D modeling using **SolidWorks**  
- Simulation and validation of the chosen design  
- Optimization through the integration of **composite materials**

---

## 🎯 Objectives
- Dimension the suspension using mathematical formulas and select an appropriate design solution.  
- Create a complete 3D model of the suspension using CAD software.  
- Validate engineering decisions through numerical simulations.  
- Reduce structural weight by introducing composite materials, leading to improved fuel efficiency.  

---

## 🏗️ Project Structure
The project is divided into four main parts:

### 1. Sizing and Design Selection
- Determining dimensions and mechanical characteristics of the suspension.  
- Selecting the most suitable constructive solution.  

### 2. 3D Modeling
- Developing a full 3D model in **SolidWorks**.  
- Highlighting geometry and key structural components.  

### 3. Validation through Simulation
- Using the **SolidWorks Simulation** module.  
- Analyzing deformations and stress distribution under realistic conditions.  

### 4. System Improvements
- Exploring weight reduction strategies aligned with automotive industry trends.  
- Integrating **composite materials** into the leaf package to improve efficiency and reduce fuel consumption.  

---

## 1. Calculation and Design of the Leaf Spring Suspension

The calculation and sizing stage aims to determine the **optimal dimensions** of the suspension system.  
This step is critical, as several key factors depend on it:

- ⚙️ **Proper functioning** – ensuring the suspension performs as intended under operating conditions.  
- 🛡️ **Strength and durability** – resistance to different mechanical loads and stresses.  
- 🚗 **Safety** – maintaining stability and reliability of the vehicle.  
- 💰 **Economic efficiency** – achieving a balance between performance and cost-effectiveness.  


# 📊 Leaf Spring Suspension Calculations

## 🔹 Input Parameters and Results

| Parameter | Formula / Description | Value |
|-----------|------------------------|-------|
| Force acting on each side of the axle | `F = 5150 · g` | **50 521 [kN]** |
| Distance between leaf spring supports | `L = C · ³√F` | **1260 [mm]** |
| Allowable stress | `σ_adm = σ_rupture / 1.5` | **750 [MPa]** |
| Maximum moment at the extremities | `M_max = (F · L) / 4` | **15.94 · 10³ [N·m]** |
| Total moment of inertia | `M_max = σ_adm · (I_total / y)` → `I_total = (M_max · y) / σ_adm` | **1.594 · 10⁶ [mm⁴]** |
| Total number of leaves | `I_l = (b · h³) / 12` ; `n = I_t / I_l` | **9 [-]** |

---

## 🔹 Geometrical Properties

| Parameter | Value |
|-----------|-------|
| Leaf thickness (height) | **15 [mm]** |
| Leaf width | **76.2 [mm]** |

---

## 🔹 Verification Checks

| Check | Formula | Result |
|-------|----------|--------|
| Maximum stress verification | `I_total_real = n · I_l` ; `σ = (M_max · y) / I_total_real` | **620 [MPa]** |
| Shear stress verification | `τ = (3 · F) / (2 · n · b · h)` | **736 [MPa]** |
| Deflection verification | `f = (F · L³) / (48 · E · I_total)` | **63.38 [mm]** |

---

## 2. Chassis Modeling

Chassis modeling is a **complex engineering task**, as the designer must consider multiple factors to ensure functionality, safety, and manufacturability.  

Key aspects include:
 🚛 **Total load capacity** – the maximum load the vehicle is expected to carry.  
 📏 **General dimensions** – such as overall vehicle length, wheelbase, and track width.  
 ⚙️ **Axle configuration** – number of axles and number of driven axles.  
 🏗️ **Frame type** – whether the chassis uses longitudinal side members, a ladder-type structure, or other frame designs.  
 🔄 **Compatibility with subsystems** – ensuring proper integration with suspension, drivetrain, and other assemblies.  
 💡 **Manufacturing and cost efficiency** – a well-designed chassis simplifies fabrication processes and optimizes production costs.  

✅ A high-quality chassis design ensures **structural integrity, ease of manufacturing, and cost-effectiveness**, while meeting performance and safety requirements.  

<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/7dbf3fb8-7ca1-4e9f-9557-f9e6e1e147e2" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/283186a0-a196-4790-a311-0c1c09c17b19" />
<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/ab98a42d-5645-4f85-84a9-b9d31f2d8de0" />
<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/8a1b37a9-1c03-4784-bd66-e6a98c6bfb73" />
<img width="974" height="547" alt="image" src="https://github.com/user-attachments/assets/e565261e-4e4b-4ee7-9cc0-6456d048a90d" />
<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/1a622e12-3f6c-433b-9223-d68b02c678b0" />
<img width="975" height="549" alt="image" src="https://github.com/user-attachments/assets/1c2c301f-4e74-4c69-ba5c-dc02010fde16" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/50710a8d-c6d1-473e-9c68-572f90d3b337" />
<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/a8223efa-c2e8-40fe-8fab-5fe8a2380a1c" />
<img width="974" height="550" alt="image" src="https://github.com/user-attachments/assets/fb1b9173-1cbd-4355-9ee3-e0dced995719" />
<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/e3a4b1eb-a5a6-4021-828f-5c9a496511d9" />
<img width="975" height="549" alt="image" src="https://github.com/user-attachments/assets/4cdaf719-6a45-4cdf-974c-154097815279" />
<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/1d58a208-42bb-4fe9-97bc-796ddb02511b" />
<img width="975" height="547" alt="image" src="https://github.com/user-attachments/assets/981b580e-3a0c-492b-854c-4739fab3f203" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/3c70ad5a-9b4f-453b-8695-4bc60d3b9b50" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/fb783f6f-678f-4c08-b079-1fe8ca5edd20" />
<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/1bc64707-a94d-4454-8c82-3623036a5f2a" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/fec42b87-0a20-485a-a674-1b7ef9e1f13b" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/9e70d186-1c4c-4bc8-8403-a67330e3f755" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/a9c0966c-42ab-48d8-a74b-11014cf1f800" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/323c3fa3-edc6-473a-aabd-d28a48a1612c" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/316bff9d-5798-49ae-b42f-c1097ac27e7e" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/725b2ef7-c264-4125-a919-2e973c3e3680" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/a08f5611-b366-402b-abe0-d33812778a5e" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/4171a04c-020a-446b-b9df-846427dc5290" />
<img width="974" height="547" alt="image" src="https://github.com/user-attachments/assets/837b604a-0887-4f29-b385-d2514c63a64c" />
<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/7fd0ee8f-c654-4510-8e7a-ca000c327960" />
<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/942b2062-bde2-455a-b612-7b85bdc48277" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/49d372ed-14ce-4bef-825d-4d3866348326" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/40800f4d-43ed-4d56-b23c-5333d197a50d" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/3d0c26f2-3661-416f-aeb7-ab079c854440" />
<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/2df7c6d5-4c22-4f61-9375-6b7ef6e0d302" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/c63b47cb-af2c-4975-b494-befd0d042dac" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/87431c1b-b345-4b66-9019-846ac7a97708" />
<img width="975" height="550" alt="image" src="https://github.com/user-attachments/assets/c7a0f474-a346-4fef-8df7-d1619183ef87" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/2460aa28-81e3-4f8c-a9df-7cb8e85e5862" />
<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/ec0f1e7c-220c-462f-9627-00a5667c3cdc" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/4d4331de-dc75-4ccf-89b6-1ad6e13ba9fb" />
<img width="974" height="551" alt="image" src="https://github.com/user-attachments/assets/4d2b37a0-a254-4ddf-8676-f60871491a0d" />


## 3. Simulation of the Designed Assembly

This part presents the results obtained from the simulation of the designed assembly.  
The analysis was carried out using **SolidWorks** with its dedicated **Simulation** module.  

The main objectives of the simulations were:
 🔹 To evaluate the **structural behavior** of the assembly under static operating loads.  
 🔹 To provide a **validation** of the sizing and modeling procedures applied during the design stage.  
 🔹 To identify the **stress distribution** and **displacements** within the structure.  

### ✅ Advantages of Simulation
- Allows evaluation of load distribution and displacements **without the need for a physical prototype**.  
- Helps identify and optimize **critical mechanical areas** early in the design process.  
- Reduces development costs and improves reliability before manufacturing.  


## Material Selection

The first step was selecting a suitable material for each component.  
For the **leaf spring plates**, the chosen material was **51CrV4**, as specified in the sizing chapter.  

Since this material is not available in the predefined **SolidWorks** material library, it was manually added.  
The following mechanical properties were introduced:

### 📑 Mechanical Properties of 51CrV4 [32]

| Property | Value | Unit |
|----------|-------|------|
| Elastic modulus | 2.1 × 10¹¹ | N/m² |
| Poisson’s ratio | 0.3 | – |
| Shear modulus (torsion) | 8.1 × 10¹⁰ | N/m² |
| Density | 7850 | kg/m³ |
| Tensile strength | 1.1 × 10⁹ | N/m² |
| Compressive strength | 1.1 × 10⁹ | N/m² |
| Yield strength | 8.5 × 10⁸ | N/m² |
| Thermal expansion coefficient | 1.1 × 10⁻⁵ | 1/K |
| Thermal conductivity | 35 | W/(m·K) |
| Specific heat | 460 | J/(kg·K) |
| Damping coefficient | 0.01 | – |

---

✅ With these properties defined, SolidWorks simulations could be performed more accurately, reflecting the real-world mechanical and thermal behavior of the 51CrV4 alloy.  


# Chassis and Component Material Selection ⚙️

In the next stage, for the **chassis elements**, **fastening components**, and **movable flanges**, the material **AISI 4340 Steel (annealed)** was used. This material was chosen for its:  

- 💪 Excellent **mechanical strength**  
- 🔄 Very good **fatigue resistance**  
- 🔥 Ability to be **heat treated** for enhanced strength  

---

## Fasteners: Bolts and Nuts 🔩

Equally important was the **material selection for bolts and nuts** used in the assembly. A great choice is **Alloy Steel SS**, thanks to:  

- 💪 Good **mechanical strength**  
- 📏 **Reasonable values** for **elastic modulus** and **density**  

---

## Assembly Fixation and Force Application 🛠️

The next step involved **securing the assembly** by applying **restraining conditions** and **external forces**:  

1. 🏗️ **Restrictions** were applied on the **chassis surface** to limit movement.  
2. ⚡ **External force** was applied according to the **real operational conditions** to simulate actual usage.  

This ensures that the **chassis assembly** behaves realistically under expected operating conditions.  

---

📌 **Note:** Proper material selection and constraint application are crucial for **structural integrity** and **long-term performance**.


<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/40fb435b-576a-46a7-ad13-60da0651b52c" />

## Assembly Simulation 🚀

The next step was to proceed with the **actual simulation of the assembly**.  

- 🎯 The goal of this stage is to **analyze the structural behavior** under applied forces and constraints.  
- 🧩 All previously defined **materials**, **restrictions**, and **loads** are now implemented in the simulation environment.  
- 📊 This allows engineers to **observe stress distribution, deformation, and potential weak points** before actual manufacturing.  

> Simulation ensures that the assembly meets the **design requirements** and performs reliably under **real operating conditions**.

<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/d0e9ea81-31c6-43ec-9323-0c8a232cd887" />

<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/db19054b-3413-4f1d-9791-7dfd50142a4c" />

<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/e7fa4090-cd3a-4105-bcb5-17ec97edfc66" />

## 4. Transition to Composite Materials in Automotive Industry 🚗🔧

In response to increasingly strict requirements regarding **energy efficiency**, **weight reduction**, and **longer component lifespan**, the automotive industry is gradually **shifting toward composite materials**.  

### Advantages of Lightweight Suspensions ⚖️

Reducing the **unsprung mass** in a suspension system brings multiple benefits:  

- ⛽ **Lower fuel consumption**  
- 🚗 **Improved handling**  
- 😌 **Increased ride comfort**  

A good alternative to **51CrV4 steel** is the **GFRP (Glass Fiber Reinforced Polymer)** composite.  

---

### What is GFRP? 🧪

GFRP consists of:  

- **Polymer matrix** (usually polyester resin) – provides **structural support** and **chemical resistance**  
- **Glass fibers** – enhance **mechanical strength** to withstand applied loads  

---

### Benefits of GFRP over Traditional Laminates ✅

- ⚡ **Much lower density**, reducing weight by up to **85%**  
- 🛡️ **Higher corrosion and fatigue resistance**  
- 💥 **Higher energy absorption per unit weight**  
- 🏭 **Manufacturing flexibility** – can be **cast or laminated**, ideal for automotive applications  

---

### Potential Drawbacks ⚠️

While GFRP offers significant advantages, there are some downsides:  

- 💰 **Higher cost** compared to steel  
  - Estimated GFRP: **4–10 €/kg**  
  - Estimated 51CrV4 steel: **1.5–3 €/kg**  
- ♻️ **Recycling is more difficult**  
- ❗ **Unpredictable behavior in case of failure**  

> Overall, GFRP is a promising material for automotive suspension systems, but careful consideration of cost and manufacturing challenges is required.


## Defining GFRP Composite Material in SolidWorks 🛠️

We started by **defining the GFRP (Glass Fiber Reinforced Polymer) composite material**, as it is **not included in SolidWorks' predefined materials list**.  

The key **material properties** required for the simulation are:  

- 📐 **Elastic modulus**  
- ⚖️ **Poisson's ratio**  
- ✂️ **Shear modulus**  
- 🏋️ **Density**  
- 🧲 **Tensile strength**  
- 🏗️ **Compressive strength**  
- 🔧 **Yield strength**  
- 🌡️ **Thermal expansion coefficient**  
- 🔥 **Thermal conductivity**  
- 💨 **Specific heat**  
- 🎵 **Damping factor**  

> Defining these properties accurately ensures that the simulation results reflect the **real behavior** of the GFRP composite in the assembly.

<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/c9c456f3-29dc-48d2-95a3-d8e2b06a5a8a" />

<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/7ed5cd95-5f42-42d7-b961-34c08f56c2a3" />

<img width="974" height="548" alt="image" src="https://github.com/user-attachments/assets/2b96691d-4120-4478-b2cf-139aed29f11f" />


## 5. Conclusions 🏁

This work focused on the **research, optimization, and analysis of a rear leaf spring suspension for trucks**.  

### Key Findings from 51CrV4 Steel Simulations ⚙️

- Simulations of the **leaf spring pack made from 51CrV4 steel** showed that:  
  - Von Mises stress ✅  
  - Maximum displacement ✅  
  - Strain distribution ✅  

All fell **within the normal parameters** for this steel.  
This demonstrates that the **chosen solution meets mechanical strength and stiffness requirements** without elastic deformations. The material provides **adequate behavior under real operating conditions**.  
> The results validate the **dimensioned assembly** and support the **technical feasibility** of the chosen method.  

---

### Motivation for Composite Materials 🌱

Due to **stricter energy efficiency requirements**, **emission reduction**, and the need to **improve vehicle handling**, exploring alternative materials became essential.  

One promising option is **replacing steel with GFRP (Glass Fiber Reinforced Polymer)** for the leaf spring pack, which helps **reduce unsprung mass**—a key factor in modern truck suspension design.  

---

### Key Findings from GFRP Simulations 🧪

- Using **GFRP composite material**:  
  - Von Mises stress, maximum displacement, and strain **fall within the allowed mechanical property ranges**  
  - The suspension system exhibits **stable and predictable behavior** under load  
  - **Excessive deformations are prevented**  

- ✅ **GFRP is a feasible alternative** to alloy steel:  
  - Efficiently handles dynamic loads  
  - Significantly reduces assembly weight  

---

### Final Remarks 📌

This study bridges **traditional engineering methods** with **modern computer-aided design approaches** for suspension systems.  
It demonstrates that integrating **advanced materials like GFRP** can lead to **lighter, more efficient, and technically robust truck suspensions** while keeping the system reliable under real-world operating conditions.
