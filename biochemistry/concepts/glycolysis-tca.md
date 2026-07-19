---
format_version: 1
type: concept_set
set: Glycolysis & TCA Cycle
concepts:
  # ── GLYCOLYSIS ──
  - id: c-glycolysis
    name: Glycolysis
    parent_id: null
  - id: c-glycolysis-phases
    name: Energy Investment & Payoff Phases
    parent_id: c-glycolysis
  - id: c-hexokinase
    name: Hexokinase (Step 1)
    parent_id: c-glycolysis
  - id: c-glucose-phosphate-isomerase
    name: Glucose Phosphate Isomerase (Step 2)
    parent_id: c-glycolysis
  - id: c-pfk1
    name: Phosphofructokinase-1 (Step 3)
    parent_id: c-glycolysis
  - id: c-aldolase
    name: Aldolase (Step 4)
    parent_id: c-glycolysis
  - id: c-triose-phosphate-isomerase
    name: Triose Phosphate Isomerase (Step 5)
    parent_id: c-glycolysis
  - id: c-gapdh
    name: Glyceraldehyde-3-Phosphate Dehydrogenase (Step 6)
    parent_id: c-glycolysis
  - id: c-phosphoglycerate-kinase
    name: Phosphoglycerate Kinase (Step 7)
    parent_id: c-glycolysis
  - id: c-phosphoglyceromutase
    name: Phosphoglyceromutase (Step 8)
    parent_id: c-glycolysis
  - id: c-enolase
    name: Enolase (Step 9)
    parent_id: c-glycolysis
  - id: c-pyruvate-kinase
    name: Pyruvate Kinase (Step 10)
    parent_id: c-glycolysis
  - id: c-glycolysis-regulation
    name: Regulation of Glycolysis
    parent_id: c-glycolysis
  - id: c-glycolysis-energy-yield
    name: Glycolysis Energy Yield
    parent_id: c-glycolysis
  - id: c-anaerobic-glycolysis
    name: Anaerobic Glycolysis & Lactate Fermentation
    parent_id: c-glycolysis
  - id: c-substrate-level-phosphorylation
    name: Substrate-Level Phosphorylation
    parent_id: c-glycolysis

  # ── PYRUVATE DECARBOXYLATION ──
  - id: c-pyruvate-decarboxylation
    name: Pyruvate Decarboxylation (Link Reaction)
    parent_id: null
  - id: c-pdh-complex
    name: Pyruvate Dehydrogenase Complex
    parent_id: c-pyruvate-decarboxylation
  - id: c-pdh-e1
    name: E1 — Pyruvate Dehydrogenase
    parent_id: c-pdh-complex
  - id: c-pdh-e2
    name: E2 — Dihydrolipoyl Transacetylase
    parent_id: c-pdh-complex
  - id: c-pdh-e3
    name: E3 — Dihydrolipoyl Dehydrogenase
    parent_id: c-pdh-complex
  - id: c-pdh-cofactors
    name: PDH Complex Cofactors (TPP, Lipoate, CoA, FAD, NAD⁺)
    parent_id: c-pdh-complex

  # ── TCA CYCLE ──
  - id: c-tca-cycle
    name: TCA Cycle (Krebs Cycle / Citric Acid Cycle)
    parent_id: null
  - id: c-tca-citrate-synthase
    name: Step 1 — Citrate Synthase
    parent_id: c-tca-cycle
  - id: c-tca-aconitase
    name: Step 2 — Aconitase
    parent_id: c-tca-cycle
  - id: c-tca-isocitrate-dehydrogenase
    name: Step 3 — Isocitrate Dehydrogenase
    parent_id: c-tca-cycle
  - id: c-tca-alpha-ketoglutarate-dehydrogenase
    name: Step 4 — α-Ketoglutarate Dehydrogenase
    parent_id: c-tca-cycle
  - id: c-tca-succinyl-coa-synthetase
    name: Step 5 — Succinyl-CoA Synthetase
    parent_id: c-tca-cycle
  - id: c-tca-succinate-dehydrogenase
    name: Step 6 — Succinate Dehydrogenase
    parent_id: c-tca-cycle
  - id: c-tca-fumarase
    name: Step 7 — Fumarase
    parent_id: c-tca-cycle
  - id: c-tca-malate-dehydrogenase
    name: Step 8 — Malate Dehydrogenase
    parent_id: c-tca-cycle
  - id: c-tca-regulation
    name: TCA Cycle Regulation
    parent_id: c-tca-cycle
  - id: c-tca-energy-yield
    name: TCA Cycle Energy Yield
    parent_id: c-tca-cycle
  - id: c-tca-amphibolic
    name: Amphibolic Nature of TCA Cycle
    parent_id: c-tca-cycle

  # ── OVERALL ──
  - id: c-glucose-oxidation-yield
    name: Overall Energy Yield from Complete Glucose Oxidation
    parent_id: null
  - id: c-oxidative-phosphorylation
    name: Oxidative Phosphorylation (ETC & ATP Yield)
    parent_id: c-glucose-oxidation-yield
