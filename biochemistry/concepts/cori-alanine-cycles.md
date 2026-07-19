---
format_version: 1
type: concept_set
set: Cori & Alanine Cycles
concepts:
  # ── CORI CYCLE ──
  - id: c-cori-cycle
    name: Cori Cycle
    parent_id: null
  - id: c-cori-muscle-component
    name: Muscle Component of Cori Cycle
    parent_id: c-cori-cycle
  - id: c-cori-liver-component
    name: Liver Component of Cori Cycle
    parent_id: c-cori-cycle
  - id: c-cori-tissues
    name: Tissues Participating in Cori Cycle
    parent_id: c-cori-cycle
  - id: c-cori-significance
    name: Significance of the Cori Cycle
    parent_id: c-cori-cycle

  # ── ALANINE CYCLE ──
  - id: c-alanine-cycle
    name: Alanine Cycle (Glucose–Alanine Cycle)
    parent_id: null
  - id: c-alanine-muscle-component
    name: Muscle Component of Alanine Cycle
    parent_id: c-alanine-cycle
  - id: c-alanine-liver-component
    name: Liver Component of Alanine Cycle
    parent_id: c-alanine-cycle
  - id: c-alanine-transamination
    name: Transamination in Alanine Cycle
    parent_id: c-alanine-cycle

  # ── GLUCONEOGENESIS ──
  - id: c-gluconeogenesis
    name: Gluconeogenesis
    parent_id: null
  - id: c-gluconeogenesis-precursors
    name: Gluconeogenic Precursors
    parent_id: c-gluconeogenesis
  - id: c-bypass-pyruvate-to-pep
    name: "Bypass 1: Pyruvate → PEP"
    parent_id: c-gluconeogenesis
  - id: c-bypass-f16bp-to-f6p
    name: "Bypass 2: Fructose-1,6-bisphosphate → Fructose-6-phosphate"
    parent_id: c-gluconeogenesis
  - id: c-bypass-g6p-to-glucose
    name: "Bypass 3: Glucose-6-phosphate → Glucose"
    parent_id: c-gluconeogenesis
  - id: c-pyruvate-carboxylase
    name: Pyruvate Carboxylase
    parent_id: c-bypass-pyruvate-to-pep
  - id: c-pepck
    name: PEP Carboxykinase (PEPCK)
    parent_id: c-bypass-pyruvate-to-pep
  - id: c-fructose-1-6-bisphosphatase
    name: Fructose-1,6-bisphosphatase
    parent_id: c-bypass-f16bp-to-f6p
  - id: c-glucose-6-phosphatase
    name: Glucose-6-phosphatase
    parent_id: c-bypass-g6p-to-glucose
  - id: c-gluconeogenesis-regulation
    name: Regulation of Gluconeogenesis
    parent_id: c-gluconeogenesis
  - id: c-oaa-shuttle
    name: Oxaloacetate Shuttle (Mitochondrial → Cytosolic)
    parent_id: c-bypass-pyruvate-to-pep
---

## c-cori-cycle

A metabolic cycle (discovered by Carl and Gerty Cori) linking anaerobic glycolysis in muscle (and other glycolytic tissues) with gluconeogenesis in the liver. Muscle produces lactate from pyruvate under anaerobic conditions; lactate travels via blood to the liver, where it is converted back to glucose and returned to muscle.

Steps: (1) Muscle converts pyruvate → lactate via lactate dehydrogenase, regenerating NAD⁺. (2) Lactate diffuses into blood → transported to liver. (3) Liver converts lactate → pyruvate (reverse LDH reaction). (4) Liver performs gluconeogenesis: pyruvate → glucose. (5) Glucose released into blood → taken up by muscle. Cycle repeats. This is a net energy-consuming process (muscle gains 2 ATP per glucose; liver spends 6 ATP to regenerate glucose).

## c-cori-muscle-component

In the muscle, pyruvate produced by glycolysis is reduced to lactate by lactate dehydrogenase, regenerating NAD⁺ so glycolysis can continue under anaerobic conditions.

Under intense exercise or low O₂, the rate of pyruvate production by glycolysis exceeds the rate of its oxidation by the TCA cycle. Less than 10% of pyruvate enters the citric acid cycle. Lactate diffuses out of muscle into the bloodstream. Fast-twitch muscle fibres have limited mitochondria, making them particularly dependent on anaerobic glycolysis.

## c-cori-liver-component

