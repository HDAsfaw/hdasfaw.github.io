---
title: "SMILED Lab - wiki"
layout: textlay
excerpt: "SMILED Lab: wiki"
sitemap: false
permalink: /wiki/
---
## Executive Summary

Hard carbon is widely regarded as the most practical anode class for sodium-ion batteries because it combines low operating potential, relatively high reversible capacity, broad precursor availability, and compatibility with scalable carbon-processing routes. Unlike graphite, which performs poorly for reversible sodium intercalation in conventional carbonate electrolytes, hard carbon contains turbostratic graphene fragments, expanded interlayer spacing, defects, heteroatoms, and open or closed pores that can host sodium through multiple storage modes.

The most important synthesis variables are **precursor chemistry**, **carbonization temperature**, **heating rate**, **pre-treatment**, **post-treatment**, **particle size**, and **surface chemistry**. Biomass, sugars, polymers, resins, pitch, and lignin can all yield hard carbon, but each precursor gives different ash content, oxygen functionality, microtexture, pore architecture, and carbon yield. In many biomass-derived systems, heat treatment around **1200–1400 °C** often balances disorder, closed pores, interlayer spacing, and surface area, though the optimum depends strongly on feedstock and processing history.

Current research aims to increase reversible capacity, initial Coulombic efficiency (ICE), rate capability, long-term cycling stability, and full-cell energy density. Major strategies include impurity removal, controlled pre-carbonization, high-temperature graphitic-domain development, pore engineering, heteroatom doping, electrolyte optimization, artificial SEI formation, and presodiation. The practical target is not merely a high half-cell capacity, but a reproducible, low-cost, low-surface-area hard carbon that delivers high ICE, stable low-voltage plateau capacity, acceptable rate performance, and manufacturable electrode density.

---

## 1. Background: Why Sodium-Ion Batteries Need Hard Carbon

Sodium-ion batteries are attractive for stationary storage, low-cost mobility, and supply-chain-resilient applications because sodium is abundant and widely distributed. SIBs share many engineering concepts with lithium-ion batteries, but the larger Na⁺ ion radius and different solvation/desolvation behavior impose stricter requirements on electrode host structures. The anode is particularly challenging: graphite, the dominant lithium-ion anode, does not provide sufficiently robust reversible Na⁺ storage in standard carbonate-based SIB electrolytes.

Hard carbon addresses this gap. It is a non-graphitizable carbon with short-range graphitic ordering and long-range disorder. Its structure can be imagined as randomly oriented graphene-like nanodomains, defects, edge sites, and nanometer-scale voids. These features create multiple sodium-storage environments: adsorption at defects and edges, intercalation between turbostratic layers, and filling or clustering in closed nanopores at low potential.

---

## 2. Structure of Hard Carbon

Hard carbon is not a single well-defined phase; it is a family of disordered carbons whose properties depend strongly on synthesis. The most relevant structural descriptors are:

- **Interlayer spacing, d002:** Expanded spacing relative to graphite can enable Na⁺ insertion between graphene-like layers.
- **Graphitic domain size and stacking:** Larger ordered domains can improve conductivity and plateau behavior, but excessive ordering may reduce accessible storage sites.
- **Defect density:** Defects and edge sites contribute to sloping capacity but may also increase irreversible electrolyte decomposition.
- **Specific surface area:** High surface area can improve wetting and kinetics, but usually lowers ICE by promoting SEI formation.
- **Open pores vs closed pores:** Open pores contact electrolyte and can increase irreversible reactions; closed pores are often associated with low-voltage plateau capacity.
- **Heteroatom content:** O, N, S, P, B, and F can tune electronic structure, wettability, binding energy, and SEI chemistry.
- **Ash and inorganic impurities:** Biomass-derived carbons often require purification because mineral residues can harm electrochemical performance and reproducibility.

A practical HC anode typically requires a compromise: enough disorder and pore structure to store Na⁺, but sufficiently low surface area and controlled defects to minimize irreversible capacity loss.

