---
format_version: 1
type: concept_set
set: Respiratory Physiology
concepts:
  - id: c-resp-001
    name: Gaseous Exchange in the Lung
    parent_id: null
  - id: c-resp-002
    name: Partial Pressures of Respiratory Gases
    parent_id: c-resp-001
  - id: c-resp-003
    name: Factors Affecting Gas Exchange
    parent_id: c-resp-001
  - id: c-resp-004
    name: Diffusing Capacity
    parent_id: c-resp-001
  - id: c-resp-005
    name: Oxygen Transport
    parent_id: null
  - id: c-resp-006
    name: Hemoglobin and O2 Binding
    parent_id: c-resp-005
  - id: c-resp-007
    name: Oxyhemoglobin Dissociation Curve
    parent_id: c-resp-005
  - id: c-resp-008
    name: Bohr Effect and Factors Affecting Hb-O2 Affinity
    parent_id: c-resp-005
  - id: c-resp-009
    name: Myoglobin
    parent_id: c-resp-005
  - id: c-resp-010
    name: P50
    parent_id: c-resp-007
  - id: c-resp-011
    name: Carbon Dioxide Transport
    parent_id: null
  - id: c-resp-012
    name: Bicarbonate Transport and Chloride Shift
    parent_id: c-resp-011
  - id: c-resp-013
    name: Carbamino Compound Transport
    parent_id: c-resp-011
  - id: c-resp-014
    name: Haldane Effect
    parent_id: c-resp-011
  - id: c-resp-015
    name: Carbon Monoxide Transport
    parent_id: c-resp-005
  - id: c-resp-016
    name: Regulation of Respiration
    parent_id: null
  - id: c-resp-017
    name: Medullary Respiratory Centers
    parent_id: c-resp-016
  - id: c-resp-018
    name: Dorsal Respiratory Group (DRG)
    parent_id: c-resp-017
  - id: c-resp-019
    name: Ventral Respiratory Group (VRG)
    parent_id: c-resp-017
  - id: c-resp-020
    name: Pontine Respiratory Centers
    parent_id: c-resp-016
  - id: c-resp-021
    name: Peripheral Chemoreceptors
    parent_id: c-resp-016
  - id: c-resp-022
    name: Central Chemoreceptors
    parent_id: c-resp-016
  - id: c-resp-023
    name: Hypoxia
    parent_id: null
  - id: c-resp-024
    name: Hypoxic Hypoxia
    parent_id: c-resp-023
  - id: c-resp-025
    name: Anemic Hypoxia
    parent_id: c-resp-023
  - id: c-resp-026
    name: Stagnant Hypoxia
    parent_id: c-resp-023
  - id: c-resp-027
    name: Histotoxic Hypoxia
    parent_id: c-resp-023
  - id: c-resp-028
    name: Hypercapnea
    parent_id: null
  - id: c-resp-029
    name: Deep Sea Diving and Respiration
    parent_id: null
  - id: c-resp-030
    name: Decompression Sickness
    parent_id: c-resp-029
  - id: c-resp-031
    name: High Altitude and Respiration
    parent_id: null
  - id: c-resp-032
    name: Acclimatization at High Altitude
    parent_id: c-resp-031
  - id: c-resp-033
    name: Acute and Chronic Mountain Sickness
    parent_id: c-resp-031
  - id: c-resp-034
    name: Exercise and Respiration
    parent_id: null
  - id: c-resp-035
    name: Fatigue
    parent_id: c-resp-034
  - id: c-resp-036
    name: Ventilation-Perfusion (V/Q) Ratio
    parent_id: null
  - id: c-resp-037
    name: V/Q Mismatch and Clinical Conditions
    parent_id: c-resp-036
  - id: c-resp-038
    name: Pulmonary Circulation
    parent_id: c-resp-036
---

## c-resp-001

### Physical Principles
1. Gases diffuse from higher to lower concentration (random molecular motion)
2. Kinetic energy is provided by molecular motion
3. Total gas pressure is directly proportional to gas molecule concentration
4. Pressure of dissolved gas is determined by its solubility coefficient

### Solubility Coefficients
| Gas | Solubility Coefficient |
|-----|----------------------|
| O2 | 0.024 |
| CO2 | 0.57 |
| CO | 0.18 |
| N2 | 0.012 |
| He | 0.008 |

CO2 has a high solubility coefficient (attracted to water); other gases have low coefficients. Henry's Law: Pressure = Concentration of dissolved gas / Solubility coefficient.