---

## c-glycolysis

An enzyme-catalysed pathway occurring in the cytosol that breaks one molecule of glucose (6C) into two molecules of pyruvate (3C). It is employed by both aerobic and anaerobic cells and yields a net gain of 2 ATP and 2 NADH per glucose. Also called the Embden–Meyerhof pathway.

Glycolysis was elucidated by 1940 (Gustav Embden, Otto Meyerhof, Jacob Parnas). It is divided into two phases: the energy investment phase (steps 1–5) and the energy payoff phase (steps 6–10). All reactions occur in the cytosol.

## c-glycolysis-phases

Glycolysis is divided into Phase I (energy investment / preparatory, steps 1–5) which phosphorylates and cleaves glucose consuming 2 ATP, and Phase II (energy payoff / oxidative, steps 6–10) which converts two GAP molecules to pyruvate generating 4 ATP and 2 NADH.

Net yield: 4 ATP produced − 2 ATP consumed = 2 ATP net. Two NADH are also produced in the payoff phase. The stoichiometry of Phase II is doubled because one 6C glucose yields two 3C triose phosphates.

## c-hexokinase

Catalyses Step 1: Glucose + ATP → Glucose-6-phosphate + ADP. Traps glucose inside the cell since G6P cannot cross the plasma membrane.

Hexokinase has a low Km (high affinity) and is present in all cells. It is inhibited by its product G6P (feedback inhibition). Glucokinase is a liver isoenzyme with a higher Km (lower affinity) that acts when blood glucose is high (postprandial state) and helps maintain blood glucose homeostasis.

## c-glucose-phosphate-isomerase

Catalyses Step 2: Glucose-6-phosphate ⇌ Fructose-6-phosphate. Converts an aldose (glucose) to a ketose (fructose) by converting the C-2 hydroxyl to a ketone.

This is a reversible reaction. The conversion to a ketose at C-2 is necessary for the subsequent phosphorylation at C-1 by PFK-1, which prepares the molecule for symmetrical cleavage into two 3-carbon units.

## c-pfk1

Catalyses Step 3: Fructose-6-phosphate + ATP → Fructose-1,6-bisphosphate + ADP. This is the rate-limiting and committed step of glycolysis. Requires Mg²⁺.

PFK-1 is a tetrameric allosteric enzyme with tissue-specific isoenzymes: L (liver) and M (muscle) subunits that form homotetramers (L₄, M₄) or heterotetramers (M₃L, M₂L₂, ML₃) depending on tissue. Inhibited by ATP and citrate; activated by AMP and fructose-2,6-bisphosphate.

## c-aldolase

Catalyses Step 4: Fructose-1,6-bisphosphate (6C) → Glyceraldehyde-3-phosphate (GAP, 3C) + Dihydroxyacetone phosphate (DHAP, 3C). Aldol cleavage of the 6-carbon sugar into two triose phosphates.