The liver takes up lactate from the blood, converts it to pyruvate (via LDH), and channels pyruvate into gluconeogenesis to produce glucose, which is released back into the blood.

The liver has abundant mitochondria and the full complement of gluconeogenic enzymes. Glucose produced is delivered to muscle, RBCs, neurons, and other glucose-dependent tissues. The cycle represents metabolic cooperation between tissues.

## c-cori-tissues

The Cori cycle occurs between liver and all tissues that do not completely oxidise glucose to CO₂ and H₂O. These include: skeletal muscle (especially fast-twitch), mature RBCs, immune cells in lymph nodules, proliferating bone marrow cells, and skin epithelial cells.

These cells continually produce lactate because they either lack mitochondria (RBCs) or have limited mitochondrial capacity. The cycle ensures these tissues can continue to obtain glucose even when their glycolytic output exceeds their oxidative capacity.

## c-cori-significance

The Cori cycle allows glucose-consuming tissues to continue glycolysis under anaerobic conditions while the liver bears the metabolic cost of gluconeogenesis (6 ATP per glucose regenerated vs. 2 ATP gained by muscle).

It prevents lactate accumulation, maintains blood glucose levels, and enables sustained anaerobic glycolysis. Important during intense exercise, fasting, and in conditions of limited oxygen supply.

## c-alanine-cycle

Also called the glucose–alanine cycle. A metabolic cycle between muscle and liver analogous to the Cori cycle, but uses alanine instead of lactate as the transport form of pyruvate. Additionally serves to transport amino nitrogen from muscle to liver.

Muscle: Pyruvate + amino group → Alanine (via transamination). Alanine → blood → liver. Liver: Alanine → Pyruvate (reverse transamination) → gluconeogenesis → Glucose → blood → muscle. The amino group is disposed of in the liver via the urea cycle.

## c-alanine-muscle-component

In muscle, pyruvate is transaminated to alanine by alanine aminotransferase (ALT), using amino groups from amino acids (particularly from protein catabolism or glucogenic amino acid catabolism).

Alanine may also be produced directly from protein breakdown or catabolism of glucogenic amino acids in muscle. The transamination reaction: Pyruvate + Glutamate ⇌ Alanine + α-Ketoglutarate.

## c-alanine-liver-component

The liver takes up alanine, transaminates it back to pyruvate, and channels pyruvate into gluconeogenesis. The amino group is disposed of via the urea cycle.

Reverse transamination: Alanine + α-Ketoglutarate → Pyruvate + Glutamate. The glutamate donates its amino group to the urea cycle for disposal. Glucose produced is returned to muscle via the blood.

## c-alanine-transamination

Transamination is the transfer of an amino group from an amino acid to a keto acid, catalysed by aminotransferases (transaminases) requiring PLP (pyridoxal phosphate, derived from vitamin B₆) as a coenzyme.

In the alanine cycle, alanine aminotransferase (ALT/GPT) converts pyruvate to alanine in muscle and alanine back to pyruvate in liver. This is distinct from the Cori cycle which uses lactate dehydrogenase. The alanine cycle has the additional function of transporting nitrogen safely in a non-toxic form.

## c-gluconeogenesis

The metabolic pathway that synthesises glucose from non-carbohydrate precursors (lactate, amino acids, glycerol, TCA cycle intermediates). Occurs primarily in the liver (and kidney cortex). It is NOT a complete reversal of glycolysis — three irreversible glycolytic steps are bypassed using different enzymes.

Important during fasting, prolonged exercise, and when glycogen stores are depleted. Tissues dependent on glucose: brain, RBCs, exercising muscle, neurons, eyes. Seven of the ten glycolytic steps are reversible and use the same enzymes. Three steps require bypass enzymes.

## c-gluconeogenesis-precursors

Non-carbohydrate precursors for gluconeogenesis include: lactate (from anaerobic glycolysis), glucogenic amino acids (pyruvate, TCA intermediates via catabolism), glycerol (from fat/triglyceride catabolism), and TCA cycle intermediates (must be converted to oxaloacetate).

Amino acid catabolism products: pyruvate, oxaloacetate, or precursors of these. Muscle proteins may break down to supply amino acids. These are transported to the liver where they are deaminated and converted to gluconeogenic precursors. Glycerol enters via glycerol-3-phosphate → DHAP (a glycolytic intermediate).

## c-bypass-pyruvate-to-pep