### Partial Pressures (mmHg)
| Gas | Inspired Air | Alveolus | Arterial Blood | Venous Blood | Expired Air |
|-----|-------------|----------|---------------|-------------|------------|
| O2 | 158.0 | 100.0 | 95.0 | 40.0 | 116.0 |
| CO2 | 0.3 | 40.0 | 40.0 | 46.0 | 32.0 |
| H2O | 5.7 | 47.0 | 47.0 | 47.0 | 47.0 |
| N2 | 596.0 | 573.0 | 573.0 | 573.0 | 565.0 |

### Factors Affecting Gas Exchange
1. **Pressure difference**: Gases diffuse from high to low concentration. Arterial PO2 < Alveolar PO2 due to arteriovenous shunts (Thebesian veins, bronchopulmonary anastomoses)
2. **Thickness of respiratory membrane**: Normally ~0.5 μm. Fibrosis increases thickness → reduces diffusion (inversely proportional)
3. **Surface area**: Reduced in emphysema or pneumonia → impedes exchange (directly proportional)
4. **Diffusing capacity**: Volume of gas diffusing per minute per 1 mmHg pressure difference

### Diffusing Capacity
- O2: ~21 mL/min/mmHg
- CO2: ~400-450 mL/min/mmHg (20× greater than O2)
- Directly proportional to membrane surface area
- Inversely proportional to membrane thickness
- Exercise increases diffusing capacity of O2, CO2, and CO

---

## c-resp-005

O2 delivery depends on: amount entering lungs, pulmonary gas exchange, blood flow to tissue, cardiac output, and blood O2-carrying capacity.

### Forms of O2 Transport
- **Dissolved in plasma**: 0.29 mL/100 mL arterial blood (1.5%)
- **Bound to hemoglobin**: 19.5 mL/100 mL arterial blood (98.5%)

### Hemoglobin
- Protein with 4 subunits, each containing a heme moiety (porphyrin + ferrous iron) attached to a polypeptide chain
- Each of 4 iron atoms binds 1 O2 molecule reversibly (oxygenation — iron stays ferrous)
- Theoretical O2 binding capacity: 1.39 mL O2/g Hb at 100% saturation
- Functional capacity: **1.34 mL O2/g Hb** (some Hb as methemoglobin 1-2%, CO-bound 1-2%)
- 100 mL blood with 15 g Hb fully saturated = 20.1 mL O2
- Systemic blood is 97% saturated → 19.8 mL O2/100 mL blood

### Saturation Levels
| Blood Type | Hb Saturation | O2/g Hb | Total O2/100 mL |
|-----------|---------------|---------|-----------------|
| Arterial | 97% | 1.30 mL | 19.8 mL |
| Venous | 75% | 1.02 mL | 15.3 mL |

At rest, 4.5 mL O2/100 mL extracted (3.8% dissolved, 96.2% from Hb).

### Oxyhemoglobin Dissociation Curve
- **Sigmoid shape** — reflects cooperative binding of O2 to Hb
- Flat portion (top): Small PO2 changes cause large saturation changes → loading in lungs
- Steep portion (bottom): Small PO2 changes cause large O2 release → unloading in tissues

### Factors Shifting Curve to the RIGHT (↑ unloading)
- ↑ Temperature
- ↓ pH (Bohr effect)
- ↑ PCO2
- ↑ 2,3-DPG

These conditions occur in exercising/active tissues → more O2 delivered where needed.

### Factors Shifting Curve to the LEFT (↓ unloading)
- ↓ Temperature
- ↑ pH
- ↓ PCO2
- ↓ 2,3-DPG

### Factors Affecting 2,3-DPG
- pH (falls when pH is low)
- Exercise
- High altitude
- Hormones: thyroid hormones, growth hormone, androgens

### P50
- The PO2 at which Hb is 50% saturated with O2
- Higher P50 = lower Hb affinity for O2 = right shift
- Normal P50 ≈ 27 mmHg

### Bohr Effect
Decrease in O2 affinity of Hb when blood pH falls. Deoxygenated Hb binds H+ more actively than oxyhemoglobin. Facilitates O2 unloading in metabolically active (acidic) tissues.

### Myoglobin
- Iron-containing pigment in skeletal muscle
- Binds 1 mol O2 per mole (hyperbolic dissociation curve)
- Curve is to the left of Hb curve → picks up O2 from Hb
- Releases O2 only at very low PO2 (exercising muscles)
- Facilitates O2 diffusion from blood to mitochondria