This cleavage reaction splits the six-carbon sugar into two three-carbon fragments. Only GAP continues directly in glycolysis; DHAP must be converted to GAP by triose phosphate isomerase in Step 5.

## c-triose-phosphate-isomerase

Catalyses Step 5: Dihydroxyacetone phosphate (DHAP) ⇌ Glyceraldehyde-3-phosphate (GAP). Ensures both triose phosphates from aldolase can proceed through glycolysis.

Only GAP continues in the oxidative phase. TPI converts DHAP to GAP, so stoichiometrically, each glucose produces two molecules of GAP entering Phase II. This is a near-perfect enzyme (catalytic efficiency near diffusion limit).

## c-gapdh

Catalyses Step 6: Glyceraldehyde-3-phosphate + NAD⁺ + Pi → 1,3-Bisphosphoglycerate + NADH + H⁺. Oxidative phosphorylation of GAP generates a high-energy acyl phosphate.

GAPDH is a tetramer (MW ~145 kDa) requiring NAD⁺ as coenzyme. The product 1,3-BPG has a standard free energy of hydrolysis (−11.8 kcal/mol) higher than ATP (−7.7 kcal/mol), making it capable of driving ATP synthesis. The NADH produced passes electrons to the ETC under aerobic conditions. This is the first oxidation reaction of glycolysis.

## c-phosphoglycerate-kinase

Catalyses Step 7: 1,3-Bisphosphoglycerate + ADP → 3-Phosphoglycerate + ATP. First substrate-level phosphorylation of glycolysis producing ATP.

The high-energy phosphate group of 1,3-BPG is transferred directly to ADP. Since two molecules of GAP enter the payoff phase, two ATP are produced here. This is the first ATP-generating step of glycolysis.

## c-phosphoglyceromutase

Catalyses Step 8: 3-Phosphoglycerate ⇌ 2-Phosphoglycerate. Transfers the phosphate group from C-3 to C-2.

A mutase reaction (intramolecular transfer). This rearrangement positions the phosphate for the subsequent dehydration reaction that creates the high-energy enol phosphate bond in PEP.

## c-enolase

Catalyses Step 9: 2-Phosphoglycerate → Phosphoenolpyruvate (PEP) + H₂O. Dehydration creates a high-energy enol phosphate bond.

Requires Mg²⁺. The product PEP has a free energy of hydrolysis of −14.8 kcal/mol, which is higher than ATP (−7.7 kcal/mol). This dehydration redistributes energy within the molecule, creating the high-energy phosphate transfer potential.

## c-pyruvate-kinase

Catalyses Step 10: Phosphoenolpyruvate + ADP → Pyruvate + ATP. Second substrate-level phosphorylation of glycolysis. Pyruvate is the end product.

Pyruvate kinase is a tetrameric allosteric enzyme and a key regulatory point. It is activated by fructose-1,6-bisphosphate (feedforward activation) and inhibited by ATP and alanine. The liver isoenzyme is also regulated by covalent modification (phosphorylation by PKA inhibits it).

## c-glycolysis-regulation

Glycolysis is regulated at three irreversible steps catalysed by hexokinase, PFK-1, and pyruvate kinase through allosteric effectors, covalent modification, and induction/repression of enzyme synthesis.

Hexokinase: inhibited by G6P (feedback). PFK-1 (rate-limiting): inhibited by ATP, citrate; activated by AMP, F-2,6-BP. Pyruvate kinase: activated by F-1,6-BP (feedforward); inhibited by ATP, alanine. Liver pyruvate kinase is also phosphorylated (inactivated) by glucagon-stimulated PKA. Short-term regulation is allosteric/covalent; long-term is induction/repression.

## c-glycolysis-energy-yield

Per glucose molecule: Aerobic glycolysis yields 2 ATP (net) + 2 NADH (= 8 ATP via ETC at 3 ATP/NADH) = ~8 ATP total. Anaerobic glycolysis yields only 2 ATP (net) because NADH cannot enter ETC and is instead consumed regenerating NAD⁺ for lactate formation.

