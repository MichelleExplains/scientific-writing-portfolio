# Standard Operating Procedure (SOP)
**Document ID:** SOP-MYC-042  
**Effective Date:** October 10, 2026  
**Version:** 1.0  
**Author:** MichelleExplains, Scientific Technical Writer  

---

## 1. Purpose & Scope
This document outlines the standardized workflow for isolating, preparing, and identifying fungal symbionts from host plant root tissue. This procedure encompasses surface sterilization, microscopic verification, and preparation for definitive downstream molecular barcoding. This protocol applies to all laboratory technicians and quality control analysts operating within the molecular mycology division.

## 2. Health, Safety, & Hazardous Materials
* **Personal Protective Equipment (PPE):** Nitrile gloves, chemical splash goggles, and a fluid-resistant laboratory coat must be worn throughout this procedure.
* **Chemical Hazards:**
  * *Sodium Hypochlorite (NaClO) & Ethanol (C₂H₅OH):* Strong irritants. Perform all surface sterilization steps inside a certified Class II Biosafety Cabinet (BSC).
  * *Potassium Hydroxide (KOH):* Corrosive agent utilized for tissue clearing. Handle with extreme caution; avoid all skin and eye contact.
* **Waste Disposal:** All colonized agar plates and biological tissue remnants must be autoclaved at 121°C for 20 minutes prior to disposal in hazardous bio-waste streams.

## 3. Materials & Equipment
* Host plant root specimens (stored at 4°C for no more than 24 hours).
* Sterile 70% Ethanol and 2% Sodium Hypochlorite solutions.
* Sterile Deionized Water (dH₂O) and molecular-grade Nuclease-Free Water.
* 10% Potassium Hydroxide (KOH) clearing reagent.
* Lactophenol Cotton Blue (LPCB) diagnostic stain.
* Sabouraud Dextrose Agar (SDA) plates fortified with chloramphenicol.
* Sterile petri dishes, micro-scalpels, and fine-tip forceps.
* Compound brightfield microscope equipped with 10x, 40x, and 100x (oil immersion) objectives.
* Genomic DNA extraction kit, 2X Taq Master Mix, and primers (ITS1 and ITS4).
* Automated thermal cycler and horizontal agarose gel electrophoresis system.

```text
+-----------------------------------------+

|  Root Tissue Harvest & Coarse Cleaning  |
+--------------------+--------------------+
                     |
                     v
+--------------------+--------------------+

|  Surface Sterilization (EtOH & NaClO)   |
+--------------------+--------------------+
                     |
                     v
+--------------------+--------------------+

|  Aseptic Plating & Colony Incubation    |
+--------------------+--------------------+
                     |
                     v
+--------------------+--------------------+

| Microscopic Diagnosis & Target Slicing  |
+--------------------+--------------------+
                     |
                     v
+--------------------+--------------------+

|   Genomic DNA Extraction & Purification   |
+--------------------+--------------------+
                     |
                     v
+--------------------+--------------------+

|   PCR Amplification & Gel Electrophoresis|
+--------------------+--------------------+
                     |
                     v
+--------------------+--------------------+

|    NCBI BLAST Bioinformatic Analysis    |
+-----------------------------------------+
```

## 4. Step-by-Step Procedure

### Phase 1: Surface Sterilization of Root Segments
1. **Coarse Rinse:** Submerge the target plant root systems under running tap water to remove remaining soil matrix, then transfer to a sterile petri dish.
2. **Sectioning:** Using a sterile micro-scalpel, section thin root fragments into precise 1.0 cm segments, selecting active lateral root intersections where mycorrhizal structures are densest.
3. **Chemical Disinfection:** Execute the sequential washing sequence inside the Biosafety Cabinet using sterile 50 mL conical tubes:
   * Agitate segments in **70% Ethanol** for exactly 60 seconds.
   * Transfer directly into **2% Sodium Hypochlorite** for 3 minutes.
   * Submerge in a second bath of **70% Ethanol** for 30 seconds.
4. **Rinsing Baseline:** Rinse the sterilized segments through three consecutive changes of sterile dH₂O for 1 minute per wash cycle. Retain 100 μL of the final rinse water to plate as a negative sterility control block.