---

## c-resp-011

Venous blood contains ~52.7 mL CO2/100 mL. Body produces ~200 mL CO2/min.

### Three Forms of Transport
1. **Dissolved CO2** (10%): Proportional to PCO2 in plasma
2. **Carbamino compounds** (30%): CO2 reversibly binds Hb — R-NH2 + CO2 ⇌ R-COO- + H+. Deoxygenated Hb carries more CO2 (Haldane effect)
3. **Bicarbonate (HCO3-)** (60%): Major form. CO2 + H2O → H2CO3 → H+ + HCO3- (catalyzed by carbonic anhydrase inside RBCs, absent in plasma)

### Chloride Shift
- ~70% of HCO3- produced in RBCs leaves in exchange for Cl- ions
- Mediated by membrane protein Band 3
- Maintains electrical neutrality across RBC membrane

### In the Alveoli (Reversal)
- High PO2 causes O2 to replace CO2 on Hb (Haldane effect)
- Reverse reactions occur: HCO3- re-enters RBC, converts back to CO2
- CO2 diffuses down gradient into alveolar sacs

### Haldane Effect
Deoxygenation shifts the CO2 dissociation curve upward — deoxygenated Hb carries more CO2 than oxygenated Hb. In tissues: Hb gives up O2 → picks up more CO2. In lungs: Hb picks up O2 → releases CO2.

---

## c-resp-015

- CO binds Hb ~210× more strongly than O2
- Forms carboxyhemoglobin (COHb)
- Displaces O2 from Hb → CO poisoning
- Sources: Smoke inhalation, suicide attempts, smog, cigarette smoking
- Normal COHb in nonsmokers: ≤1.5%
- Treatment: Hyperbaric oxygen (100% O2 at 2-3 atmospheres)

---

## c-resp-016

The nervous system maintains adequate O2, CO2, and pH via a **negative feedback system**.

### Components
- **Sensors**: Chemoreceptors, lung stretch receptors
- **Central controller**: Brainstem (pons, medulla)
- **Effectors**: Respiratory muscles

### Neural Control
1. **Voluntary control**: Cerebral cortex → corticospinal tract → respiratory motor neurons (e.g., breath-holding)
2. **Automatic control**: Medulla oblongata and pons

### Medullary Respiratory Centers

**Dorsal Respiratory Group (DRG):**
- Located in nucleus tractus solitarius (NTS)
- Sensory termination of IX and X cranial nerves
- Contains inspiratory neurons
- Generates basic respiratory rhythm
- Impulses to inspiratory muscles delivered in ramp fashion (not instantaneous)
- Inspiration time > expiration time

**Ramp Mechanism:**
- Ramp increases rapidly → lungs fill rapidly
- Earlier ramp cessation → shorter inspiration → increased respiration rate
- Off-switch abruptly decreases firing rate → end of inspiration

**Ventral Respiratory Group (VRG):**
- Cranial division: Nucleus ambiguus
- Caudal division: Nucleus retroambigualis
- Drives spinal respiratory motorneurons (intercostals, abdominals)
- Drives auxiliary muscles innervated by vagus

### Pontine Respiratory Centers

**Pneumotaxic Center** (upper pons, nucleus parabrachialis):
- Prevents apneusis (arrest at inspiration)
- Increases respiration rate
- Makes medullary discharge smooth and regular

**Apneustic Center** (lower pons):
- Tonic activity → causes apneusis
- Inhibited by pneumotaxic center

### Peripheral Chemoreceptors

**Carotid Bodies:**
- Located at bifurcation of common carotid artery
- Afferent via carotid sinus nerve (IX cranial nerve)
- Blood flow: ~2000 mL/min/100g tissue
- Stimulated by: ↓ arterial PO2, ↓ O2 delivery per unit time, cyanide, nicotine, lobeline
- NOT stimulated by anemia or CO poisoning (dissolved O2 normal)

**Aortic Bodies:**
- Located at arch of aorta
- Afferent via aortic nerves (X cranial nerve)
- Similar histology to carotid bodies

**Cell Types:**
- Type I (glomus) cells: Epithelioid, 10-15 μm, contain dense core vesicles with dopamine, noradrenaline, ACh, ATP, ions
- Type II (sustentacular) cells: Surround Type I cells

**Stimulants:** ↓ PaO2, ↑ PaCO2, ↓ pH

### Central Chemoreceptors (Chemosensitive Areas of Medulla)