In RBCs without 2,3-BPG synthesis: 2 ATP net. With 2,3-BPG shunt: 0 ATP net. Aerobic glycolysis net energy: 8 ATP. Anaerobic glycolysis net energy: 2 ATP.

## c-anaerobic-glycolysis

Under anaerobic conditions (no O₂ and/or no mitochondria), pyruvate is reduced to lactate by lactate dehydrogenase, regenerating NAD⁺ so glycolysis can continue. NADH produced cannot be used by ETC for ATP production.

Lactate formation is obligatory — without it all cellular NAD⁺ would be converted to NADH with no means of replenishment, halting glycolysis and causing cell death. Mature RBCs, fast-twitch muscle fibres, immune cells, proliferating bone marrow cells, and skin epithelial cells rely on anaerobic glycolysis. In yeast, pyruvate is decarboxylated to acetaldehyde then reduced to ethanol (alcoholic fermentation).

## c-substrate-level-phosphorylation

Direct transfer of a phosphate group from a high-energy organic substrate to ADP forming ATP, catalysed by a kinase enzyme. Occurs in glycolysis (steps 7 and 10) and TCA cycle (succinyl-CoA synthetase).

Distinct from oxidative phosphorylation which couples ATP synthesis to electron transfer through the ETC. Substrate-level phosphorylation can occur in the cytosol or mitochondria.

## c-pyruvate-decarboxylation

The irreversible oxidative decarboxylation of pyruvate to acetyl-CoA, catalysed by the pyruvate dehydrogenase (PDH) complex. This is the link reaction connecting glycolysis to the TCA cycle, occurring in the mitochondrial matrix.

Pyruvate + CoA + NAD⁺ → Acetyl-CoA + CO₂ + NADH. The reaction is irreversible and commits pyruvate carbon to the TCA cycle or fatty acid synthesis.

## c-pdh-complex

A multi-enzyme complex consisting of three enzymes (E1, E2, E3) that catalyses the oxidative decarboxylation of pyruvate to acetyl-CoA. Requires five cofactors.

The complex is structurally and functionally analogous to the α-ketoglutarate dehydrogenase complex in the TCA cycle (same E3 subunit, homologous E1 and E2). It undergoes five sequential reactions: decarboxylation, oxidation, transfer of the acetyl group to lipoamide, transfer to CoA, and reoxidation of FADH₂.

## c-pdh-e1

Pyruvate dehydrogenase (E1): Decarboxylates pyruvate, forming a hydroxyethyl-TPP intermediate and releasing CO₂ as the first product.

Requires thiamine pyrophosphate (TPP) as a cofactor — TPP is derived from vitamin B₁ (thiamine). The acetyl group is then transferred to the lipoamide arm of E2.

## c-pdh-e2

Dihydrolipoyl transacetylase (E2): Accepts the acetyl group from E1 via its lipoamide prosthetic group, then transfers it to CoA forming acetyl-CoA.

The flexible lipoyl-lysine arm shuttles substrates between active sites. E2 has a central core with multiple lipoyl domains. Acetyl-CoA is the second product released from the complex.

## c-pdh-e3

Dihydrolipoyl dehydrogenase (E3): Reoxidises the reduced lipoamide using FAD, then transfers electrons from FADH₂ to NAD⁺ forming NADH.

E3 contains FAD as a prosthetic group and is identical to the E3 subunit of the α-ketoglutarate dehydrogenase complex. The final product NADH passes electrons to the ETC. The reactivated lipoamide is ready for another cycle.

## c-pdh-cofactors

Five cofactors required by the PDH complex: TPP (thiamine pyrophosphate, from vitamin B₁), lipoic acid, CoA (from pantothenic acid, vitamin B₅), FAD (from riboflavin, vitamin B₂), and NAD⁺ (from niacin, vitamin B₃).