### Phase 2: Isolation & Cultivation
1. **Aseptic Implantation:** Blot the sterile root segments dry on sterile filter paper. Using fine forceps, press 3 to 5 segments firmly onto the surface of an SDA plate infused with chloramphenicol.
2. **Incubation:** Seal plates using laboratory parafilm. Incubate inverted at 25°C ± 2°C, checking daily for emergent hyphal halos extending outward from the root margins.

### Phase 3: Morphological and Microscopic Evaluation
1. **Wet Mount Preparation:** Transfer a minimal hyphal loop or a cleared root slice onto a glass slide containing one drop of **10% KOH clearing solution**. Let sit for 10 minutes to dissolve host root structural proteins.
2. **Staining:** Add one drop of **Lactophenol Cotton Blue**, apply a coverslip gently to avoid trapping air bubbles, and examine under the microscope.
3. **Optical Assessment:** Scan fields at 10x magnification to locate fungal structures. Shift to 40x and 100x oil immersion objectives to characterize structural details:
   * *Aseptate hyphae with dichotomous branching:* Classify tentatively as **Glomeromycota / Arbuscular Mycorrhizae**.
   * *Septate hyphae displaying clamp connections:* Classify tentatively as **Basidiomycota symbionts**.

| **Fungal Phenotype** | **Primary Microscopic Feature** | **Key Diagnostic Identifier** |
| :--- | :--- | :--- |
| **Arbuscular Mycorrhizae (AM)** | Intracellular branched arbuscules | Coenocytic (aseptate) hyphae |
| **Ectomycorrhizae (ECM)** | Intercellular Hartig net matrix | Fungal mantle enveloping root tip |
| **Septate Endophytes** | Dark, partitioned intracellular hyphae | Distinct regular septations; microconidia |

### Phase 4: Downstream Molecular Verification (DNA Barcoding)
1. **Genomic DNA Extraction:** Collect 50–100 mg of fresh mycelial biomass. Flash-freeze using liquid nitrogen, homogenize with a sterile micro-pestle, and process through standard spin-column lysis and elution using 50 μL of Elution Buffer.
2. **Master Mix Assembly:** Prepare the PCR reaction mix inside a laminar flow hood according to the following matrix:

| **Component** | **Volume per Reaction (μL)** | **Final Concentration** |
| :--- | :--- | :--- |
| **2X Taq Master Mix** | 12.5 μL | 1X |
| **Forward Primer (ITS1)** | 1.0 μL | 0.4 μM |
| **Reverse Primer (ITS4)** | 1.0 μL | 0.4 μM |
| **Template DNA** | 2.0 μL | Variable (~20 ng) |
| **Nuclease-Free Water** | 8.5 μL | -- |
| **Total Volume** | **25.0 μL** | -- |

3. **Thermocycler Profile Setup:** Program the thermal cycler using the following optimized parameters:
   * *Initial Denaturation:* 95°C for 5 minutes
   * *Amplification Cycles (35 cycles):* Denaturation at 95°C for 30s, Annealing at 55°C for 30s, Extension at 72°C for 1 min.
   * *Final Extension:* 72°C for 10 minutes, then hold at 4°C.
4. **Sequence Identification via BLAST Analysis:** Run 5 μL of the PCR product on a **1.5% agarose gel** to confirm a target band at 500–700 bp. Submit clean samples for sequencing, and query the returned FASTA sequence strings against the **NCBI BLAST** fungal ITS database. Assign definitive taxonomy at ≥ 99% sequence identity.

## 5. Troubleshooting & Quality Control
* **Symptom: Growth on Sterility Control Plates.**
  * *Root Cause:* Insufficient surface sterilization technique or contaminated rinsing water.
  * *Corrective Action:* Discard batch data. Re-prepare chemical sterilants, verify BSC airflow compliance, and repeat protocols using fresh tissue.
* **Symptom: Massive Overgrowth by Saprophytic Moulds.**
  * *Root Cause:* Airborne spore contamination or delayed plating sequences.
  * *Corrective Action:* Reduce plate exposure times. Clean the interior surfaces of the BSC thoroughly with 70% ethanol prior to processing subsequent samples.