Bypass 1: Pyruvate → Phosphoenolpyruvate (PEP). The irreversible pyruvate kinase reaction of glycolysis is bypassed by two enzymes: pyruvate carboxylase (mitochondrial) and PEP carboxykinase (PEPCK).

(1) Pyruvate + CO₂ + ATP → Oxaloacetate + ADP + Pi + 2H⁺ (pyruvate carboxylase, requires biotin, mitochondrial matrix). (2) Oxaloacetate + GTP → PEP + CO₂ + GDP (PEPCK). Oxaloacetate must be shuttled from mitochondria to cytosol as malate or aspartate, then reconverted to OAA before conversion to PEP.

## c-bypass-f16bp-to-f6p

Bypass 2: Fructose-1,6-bisphosphate + H₂O → Fructose-6-phosphate + Pi. Catalysed by fructose-1,6-bisphosphatase, bypassing the irreversible PFK-1 reaction of glycolysis.

Fructose-1,6-bisphosphatase is an allosteric enzyme and key regulatory point for gluconeogenesis. Inhibited by AMP and fructose-2,6-bisphosphate; activated by citrate and ATP. The product F6P is easily converted to G6P.

## c-bypass-g6p-to-glucose

Bypass 3: Glucose-6-phosphate + H₂O → Glucose + Pi. Catalysed by glucose-6-phosphatase, bypassing the irreversible hexokinase/glucokinase reaction.

Glucose-6-phosphatase is located in the endoplasmic reticulum membrane (lumen) and is found primarily in liver and kidney. It allows the liver to release free glucose into the blood for maintenance of blood glucose homeostasis. G6P is also a precursor for glycogen synthesis.

## c-pyruvate-carboxylase

Catalyses: Pyruvate + CO₂ + ATP → Oxaloacetate + ADP + Pi. A biotin-requiring enzyme located in the mitochondrial matrix. Fixes CO₂ (biotin is always involved in CO₂ fixation reactions).

This is an anaplerotic reaction. Biotin (vitamin) carries CO₂ as a carboxybiotin intermediate. The reaction requires ATP. OAA produced can then be converted to PEP by PEPCK, or enter the TCA cycle for energy.

## c-pepck

PEP Carboxykinase catalyses: Oxaloacetate + GTP → PEP + CO₂ + GDP. Converts OAA to PEP, consuming GTP (a high-energy compound).

Located in both mitochondria and cytosol (tissue-dependent). The GTP is provided by succinyl-CoA synthetase in the TCA cycle or by nucleoside diphosphate kinase. This completes the bypass of the pyruvate kinase reaction.

## c-fructose-1-6-bisphosphatase

Fructose-1,6-bisphosphatase (FBPase-1): Fructose-1,6-bisphosphate + H₂O → Fructose-6-phosphate + Pi. Key regulatory enzyme of gluconeogenesis.

Allosterically inhibited by AMP and fructose-2,6-bisphosphate (potent inhibitor). Activated by citrate and high energy charge. This enzyme and PFK-1 are reciprocally regulated — when one is active, the other is inhibited.

## c-glucose-6-phosphatase

Glucose-6-phosphatase: Glucose-6-phosphate + H₂O → Glucose + Pi. Final step of gluconeogenesis allowing glucose release into the blood.

Found only in liver and kidney cortex (ER membrane enzyme). RBCs, muscle, and brain lack this enzyme and therefore cannot release free glucose. This explains why muscle glycogen is for local use only (phosphorylated glucose cannot exit the cell).

## c-gluconeogenesis-regulation

Gluconeogenesis is regulated by reciprocal control with glycolysis — when one pathway is active, the other is inhibited. Key regulatory points are the three bypass enzymes.

Fructose-1,6-bisphosphatase is inhibited by AMP and F-2,6-BP. Pyruvate carboxylase is activated by acetyl-CoA. PEPCK and glucose-6-phosphatase are regulated at the transcriptional level (glucagon/cortisol induce; insulin represses). Glucagon raises cAMP → activates PKA → inhibits glycolysis (phosphorylates pyruvate kinase) and activates gluconeogenesis (induces PEPCK, FBPase).

## c-oaa-shuttle

Oxaloacetate cannot cross the inner mitochondrial membrane. It is converted to malate or aspartate, which shuttles to the cytosol, where it is reconverted to oxaloacetate before conversion to PEP.

The malate shuttle also carries reducing equivalents (NADH) to the cytosol, which is important for the energetics of gluconeogenesis. Aspartate is an alternative shuttle route.