Mnemonic: "Tender Loving Care For Nancy = TPP, Lipoate, CoA, FAD, NAD⁺." The reactions proceed in order: decarboxylation (TPP), oxidation and acetyl transfer (lipoate, CoA), reoxidation (FAD), and electron transfer (NAD⁺).

## c-tca-cycle

A cyclic pathway in the mitochondrial matrix (discovered by Hans Krebs, 1937) that oxidises the acetyl group of acetyl-CoA to 2 CO₂, harvesting high-energy electrons as NADH and FADH₂ for the ETC. Also called the Krebs cycle, citric acid cycle, or tricarboxylic acid cycle. It is the final common pathway for oxidation of carbohydrates, fats, and proteins.

Per turn (per acetyl-CoA): 3 NADH, 1 FADH₂, 1 GTP, 2 CO₂. Two carbon atoms enter as acetyl-CoA and two leave as CO₂. Four oxidation-reduction reactions occur. The cycle is amphibolic — it provides intermediates for biosynthesis.

## c-tca-citrate-synthase

Step 1: Acetyl-CoA (2C) + Oxaloacetate (4C) → Citrate (6C) + CoA. Condensation of the acetyl group with oxaloacetate. Citryl-CoA is a high-energy thioester intermediate whose hydrolysis drives the reaction forward.

Inhibited by ATP, NADH, succinyl-CoA, and citrate. The hydrolysis of the thioester bond in citryl-CoA provides the thermodynamic driving force for citrate synthesis.

## c-tca-aconitase

Step 2: Citrate ⇌ Isocitrate (via cis-aconitate). Isomerisation through dehydration followed by rehydration, catalysed by aconitase.

Aconitase is stereospecific — it interconverts a hydrogen atom and a hydroxyl group. cis-Aconitate is an intermediate. The isomerisation is necessary to enable oxidative decarboxylation in the next step.

## c-tca-isocitrate-dehydrogenase

Step 3: Isocitrate (6C) → α-Ketoglutarate (5C) + CO₂. Oxidative decarboxylation via an oxalosuccinate intermediate. Produces the first NADH of the cycle.

This is the first CO₂ release and first NADH production in the TCA cycle. Inhibited by ATP and NADH; activated by ADP and NAD⁺. This is a key regulatory step. The hydride ion from C-2 of isocitrate transfers to NAD⁺.

## c-tca-alpha-ketoglutarate-dehydrogenase

Step 4: α-Ketoglutarate (5C) + CoA + NAD⁺ → Succinyl-CoA (4C) + CO₂ + NADH. Second oxidative decarboxylation. Complex is homologous to PDH complex.

Three enzymes: E1 (α-ketoglutarate dehydrogenase with TPP), E2 (dihydrolipoyl succinyltransferase with lipoamide), E3 (dihydrolipoyl dehydrogenase with FAD — identical to PDH E3). Inhibited by succinyl-CoA and NADH (product inhibition) and by high energy charge. Same cofactors as PDH complex.

## c-tca-succinyl-coa-synthetase

Step 5: Succinyl-CoA + GDP + Pi → Succinate + GTP + CoA. Substrate-level phosphorylation conserving the thioester energy of succinyl-CoA.

The ΔG° for hydrolysis of succinyl-CoA is −8 kcal/mol (−33.5 kJ/mol), comparable to ATP. The free energy of the thioester bond is conserved as GTP (or ATP in some organisms). This is the only step in the TCA cycle that directly produces a high-energy phosphorylated compound via substrate-level phosphorylation. GTP can readily convert to ATP via nucleoside diphosphate kinase.

## c-tca-succinate-dehydrogenase

Step 6: Succinate + FAD → Fumarate + FADH₂. Oxidation of succinate to fumarate by succinate dehydrogenase (Complex II of the ETC).