---

## 3. Sodium-Storage Mechanisms

Sodium storage in hard carbon remains more complex than lithium storage in graphite. Several models have been proposed, including insertion–filling, adsorption–insertion, three-stage adsorption/intercalation/filling, and adsorption–pore-filling models. Most modern interpretations agree that different voltage regions correspond to different storage environments, though the exact assignment depends on material structure and electrolyte.

### 3.1 Sloping Region

The sloping region, typically above ~0.1 V vs Na/Na⁺, is commonly associated with sodium adsorption at defects, edges, functional groups, and sometimes insertion into more disordered carbon layers. Materials with high defect density and surface area often show large sloping capacity, but this can come at the cost of lower ICE and larger hysteresis.

### 3.2 Plateau Region

The low-voltage plateau, typically below ~0.1 V vs Na/Na⁺, is often connected with Na⁺ insertion into more ordered turbostratic domains and/or filling of closed nanopores. A strong plateau contribution is attractive for full-cell energy density because it occurs at low anode potential. However, operating too close to 0 V vs Na/Na⁺ raises concerns about sodium plating, especially at high rates, low temperature, or high areal loading.

### 3.3 Implications for Design

A high-performance HC anode should maximize reversible low-voltage capacity while avoiding excessive irreversible reactions. Therefore, synthesis should aim for:

1. Expanded but stable interlayer spacing.
2. Sufficient closed pores for plateau capacity.
3. Low external surface area to increase ICE.
4. Controlled surface functional groups to form a stable SEI.
5. Good electronic conductivity and electrode-level density.

---

## 4. Precursors for Hard Carbon

### 4.1 Biomass-Derived Precursors

Biomass is attractive because it is renewable, low cost, and structurally diverse. Common examples include coconut shell, bamboo, wood, lignin, cellulose, starch, peat, bagasse, nut shells, fruit peels, and agricultural residues. Biomass-derived carbons can offer hierarchical microstructures and naturally doped heteroatoms, but they also introduce variability in composition, moisture, ash, and mineral impurities.

**Advantages:**

- Renewable and potentially low-cost.
- Large variety of feedstocks.
- Can valorize agricultural or forestry waste.
- Often forms useful porous and turbostratic structures.

**Challenges:**

- Batch-to-batch variability.
- Mineral impurities and ash.
- Need for washing, drying, milling, and classification.
- Lower carbon yield for some feedstocks.
- Sustainability depends on collection, transport, and chemical-treatment burden.

### 4.2 Sugar and Carbohydrate Precursors

Glucose, sucrose, starch, and cellulose are frequently used in mechanistic studies because their chemistry is relatively well defined. They are useful for studying carbonization temperature effects and sodium-storage models. However, purified sugars may be more expensive than waste biomass for large-scale production.

### 4.3 Polymer and Resin Precursors

Phenolic resin, polyacrylonitrile, polyaniline, and other polymers can provide controlled chemistry and reproducible carbon frameworks. Resins can be tailored through crosslinking, curing, and templating. Their disadvantages include precursor cost and the environmental burden of polymer production.

### 4.4 Pitch, Lignin, and Industrial Carbon Sources

Pitch and lignin are attractive for scale because they are available from petroleum, coal, or biorefinery streams. However, pitch-derived carbons may require careful stabilization or crosslinking to avoid forming soft carbon or graphitizable textures. Lignin is abundant and aromatic but chemically heterogeneous.

---

## 5. Synthesis Routes

### 5.1 Direct Pyrolysis / One-Step Carbonization

The simplest route is direct carbonization of the precursor under inert atmosphere, commonly N₂ or Ar. The precursor is heated to a final temperature, held for several hours, and cooled under inert gas.

**Typical steps:**

1. Dry and grind precursor.
2. Heat under inert gas.
3. Hold at target carbonization temperature.
4. Cool under inert gas.
5. Mill and sieve final carbon.