- Specialized cells on ventrolateral surface of medulla
- Sensitive to ECF changes (via CSF)
- CSF is protein-free, secreted by choroid plexus
- Blood-brain barrier separates blood from CSF (low ionic permeability)
- CO2 diffuses rapidly across BBB → PCO2 in CSF parallels arterial PCO2
- CO2 + H2O → H2CO3 → HCO3- + H+ → H+ stimulates chemoreceptors
- Stimulatory effect greatest in first few hours, declines over 1-2 days as renal readjustment of H+ occurs

**Stimulants:** ↓ PO2, ↑ PCO2, ↓ pH

### Factors Affecting Respiratory Center
**Stimulatory (+):** ↑ PCO2, ↓ pH, ↓ PO2, peripheral chemoreceptors, central chemoreceptors, proprioceptors, baroreceptors, pain, temperature, irritant receptors, cortex, stretch receptors

**Inhibitory (-):** Anaesthesia

---

## c-resp-023

Oxygen deficiency at tissue level.

### Types

**Hypoxic Hypoxia:**
- ↓ PO2 in inspired air (high altitude, oxygen-poor gas)
- Hypoventilation (airway obstruction, respiratory muscle paralysis, drugs like morphine, ↑ airway resistance in asthma/emphysema)
- Alveolar-capillary diffusion block (pulmonary fibrosis, pneumonia)
- Abnormal V/Q ratio (emphysema, cyanotic congenital heart disease)

**Anemic Hypoxia:**
- Arterial PO2 is normal
- Reduced Hb available to carry O2
- Seen in CO poisoning (CO displaces O2 from Hb)

**Stagnant Hypoxia:**
- Slow blood flow to tissues despite normal PO2 and Hb
- Adequate O2 not delivered
- Seen in congestive heart failure

**Histotoxic Hypoxia:**
- Adequate O2 delivered to tissue
- Tissue cannot use O2 due to toxic agent
- Seen in cyanide poisoning (inhibits cytochrome oxidase)
- Cyanide found in poorly prepared cassava

---

## c-resp-028

Retention of CO2 in the body. Occurs when CO2 formation > removal.

### Effects
- ↑ PCO2 → respiratory acidosis
- Excretion of large amounts of bicarbonate
- CNS depression, confusion, diminished sensory acuity, coma, respiratory depression
- In asphyxia/drowning: Both hypoxia and hypercapnea present → ↑ respiration, BP, HR, catecholamines, ↓ pH → eventually cardiac arrest

---

## c-resp-029

### Pressure Changes
- Ambient pressure increases 1 ATM per 10 m depth in seawater (every 10.4 m in fresh water)
- SCUBA gear reduces hazards

### Problems of Increased Barometric Pressure
- O2 toxicity, lung damage, convulsions
- N2 narcosis
- Euphoria, impaired performance, tremors, somnolence

### Decompression Sickness
- Related to ascent rate
- Rapid ascent → N2 escapes from solution → bubbles form in tissues and blood
- Symptoms: Joint pain, itching, arterial obstruction in brain (paralysis, respiratory failure)
- Prevention: Slow ascent, substitute He for N2 (He is ½ as soluble as N2, 1/7 molecular weight → diffuses out faster)

---

## c-resp-031

### Effects of Reduced Barometric Pressure
- ↓ PO2 → hypoxic stimulation of chemoreceptors
- ↑ Ventilation → ↓ alveolar and arterial PCO2 → respiratory alkalosis
- At 12,000 ft unacclimatized: Drowsiness, lassitude, fatigue, headache, nausea, euphoria

### Altitude Reference
| Altitude (ft) | Barometric Pressure (mmHg) | PO2 in Air (mmHg) |
|--------------|---------------------------|-------------------|
| 0 | 760 | 159 |
| 10,000 | 523 | 110 |
| 20,000 | 349 | 73 |
| 30,000 | 226 | 47 |
| 40,000 | 141 | 29 |
| 50,000 | 87 | 18 |

At 18,000-23,000 ft: Twitchings/seizures, coma, death.

### Acclimatization Mechanisms
- ↑ 2,3-DPG → ↑ O2 delivery to tissues
- ↑ Erythropoietin secretion
- ↑ Mitochondria
- ↑ Myoglobin
- ↑ Tissue cytochrome oxidase

### Natural Acclimatization (Highlanders)
Living at 13,000-17,500 ft, working at 19,000 ft (Peruvian Andes, Himalayas):
- Greatly increased chest size
- Slightly decreased body size → high ventilatory capacity-to-body mass ratio
- Larger hearts → increased cardiac output
- Better O2 delivery to tissues