This enzyme is embedded in the inner mitochondrial membrane (unique among TCA enzymes). It contains FAD as a prosthetic group and iron-sulfur clusters. Electrons are transferred from succinate → FAD → ubiquinone (Q) in the ETC. Only the trans isomer (fumarate) is formed (stereospecific).

## c-tca-fumarase

Step 7: Fumarate + H₂O → L-Malate. Stereospecific trans addition of water across the double bond of fumarate.

Fumarase catalyses stereospecific trans addition of H and OH across the double bond. The hydroxyl adds to only one side, so only L-malate is formed. A simple hydration reaction with no cofactor requirements.

## c-tca-malate-dehydrogenase

Step 8: L-Malate + NAD⁺ → Oxaloacetate + NADH. Regenerates oxaloacetate to complete the cycle. Produces the third NADH.

Despite having a highly positive standard free energy change (unfavourable), the reaction proceeds because oxaloacetate is rapidly consumed by citrate synthase (low steady-state concentration). This is the third and final NADH produced in the cycle.

## c-tca-regulation

TCA cycle regulation occurs at three key enzymes: citrate synthase (Step 1), isocitrate dehydrogenase (Step 3), and α-ketoglutarate dehydrogenase (Step 4). Primarily controlled by substrate availability and energy charge.

Citrate synthase: inhibited by ATP, NADH, succinyl-CoA, citrate. Isocitrate dehydrogenase: inhibited by ATP, NADH; activated by ADP, NAD⁺. α-Ketoglutarate dehydrogenase: inhibited by succinyl-CoA, NADH, high energy charge. Overall: high NADH/NAD⁺ ratio and high ATP/ADP ratio slow the cycle; high ADP and NAD⁺ accelerate it.

## c-tca-energy-yield

Per turn of TCA cycle (per acetyl-CoA): 3 NADH × 2.5 ATP = 7.5 ATP + 1 FADH₂ × 1.5 ATP = 1.5 ATP + 1 GTP = 1 ATP = ~10 ATP total.

From complete oxidation of one glucose: 2 acetyl-CoA enter TCA → ~20 ATP from TCA alone. Combined with glycolysis (~8 ATP) and PDH complex (2 NADH = 5 ATP), total is ~30-32 ATP per glucose.

## c-tca-amphibolic

The TCA cycle is amphibolic — it functions in both catabolism (oxidation of acetyl-CoA for energy) and anabolism (providing precursors for biosynthesis).

Intermediates serve as precursors: oxaloacetate → gluconeogenesis, aspartate; α-ketoglutarate → glutamate, amino acids; succinyl-CoA → porphyrin synthesis; citrate → fatty acid synthesis (exported to cytosol). Anaplerotic reactions replenish intermediates drawn off for biosynthesis.

## c-glucose-oxidation-yield

Complete aerobic oxidation of one glucose yields approximately 30–32 ATP: Glycolysis (2 ATP + 2 NADH → ~8 ATP), PDH complex (2 NADH → ~5 ATP), TCA cycle ×2 (6 NADH + 2 FADH₂ + 2 GTP → ~20 ATP).

Aerobic glycolysis net: ~8 ATP. PDH: 2 NADH × 2.5 = 5 ATP. TCA: 2 × 10 = 20 ATP. Total ~32 ATP (range 30-32 depending on the shuttle used for cytoplasmic NADH: malate-aspartate shuttle = 2.5 ATP/NADH; glycerol-3-phosphate shuttle = 1.5 ATP/NADH). Anaerobic glycolysis yields only 2 ATP per glucose.

## c-oxidative-phosphorylation

The formation of ATP by phosphorylation of ADP coupled to transfer of electrons from NADH and FADH₂ to molecular oxygen via the electron transport chain (ETC). Occurs in the inner mitochondrial membrane.

Each NADH yields approximately 2.5 ATP; each FADH₂ yields approximately 1.5 ATP. The ETC consists of Complexes I–IV and ATP synthase (Complex V). Oxygen is the final electron acceptor, forming water. The proton gradient (chemiosmotic coupling) drives ATP synthesis.