**Strengths:** simple and scalable.  
**Weaknesses:** limited control over volatile release, pore closure, and impurity removal.

### 5.2 Two-Step Carbonization

A common industrially relevant strategy uses a lower-temperature pre-carbonization followed by high-temperature carbonization. Pre-carbonization removes volatiles, stabilizes morphology, reduces tar formation, and protects high-temperature furnaces. The second step develops the final turbostratic and pore structure.

**Example process window:**

- Pre-carbonization: 300–700 °C.
- Final carbonization: 1000–1600 °C.
- Atmosphere: N₂ or Ar.
- Holding time: typically 1–6 h, depending on material and furnace design.

### 5.3 Hydrothermal Carbonization Followed by Pyrolysis

Hydrothermal carbonization (HTC) treats biomass or carbohydrates in water at moderate temperature and autogenous pressure, producing hydrochar. The hydrochar is then pyrolyzed. HTC can improve morphology, oxygen functionality distribution, and carbon yield, but it adds process complexity and wastewater considerations.

### 5.4 Chemical Pre-Treatment

Chemical washing or activation can remove ash, alter functional groups, and tune pores.

- **Acid washing** removes metal impurities and ash-forming minerals.
- **Alkali treatment** can etch carbon and create porosity but may increase surface area excessively.
- **Deep eutectic solvent treatment** and other greener solvent methods are emerging for biomass restructuring.

The key risk is over-activation: too many open pores and defects can lower ICE.

### 5.5 Template-Assisted and Pore-Engineering Routes

Templates can create controlled meso/microporous structures, but template removal may require corrosive chemicals and may be hard to scale. For SIB anodes, the goal is not maximum surface area; rather, it is selective formation of beneficial closed pores and ion-accessible transport pathways while minimizing electrolyte-exposed surface.

### 5.6 Heteroatom Doping

Doping with N, S, P, B, F, or co-dopants can improve electronic conductivity, tune Na binding, increase active sites, and regulate SEI chemistry. However, dopants can also increase irreversible reactions if they generate excessive defects or unstable surface groups. Doping is most useful when integrated with careful surface-area control.

---

## 6. Effect of Carbonization Temperature

Carbonization temperature is one of the most influential synthesis parameters.

### Low Temperatures (<1000 °C)

- High defect and heteroatom content.
- Larger sloping capacity.
- Higher surface area and more irreversible reactions.
- Lower conductivity and lower ICE.

### Intermediate Temperatures (~1200–1400 °C)

- Balanced graphitic-domain growth and closed-pore formation.
- Often favorable reversible capacity and ICE for biomass-derived HCs.
- Reduced surface functionality and improved conductivity.

### High Temperatures (>1600 °C)

- Greater ordering and lower defect density.
- Lower surface area and potentially higher ICE.
- Possible loss of adsorption capacity.
- Higher energy cost and potentially reduced sustainability.

Because carbonization temperature changes several variables simultaneously, it should be optimized together with precursor selection, heating rate, hold time, and pre-treatment.

---

## 7. Electrochemical Performance Metrics

### 7.1 Reversible Capacity

Hard carbon commonly delivers reversible capacities around 250–350 mAh g⁻¹ in laboratory half cells, with some optimized reports exceeding this range. Capacity should always be interpreted with current density, voltage window, electrode loading, and testing protocol.

### 7.2 Initial Coulombic Efficiency

ICE is a critical practical metric because sodium consumed during first-cycle SEI formation reduces full-cell capacity. Low ICE is one of the biggest barriers to HC commercialization. ICE can be improved by reducing surface area, removing unstable functional groups, controlling defects, forming stable SEI, using electrolyte additives, or applying presodiation.

### 7.3 Rate Capability

Rate performance depends on particle size, electrode porosity, electronic conductivity, ion-transport pathways, SEI resistance, and Na⁺ diffusion in carbon domains. Highly dense, low-surface-area carbons may have excellent ICE but limited rate performance unless electrode architecture is optimized.

### 7.4 Cycling Stability