### Work Capacity at 17,000 ft
| Status | Work Capacity (% normal) |
|--------|------------------------|
| Unacclimatized | 50% |
| Acclimatized 2 months | 68% |
| Native at 13,200 ft working at 17,000 ft | 87% |

### Acute Mountain Sickness
- Develops 8-24 hours after arrival at altitude, lasts 4-8 days
- Headache, nausea/vomiting, irritability, insomnia, breathlessness, decreased mental proficiency
- Can cause pulmonary edema and cerebral edema (cerebral edema from hypoxic vasodilation)
- Treatment: O2, rest, slow ascent, avoid exertion

### Chronic Mountain Sickness
- Remaining at high altitude too long
- ↑↑ Red cell mass and hematocrit → ↑ blood viscosity → ↓ tissue blood flow → ↓ O2 delivery
- ↑ Pulmonary arterial pressure → right heart enlargement → peripheral BP falls → congestive heart failure
- Often fatal if not removed to lower altitude (most recover within days/weeks)

---

## c-resp-034

### Ventilation Changes
- **Abrupt increase** at onset of exercise (psychic stimuli, proprioceptors in muscles/tendons/joints)
- **Gradual increase** (humoral: ↑ H+, ↑ temperature, ↑ CO2 sensitivity, ↑ K+)
- **Abrupt decrease** at cessation (does not reach baseline immediately — O2 debt)
- During moderate exercise: ↑ tidal volume (depth) and respiratory rate

### Tissue Changes During Exercise
- Capillary beds dilate; previously closed capillaries open
- ↓ Mean distance from blood to tissues → facilitates O2 movement
- Contracting muscle uses O2 → tissue PO2 falls to nearly zero
- More O2 diffuses from blood → blood PO2 drops → more O2 dissociates from Hb
- ↑ Temperature and ↑ 2,3-DPG → right shift of dissociation curve → enhanced unloading

### O2 Debt
- Accumulated H+ must be removed before ventilation returns to baseline

### Fatigue
Poorly understood phenomenon. Possible mechanisms:
- Acidosis on brain
- Muscle ischemia during prolonged contractions
- Accumulation of Substance P (stimulates pain receptors)
- Accumulation of interstitial fluid in muscles during exertion

---

## c-resp-036

### Concept
Relationship between airflow to alveoli (ventilation, V) and blood flow in surrounding capillaries (perfusion, Q).

- V = ventilation = ~4 L/min at rest
- Q = perfusion = cardiac output = ~5 L/min
- **Optimal V/Q ≈ 1.0** (well-matched for efficient gas exchange)
- **Average V/Q ≈ 0.8** (4/5) — more ventilation in upper lung; more perfusion in lower lung

### Pulmonary Circulation Characteristics
- Output same as systemic: 5 L/min
- Low resistance bed: 25/10 mmHg
- Low capillary pressure: 10 mmHg (prevents alveolar fluid exudation)
- Distensible vessels (virtually no muscle coat)
- Reservoir function: Contains ~1 L blood

### Regulation
- **Hypoxia** → hypoxic pulmonary vasoconstriction
- **Hypercapnea / ↓ pH** → pulmonary vasoconstriction
- **Constrict**: Adrenaline, noradrenaline, angiotensin II, thromboxanes, PGF2α
- **Vasodilate**: ACh, isoprenaline, PGI2
- Baroreceptor stimulation → slight vasodilation
- Chemoreceptor stimulation → vasoconstriction

### V/Q Mismatch

**Low V/Q (< 0.8) — Shunt:**
- Ventilation reduced, perfusion continues
- Deoxygenated blood passes through lungs without O2 pickup
- Causes: Pneumonia, asthma, mucous plugs, atelectasis (alveolar collapse)

**High V/Q (> 0.8) — Dead Space:**
- Ventilation normal, but blood flow blocked
- Air enters alveoli but no blood to absorb O2
- Causes: Pulmonary embolism, emphysema

### Clinical Conditions
| Condition | V/Q | Mechanism |
|-----------|-----|-----------|
| Pulmonary embolism | High | Blood clot blocks perfusion → ventilated but unperfused alveoli |
| Pneumonia | Low | Fluid/inflammation impairs ventilation → perfused but unventilated |
| COPD | Variable | Chronic airway obstruction → some regions over-perfused |
| Asthma | Low | Bronchoconstriction → reduced airflow, normal blood flow |
