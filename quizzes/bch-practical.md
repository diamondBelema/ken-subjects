---
format_version: 1
type: quiz_set
set: BCH Practical
questions:
  # ── PROTEINURIA ──
  - id: bch-q-001
    type: mcq
    question: "In the heat coagulation test, what is the purpose of adding 5% acetic acid?"
    options:
      - "To denature the protein further"
      - "To dissolve phosphate precipitates (false positives)"
      - "To increase the temperature of the solution"
      - "To neutralize the alkaline pH"
    answer: 1
    explanation: "Acetic acid dissolves phosphate precipitates (which form false positives on heating) while protein precipitates persist. This distinguishes true proteinuria from phosphate interference."
    concept_id: bch-proteinuria
    tags: [proteinuria]
  - id: bch-q-002
    type: mcq
    question: "Which protein is most sensitively detected by the heat coagulation test?"
    options:
      - "Globulin"
      - "Bence Jones protein"
      - "Albumin"
      - "Fibrinogen"
    answer: 2
    explanation: "Albumin coagulates rapidly upon heating and is the most abundant protein in pathological urine, making it the most sensitively detected by this test."
    concept_id: bch-proteinuria
    tags: [proteinuria]
  - id: bch-q-003
    type: mcq
    question: "A urine sample shows turbidity after heating that disappears after adding acetic acid. What does this indicate?"
    options:
      - "Positive for proteinuria"
      - "False positive from phosphate precipitate"
      - "The urine contains albumin"
      - "The patient has nephrotic syndrome"
    answer: 1
    explanation: "Turbidity that dissolves in acid is phosphate precipitate, not protein. This is a false positive that is correctly identified by the acid step."
    concept_id: bch-proteinuria
    tags: [proteinuria]

  # ── CHROMATOGRAPHY ──
  - id: bch-q-004
    type: mcq
    question: "In paper chromatography, what is the stationary phase?"
    options:
      - "The cellulose paper itself"
      - "The water adsorbed within cellulose fibres"
      - "The organic solvent"
      - "The glass jar"
    answer: 1
    explanation: "The stationary phase is the thin layer of water trapped within the cellulose fibres. The paper supports it, but partition occurs in the water."
    concept_id: bch-chromatography
    tags: [chromatography]
  - id: bch-q-005
    type: mcq
    question: "Why do polar amino acids travel slower in paper chromatography?"
    options:
      - "They are heavier than non-polar amino acids"
      - "They interact more strongly with the polar stationary water phase"
      - "They react with the paper"
      - "They are broken down by the solvent"
    answer: 1
    explanation: "Polar amino acids interact more strongly with the polar stationary phase (water in cellulose) and thus spend more time in the stationary phase, travelling slower."
    concept_id: bch-chromatography
    tags: [chromatography]
  - id: bch-q-006
    type: mcq
    question: "What colour does ninhydrin produce with most amino acids?"
    options:
      - "Yellow"
      - "Red"
      - "Blue-violet (Ruhemann's Purple)"
      - "Green"
    answer: 2
    explanation: "Ninhydrin reacts with primary amino groups to produce Ruhemann's Purple (blue-violet). Proline and hydroxyproline are exceptions (yellow)."
    concept_id: bch-chromatography
    tags: [chromatography]
  - id: bch-q-007
    type: mcq
    question: "Why is pencil used instead of pen to mark the origin line?"
    options:
      - "Pencil marks are easier to see"
      - "Pen ink is toxic"
      - "Pencil graphite is insoluble in the solvent and will not interfere"
      - "Pen marks fade during heating"
    answer: 2
    explanation: "Pencil contains graphite, which is insoluble in the solvent. Pen ink dissolves in the solvent, producing extra spots that interfere with separation."
    concept_id: bch-chromatography
    tags: [chromatography]

  # ── SERUM UREA ──
  - id: bch-q-008
    type: mcq
    question: "Why is urease used in the serum urea assay?"
    options:
      - "It is the cheapest enzyme available"
      - "It acts on multiple substrates"
      - "It is highly specific for urea"
      - "It works at any temperature"
    answer: 2
    explanation: "Urease is specific to urea, catalyzing only the hydrolysis of urea to ammonia and CO2. This specificity ensures no other serum components interfere."
    concept_id: bch-serum-urea
    tags: [urea]
  - id: bch-q-009
    type: mcq
    question: "What is the purpose of the blank in the serum urea assay?"
    options:
      - "To provide a known concentration for comparison"
      - "To set the spectrophotometer to zero, removing reagent absorbance"
      - "To incubate the enzyme"
      - "To dilute the sample"
    answer: 1
    explanation: "The blank contains everything except urea. It zeros the spectrophotometer, removing absorbance from reagents so only urea-derived color is measured."
    concept_id: bch-serum-urea
    tags: [urea]
  - id: bch-q-010
    type: mcq
    question: "A patient has very low serum urea. Which condition explains this?"
    options:
      - "Kidney failure"
      - "Dehydration"
      - "Severe liver disease"
      - "High-protein diet"
    answer: 2
    explanation: "The liver synthesizes urea via the urea cycle. Severe liver disease reduces urea production, causing low serum urea. Kidney failure and dehydration cause high urea."
    concept_id: bch-serum-urea
    tags: [urea]
  - id: bch-q-011
    type: mcq
    question: "At what wavelength is the indophenol blue color measured in the urea assay?"
    options:
      - "405 nm"
      - "500 nm"
      - "578 nm"
      - "700 nm"
    answer: 2
    explanation: "The indophenol blue color from the Berthelot reaction is measured at 578 nm in the serum urea assay."
    concept_id: bch-serum-urea
    tags: [urea]

  # ── ELECTROLYTES ──
  - id: bch-q-012
    type: mcq
    question: "Why does potassium determination produce turbidity rather than a true color?"
    options:
      - "Potassium is colourless"
      - "It forms a colloidal suspension with tetraphenylborate"
      - "The reagent is expired"
      - "The wavelength is wrong"
    answer: 1
    explanation: "Potassium reacts with tetraphenylborate to form a fine colloidal suspension (turbid emulsion). The spectrophotometer measures light scattered by these particles, not true color."
    concept_id: bch-electrolytes
    tags: [electrolytes]
  - id: bch-q-013
    type: mcq
    question: "What is the normal range for serum potassium?"
    options:
      - "135-145 mmol/L"
      - "3.5-5.0 mmol/L"
      - "98-106 mmol/L"
      - "2.5-7.1 mmol/L"
    answer: 1
    explanation: "Normal serum potassium is 3.5-5.0 mmol/L. Sodium is 135-145, chloride is 98-106, and urea is 2.5-7.1 mmol/L."
    concept_id: bch-electrolytes
    tags: [electrolytes]
  - id: bch-q-014
    type: mcq
    question: "In the chloride determination, what does chloride displace from mercuric thiocyanate?"
    options:
      - "Chloride ions"
      - "Thiocyanate (SCN-)"
      - "Ferric ions"
      - "Mercury ions"
    answer: 1
    explanation: "Chloride displaces thiocyanate (SCN-) from mercuric thiocyanate [Hg(SCN)2], forming HgCl2. The free SCN- then reacts with Fe3+ to produce the red ferric thiocyanate color."
    concept_id: bch-electrolytes
    tags: [electrolytes]
  - id: bch-q-015
    type: mcq
    question: "Why is hyperkalemia considered a medical emergency?"
    options:
      - "It causes kidney stones"
      - "It can cause fatal cardiac arrhythmias"
      - "It damages the liver"
      - "It causes bone fractures"
    answer: 1
    explanation: "Potassium is crucial for cardiac muscle contraction. Hyperkalemia can cause ventricular fibrillation and cardiac arrest."
    concept_id: bch-electrolytes
    tags: [electrolytes]
  - id: bch-q-016
    type: mcq
    question: "At what wavelength is sodium measured?"
    options:
      - "500 nm"
      - "578 nm"
      - "630 nm"
      - "700 nm"
    answer: 2
    explanation: "Sodium is measured at 630 nm, potassium at 578 nm, and chloride at 500 nm."
    concept_id: bch-electrolytes
    tags: [electrolytes]
  - id: bch-q-016b
    type: mcq
    question: "Why is sodium called the major extracellular cation?"
    options:
      - "It is the most abundant positively charged ion outside cells"
      - "It is the most abundant ion inside cells"
      - "It is only found in blood"
      - "It is produced by the kidneys"
    answer: 0
    explanation: "Sodium is the most abundant positively charged ion in extracellular fluid. It maintains extracellular osmotic pressure, fluid balance, and membrane potential."
    concept_id: bch-electrolytes
    tags: [electrolytes, sodium]
  - id: bch-q-016c
    type: mcq
    question: "Why does hypernatremia cause brain cells to shrink?"
    options:
      - "Sodium enters brain cells and pulls water in"
      - "High extracellular sodium makes the fluid hypertonic, drawing water out of brain cells"
      - "Sodium destroys brain cell membranes"
      - "Brain cells cannot tolerate any sodium"
    answer: 1
    explanation: "High Na+ outside cells makes extracellular fluid hypertonic. Water moves out of brain cells by osmosis, causing them to shrink."
    concept_id: bch-electrolytes
    tags: [electrolytes, sodium, clinical]
  - id: bch-q-016d
    type: mcq
    question: "Why can SIADH cause hyponatremia?"
    options:
      - "SIADH causes sodium loss in urine"
      - "Too much ADH causes water retention, which dilutes serum sodium"
      - "SIADH destroys sodium channels"
      - "SIADH increases potassium, which lowers sodium"
    answer: 1
    explanation: "In SIADH, too much ADH causes the kidney to retain too much water. This water dilutes the sodium in blood, so serum sodium concentration falls."
    concept_id: bch-electrolytes
    tags: [electrolytes, sodium, SIADH]
  - id: bch-q-016e
    type: mcq
    question: "Potassium estimation is an example of which type of method?"
    options:
      - "Colorimetric"
      - "Turbidimetric"
      - "Gravimetric"
      - "Titrimetric"
    answer: 1
    explanation: "Potassium estimation is turbidimetric — it forms a cloudy suspension (turbidity) with tetraphenylborate, and the spectrophotometer measures light scattered by the particles."
    concept_id: bch-electrolytes
    tags: [electrolytes, potassium, method]
  - id: bch-q-016f
    type: mcq
    question: "Why does kidney failure cause hyperkalemia?"
    options:
      - "Kidneys produce too much potassium"
      - "Kidneys cannot excrete potassium effectively, so it accumulates"
      - "Potassium is absorbed from the gut in kidney failure"
      - "Potassium moves from blood into cells"
    answer: 1
    explanation: "The kidneys are the main route of potassium excretion. In kidney failure, potassium cannot be excreted, so it accumulates in the blood."
    concept_id: bch-electrolytes
    tags: [electrolytes, potassium, clinical]
  - id: bch-q-016g
    type: mcq
    question: "What is the normal serum magnesium range?"
    options:
      - "3.5-5.0 mmol/L"
      - "97-108 mmol/L"
      - "1.5-2.4 mmol/L"
      - "135-145 mmol/L"
    answer: 2
    explanation: "Normal serum magnesium is 1.5-2.4 mmol/L. Magnesium is important for enzyme activity, neuromuscular function, and ATP reactions."
    concept_id: bch-electrolytes
    tags: [electrolytes, magnesium, normal-values]
  - id: bch-q-016h
    type: mcq
    question: "Give three causes of hyponatremia."
    options:
      - "Dehydration, diabetes insipidus, excess sweating"
      - "Vomiting, diuretics, SIADH"
      - "High protein diet, liver disease, gout"
      - "Renal failure, burns, trauma"
    answer: 1
    explanation: "Hyponatremia is caused by sodium loss (vomiting, diarrhea), diuretics (increased renal loss), or water retention (SIADH dilutes sodium)."
    concept_id: bch-electrolytes
    tags: [electrolytes, sodium, clinical]

  # ── CREATININE ──
  - id: bch-q-017
    type: mcq
    question: "What is the principle of the Jaffe reaction?"
    options:
      - "Creatinine reduces phosphotungstic acid"
      - "Creatinine reacts with alkaline picrate to form an orange-red complex"
      - "Creatinine binds to a dye"
      - "Creatinine is oxidized by glucose oxidase"
    answer: 1
    explanation: "In the Jaffe reaction, creatinine reacts with alkaline picrate (picric acid + NaOH) to form an orange-red creatinine-picrate complex."
    concept_id: bch-creatinine
    tags: [creatinine]
  - id: bch-q-018
    type: mcq
    question: "Why is creatinine used as a marker of kidney function?"
    options:
      - "It is produced by the liver"
      - "It is freely filtered by the glomerulus and not reabsorbed"
      - "It is only found in urine"
      - "It is produced by the kidneys"
    answer: 1
    explanation: "Creatinine is freely filtered by the glomerulus and not reabsorbed. Its blood level directly reflects glomerular filtration rate (GFR)."
    concept_id: bch-creatinine
    tags: [creatinine]
  - id: bch-q-019
    type: mcq
    question: "At what wavelength is the creatinine-picrate complex measured?"
    options:
      - "405 nm"
      - "500-520 nm"
      - "578 nm"
      - "630 nm"
    answer: 1
    explanation: "The orange-red creatinine-picrate complex from the Jaffe reaction is measured at 500-520 nm."
    concept_id: bch-creatinine
    tags: [creatinine]
  - id: bch-q-019b
    type: mcq
    question: "Why is creatinine considered a better indicator of kidney function than urea?"
    options:
      - "Creatinine is produced by the liver"
      - "Creatinine production is more constant and less influenced by diet"
      - "Creatinine is reabsorbed by the tubules"
      - "Urea is not filtered by the glomerulus"
    answer: 1
    explanation: "Creatinine production depends mainly on muscle mass and is relatively constant. Urea is affected by protein intake, hydration, and liver function, making creatinine a more reliable marker of GFR."
    concept_id: bch-creatinine
    tags: [creatinine, comparison, viva]
  - id: bch-q-019c
    type: mcq
    question: "What is the precursor of creatinine?"
    options:
      - "Uric acid"
      - "Creatine phosphate"
      - "Amino acids"
      - "Glucose"
    answer: 1
    explanation: "Creatinine is the waste product of creatine phosphate metabolism in skeletal muscle. The pathway: Creatine phosphate -> Creatinine -> Blood -> Kidney filtration -> Urine."
    concept_id: bch-creatinine
    tags: [creatinine, metabolism, trap]
  - id: bch-q-019d
    type: mcq
    question: "A patient has high serum creatinine. Give three possible causes."
    options:
      - "Liver disease, malnutrition, dehydration"
      - "Renal failure, glomerulonephritis, urinary obstruction"
      - "High protein diet, exercise, muscle hypertrophy"
      - "Diabetes, hypertension, gout"
    answer: 1
    explanation: "High creatinine indicates reduced kidney filtration: renal failure (kidneys cannot excrete creatinine), glomerulonephritis (inflammation damages filtration), and urinary obstruction (backup of waste products)."
    concept_id: bch-creatinine
    tags: [creatinine, clinical]

  # ── ALBUMIN ──
  - id: bch-q-020
    type: mcq
    question: "Why is albumin the most clinically relevant protein measured by dye binding?"
    options:
      - "It is the smallest protein"
      - "It has the strongest dye-binding capacity among serum proteins"
      - "It is the most abundant protein in blood"
      - "It is the only protein that binds dye"
    answer: 1
    explanation: "Albumin has the strongest dye-binding capacity among serum proteins, making the dye binding method relatively specific for albumin."
    concept_id: bch-albumin
    tags: [albumin]
  - id: bch-q-021
    type: mcq
    question: "A patient has low serum albumin and peripheral edema. What is the most likely explanation?"
    options:
      - "The patient is dehydrated"
      - "Low albumin reduces oncotic pressure, causing fluid to shift into tissues"
      - "The patient has high blood pressure"
      - "The kidneys are retaining water"
    answer: 1
    explanation: "Albumin maintains plasma oncotic pressure. Low albumin leads to reduced oncotic pressure, causing fluid to shift from blood vessels into tissues, resulting in edema."
    concept_id: bch-albumin
    tags: [albumin]

  # ── OGTT & GLUCOSE ──
  - id: bch-q-022
    type: mcq
    question: "Why is glucose oxidase preferred over non-enzymatic methods for blood glucose?"
    options:
      - "It is cheaper"
      - "It is specific for beta-D-glucose and does not react with other sugars"
      - "It works faster"
      - "It requires no spectrophotometer"
    answer: 1
    explanation: "Glucose oxidase is specific for beta-D-glucose. It does not react with fructose, galactose, or other sugars, making it the clinical gold standard."
    concept_id: bch-ogtt
    tags: [glucose]
  - id: bch-q-023
    type: mcq
    question: "What fasting glucose level indicates diabetes?"
    options:
      - ">= 5.6 mmol/L"
      - ">= 7.0 mmol/L"
      - ">= 11.1 mmol/L"
      - ">= 3.5 mmol/L"
    answer: 1
    explanation: "Fasting glucose >= 7.0 mmol/L indicates diabetes. < 5.6 is normal, 5.6-6.9 is impaired fasting glucose, and >= 11.1 at 2 hours also confirms diabetes."
    concept_id: bch-ogtt
    tags: [glucose]
  - id: bch-q-024
    type: mcq
    question: "In the glucose oxidase method, what produces the pink/rose-pink color?"
    options:
      - "Glucose directly"
      - "H2O2 reacting with a chromogen via peroxidase"
      - "The enzyme glucose oxidase"
      - "Uric acid reduction"
    answer: 1
    explanation: "Glucose oxidase produces H2O2, which reacts with a chromogen via peroxidase to form quinoneimine (pink/rose-pink color)."
    concept_id: bch-ogtt
    tags: [glucose]

  # ── URIC ACID ──
  - id: bch-q-025
    type: mcq
    question: "What is the principle of uric acid determination?"
    options:
      - "Uric acid binds to a dye"
      - "Uric acid reduces phosphotungstic acid to tungsten blue"
      - "Uric acid reacts with alkaline picrate"
      - "Uric acid is oxidized by glucose oxidase"
    answer: 1
    explanation: "Uric acid reduces phosphotungstic acid in an alkaline medium to produce tungsten blue (blue color), measured at 700 nm."
    concept_id: bch-uric-acid
    tags: [uric-acid]
  - id: bch-q-026
    type: mcq
    question: "What is uric acid the end product of?"
    options:
      - "Protein metabolism"
      - "Purine metabolism"
      - "Lipid metabolism"
      - "Carbohydrate metabolism"
    answer: 1
    explanation: "Uric acid is the end product of purine metabolism (adenine, guanine) in humans. It is produced in the liver and excreted by the kidneys."
    concept_id: bch-uric-acid
    tags: [uric-acid]
  - id: bch-q-027
    type: mcq
    question: "Which condition is associated with hyperuricemia?"
    options:
      - "Liver disease"
      - "Gout"
      - "Malnutrition"
      - "SIADH"
    answer: 1
    explanation: "Hyperuricemia causes gout, where monosodium urate crystals deposit in joints and soft tissues, causing inflammation and severe pain."
    concept_id: bch-uric-acid
    tags: [uric-acid]

  # ── TRANSAMINATION ──
  - id: bch-q-028
    type: mcq
    question: "What is the coenzyme required for transamination reactions?"
    options:
      - "NAD+"
      - "FAD"
      - "Pyridoxal phosphate (PLP / vitamin B6)"
      - "Coenzyme A"
    answer: 2
    explanation: "PLP (active form of vitamin B6) is the required coenzyme for all aminotransferases. It acts as an intermediate carrier of the amino group."
    concept_id: bch-transamination
    tags: [transamination]
  - id: bch-q-029
    type: mcq
    question: "Write the transamination reaction catalyzed by ALT."
    options:
      - "Glucose -> Pyruvate"
      - "Alanine + alpha-ketoglutarate -> Pyruvate + Glutamate"
      - "Urea -> Ammonia"
      - "Uric acid -> Allantoin"
    answer: 1
    explanation: "ALT catalyzes: Alanine + alpha-ketoglutarate -> Pyruvate + Glutamate. It transfers the amino group from alanine to alpha-ketoglutarate."
    concept_id: bch-transamination
    tags: [transamination]
  - id: bch-q-030
    type: mcq
    question: "Which enzyme is a specific marker for liver damage?"
    options:
      - "AST"
      - "ALT"
      - "ALP"
      - "LDH"
    answer: 1
    explanation: "ALT (alanine aminotransferase) is liver-specific and is the most specific marker for hepatocellular injury. AST is found in liver, heart, and muscle."
    concept_id: bch-transamination
    tags: [transamination]