Stable cycling requires a mechanically robust carbon structure and a stable SEI. Hard carbon generally has lower volume expansion than alloying anodes, but repeated Na⁺ insertion, pore filling, and SEI growth can still cause impedance rise.

### 7.5 Full-Cell Relevance

Half-cell performance against sodium metal can overstate practical performance. Full-cell testing with realistic cathodes, N/P ratio, electrolyte amount, electrode loading, and formation protocol is essential. A commercially relevant HC must perform under high areal capacity, lean electrolyte, and calendered electrode conditions.

---

## 8. Electrolyte and Interphase Engineering

The SEI strongly determines ICE, impedance, safety, and cycle life. Carbonate electrolytes are common, but ether-based electrolytes can sometimes improve rate capability and interphase properties. Additives such as fluoroethylene carbonate (FEC) or other film-forming agents can improve SEI stability, though additive effects are material-specific.

Important design goals include:

- Thin, ionically conductive, electronically insulating SEI.
- Minimal sodium inventory loss.
- Suppression of continuous electrolyte decomposition.
- Compatibility with low-voltage plateau operation.
- Stable behavior at elevated and low temperatures.

Presodiation is also important for practical SIB full cells. It can compensate first-cycle sodium loss, but industrial presodiation must be safe, uniform, low cost, and compatible with roll-to-roll manufacturing.

---

## 9. Characterization Methods

A rigorous HC study should combine structural, surface, and electrochemical characterization.

| Question | Useful techniques |
|---|---|
| Interlayer spacing and ordering | XRD, TEM, Raman, PDF analysis |
| Pore structure | N₂/CO₂ adsorption, SAXS/SANS, density measurements |
| Surface chemistry | XPS, FTIR, elemental analysis, TPD |
| Morphology and particle size | SEM, TEM, laser diffraction |
| Sodium-storage mechanism | Operando/ex situ XRD, Raman, NMR, SAXS, GITT, CV kinetics |
| SEI composition | XPS, TOF-SIMS, cryo-TEM, EIS |
| Practical electrode behavior | Full-cell cycling, rate tests, impedance, high-loading electrodes |

A frequent limitation in the literature is overreliance on BET surface area from N₂ adsorption. Closed pores that matter for plateau capacity may not be fully captured by standard gas adsorption, so complementary scattering, density, and electrochemical methods are needed.

---

## 10. Challenges to Commercialization

1. **Low ICE:** First-cycle sodium loss remains a key barrier, especially in full cells.
2. **Precursor variability:** Biomass and waste-derived feedstocks need standardized quality control.
3. **Energy-intensive carbonization:** High-temperature treatment raises cost and carbon footprint.
4. **Electrode density:** Highly porous carbons may reduce volumetric energy density.
5. **Mechanistic ambiguity:** Different hard carbons store sodium differently, complicating universal design rules.
6. **Scale-up reproducibility:** Lab-scale synthesis does not always translate to continuous furnaces and ton-scale batches.
7. **Full-cell validation:** Many studies report half-cell data only; practical SIBs require cathode-balanced full-cell testing.
8. **Safety near 0 V:** Low-voltage plateau capacity improves energy density but may increase sodium plating risk under abuse or fast charging.

---

## 11. Design Guidelines for Future Hard Carbon Anodes

A rational design workflow for HC anodes should include:

1. **Select scalable precursor:** prioritize stable supply, low ash, high carbon yield, and low cost.
2. **Apply mild purification:** remove minerals without creating excessive open porosity.
3. **Use controlled pre-carbonization:** stabilize structure and reduce volatile burden.
4. **Optimize final carbonization:** target the best balance of closed pores, interlayer spacing, defects, and conductivity.
5. **Minimize electrolyte-exposed surface:** improve ICE and reduce SEI growth.
6. **Engineer the SEI:** use electrolyte formulation and additives matched to carbon surface chemistry.
7. **Validate in full cells:** include realistic cathodes, N/P ratios, areal loadings, and formation procedures.
8. **Assess sustainability:** evaluate energy input, washing chemicals, wastewater, carbon yield, and precursor logistics.

---

## 12. Outlook

Hard carbon is likely to remain the benchmark anode for sodium-ion batteries because it offers the best compromise between cost, capacity, safety, and manufacturability. The next phase of progress will be driven less by isolated record capacities and more by integrated optimization: feedstock control, furnace process design, low-waste purification, electrode engineering, electrolyte compatibility, and full-cell validation.

For research, the most valuable advances will come from linking precursor chemistry to carbon microstructure and then to voltage-resolved sodium-storage behavior. For industry, the key challenge is producing hard carbon with consistent ICE, plateau capacity, tap density, impurity level, and cost at scale. Biomass-derived hard carbons are especially promising, but only if variability and process sustainability are controlled.

---

## Suggested Figure Ideas for a Longer Review

1. **Synthesis map:** precursor → pre-treatment → carbonization → post-treatment → electrode.
2. **Structure schematic:** turbostratic layers, defects, open pores, closed pores, and Na-storage sites.
3. **Voltage profile annotation:** slope vs plateau region and corresponding storage processes.
4. **Temperature–structure–performance diagram:** how heat-treatment temperature affects defects, pores, ICE, and capacity.
5. **Commercialization funnel:** lab half-cell → high-loading electrode → full cell → pouch cell → scale-up.

---

## Key References and Further Reading

1. Wu, C.; Yang, Y.; Zhang, Y.; Xu, H.; He, X.; Wu, X.; Chou, S. **Hard carbon for sodium-ion batteries: progress, strategies and future perspective.** *Chemical Science* 2024, 15, 6244–6268. DOI: [10.1039/D4SC00734D](https://doi.org/10.1039/D4SC00734D)
2. Shafiee, F. N.; Mohd Noor, S. A.; Mohd Abdah, M. A. A.; Jamal, S. H.; Samsuri, A. **Recent progress on hard carbon and other anode materials for sodium-ion batteries.** *Heliyon* 2024, 10, e29512. [Article link](https://www.cell.com/heliyon/fulltext/S2405-8440(24)05543-9)
3. Thompson, M.; Xia, Q.; Hu, Z.; Zhao, X. S. **A review on biomass-derived hard carbon materials for sodium-ion batteries.** *Materials Advances* 2021. DOI: [10.1039/D1MA00315A](https://doi.org/10.1039/D1MA00315A)
4. Tan, S.; Yang, H.; Zhang, Z.; Xu, X.; Xu, Y.; Zhou, J.; et al. **The Progress of Hard Carbon as an Anode Material in Sodium-Ion Batteries.** *Molecules* 2023, 28, 3134. DOI: [10.3390/molecules28073134](https://doi.org/10.3390/molecules28073134)
5. Mu, B.; Chi, C.; Yang, X.; Huangfu, C.; Qi, B.; Wang, G.; Li, Z.; Song, L.; Wei, T.; Fan, Z. **A review of hard carbon anodes for rechargeable sodium-ion batteries.** *New Carbon Materials* 2024, 39(5). [PDF link](https://ncmjournal.org/wp-content/uploads/NCM2024-39-05-04.pdf)

---

## Short Glossary

- **HC:** Hard carbon, a non-graphitizable disordered carbon.
- **SIB:** Sodium-ion battery.
- **ICE:** Initial Coulombic efficiency; first-charge capacity divided by first-discharge capacity.
- **SEI:** Solid electrolyte interphase, passivation layer formed on the anode.
- **d002:** Interlayer spacing of graphitic/turbostratic carbon layers.
- **Plateau capacity:** Low-voltage capacity contribution, often linked to pore filling and/or interlayer insertion.
- **Sloping capacity:** Higher-voltage capacity contribution, often linked to adsorption and defect-related storage.
- **Presodiation:** Addition of sodium inventory before or during cell assembly to compensate first-cycle losses.
