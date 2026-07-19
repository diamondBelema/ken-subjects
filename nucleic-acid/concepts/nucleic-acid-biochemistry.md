---
format_version: 1
type: concept_set
set: Nucleic Acid Biochemistry
concepts:
  # ── DNA/RNA STRUCTURE ──
  - id: c-dna-rna-structure
    name: DNA/RNA Structural Biochemistry
    parent_id: null
  - id: c-b-dna
    name: B-DNA
    parent_id: c-dna-rna-structure
    diagrams:
      - id: b-dna-helix
        label: "B-DNA Double Helix Structure"
        file: diagrams/b-dna-helix.svg
  - id: c-a-dna
    name: A-DNA
    parent_id: c-dna-rna-structure
  - id: c-z-dna
    name: Z-DNA
    parent_id: c-dna-rna-structure
  - id: c-rna-structure
    name: RNA Structure
    parent_id: c-dna-rna-structure
  - id: c-deoxyribose
    name: Deoxyribose (DNA Sugar)
    parent_id: c-dna-rna-structure
    diagrams:
      - id: deoxyribose-structure
        label: "Deoxyribose Sugar Structure"
        file: diagrams/deoxyribose.svg
  - id: c-ribose
    name: Ribose (RNA Sugar)
    parent_id: c-dna-rna-structure
    diagrams:
      - id: ribose-structure
        label: "Ribose Sugar Structure"
        file: diagrams/ribose.svg

  # ── RNA CONFORMATION ──
  - id: c-rna-conformation
    name: RNA Conformation & Functional Changes
    parent_id: null
  - id: c-riboswitches
    name: Riboswitches
    parent_id: c-rna-conformation
  - id: c-pseudoknots
    name: Pseudoknots
    parent_id: c-rna-conformation

  # ── NON-CANONICAL BASE PAIRING ──
  - id: c-noncanonical-pairing
    name: Non-Canonical Base Pairing
    parent_id: null
  - id: c-reverse-watson-crick
    name: Reverse Watson-Crick Pairing
    parent_id: c-noncanonical-pairing
  - id: c-wobble-pairing
    name: Wobble Base Pairing
    parent_id: c-noncanonical-pairing
  - id: c-tautomerism
    name: Tautomerism & Hoogsteen Pairing
    parent_id: c-noncanonical-pairing

  # ── DNA CONFORMATIONS ──
  - id: c-dna-supercoiling
    name: Cruciform & Superhelical DNA
    parent_id: null
  - id: c-cruciform
    name: Cruciform DNA
    parent_id: c-dna-supercoiling
  - id: c-triplex-dna
    name: Triplex DNA
    parent_id: c-dna-supercoiling

  # ── DNA REPLICATION ──
  - id: c-dna-replication
    name: DNA Replication
    parent_id: null
  - id: c-semi-conservative
    name: Semi-Conservative Replication
    parent_id: c-dna-replication
  - id: c-denaturation-renaturation
    name: Denaturation & Renaturation (Tm)
    parent_id: c-dna-replication

  # ── HYDROLYSIS & ENZYMES ──
  - id: c-nucleic-acid-hydrolysis
    name: Nucleic Acid Hydrolysis
    parent_id: null
  - id: c-exonucleases
    name: Exonucleases
    parent_id: c-nucleic-acid-hydrolysis
  - id: c-endonucleases
    name: Endonucleases
    parent_id: c-nucleic-acid-hydrolysis
  - id: c-restriction-enzymes
    name: Restriction Endonucleases
    parent_id: c-nucleic-acid-hydrolysis

  # ── CHEMICAL SYNTHESIS ──
  - id: c-chemical-synthesis
    name: Chemical Synthesis of Nucleic Acids
    parent_id: null
  - id: c-synthesis-cycle
    name: Phosphoramidite Synthesis Cycle
    parent_id: c-chemical-synthesis
  - id: c-rna-synthesis
    name: Chemical Synthesis of RNA
    parent_id: c-chemical-synthesis

  # ── DNA METHYLATION ──
  - id: c-dna-methylation
    name: DNA Methylation
    parent_id: null
  - id: c-cpg-islands
    name: CpG Islands & DNMTs
    parent_id: c-dna-methylation
  - id: c-methylation-disease
    name: DNA Methylation in Health & Disease
    parent_id: c-dna-methylation

  # ── PHOSPHORYLATION ──
  - id: c-nucleic-acid-phosphorylation
    name: Nucleic Acid Phosphorylation
    parent_id: null
  - id: c-tna-pnk
    name: T4 PNK
    parent_id: c-nucleic-acid-phosphorylation
  - id: c-phosphorylation-repair
    name: Phosphorylation in DNA Repair
    parent_id: c-nucleic-acid-phosphorylation

definitions:
  # ── DNA/RNA STRUCTURE ──

  - concept_id: c-dna-rna-structure
    definition: >
      The structural biochemistry of DNA and RNA encompasses three principal helical
      forms of DNA (B-form, A-form, Z-form) and the versatile single-stranded nature
      of RNA. B-DNA is the predominant form in vivo under normal physiological conditions.
    details: >
      The three DNA forms differ in diameter, handedness, rotation per base pair, and
      vertical rise per base pair. B-DNA is ~20 Å, A-DNA is ~26 Å, Z-DNA is ~18 Å.
      RNA is usually single-stranded but can fold into double-stranded regions and
      complex 3D structures essential for function.
    tags: [DNA, RNA, structure, helix]
    diagram: |
      graph TD
        A[Nucleic Acid] --> B[DNA]
        A --> C[RNA]
        B --> D[B-DNA - right-handed, predominant]
        B --> E[A-DNA - right-handed, RNA-DNA hybrids]
        B --> F[Z-DNA - left-handed, zigzag backbone]
        C --> G[Single-stranded]
        C --> H[Can form ds regions]
        C --> Folds into tRNA, ribozymes]

        style D fill:#4CAF50,color:#fff
        style F fill:#f44336,color:#fff
        style G fill:#2196F3,color:#fff

  - concept_id: c-b-dna
    definition: >
      B-DNA is the predominant right-handed double helix found in vivo under normal
      physiological conditions. It has a rotation of +36 degrees per base pair and a
      vertical rise of 3.4 Angstroms per base pair.
    details: >
      B-DNA is the standard Watson-Crick model with a diameter of ~20 Å. The two
      antiparallel strands run in opposite directions, with base pairs stacked
      perpendicular to the helix axis. The major and minor grooves provide sites
      for protein recognition and binding.
    tags: [DNA, B-form, Watson-Crick, right-handed]

  - concept_id: c-a-dna
    definition: >
      A-DNA is a right-handed double helix with a rotation of +33 degrees per base pair
      and a vertical rise of 2.56 Angstroms per base pair. It occurs in vivo when RNA
      adopts a double-stranded conformation or in RNA-DNA hybrids.
    details: >
      A-DNA is wider (~26 Å diameter) and shorter than B-DNA. The base pairs are tilted
      relative to the helix axis. A-form helices are found in dehydrated DNA and in
      RNA duplexes. The 2'-OH group of ribose favors the A-form geometry, preventing
      B-form in RNA structures.
    tags: [DNA, A-form, RNA-DNA-hybrid]

  - concept_id: c-z-dna
    definition: >
      Z-DNA is a left-handed double helix with a rotation of -30 degrees per base pair
      and a vertical rise of 3.7 Angstroms per base pair. The backbone phosphates zigzag,
      giving it the name Z-DNA.
    details: >
      Z-DNA has a diameter of ~18 Å and has been identified in vivo in short regions
      of DNA, proving DNA is quite flexible. It can form in regions of alternating
      purine-pyrimidine sequences (especially CG repeats). Z-DNA may play roles in
      gene regulation and chromatin structure.
    tags: [DNA, Z-form, left-handed, zigzag]

  - concept_id: c-rna-structure
    definition: >
      RNA is usually single-stranded but can assume double-stranded structures and
      fold back on itself to perform biological functions. tRNA is a classic example,
      constituting 10-20% of total RNA with a molecular weight of ~25,000.
    details: >
      RNA structure can be described as a versatile free-energy landscape where the
      molecule adopts different shapes, favoring the lowest energy state or shifting
      to meet functional requirements. The extra 2'-OH group in ribose enables
      additional hydrogen bonding and conformational flexibility compared to DNA.
    tags: [RNA, single-stranded, tRNA, structure]

  # ── RNA CONFORMATION ──

  - concept_id: c-rna-conformation
    definition: >
      RNA conformation arises from molecular flexibility due to the extra OH group,
      allowing diverse shapes vital for modulating gene activity. Conformations include
      secondary structures (stem-loops, hairpins, helices) and tertiary structures
      (pseudoknots, riboswitches).
    details: >
      Functional examples include riboswitches (mRNA domains that change structure to
      regulate gene expression), viral RNA regulation (switching between translation
      and replication), and protein recognition (RNA adjusting conformation upon binding
      proteins to form functional complexes).
    tags: [RNA, conformation, secondary-structure, tertiary-structure]

  - concept_id: c-riboswitches
    definition: >
      Riboswitches are mRNA domains that change structure upon binding small molecules,
      turning gene expression on or off. They are a form of RNA-based gene regulation.
    details: >
      When a ligand binds to the riboswitch aptamer domain, it triggers a conformational
      change in the expression platform, which can terminate transcription, inhibit
      translation, or affect mRNA splicing. Riboswitches are found primarily in
      bacteria.
    tags: [RNA, riboswitches, gene-regulation, aptamer]

  - concept_id: c-pseudoknots
    definition: >
      Pseudoknots are RNA structures consisting of two stems which form a helix and
      two loops. They occur when a loop hairpin pairs with another part of the nucleic
      acid, creating a knotted structure.
    details: >
      Pseudoknots can be found in mRNA and tRNA and affect translation. RNA viruses
      have pseudoknots which affect protein synthesis and RNA replication. They are
      among the most common tertiary structural motifs in RNA.
    tags: [RNA, pseudoknots, tertiary-structure, translation]

  # ── NON-CANONICAL BASE PAIRING ──

  - concept_id: c-noncanonical-pairing
    definition: >
      Non-canonical base pairings are alternative hydrogen-bonding arrangements between
      nucleic acid bases that differ from the standard Watson-Crick A-T and G-C pairs.
      They include reverse Watson-Crick, wobble, and Hoogsteen pairings.
    details: >
      These alternative pairings enable conformational diversity in nucleic acids.
      They are essential for tRNA function, ribosome structure, and various regulatory
      mechanisms. Non-canonical pairs can form G-quadruplexes and triplexes involved
      in gene regulation and disease.
    tags: [base-pairing, non-canonical, hydrogen-bonds]

  - concept_id: c-reverse-watson-crick
    definition: >
      Reverse Watson-Crick pairing occurs when a pyrimidine rotates 180 degrees in its
      plane to align hydrogen bond donors with acceptors, placing the glycosidic bond
      in an antiparallel arrangement in the reverse base pair.
    details: >
      This type of pairing allows A-T(A,U) and G-C pairs to form in alternative
      orientations. It is found at the ends of DNA strands and in RNA structures.
      The rotation allows bases to maintain hydrogen bonding while adopting different
      geometric arrangements.
    tags: [base-pairing, reverse, Watson-Crick]

  - concept_id: c-wobble-pairing
    definition: >
      Wobble base pairing occurs when bases undergo tautomerization to form noncanonical
      pairs, most notably G-U wobble pairs and G-T(U) pairings. Critical for tRNA
      anticodon-codon recognition.
    details: >
      G-U wobble pairing is a naturally occurring noncanonical base pair that does not
      require tautomerization, although rare tautomeric forms of bases can generate
      other mismatched base pairs. The wobble position (first position of anticodon,
      third of codon) allows non-standard base pairing. G-U wobble pairs are nearly
      as stable as Watson-Crick pairs and are recognized by specific enzymes. This
      explains why fewer than 61 tRNAs are needed to decode all 61 sense codons.
    tags: [base-pairing, wobble, G-U, tRNA]

  - concept_id: c-tautomerism
    definition: >
      Tautomerism allows bases to shift between amino-imino and keto-enol forms.
      Hoogsteen base pairs occur when the purine rotates from anti to syn around
      its glycosidic bond, allowing alternative hydrogen bonding.
    details: >
      The normal anti orientation allows Watson-Crick A-T and G-C base pairing.
      The altered syn conformation produces Hoogsteen base pairing. Tautomeric shifts
      can cause mispairing and mutations during DNA replication.
    tags: [base-pairing, tautomerism, Hoogsteen, anti, syn]

  # ── DNA CONFORMATIONS ──

  - concept_id: c-dna-supercoiling
    definition: >
      DNA supercoiling naturally arises during DNA replication and transcription and
      is regulated by topoisomerases. Intercalating drugs can alter DNA supercoiling
      but are not its primary cause. Palindromic sequences can form cruciform structures.
    details: >
      The sequence order of DNA nucleobases may not be random. Inverted repeats can
      form cruciform structures. DNA is quite flexible and can adopt a variety of
      conformations beyond the standard B-form helix.
    tags: [DNA, supercoiling, topology, topoisomerase]

  - concept_id: c-cruciform
    definition: >
      Cruciform DNA forms when palindromic or inverted repeat sequences create two
      hairpin-like arms with 3-4 unpaired bases at their tips, joined at a junction
      with four unpaired nucleobases.
    details: >
      A palindromic sequence reads the same from 5' to 3' on either strand. Interstrand
      and intrastrand hydrogen bonds establish hairpins between complementary bases
      in each single strand. The cruciform consists of two hairpin arms and two
      duplex DNA arms meeting at a four-way junction.
    tags: [DNA, cruciform, palindromic, hairpin]

  - concept_id: c-triplex-dna
    definition: >
      Triplex DNA forms when a third strand binds in the major groove of B-form DNA,
      with the third strand bases forming Hoogsteen hydrogen bonds with purines in
      the existing base pairs.
    details: >
      A-T and G-C base pairs leave hydrogen-bond donors and acceptors exposed in the
      major groove. Each purine has two edges available for Hoogsteen-type hydrogen
      bonding. Triplex-forming oligonucleotides have potential applications in gene
      therapy and diagnostics.
    tags: [DNA, triplex, Hoogsteen, major-groove]

  # ── DNA REPLICATION ──

  - concept_id: c-dna-replication
    definition: >
      DNA replication occurs in the S-phase of the cell cycle via a semi-conservative
      model. Synthesis proceeds exclusively in the 5' to 3' direction, meaning the
      leading strand is continuous while the lagging strand is synthesized
      discontinuously.
    details: >
      Semi-conservative replication means each daughter molecule contains one original
      strand and one newly synthesized strand. The antiparallel nature of DNA strands
      means one strand (lagging) must be synthesized in short Okazaki fragments.
    tags: [DNA, replication, S-phase, semi-conservative]

  - concept_id: c-semi-conservative
    definition: >
      Semi-conservative replication is the model where each daughter DNA molecule
      contains one strand from the original parent molecule and one newly synthesized
      strand. Proven by the Meselson-Stahl experiment.
    details: >
      This model was predicted by Watson and Crick and confirmed experimentally by
      Meselson and Stahl in 1958 using nitrogen isotopes (15N and 14N) and density
      gradient centrifugation.
    tags: [DNA, replication, Meselson-Stahl]

  - concept_id: c-denaturation-renaturation
    definition: >
      Denaturation separates DNA strands by disrupting hydrogen bonds (increasing
      temperature or decreasing salt). Renaturation (hybridization) occurs when
      separated strands spontaneously reassociate at appropriate temperature and
      salt concentrations.
    details: >
      Tm (melting temperature) is the temperature at which 50% of base pairs are
      denatured. The melting curve shows a cooperative transition. Renaturation rate
      depends on concentration, temperature, and salt concentration. This principle
      underlies many molecular biology techniques including PCR and Southern blotting.
    tags: [DNA, denaturation, renaturation, Tm, hybridization]

  # ── HYDROLYSIS & ENZYMES ──

  - concept_id: c-nucleic-acid-hydrolysis
    definition: >
      Nucleic acids can be hydrolyzed by acids (cleaving glycosidic bonds), by alkali
      (RNA more susceptible due to 2'-OH), and enzymatically by nucleases. Strong acid
      at high temperature hydrolyzes both RNA and DNA into individual components.
    details: >
      Acid hydrolysis cleaves the N-glycosidic bond creating apurinic sites. Alkaline
      hydrolysis preferentially cleaves RNA phosphodiester bonds via the 2'-OH group,
      producing 2',3'-cyclic monophosphate intermediates. DNA is resistant to alkaline
      hydrolysis because it lacks the 2'-OH.
    tags: [hydrolysis, acid, alkali, nuclease]

  - concept_id: c-exonucleases
    definition: >
      Exonucleases cleave nucleotides one at a time from the end of a polynucleotide
      chain. They are classified as 3' or 5' specific based on which end they degrade from.
    details: >
      3' exonucleases remove nucleotides from the 3' end, while 5' exonucleases remove
      from the 5' end. They play roles in DNA repair, recombination, and degradation
      of foreign DNA. Example: exonuclease III (3') and T7 gene 6 exonuclease (5').
    tags: [nuclease, exonuclease, 3-prime, 5-prime]

  - concept_id: c-endonucleases
    definition: >
      Endonucleases cleave phosphodiester bonds at specific internal sites within a
      polynucleotide chain. They can be phosphate-specific or pentose-specific, and
      include both RNases and DNases.
    details: >
      Endonucleases are essential for DNA repair, recombination, and restriction
      digestion. Unlike exonucleases, they cut within the chain rather than from
      the ends. Many endonucleases are sequence-specific (restriction enzymes).
    tags: [nuclease, endonuclease, RNase, DNase]

  - concept_id: c-restriction-enzymes
    definition: >
      Restriction endonucleases recognize specific palindromic DNA sequences and cleave
      both strands at defined positions within or near those sequences. First isolated
      from bacteria where they serve as a defense against foreign DNA (bacteriophages).
    details: >
      Example: BamHI recognizes 5'-GGATCC-3' and cuts between the two Gs on each strand.
      Type II restriction enzymes are most useful for molecular biology because they
      cut at predictable positions within the recognition sequence. They produce either
      sticky ends (overhangs) or blunt ends.
    tags: [restriction-enzyme, BamHI, palindromic, molecular-cloning]

  # ── CHEMICAL SYNTHESIS ──

  - concept_id: c-chemical-synthesis
    definition: >
      Nucleic acids can be chemically synthesized using solid-phase phosphoramidite
      chemistry in an automated, step-by-step assembly. The synthesis produces
      oligonucleotides of 10-200 bp in the 3' to 5' direction (opposite to biological
      synthesis).
    details: >
      The standard method uses DMT (4,4'-dimethoxytrityl) as a protecting group.
      The 3' to 5' synthesis direction is opposite to the natural 5' to 3' direction
      of biological synthesis. Applications include PCR primers, sequencing primers,
      gene synthesis, and modified vaccines.
    tags: [synthesis, phosphoramidite, DMT, oligonucleotide]

  - concept_id: c-synthesis-cycle
    definition: >
      The phosphoramidite synthesis cycle consists of 4 steps: (1) Detritylation -
      removal of DMT protecting group, (2) Coupling - addition of phosphoramidite
      monomer, (3) Oxidation - conversion of phosphite triester to phosphodiester,
      (4) Capping - blocking unreacted 5'-OH groups.
    details: >
      In theory, 3 steps suffice (detritylation, coupling, oxidation). Capping is
      an industrial addition to prevent accumulation of short undesired oligomers.
      Detritylation uses acid to remove DMT. Coupling activates the phosphoramidite.
      Oxidation uses I2/H2O. Capping uses acetic anhydride.
    tags: [synthesis, detritylation, coupling, oxidation, capping]

  - concept_id: c-rna-synthesis
    definition: >
      RNA chemical synthesis requires protection of the 2'-OH of ribonucleosides
      in addition to standard protecting groups. The 2'-protecting group commonly
      used is t-butyldimethylsilyl (TBDMS), removed by fluoride ion treatment.
    details: >
      The 2'-OH protection is critical because RNA is much more susceptible to
      degradation than DNA due to the 2'-OH. TBDMS is stable during synthesis
      but can be selectively removed with fluoride (TBAF or TBAF). This allows
      the 3'-5' backbone to be assembled while protecting the reactive 2'-OH.
    tags: [RNA, synthesis, TBDMS, 2-prime-OH, protection]

  # ── DNA METHYLATION ──

  - concept_id: c-dna-methylation
    definition: >
      DNA methylation is an enzymatic process where methyl groups are added to DNA,
      acting as an epigenetic mechanism that alters gene expression. It primarily
      occurs at CpG islands and is catalyzed by DNA methyltransferases (DNMTs).
    details: >
      The reaction transfers a methyl group from S-adenosylmethionine (SAM) to the
      5th carbon of cytosine, forming 5-methylcytosine and S-adenosylhomocysteine
      (SAH). Methylated cytosines are usually symmetrical at CpG islands, with
      guanine nucleotides diagonally opposite on opposing strands.
    tags: [methylation, epigenetics, DNMT, SAM, CpG]

  - concept_id: c-cpg-islands
    definition: >
      CpG islands are regions where cytosine nucleotides are followed by guanine
      nucleotides. DNA methyltransferases (DNMTs) catalyze methyl transfer from SAM
      to the 5th carbon of cytosine, forming 5-methylcytosine.
    details: >
      The methylated cytosine residues are usually symmetrical at CpG islands, with
      the guanine on the opposite strand also being methylated (maintenance
      methylation by DNMT1). CpG islands are often found near gene promoters.
    tags: [CpG, DNMT, 5-methylcytosine, promoter]

  - concept_id: c-methylation-disease
    definition: >
      Abnormal DNA methylation patterns are linked to cancer, muscular dystrophy,
      and defects in imprinting, embryonic development, X-chromosome inactivation,
      and chromosome stability. Hypermethylation of tumor suppressor genes can
      silence them, leading to unchecked tumor growth.
    details: >
      DNA methylation in promoter regions acts as a physical blocker preventing
      transcription factor binding, thus silencing gene expression. Global
      hypomethylation can activate oncogenes, while local hypermethylation can
      silence tumor suppressors. This makes methylation both a biomarker and
      therapeutic target in cancer.
    tags: [methylation, cancer, epigenetics, tumor-suppressor]

  # ── PHOSPHORYLATION ──

  - concept_id: c-nucleic-acid-phosphorylation
    definition: >
      Nucleic acid phosphorylation is the enzymatic addition of a phosphate group
      (PO4 3-) to DNA or RNA. The most widely used enzyme is T4 polynucleotide
      kinase (T4 PNK), which transfers the gamma phosphate from ATP to 5'-OH ends.
      This is distinct from histone phosphorylation, which is an epigenetic modification.
    details: >
      Essential in molecular biology for preparing DNA fragments for ligation,
      labeling nucleic acids, and repairing DNA breaks. In nature, phosphorylation
      is critical for DNA damage repair, where polynucleotide kinase phosphorylates
      broken 5'-OH ends to enable ligation. Cells also recognize nucleic acids
      partly through phosphorylation status (e.g., viral 5'-triphosphates activate
      RIG-I innate immune signaling).
    tags: [phosphorylation, T4-PNK, ATP, 5-prime-OH]

  - concept_id: c-tna-pnk
    definition: >
      T4 polynucleotide kinase (T4 PNK) is the most widely used enzyme for nucleic
      acid phosphorylation. It efficiently transfers the terminal gamma phosphate
      group from ATP to the 5' hydroxyl termini of DNA or RNA oligonucleotides.
    details: >
      T4 PNK has both 5'-kinase and 3'-phosphatase activities. It is used in
      molecular cloning to phosphorylate PCR products (Taq polymerase leaves 5'-OH
      unless phosphorylated primers were used) before ligation. Also used for
      end-labeling nucleic acids with radioactive or fluorescent tags.
    tags: [T4-PNK, kinase, ATP, ligation]

  - concept_id: c-phosphorylation-repair
    definition: >
      Phosphorylation plays a critical role in DNA damage repair. Polynucleotide
      kinase rapidly phosphorylates broken 5'-OH ends at sites of ionization,
      radiation, or oxidative stress damage, enabling DNA ligation by Ligase IV.
      Failure to repair activates DNA damage response, potentially leading to apoptosis.
    details: >
      Without phosphorylation of broken ends, the DNA repair machinery cannot
      recognize and repair the damage. Unrepaired damage triggers the DNA damage
      response, which can lead to apoptosis (programmed cell death). Cells also
      use phosphorylation status to distinguish human from viral nucleic acids
      in innate immunity (e.g., viral 5'-triphosphates activate RIG-I signaling).
      Note: histone phosphorylation is a separate epigenetic modification that
      regulates chromatin structure, not nucleic acid phosphorylation.
    tags: [DNA-repair, phosphorylation, apoptosis, innate-immunity]
---

## c-dna-rna-structure
DNA exists in three principal helical forms: B-DNA (predominant in vivo), A-DNA (found in RNA-DNA hybrids), and Z-DNA (left-handed, zigzag backbone). RNA is usually single-stranded but can fold into complex functional structures.

## c-dna-rna-structure:summary
### Stage 1 — The Big Picture: Why DNA and RNA Look the Way They Do

Everything in this chapter starts with one question:

> **How do cells store, copy, read and protect genetic information?**

The answer is DNA and RNA.

#### DNA vs RNA

| DNA | RNA |
|------|-----|
| Stores genetic information | Uses genetic information |
| Very stable | More flexible |
| Usually double-stranded | Usually single-stranded |
| Contains deoxyribose sugar | Contains ribose sugar (extra OH group) |
| Contains thymine (T) | Contains uracil (U) |

Think of it like this: DNA = The library. RNA = The workers that use the books in the library.

#### Why is RNA More Flexible?

The biggest structural difference is one tiny atom. DNA sugar has H, RNA sugar has OH. That extra **2'-OH group** allows RNA to bend, fold, twist, and form complicated 3D shapes. This is why RNA can do much more than simply carry information. Examples: tRNA folds into a cloverleaf, rRNA forms the ribosome, riboswitches change shape to control genes. DNA lacks this flexibility because it is designed for **long-term information storage.**

#### DNA Helices

DNA is not always shaped the same. There are **three major conformations.**

**B-DNA (Normal DNA):** The form inside most living cells. Right-handed helix, most stable, most common. If someone says "DNA", they almost always mean B-DNA.

**A-DNA:** Also right-handed. Occurs mainly in DNA-RNA hybrids, double-stranded RNA, and dehydrated DNA. It is shorter, wider, and more compact.

**Z-DNA:** Left-handed helix with a zig-zag phosphate backbone. Rare, appears only in small regions. Scientists think Z-DNA helps regulate gene expression and relieve torsional stress.

**Easy mnemonic:** B = **Biological** (normal DNA). A = **Altered** (special conditions). Z = **Zigzag** (left-handed).

#### DNA Flexibility

DNA is **not rigid.** It changes shape depending on proteins, water content, sequence, and mechanical stress. This flexibility is important because proteins need to open DNA during replication, transcription, and repair.

#### The Flow

DNA stores information safely → Because DNA must protect information, it is stable → RNA must perform many jobs → RNA is flexible because of the extra 2'-OH group → This flexibility allows RNA to fold into many functional structures → DNA also changes shape when necessary, giving rise to B-, A-, and Z-DNA.

## c-b-dna
B-DNA is the predominant right-handed double helix found in vivo under normal physiological conditions, with +36° rotation and 3.4 Å rise per base pair.

```
            B-DNA — Top View (looking down helix axis)
            ─────────────────────────────────────────
                          20 Å
                     ┌────────────┐
                    ╱   ┌──────┐  ╲
                   ╱   ╱ MAJOR  ╲  ╲
                  │   │ GROOVE  │   │
                  │   │  ~12Å   │   │
                   ╲   ╲       ╱  ╱
                    ╲   └──────┘  ╱
                     └────────────┘
                        MINOR
                        GROOVE
                         ~8Å

        Side View (one turn = 10 bp, 34 Å)
        ───────────────────────────────────

           5'─ G ≡ C ─3'      ─3'
              │       │         │
           3'─ C ≡ G ─5'      ─5'
              │       │
           5'─ A ═ T ─3'
              │       │
           3'─ T ═ A ─5'
              │       │
           5'─ G ≡ C ─3'
              │       │
           3'─ C ≡ G ─5'
              │       │
           5'─ A ═ T ─3'
              │       │
           3'─ T ═ A ─5'
              │       │
           5'─ G ≡ C ─3'
              │       │
           3'─ C ≡ G ─5'

        ───────────────────────────────────
         10 bp per turn  │  3.4 Å per bp
         36° per bp      │  Sugar: C2'-endo
         Right-handed    │  ≡ = triple bond (GC)
                         ═ = double bond (AT)
```

## c-b-dna:summary
Standard Watson-Crick model. Antiparallel strands with major and minor grooves for protein recognition. Most stable and common form under physiological conditions.

## c-a-dna
A-DNA is a right-handed helix (+33°/bp, 2.56 Å rise) that occurs in RNA-DNA hybrids and dehydrated conditions.

```
            A-DNA — Top View (looking down helix axis)
            ─────────────────────────────────────────
                          26 Å
                     ┌──────────────┐
                    ╱   ┌────────┐  ╲
                   ╱   ╱  MAJOR   ╲  ╲
                  │   │  GROOVE    │   │
                  │   │   ~11Å     │   │
                   ╲   ╲          ╱  ╱
                    ╲   └────────┘  ╲
                     └──────────────┘
                       MINOR GROOVE
                         ~2-6Å (narrow)
                         BASES TILTED

        Side View (one turn = 11 bp, 28 Å)
        ───────────────────────────────────

           5'─ G ≡ C ─3'      ─3'
              ╲       ╱         │
           3'─ C ≡ G ─5'      ─5'
              ╲       ╱
           5'─ A ═ T ─3'    (base pairs tilted
              ╲       ╱      ~20° to helix axis)
           3'─ T ═ A ─5'
              ╲       ╱
           5'─ G ≡ C ─3'
              ╲       ╱
           3'─ C ≡ G ─5'
              ╲       ╱
           5'─ A ═ T ─3'
              ╲       ╱
           3'─ T ═ A ─5'
              ╲       ╱
           5'─ G ≡ C ─3'
              ╲       ╱
           3'─ C ≡ G ─5'

        ───────────────────────────────────
         11 bp per turn  │  2.56 Å per bp
         33° per bp      │  Sugar: C3'-endo
         Right-handed    │  Helix axis through
                         │  center of base pairs
```

## c-a-dna:summary
Wider and shorter than B-DNA. Base pairs tilted relative to helix axis. Found in RNA duplexes and dehydrated DNA. Important for understanding RNA structure.

## c-z-dna
Z-DNA is a left-handed helix (-30°/bp, 3.7 Å rise) with a zigzag phosphate backbone, found in short genomic regions.

## c-z-dna:summary
Left-handed helix identified in vivo. Forms in alternating purine-pyrimidine sequences (CG repeats). Proves DNA flexibility. May play roles in gene regulation.

## c-rna-structure
RNA is usually single-stranded but can form double-stranded regions and complex 3D structures. tRNA (10-20% of total RNA, MW ~25,000) is a classic example.

```
        RNA vs DNA — Key Structural Differences
        ────────────────────────────────────────

        DNA (double-stranded)          RNA (usually single-stranded)
        ─────────────────────          ─────────────────────────────

          5'─ G ≡ C ─3'                 5'─ A ─ U ─ G ─ C ─ A ─ U ─ G ─3'
             │       │                        ╲       ╱
          3'─ C ≡ G ─5'                    3'─ U ─ A ─ C ─ G ─ U ─ A ─ C
             │       │                          (can fold back)
          5'─ A ═ T ─3'                        │       │
             │       │                         G ≡ C   A ═ U
          3'─ T ═ A ─5'                        │       │
             │       │                         C ─ G   U   A
          5'─ G ≡ C ─3'                        ╲     ╱
             │       │                         loop
          3'─ C ≡ G ─5'

        ─────────────────────          ─────────────────────────────
         Sugar: deoxyribose             Sugar: ribose (2'-OH present)
         Strands: antiparallel          Usually single-stranded
         Base T: thymine                Base U: uracil
         Helix: B-form (most common)    Folds into diverse structures
```

## c-rna-structure:summary
RNA structure follows a free-energy landscape, adopting lowest-energy or functionally-required shapes. The 2'-OH group enables additional hydrogen bonding and conformational flexibility beyond DNA.

## c-deoxyribose
Deoxyribose is a 5-carbon aldopentose sugar found in DNA. It differs from ribose by lacking a hydroxyl group at the 2' carbon (hence "deoxy"). In DNA it adopts the C2'-endo conformation in B-DNA.

```
        Deoxyribose (β-D-2-deoxyribose)
        ────────────────────────────────

                  CH₂OH
                    │
            O ─────C───── 5'
           ╱ ╲     │
          │   │    4'
          │   │
     1'── C   C ── 3'
          │   │
          ╲   ╱
           C─── 2'
           │
           H      ← No OH at 2' (deoxy!)
           H

        ────────────────────────────────
         In DNA: C2'-endo (B-DNA)
                 C3'-endo (A-DNA)
         2' position: H, H (no hydroxyl)
         Ring: furanose (5-membered)
         Bond to base: β-N-glycosidic
         Bond to phosphate: 5'-ester
```

## c-ribose
Ribose is a 5-carbon aldopentose sugar found in RNA. It has a hydroxyl group at the 2' carbon (unlike deoxyribose). In RNA it adopts the C3'-endo conformation, giving RNA a more compact A-form helix.

```
        Ribose (β-D-ribose)
        ────────────────────

                  CH₂OH
                    │
            O ─────C───── 5'
           ╱ ╲     │
          │   │    4'
          │   │
     1'── C   C ── 3'
          │   │
          ╲   ╱
           C─── 2'
           │
           OH     ← OH present at 2' (ribose!)
           H

        ────────────────────
         In RNA: C3'-endo (A-form)
         2' position: OH, H
         Ring: furanose (5-membered)
         2'-OH enables:
           • Additional H-bonding
           • 2',3'-cyclic phosphate (hydrolysis)
           • RNA hydrolysis susceptibility
           • Ribozyme catalysis
```

## c-rna-conformation
RNA conformation arises from the extra OH group, enabling diverse shapes for gene regulation. Includes secondary (stem-loops, hairpins) and tertiary (pseudoknots, riboswitches) structures.

```
        Levels of RNA Structure
        ───────────────────────

        PRIMARY:     A ─ U ─ G ─ C ─ C ─ A ─ U ─ G ─ A ─ A ─ C
                     (linear nucleotide sequence)

        SECONDARY:   Stems (paired) + Loops (unpaired)

                     Hairpin / Stem-Loop:
                           ┌─── G
                     A ─ U │
                     G ≡ C │    ← loop (unpaired)
                     C ≡ G │
                     U ─ A │
                     A ═ U └─── U
                     │
                     G ≡ C
                     C ≡ G       ← stem (base-paired)
                     U ═ A
                     A ≡ U

        TERTIARY:    Secondary structures fold into 3D shapes
                     (driven by Mg²⁺, base stacking, H-bonds)

        ───────────────────────────────────────────────────────────

        tRNA — Cloverleaf (Secondary)     tRNA — L-shape (Tertiary)
        ─────────────────────────────     ─────────────────────────

                  AA                                        AA
                   │                                         │
              ┌────┴────┐                              ┌─────┘
              │  ACC    │ ← acceptor stem              │
              ├─────────┤                              │
              │         │                           ┌──┘
         ┌────┤         ├────┐                   ┌──┘
         │D   │         │  TΨC│ ← TΨC loop     │  TΨC
    D    │loop│  anticodon   │                   │  loop
  loop   ├────┤  loop        │                   └──┐
         │    │    │         │                      │
         └────┘    │         │                   ┌──┘
                    └────┬────┘                   │ anticodon
                         │                        │ loop
                    anticodon                     │
                      loop                        └─── D loop

        ── RNA 3D Folding Visualization ──

-------------------------------------------=*#++++**----------+#++**=+==+==+=+=++++=------------------------------
==---------------=-----------------------=+*++----++*+--------=*####-*+==+=*+++****+=-----------------------------
+##**##******=+#%***###*#%+***+**+-----+*%=----------+%*=-----=++=------------------------------------------------
==+==========-=-===========-=+==-----+#*=----------=#*=+@@@%*---------------------------------------------------
--------------%*-----------------------==-------------=+----------------------------------------------------------
-------------+*=-----------------------=#+-----------=*#----------------------------------------------------------
-------------#*------------------------+*%=----------+%*+---------------------------------------------------------
------------%@#--------------------------=*+==----==+*------------------------------------------------------------
------------##-----------------------------+@@+==*@%=-------------------------------------------------------------
----------=*+=------------------------------+=----==--------------------------------------------------------------
----------+#*=-----------------------------=@@#++#@%---------------------=--=---=---===-=-=-=-=-------------------
-----+#*=---*#+=----------------------------**---=*+---------------------=+*#@@%++**+=*#*#**#**=------------------
-----=**=-==*%%+---------------------------=%%+==*%#-------------------------------+=------==---------------------
-------*@@*---*#*=-------------------------=%%---=%#-----------------------------=#*=-----------------------------
--------+*+==+%%%=--------------------------*+---=*+----------------------------+#+-------------------------------
---------*@%+---+@%=---------------------==%%%---=%%%==-----------------------*@@+--------------------------------
-----------++--+#@@=------------------++*=------------=++=----------------+*-=*+++--------------------------------
-----------*@@+---+%@=----------------#+=--------------=*#---------------+#+=-=+*#*-------------------------------
------------=*+-=#+*+==#-------------*+------------------**------------++---------=#+-----------------------------
-------------*@@+------+@@=+@%**@@*+%@+------------------*@%+%@@+#@@==@%=----------*%@*+@@*=@@*+@@#+%@@=----------
-------------=+=--------+=--=+--=+--==--------------------==--*=--+=--==------------+=--==---+--=+---=------------
-------------=+=--------+=--=*--+*--+=--------------------++--%+--#=--==------------*+--=+---*--=*---++-----------
-------------*%%+------+@@=+@%**@@*+%@+------------------*@#+%@@+*@@==@%=----------*%@*=@@+=@@*+%@#-+@@-----------
--------------=+++++++=*==--==--==--=#+------------------**=--==@+==--=*+---------=*+=--==--==--==--=#*=----------
-------------+@@+-+##=----------------*++-------------=+*+-----=@@=-----=***+-=+*#*=-----------------**===========
------------=%@*----------------------+**+-----------=++*=------@+-------=**===+*+=------------------**===========
-----------*#=----------------------------+#*#====*##+----------@+-----------------------------------=============
---------=#*--------------------------------**-@-=**------------@+-------------------------%*+#=*+*+*****=**+*+%*#
-#%*=###*#++***#####=-------------------------+@+---------------=--------------------------*+=*==+**==++#++*+++*+*
-=+=+=*#++==++=++*++=-------------------------=@=----------=@@@@@%=###=-------------------------------------------
-----------------------------------------------@------------==========--------------------------------------------
-----------------------------------------------@------------------------------------------------------------------
--------------------------------=**#+*#+++=++=*%++#+=#=+++***+=---------------------------------------------------
--------------------------------=**####+++=-##*##+**=#+###@%#*=---------------------------------------------------
```

## c-rna-conformation:summary
### Stage 2 — How RNA Folds into Functional Molecules

In Stage 1, we learned that DNA is stable because its job is to store information, and RNA is flexible because of its extra 2'-OH group. Now the question becomes: **Why does RNA need to be flexible?** Because RNA doesn't just carry information — it also **works**.

#### From a Straight String to a Functional Molecule

Imagine a long rope. Stretched out, it doesn't do much. But if you tie knots and loops into it, now it has a shape. RNA behaves the same way — instead of remaining a straight strand, it folds into precise shapes that allow it to perform different biological functions. **Function follows structure** — one of the most important ideas in biochemistry.

#### Why Can RNA Fold?

The nitrogenous bases can hydrogen bond with other bases on the **same RNA molecule**, creating internal base pairing. These paired regions form stable structures.

#### Levels of RNA Structure

**Primary structure:** Simply the nucleotide sequence (A-U-G-C-C-A-U-G...). Nothing has folded yet.

**Secondary structure:** Complementary bases pair, forming stems, hairpins, stem-loops, and helices. These structures make RNA much more stable.

**Tertiary structure:** Secondary structures fold again into complex 3D shapes. These shapes allow RNA to interact with proteins, DNA, other RNA molecules, and small molecules — this is how RNA becomes biologically active.

#### Hairpin (Stem-Loop)

One of the simplest RNA structures. The stem is held together by complementary base pairing. The loop remains unpaired. Hairpins appear in mRNA, tRNA, rRNA, and viral RNA.

#### tRNA: A Perfect Example

Transfer RNA folds into a characteristic **cloverleaf** shape. Each loop has a specific job — one loop recognizes the mRNA codon, another carries an amino acid. Without folding, tRNA could not perform either function.

#### Pseudoknots

A pseudoknot forms when a loop pairs with another distant part of the RNA, making the RNA appear "knotted." It is called a pseudoknot because it resembles a knot but is not a true physical knot. Found in viruses, mRNA, and some tRNA molecules. They help control translation, RNA replication, and protein synthesis. Many RNA viruses depend on pseudoknots for survival.

#### Riboswitches

A riboswitch is part of an mRNA molecule. Normally the RNA has one shape. When a small molecule binds, the RNA changes shape, changing gene expression — the gene may be turned ON or OFF. No protein is required. The RNA itself senses the molecule.

#### RNA as a Dynamic Molecule

RNA is **not locked into one shape**. It constantly samples many conformations. Environmental conditions influence which shape is most stable: temperature, ions (especially Mg²⁺), proteins, and small molecules. The RNA settles into the shape that best performs its current function.

#### The Flow

DNA is stable → RNA is flexible → Because RNA can fold → Folding creates secondary structures → Secondary structures combine into tertiary structures → These structures allow RNA to carry amino acids (tRNA), regulate genes (riboswitches), control translation (pseudoknots), build ribosomes (rRNA), and perform many other cellular functions.

#### Key Takeaways

- RNA folds because of its extra 2'-OH group and internal base pairing.
- RNA has three structural levels: primary, secondary, and tertiary.
- Hairpins and stem-loops are common secondary structures.
- tRNA folds into a cloverleaf that enables protein synthesis.
- Pseudoknots form when loops pair with distant RNA regions.
- Riboswitches regulate gene expression by changing RNA shape.
- RNA structure determines RNA function.

#### Plain English Guide to RNA Folding

To understand how RNA folds, it helps to picture it like a piece of string or wire. Here is exactly what those weird structural terms mean in plain English:

**1. The "Ribbon" (The Backbone)**

When scientists draw RNA, they often draw the main strand as a continuous, twisting ribbon. What it actually is: This represents the sugar-phosphate backbone of the RNA molecule. The vibe: Think of it like the plastic spine of a zipper. The genetic letters (A, U, G, C) stick out from this ribbon like the zipper teeth.

**2. The "Stem" (The Zipped-Up Part)**

A stem happens when a single strand of RNA loops back on itself and locks together. What it actually is: It is a double-stranded region where complementary bases line up perfectly (A pairs with U, and G pairs with C) and bond together. The vibe: This is the part of the zipper that is completely zipped up. Because it is locked in place, the stem is very rigid and stable.

**3. The "Loop" (The Unzipped Bubble)**

A loop is the open, unbonded bubble at the very end of a stem. What it actually is: A sequence of nucleotides that do not match up with the bases opposite them. Because they cannot find a partner to bond with, they stay single-stranded and flexible. The vibe: Picture a hairpin or a bobby pin. The straight sides facing each other are the stem, and the curved, open top is the loop.

**Putting it Together: The Hairpin (Stem-Loop)**

When you combine a stem and a loop, you get a stem-loop (often just called a hairpin). It is one of the most common pieces of RNA architecture. The rigid stem acts like a structural pillar to give the RNA shape, while the flexible loop acts like a hook or a landing pad, waiting to interact with other molecules or proteins in the cell.

## c-riboswitches
Riboswitches are mRNA domains that change structure upon binding small molecules, turning gene expression on or off.

```
        Riboswitch — Ligand-Triggered Conformational Change
        ─────────────────────────────────────────────────────

        BEFORE ligand binding:              AFTER ligand binding:

        5'──────────┐  ┌──────────── 3'    5'──────────┐  ┌──────────── 3'
                     │  │                               │  │
                  ┌──┴──┴──┐                        ┌──┴──┴──┐
                  │ aptamer │ ← binds ligand        │ aptamer │──● ligand
                  │ domain  │                       │ domain  │  bound!
                  └──┬──┬──┘                        └──┬──┬──┘
                     │  │                               │  │
                  ┌──┴──┤                            ┌──┴──┤
                  │expression│ ← ON or OFF           │express.│ ← CONFORMATIONAL
                  │platform  │                       │platform│    CHANGE
                  └──────┤                            └─────┘
                         ↓                               ↓
                   gene expressed                   gene silenced
                   (mRNA made)                   (or vice versa)

        ─────────────────────────────────────────────────────
         No protein needed — RNA senses the molecule directly
         Found primarily in bacteria (5' UTR of mRNA)
         Aptamer domain: binds ligand (e.g. TPP, FMN, CoB₁₂)
         Expression platform: controls gene output
```

## c-riboswitches:summary
Ligand binding triggers conformational change in the aptamer domain, affecting the expression platform. Can terminate transcription, inhibit translation, or affect splicing. Found primarily in bacteria.

#### Plain English Guide to Riboswitches

Think of a riboswitch as a built-in dimmer switch made out of the RNA itself. It allows the RNA to sense its environment and turn its own protein production on or off, completely on autopilot.

**The Two Main Parts**

Every riboswitch has two main sections right next to each other on the RNA strand:

- **The Sensor (Aptamer):** This is a folded-up pocket of RNA (usually made of stems and loops) that acts like a lock. It is specifically shaped to fit one exact target molecule — like a specific vitamin, sugar, or metal ion.
- **The Switch (Expression Platform):** This is the part of the RNA that actually controls whether a protein gets made. It can shift between two shapes: one that lets the cell read the RNA, and one that blocks it.

**How the Switch Flips**

Imagine the RNA is a wire leading to a lightbulb (the protein).

- **State A (No Target):** When the target molecule is not around, the Sensor is empty. The Switch rests in a shape that allows the cell's machinery (the ribosome) to easily glide down the RNA and build the protein. The switch is ON.
- **The "Snap" (Target Arrives):** Suddenly, the target molecule floats by and lands right into the Sensor lock.
- **State B (Target Bound):** The moment the molecule clicks into place, the chemical bonds pull the RNA tight. This forces the Switch section to instantly warp and snap into a totally different shape — usually a tight hairpin or a pseudoknot. This new shape physically blocks the ribosome from moving forward. The switch is now OFF.

**Why does the target molecule cause the switch?**

It all comes down to basic physics and chemistry: thermodynamics and molecular tug-of-war.

When the ligand drops into the sensor pocket, it forms a bunch of new, highly stable chemical bonds (hydrogen bonds, electrostatic attractions, etc.) with the RNA:

1. **The "Energy Drop" (Thermodynamics):** In nature, molecules always want to be in the most stable, lowest-energy state possible. Before binding, the RNA sensor pocket is somewhat loose and dynamically shifting. After binding, the new bonds between the ligand and the RNA make this specific bound shape incredibly stable. The RNA wants to snap into this shape because it is energetically favorable.
2. **The Molecular Tug-of-War:** Because the ligand fits so snugly, it acts like a magnet pulling the walls of the sensor pocket inward. To wrap tightly around the ligand, the nucleotides in the sensor pocket have to shift their positions. When these nucleotides shift, they literally yank on the rest of the RNA strand connected to them.
3. **The Re-Zipping Effect:** The RNA nucleotides that used to be zipped up in the "ON" position suddenly get pulled away by this shift. Because they have been pulled out of their old pairs, they look around for new partners. A nearby sequence of the RNA — which was previously hidden or single-stranded — is suddenly exposed. The loose bases snap together with this new section, instantly zipping up into a brand new hairpin (the terminator stem) or a pseudoknot.

**The Mouse Trap Analogy**

Think of it like a mouse trap:

- The empty riboswitch is a set mouse trap. It has potential energy, held in place by a loose latch (the sensor).
- The ligand is the mouse stepping on the tripwire.
- The moment the ligand touches the sensor, the latch releases, the built-in tension shifts, and the whole apparatus snaps violently into its final, stable "sprung" shape (the OFF position).

**Why is this genius?**

Normally, cells need complex proteins to act as supervisors to turn genes on and off. But a riboswitch cuts out the middleman. The RNA molecule is the supervisor. It senses the environment and changes its own 3D shape in real-time to control itself. For example, if a bacteria has enough Vitamin B12 floating around, the B12 binds to the riboswitch, flips it OFF, and stops the bacteria from wasting energy making more Vitamin B12. Simple, fast, and fully automated.

## c-pseudoknots
Pseudoknots are RNA structures with two helical stems and two loops, formed when a loop hairpin pairs with another region of the nucleic acid.

```
        Pseudoknot Formation — Loop-Region Pairing
        ───────────────────────────────────────────

        Step 1: Hairpin forms            Step 2: Loop pairs with distant region

              ┌──── G                          ┌──── G
              │    │                           │    │
              C ≡  G                           C ≡  G
              G ≡  C     Loop                  G ≡  C     ┌──── Loop 1
              │    │     1                     │    │     │
              A ═  U     │                     A ═  U ────┤
              │    │     │     Distant          │    │    │
              U ═  A     │     region           U ═  A    │
              │    │     │         │            │    │    │
              G ≡  C     │         │            G ≡  C    │
              C ≡  G─────┘         │            C ≡  G────┘
              │                    │            │         │
              U ═  A               │            U ═  A ───┤
              A ═  U ──────────────┘            A ═  U    │
              │                                 │    │    │
              └──── Stem 1                      └────┘    │
                                         Stem 2 ──────────┘
                                                       Loop 2

        ───────────────────────────────────────────
         Two stems (Stem 1, Stem 2) + two loops
         NOT a physical knot — just appears knotted
         Found in: viruses, mRNA, tRNA
         Function: translation control, RNA replication
         Important for retroviral frameshifting
```

## c-pseudoknots:summary
Common tertiary structural motif in RNA. Found in mRNA and tRNA where they affect translation. RNA viruses use pseudoknots to affect protein synthesis and replication.

#### Step 1: The Normal Hairpin

Imagine you take a single shoelace (the RNA strand) and fold it to make a simple loop, holding the middle together with your fingers.

- The part you are holding is the **stem**.
- The open circle at the top is the **loop**.
- The rest of the shoelace just hangs loose past your fingers as a **tail**.

#### Step 2: The "Fake" Knot

Now, imagine the loose tail loops back around and decides to cross over and glue itself to the inside of that first loop.

Because the RNA bases inside the loop match perfectly with the bases on the tail, they snap together. You now have two different stems interlocking with each other. It looks like a tangled, messy knot.

#### Why is it called a "Pseudo" (Fake) Knot?

It is called a pseudoknot because it is not a true mathematical knot.

- **A Real Knot:** If you tie a knot in a rope and pull both ends, the knot gets tighter and stuck. You would have to cut it or carefully untie it.
- **A Pseudoknot:** If you grabbed the two far ends of this RNA strand and pulled them straight, the whole thing would completely unzip and flatten back into a straight line. Nothing is actually trapped.

#### Why does the cell care?

By interlocking like this, the RNA goes from a flat, floppy shape into a tough, rigid 3D block.

Cells and viruses use pseudoknots like little mechanical tripwires. When a ribosome (the cell's protein-building machine) is sliding along the RNA and hits a chunky pseudoknot, it gets physically stuck or slowed down. This structural roadblock forces the machine to change how it reads the genetic code, allowing the cell to control exactly how much of a protein gets made.

## c-noncanonical-pairing
Non-canonical base pairings are alternative H-bonding arrangements between nucleic acid bases, including reverse Watson-Crick, wobble, and Hoogsteen pairings.

## c-noncanonical-pairing:summary
### Stage 3 — Beyond Normal Base Pairing: Non-Canonical Base Pairing

In Stage 2, we learned that RNA folds into complex structures. But this raises an important question: **How can RNA fold into so many different shapes if bases only pair as A-U and G-C?** The answer: **They don't.** Besides the normal Watson-Crick base pairs, nucleic acids can form **non-canonical (non-standard) base pairs**. These unusual pairings make complex RNA and DNA structures possible.

#### The Normal Rule

Watson-Crick base pairs (A-T/A-U and G-C) are the most stable, most common, and responsible for accurate DNA replication. If only these existed, DNA and RNA would have very limited shapes.

#### What is Non-Canonical Base Pairing?

**Non-canonical** means any base pairing that is NOT the standard Watson-Crick pairing. These pairings are less common but extremely important — they allow DNA and RNA to fold into unusual shapes, regulate genes, bind proteins, recognize other RNAs, and perform catalytic functions. Think of Watson-Crick pairing as driving on a normal road. Non-canonical pairing is like taking shortcuts or side roads to reach places the main road cannot.

#### 1. Wobble Base Pair

The G-U wobble pair is one of the most famous non-canonical pairings. The hydrogen bonds are different from G-C, but the pair is still stable enough to exist. During translation, one tRNA can recognize several codons because of wobble pairing at the third nucleotide position. This explains why **64 codons can be read using fewer than 64 tRNAs**.

#### 2. Reverse Watson-Crick Pairing

Normally, bases meet in one orientation. Sometimes they rotate and pair differently while still forming hydrogen bonds. Think of two people shaking hands — normally right hand to right hand, reverse pairing is like left hand to left hand. Still connected, just differently. These pairings help stabilize unusual RNA structures.

#### 3. Hoogsteen Base Pairing

In Hoogsteen pairing, the purine base rotates into a different orientation, using a different edge to form hydrogen bonds. Hoogsteen pairing helps form triplex DNA, protein-DNA complexes, DNA under stress, and regulatory DNA structures. Some DNA-binding proteins actually prefer Hoogsteen base pairs.

#### 4. Tautomerization

Bases are not completely rigid. Occasionally they temporarily change their chemical structure — keto to enol, or amino to imino. These rare tautomeric forms can change which bases pair together. Sometimes DNA polymerase mistakes these unusual pairings for correct ones, producing mutations after DNA replication. Rare tautomeric forms are one source of spontaneous mutations.

#### 5. G-Quadruplexes

Sometimes four guanine bases come together to form a G-quartet (a square arrangement). Several stacked G-quartets form a **G-quadruplex**. Often found in telomeres, promoter regions, and oncogenes. Scientists believe they help regulate gene expression, DNA replication, and chromosome stability.

#### 6. Triplex DNA

Normally DNA has two strands. Sometimes a third strand binds in the major groove using **Hoogsteen hydrogen bonds**, creating **Triplex DNA**. Triplex DNA can regulate gene expression, interfere with transcription, and participate in chromosome organization. Scientists are studying it as a possible gene therapy tool.

#### The Flow

Watson-Crick pairing → Wobble → Hoogsteen → Reverse Watson-Crick → G-Quadruplexes → Triplex DNA. These additional interactions greatly expand the possible shapes of nucleic acids.

#### Big Picture

DNA and RNA are not rigid molecules — they are flexible molecular machines. Different base-pairing patterns allow them to fold, regulate genes, recognize proteins, repair DNA, control translation, and evolve new biological functions.

#### Key Takeaways

- Watson-Crick pairing (A-T/A-U and G-C) is the standard form of base pairing.
- Non-canonical base pairing includes wobble, Hoogsteen, reverse Watson-Crick, and other unusual interactions.
- G-U wobble pairing allows one tRNA to recognize multiple codons.
- Hoogsteen pairing is essential for triplex DNA and some protein-DNA interactions.
- Rare tautomeric forms of bases can lead to mutations during DNA replication.
- G-quadruplexes are four-stranded guanine-rich structures involved in gene regulation and chromosome stability.
- Triplex DNA contains a third DNA strand bound in the major groove by Hoogsteen hydrogen bonds.
- Non-canonical base pairing greatly increases the structural and functional diversity of nucleic acids.

## c-reverse-watson-crick
Reverse Watson-Crick pairing occurs when pyrimidines rotate 180° to align H-bond donors with acceptors in an antiparallel glycosidic arrangement.

## c-reverse-watson-crick:summary
Pyrimidine rotation enables alternative base-pairing geometry. Found at DNA strand ends and in RNA structures. Maintains H-bonding while changing geometry.

#### Reverse Watson-Crick Pairing — Plain English

Normally, bases meet in one orientation. Sometimes they rotate and pair differently while still forming hydrogen bonds. Think of two people shaking hands — normally right hand to right hand. Reverse pairing is like left hand to left hand. Still connected, just differently.

**Why does RNA do this?** RNA folds into extremely complicated shapes — hairpins, loops, bulges, junctions. Sometimes normal pairing does not fit. Reverse Watson-Crick lets RNA bend without breaking. Think of folding paper — sometimes you need to rotate a piece to make the model.

**Exam point:** Reverse Watson-Crick pairing helps stabilize unusual RNA structures.

**Memory aid:** Reverse Watson-Crick = "Same partners, different orientation."

## c-wobble-pairing
Wobble base pairing occurs through tautomerization, forming noncanonical G-U and G-T(U) pairs. Critical for tRNA anticodon-codon recognition.

## c-wobble-pairing:summary
G-U wobble pairing is a naturally occurring noncanonical base pair that does NOT require tautomerization (though rare tautomeric forms can cause other mismatches). Nearly as stable as Watson-Crick pairs. The wobble position allows fewer than 61 tRNAs to decode all 61 sense codons.

#### Wobble Base Pairing — Plain English

Normally G pairs with C and U pairs with A. But in RNA, G can sometimes pair with U. It is not as strong as G-C, but it still works — like two LEGO blocks that do not quite match but still clip together.

**Why does this happen?** During translation, mRNA contains codons and tRNA has anticodons. The first two bases must match exactly. The third base can wobble. For example, codons UUU and UUC both code for phenylalanine. Instead of making two different tRNAs, one tRNA can recognize both because of wobble at the third position.

**Why is wobble useful?** There are 64 codons but humans have roughly 40-45 tRNAs. Because one tRNA can read several codons, we do not need 64 different tRNAs.

**Easy exam point:** Wobble occurs at the third base of the codon (first base of the anticodon) and allows one tRNA to recognize multiple codons.

**Memory aid:** Wobble = "Wrong partner, but only a little" (G-U pairing in RNA).

## c-tautomerism
Tautomerism allows bases to shift between amino-imino and keto-enol forms, enabling Hoogsteen pairing via the syn glycosidic orientation.

## c-tautomerism:summary
Anti orientation = Watson-Crick pairing. Syn orientation = Hoogsteen pairing (purine rotates from anti to syn). Tautomeric shifts can cause mispairing and mutations during DNA replication.

#### Hoogsteen Base Pairing — Plain English

Every base has several "sides" that can form hydrogen bonds. Imagine a cube with Front, Back, Left, Right, Top, Bottom. Normally bases use the Watson-Crick edge. Hoogsteen pairing uses a different side — the Hoogsteen edge. The purine (A or G) rotates. Same two bases, different contact surface.

**Why is this important?** Sometimes DNA is bent or under stress. Proteins bind DNA. DNA twists. Cells regulate genes. Hoogsteen pairing helps DNA survive these situations. It is found in triplex DNA, protein-DNA complexes, DNA under mechanical stress, and regulatory DNA.

Think of it like a normal door that opens normally versus a Hoogsteen door that opens from another hinge. Still a door, different movement.

**Memory aid:** Hoogsteen = "Same partners, different bonding face."

#### Tautomerization — Plain English

Bases normally exist in stable forms. But sometimes, very briefly, a base changes form — keto to enol, or amino to imino. These are called tautomers.

Think of it like this: your friend normally wears blue. One day, for only a few seconds, he wears red. You mistake him for someone else. That is exactly what DNA polymerase does. If a base changes form temporarily, it may pair incorrectly. DNA polymerase thinks "Looks okay" and copies it. After the next round of replication, the mistake becomes permanent. That is a mutation.

Example: Normal A-T pair. A temporarily changes to a rare tautomer. DNA polymerase copies A* with C. Later, C pairs with G. Now the original A-T became G-C. Permanent mutation. This is one cause of spontaneous mutations — mutations that happen naturally without radiation or chemicals.

**Memory aid:** Tautomerization = "The base temporarily changes its identity, so it pairs with the wrong partner."

#### Quick Comparison

| Concept | What changes? | Where is it important? |
|---------|--------------|----------------------|
| Wobble pairing | G pairs with U instead of C | Translation; one tRNA recognizes multiple codons |
| Reverse Watson-Crick | Bases pair in reversed orientation | Stabilizes complex RNA structures |
| Hoogsteen pairing | Purine rotates, uses different bonding edge | Triplex DNA, protein-DNA binding, stressed or regulatory DNA |
| Tautomerization | Base temporarily changes chemical form | Can cause incorrect base pairing and spontaneous mutations |

## c-dna-supercoiling
DNA can adopt cruciform structures from palindromic sequences and superhelical conformations affected by topological constraints and intercalating drugs.

## c-dna-supercoiling:summary
### Stage 4 — DNA Topology: How DNA Twists, Coils, and Packs Itself

DNA in humans is about 2 meters long. How does it fit inside a nucleus that is only about 6 micrometers wide? **DNA twists, coils, and folds.** This is called DNA topology.

#### The Big Idea

DNA is not just a straight double helix. It can twist, supercoil, loop, fold, and unwind. These changes help the cell package DNA, replicate DNA, repair DNA, and regulate gene expression. Think of a telephone cable — if you keep twisting it, it begins to coil. DNA behaves similarly.

#### Levels of DNA Organization

Step 1: A straight rope — the normal DNA double helix. Step 2: Twisting the rope — supercoiling. Step 3: Coiling the coils — eventually the DNA becomes highly compact, allowing enormous DNA molecules to fit inside tiny cells.

#### What is DNA Supercoiling?

Supercoiling means the DNA double helix twists around itself. DNA already has one twist (the double helix). Supercoiling is an **additional level of twisting** — think of twisting an already twisted rope.

#### Why Does DNA Supercoil?

Whenever DNA is opened (during replication, transcription), the remaining DNA experiences mechanical stress. Imagine unzipping part of a zipper — the unopened part twists tighter. Exactly the same thing happens in DNA.

#### Positive vs Negative Supercoiling

**Positive supercoiling:** DNA becomes overwound — harder to separate strands, more compact, slows replication. **Negative supercoiling:** DNA becomes underwound — easier to open DNA, promotes replication and transcription. Most bacteria maintain negatively supercoiled DNA because it makes gene expression easier.

#### Topoisomerases

If DNA keeps twisting, eventually it becomes impossible to copy. Cells solve this using **topoisomerases** — DNA untangling machines.

**Type I Topoisomerase:** Cuts one DNA strand. Relieves supercoiling. Does not require ATP.

**Type II Topoisomerase:** Cuts both DNA strands. Removes knots, tangles, and separates chromosomes after replication. Usually requires ATP.

Without topoisomerases, replication and transcription would stop, and chromosomes could not separate. Many antibiotics and anticancer drugs work by inhibiting topoisomerases.

#### Palindromic DNA Sequences

Some DNA sequences read the same in the 5' → 3' direction on both strands (e.g., 5'-GAATTC-3' / 3'-CTTAAG-5'). Called a **DNA palindrome**. Recognized by restriction enzymes and DNA-binding proteins. Can also form unusual DNA structures.

#### Cruciform DNA

If DNA contains an inverted repeat, both strands fold outward, resembling a cross — hence **cruciform**. Each arm contains a hairpin structure. Forms because complementary bases within the same strand pair with each other, similar to how RNA forms hairpins. Scientists believe cruciform structures help with gene expression regulation, DNA replication, recombination, and chromosome organization.

#### Triplex DNA (Revisited)

Normally DNA has two strands. Sometimes a third strand binds in the **major groove** using **Hoogsteen hydrogen bonds**, creating triplex DNA. Forms mainly in purine-rich sequences. May regulate transcription, affect chromosome stability, influence DNA repair. Researchers are studying it for targeted gene therapy.

#### Connecting Everything

Stage 1: DNA stores information, RNA performs functions. Stage 2: RNA folds into complex structures. Stage 3: Special base pairings make those structures possible. Stage 4: DNA itself is dynamic — it twists, supercoils, forms cruciform structures, forms triplex DNA — allowing the cell to package DNA and regulate genes efficiently.

#### Big Picture

DNA is much more than a double helix. It is a dynamic molecule that constantly changes its shape to meet the cell's needs. The cell controls these changes using DNA sequence, proteins, topoisomerases, and mechanical forces generated during replication and transcription. **Structure determines function.**

#### Key Takeaways

- DNA topology describes how DNA twists and folds in three dimensions.
- Supercoiling helps package DNA and influences replication and transcription.
- Positive supercoiling overwinds DNA, while negative supercoiling underwinds it.
- Topoisomerases relieve DNA tension by cutting and rejoining DNA strands.
- Palindromic DNA sequences are important recognition sites for restriction enzymes and can form cruciform structures.
- Cruciform DNA forms from inverted repeat sequences that fold into hairpins.
- Triplex DNA contains a third strand bound in the major groove through Hoogsteen hydrogen bonds.
- DNA is a dynamic molecule whose shape changes to support its biological functions.

## c-cruciform
Cruciform DNA forms from palindromic sequences creating two hairpin arms with 3-4 unpaired bases at tips, joined at a four-way junction.

## c-cruciform:summary
Palindromic sequences read the same 5' to 3' on both strands. Interstrand and intrastrand H-bonds create hairpins. Structure consists of two hairpin arms and two duplex arms.

## c-triplex-dna
Triplex DNA forms when a third strand binds the major groove of B-DNA via Hoogsteen hydrogen bonds with purines in base pairs.

## c-triplex-dna:summary
A-T and G-C pairs expose H-bond donors/acceptors in the major groove. Third strand uses Hoogsteen pairing. Potential applications in gene therapy.

## c-dna-replication
DNA replication occurs in S-phase via semi-conservative mechanism. Synthesis proceeds 5' to 3', with leading strand continuous and lagging strand in Okazaki fragments.

## c-dna-replication:summary
### Stage 5 — DNA Replication, Denaturation, and Renaturation

So far: Stage 1 — DNA stores genetic information. Stage 2 — RNA folds into functional molecules. Stage 3 — Special base pairings create diverse nucleic acid structures. Stage 4 — DNA twists and supercoils to fit inside cells. Now: **If DNA stores genetic information, how does a cell make an exact copy before it divides?** The answer is DNA replication.

#### Why Must DNA Replicate?

Every new cell needs a complete copy of the genome. Without replication, daughter cells would not inherit genetic information — growth, repair, and reproduction would be impossible.

#### When Does DNA Replication Occur?

During the **S (Synthesis) phase** of the cell cycle (G1 → S → G2 → M). After replication, each chromosome consists of two identical sister chromatids.

#### Semi-Conservative Replication

Every new DNA molecule contains **one old (parental) strand** and **one newly synthesized strand**. Called semi-conservative because **half of the original molecule is conserved** in each daughter DNA molecule. The old strand acts as a **template** — each base tells the cell which nucleotide to add next, ensuring accurate copying.

#### DNA Replication Always Proceeds 5' → 3'

DNA polymerase can **only add nucleotides to the 3'-OH end** of a growing strand. Each new nucleotide forms a phosphodiester bond using the free 3'-OH group of the previous nucleotide. No free 3'-OH means no extension.

#### Leading and Lagging Strands

DNA consists of two antiparallel strands. **Leading strand:** DNA polymerase can continuously synthesize DNA. **Lagging strand:** DNA polymerase cannot work continuously because it must still synthesize 5' → 3'. Instead, it builds short fragments called **Okazaki fragments**, later joined by **DNA ligase**.

#### Denaturation

DNA strands separate when exposed to high temperature, extreme pH, or certain chemicals. The hydrogen bonds break, but **the phosphodiester backbone does NOT break** — only hydrogen bonds between complementary bases are disrupted.

#### Melting Temperature (Tm)

The temperature at which **50% of DNA molecules are double-stranded and 50% are single-stranded**. Not the temperature where all DNA melts.

**GC content:** G-C pairs have 3 hydrogen bonds (stronger bonding, higher Tm). **AT content:** A-T pairs have 2 hydrogen bonds (weaker bonding, lower Tm). Rule: More G-C → Higher Tm. More A-T → Lower Tm.

#### Renaturation (Reannealing)

When conditions return to normal, separated strands can come back together. Also called reannealing or hybridization (especially when complementary strands from different sources pair). Many laboratory techniques depend on it: PCR, DNA probes, Southern blotting, DNA sequencing.

#### DNA-RNA Hybridization

DNA can also pair with complementary RNA, forming DNA-RNA hybrids. Important during transcription, reverse transcription, and molecular biology experiments.

#### The Flow

DNA stores information → DNA changes shape (B, A, Z forms) → DNA twists and supercoils → DNA must be copied → Replication begins → Hydrogen bonds separate (Denaturation) → New strands are synthesized (5' → 3') → Complementary strands pair again (Renaturation).

#### Key Takeaways

- DNA replication occurs during the **S phase** of the cell cycle.
- DNA replication is **semi-conservative** — each daughter DNA contains one old strand and one new strand.
- DNA polymerase always synthesizes DNA in the **5' → 3' direction**.
- The leading strand is synthesized continuously, while the lagging strand is synthesized as **Okazaki fragments**.
- **Denaturation** separates DNA strands by breaking hydrogen bonds, not phosphodiester bonds.
- **Melting temperature (Tm)** is the temperature at which half of the DNA molecules are denatured.
- DNA with a higher **GC content** has a higher melting temperature.
- **Renaturation (reannealing)** occurs when complementary strands pair again under suitable conditions.
- Complementary base pairing is the foundation of DNA replication and many molecular biology techniques.

## c-semi-conservative
Semi-conservative replication: each daughter DNA has one original and one new strand, proven by Meselson-Stahl experiment (1958).

## c-semi-conservative:summary
Predicted by Watson and Crick. Confirmed using 15N/14N density gradient centrifugation. Each strand serves as template for new complementary strand.

## c-denaturation-renaturation
Denaturation separates DNA strands (heat/salt changes). Renaturation (hybridization) occurs when strands reassociate at appropriate conditions. Tm = 50% denatured.

## c-denaturation-renaturation:summary
Tm is the melting temperature where 50% of base pairs are disrupted. Cooperative transition. Renaturation depends on concentration, temperature, and salt. Basis for PCR and Southern blotting.

## c-nucleic-acid-hydrolysis
Nucleic acids hydrolyze with acid (glycosidic bond cleavage), alkali (RNA via 2'-OH), and enzymatically by nucleases (exonucleases and endonucleases).

## c-nucleic-acid-hydrolysis:summary
### Stage 6 — Cutting DNA: Hydrolysis, Nucleases, and Restriction Enzymes

In Stage 5, we learned how DNA is copied. Now: **If cells can copy DNA, can they also destroy or cut DNA?** Yes. Cells constantly cut DNA and RNA — sometimes normally (DNA repair), controlled (gene regulation), defensively (against viruses), or experimentally (genetic engineering). The process of breaking nucleic acids is called **hydrolysis**.

#### What is Hydrolysis?

Breaking a chemical bond by adding water. "Hydro" = water, "Lysis" = break.

#### Which Bonds Can Be Broken?

**Phosphodiester bond:** Connects one nucleotide to the next. Breaking this cuts the DNA/RNA backbone. **N-glycosidic bond:** Connects the nitrogenous base to the sugar. Breaking this removes the base but leaves the backbone, creating an **AP site (Apurinic/Apyrimidinic site)**.

#### Acid Hydrolysis

Strong acids mainly break the **N-glycosidic bond**, removing purines (adenine and guanine) — called **depurination**. Creates AP sites.

#### Alkaline Hydrolysis

RNA has the **2'-OH group** which attacks the phosphodiester bond under alkaline conditions, breaking RNA. DNA lacks the 2'-OH group, so it is much more resistant to alkaline hydrolysis. That tiny OH group makes RNA more reactive, less chemically stable, and easier to degrade — this is why RNA experiments require great care.

#### Chemical vs Enzymatic Hydrolysis

**Chemical:** Uses acids, alkalis, chemicals. Less specific. **Enzymatic:** Uses enzymes called **nucleases**. Highly specific. Much more common in living cells.

#### What Are Nucleases?

Nucleases are enzymes that cut nucleic acids — **molecular scissors**. Different nucleases cut in different ways.

**Exonucleases:** Remove nucleotides from the **ends** of DNA or RNA. Like eating corn one kernel at a time. Some work from the 5' end, others from the 3' end.

**Endonucleases:** Cut **within** the molecule. Make internal cuts rather than trimming ends.

| Exonuclease | Endonuclease |
|-------------|--------------|
| Cuts from the ends | Cuts inside the strand |
| Removes one nucleotide at a time | Makes internal cuts |
| Useful for proofreading | Useful for repair and defense |

**DNases** cut DNA. **RNases** cut RNA.

#### Restriction Endonucleases

Special endonucleases found naturally in bacteria. Their job is to protect bacteria from invading viruses (bacteriophages). Each recognizes a **specific DNA sequence** — like a lock and key.

#### Palindromic Sequences

Most restriction enzymes recognize **palindromic DNA sequences** (e.g., 5'-GAATTC-3' / 3'-CTTAAG-5'). Reading each strand from 5' → 3' gives the same sequence. This symmetry allows the enzyme to bind both strands correctly.

#### Example: BamHI

Recognition sequence: 5'-G↓GATCC-3' / 3'-CCTAG↑G-5'. Many restriction enzymes leave **sticky ends** (short overhangs that can base-pair with matching DNA), ideal for joining DNA during cloning. Others produce **blunt ends** (no overhangs).

#### Why Do Bacteria Have Restriction Enzymes?

When a virus injects its DNA, the bacterial restriction enzyme recognizes and cuts the foreign DNA. To avoid cutting its own DNA, the bacterium chemically modifies (methylates) its own recognition sites — creating a **restriction-modification system**.

#### Why Are Restriction Enzymes Important in Biotechnology?

Scientists use them to cut DNA at precise locations, insert genes into plasmids, create recombinant DNA, clone genes, and prepare DNA for sequencing. Without restriction enzymes, modern genetic engineering would be extremely difficult.

#### The Flow

DNA stores information → DNA replicates → Sometimes DNA becomes damaged → Cells cut damaged DNA → Nucleases perform controlled cutting → Restriction enzymes provide precise DNA cutting → Scientists use the same enzymes for genetic engineering.

#### Key Takeaways

- **Hydrolysis** is the breaking of chemical bonds using water.
- DNA contains **phosphodiester bonds** (between nucleotides) and **N-glycosidic bonds** (between the base and sugar).
- Acid hydrolysis commonly causes **depurination** by breaking N-glycosidic bonds.
- RNA is more susceptible to alkaline hydrolysis because of its **2'-OH group**.
- **Nucleases** are enzymes that degrade DNA or RNA.
- **Exonucleases** remove nucleotides from the ends, while **endonucleases** cut within a nucleic acid strand.
- **Restriction endonucleases** recognize specific DNA sequences, usually palindromes, and cut at or near those sites.
- Bacteria use restriction enzymes as a defense against viruses, while protecting their own DNA through **methylation**.
- Restriction enzymes are indispensable tools in recombinant DNA technology and molecular cloning.

#### Plain English Guide to Nucleic Acid Hydrolysis

This explains why DNA is stable enough to store genetic information for your whole life while RNA is much more fragile.

**What exactly are we breaking?**

Think of DNA like a train. Passengers = bases. Train cars = sugar. Couplers = phosphate. The whole train is DNA.

```
Base   Base   Base   Base
 |      |      |      |
Sugar--P--Sugar--P--Sugar--P--Sugar
```

**1. Phosphodiester Bond — cutting the string**

This bond joins one nucleotide to the next. Like a necklace: Bead --- String --- Bead. Cut the string and the necklace breaks into pieces. Breaking the phosphodiester bond cuts the DNA or RNA backbone — this is called strand cleavage.

**2. N-glycosidic Bond — pulling off a bead**

This bond connects the base to the sugar. Imagine a Christmas tree with a star on top. If the star falls off, the tree is still standing — the star is gone. The sugar-phosphate backbone remains, but the base disappears. This empty spot is called an AP site (Apurinic/Apyrimidinic site — "a place where a base used to be").

**Acid Hydrolysis — attacking purines**

Strong acid mainly attacks the N-glycosidic bond, not the backbone. Purines (A and G) fall off most easily because they have two rings, making their bond more susceptible. Loss of purines is called depurination. Result: AP sites.

**Alkaline Hydrolysis — RNA cuts itself**

Under alkaline conditions (NaOH), RNA is destroyed but DNA survives. Why? RNA has the 2'-OH group on its sugar. That OH attacks the phosphodiester bond and cuts the backbone — RNA literally cuts itself under alkaline conditions. DNA lacks the 2'-OH, so it is stable.

This matters because cells want RNA to disappear quickly. Messenger RNA only needs to exist for a short time. If RNA were as stable as DNA, cells could not control protein production efficiently. DNA must last for decades. That is why DNA lacks the 2'-OH.

**Chemical vs Enzymatic Hydrolysis**

Chemical hydrolysis uses acids/alkalis — less specific, can damage many molecules, used in laboratories. Enzymatic hydrolysis uses enzymes called nucleases — highly specific, knows exactly where/when/what to cut. Living cells use enzymes, not acids.

**Memory trick:** Think of DNA as a beaded necklace. Break the string (phosphodiester bond) = necklace snaps. Pull off a bead (N-glycosidic bond) = necklace stays intact but has an empty spot (AP site).

DNA = "D" for Durable because it lacks the 2'-OH group. RNA = "R" for Reactive because the 2'-OH can attack its own backbone under alkaline conditions.

## c-exonucleases
Exonucleases cleave nucleotides one at a time from the end of a polynucleotide chain, classified as 3' or 5' specific.

## c-exonucleases:summary
3' exonucleases degrade from the 3' end, 5' from the 5' end. Roles in DNA repair, recombination, and foreign DNA degradation. Examples: exonuclease III (3'), T7 gene 6 (5').

## c-endonucleases
Endonucleases cleave phosphodiester bonds at specific internal sites within polynucleotide chains. Include both RNases and DNases.

## c-endonucleases:summary
Cut within the chain, not from ends. Essential for DNA repair, recombination, and restriction digestion. Many are sequence-specific (restriction enzymes).

## c-restriction-enzymes
Restriction endonucleases recognize specific palindromic sequences and cleave both strands. First isolated from bacteria as defense against bacteriophages.

## c-restriction-enzymes:summary
Type II enzymes cut at predictable positions. Example: BamHI recognizes 5'-GGATCC-3' and cuts between the Gs. Produce sticky or blunt ends. Foundation of molecular cloning.

## c-chemical-synthesis
Nucleic acids are synthesized via solid-phase phosphoramidite chemistry, producing oligonucleotides of 10-200 bp in the 3' to 5' direction (opposite to biological synthesis).

## c-chemical-synthesis:summary
### Stage 7 — Building DNA: Chemical Synthesis of Nucleic Acids

In Stage 6, we learned how DNA can be cut. Now: **If scientists can cut DNA, can they also build DNA from scratch?** Yes. Using chemical synthesis, scientists can build almost any short DNA or RNA sequence they want. This is one of the foundations of modern biotechnology.

#### Natural vs Chemical DNA Synthesis

| Natural (Inside Cells) | Chemical (Laboratory) |
|-------------------------|------------------------|
| DNA polymerase builds DNA | Chemists use chemical reactions |
| Uses a DNA template | No template is needed |
| Copies existing DNA | Creates a new sequence from scratch |
| Occurs 5' → 3' | Built 3' → 5' on a solid support |

#### Why Build DNA Artificially?

To make PCR primers, DNA probes, CRISPR guide RNAs, synthetic genes, DNA for sequencing, diagnostic tests, and mRNA vaccine templates. Instead of finding DNA in nature, scientists simply **order the exact sequence they need**.

#### The Basic Idea

Like building a LEGO tower — one brick at a time. One nucleotide is added during each cycle. The very first nucleotide is attached to tiny solid beads (controlled pore glass, CPG), keeping the DNA fixed in place while chemicals are washed over it. At the end, the completed DNA is detached from the support.

#### Protecting Groups

A nucleotide has several reactive chemical groups. If all reacted at once, DNA would be built incorrectly. Chemists temporarily **protect** certain groups — like masking tape while painting a wall. The most common protecting group is **DMT (Dimethoxytrityl)**, which temporarily blocks the **5'-OH group**. Only when that group is uncovered can another nucleotide be added.

#### The Four-Step Synthesis Cycle

Each nucleotide is added through the same cycle:

1. **Detritylation:** The DMT protecting group is removed, freeing the 5'-OH for the next nucleotide.
2. **Coupling:** A new nucleotide (as a phosphoramidite) is added, forming an unstable **phosphite triester** linkage.
3. **Oxidation:** The unstable phosphite linkage is converted into a stable **phosphodiester bond** — the same type found in natural DNA.
4. **Capping:** Incomplete chains that didn't receive the new nucleotide are blocked by chemically blocking their free 5'-OH. Correctly growing chains continue; failed chains stop permanently. This greatly improves purity.

The same four reactions are repeated until the desired sequence is complete. Then the DNA is detached from the solid support, protecting groups are removed, and the final oligonucleotide is purified.

#### How is RNA Different?

RNA contains an extra **2'-OH group**, creating two reactive OH groups (5'-OH and 2'-OH). RNA synthesis requires an additional protecting group (commonly **TBDMS**) for the 2'-OH, removed after synthesis is complete.

#### Applications

- **PCR primers:** Short DNA molecules that tell DNA polymerase where to begin copying.
- **DNA sequencing:** Synthetic primers determine nucleotide sequences.
- **Gene synthesis:** Scientists can chemically create genes instead of isolating them from organisms.
- **CRISPR:** Guide RNAs used in CRISPR gene editing are chemically synthesized.
- **Vaccines:** Modern mRNA vaccines rely on chemically synthesized nucleic acid components. Synthetic nucleic acid technology played a key role in the rapid development of SARS-CoV-2 vaccines.

#### The Flow

DNA stores information → DNA replicates naturally → DNA can be cut by nucleases → Scientists learn to cut DNA precisely → Scientists also learn to build DNA from scratch → Modern biotechnology becomes possible. The ability to **cut** and **build** DNA forms the basis of genetic engineering.

#### Key Takeaways

- Chemical DNA synthesis creates DNA **without using DNA polymerase**.
- DNA is assembled **one nucleotide at a time** on a solid support.
- Laboratory synthesis proceeds in the **3' → 5' direction**, opposite to biological DNA synthesis.
- The four main steps: **Detritylation, Coupling, Oxidation, Capping**.
- Protecting groups ensure that only the correct chemical reactions occur during synthesis.
- RNA synthesis requires additional protection of the **2'-OH group**.
- Synthetic nucleic acids are essential for PCR, DNA sequencing, CRISPR, gene synthesis, diagnostics, and modern vaccine technology.

## c-synthesis-cycle
The phosphoramidite cycle: (1) Detritylation - remove DMT, (2) Coupling - add monomer, (3) Oxidation - phosphite to phosphodiester, (4) Capping - block unreacted 5'-OH.

## c-synthesis-cycle:summary
3 steps theoretically needed; capping is industrial addition to prevent short oligomers. Detritylation: acid removes DMT. Coupling: activate phosphoramidite. Oxidation: I2/H2O. Capping: acetic anhydride.

#### Plain English Guide to Phosphoramidite Synthesis

This is the standard laboratory method used to synthesize DNA (and modified RNA). Suppose you want to make 5'-ATGC-3'. The machine does not build the whole strand at once. It adds one nucleotide per cycle. Every nucleotide goes through the same cycle.

**Why "3 steps theoretically, 4 in practice"?**

Chemically, you only need three reactions to make DNA: Detritylation, Coupling, and Oxidation. These three are enough to keep extending the chain. But chemistry is not perfect. Not every DNA molecule successfully receives the new nucleotide. That is why industry added Capping — it is not required for the chemistry itself, it improves the quality of the final product.

**The Four Steps**

**1. Detritylation — Remove the DMT protecting group**

The DMT group acts like a cap on the 5'-OH. The next nucleotide cannot attach while it is there. Using weak acid (usually trichloroacetic acid / TCA), the DMT is removed, exposing the free 5'-OH. Now the chain is ready for the next nucleotide.

**2. Coupling — Add the next nucleotide**

The nucleotide is not added in its natural form. Instead it comes as a phosphoramidite — a highly reactive building block designed specifically for DNA synthesis. Chemists first activate the phosphoramidite (commonly with tetrazole), making it reactive enough to join the growing chain. The bond formed is initially an unstable phosphite triester.

**3. Oxidation — Stabilize the bond**

The phosphite triester is not stable enough. Using iodine plus water (I₂ + H₂O), the phosphite triester is converted into a normal phosphodiester bond — identical to that found in natural DNA.

**4. Capping — Block failed chains**

Suppose you have 100 DNA molecules. During coupling, 98 react and 2 fail. Those 2 still have a free 5'-OH. If nothing is done, they may react in a later cycle, producing DNA molecules of the wrong length. Using acetic anhydride, chemists permanently block those failed chains. The acetic anhydride converts the free 5'-OH into an acetate ester that can no longer react. Only correctly growing chains continue.

**Why capping improves purity:** Without capping, you get a messy mixture of different lengths (ATGC, ATGCA, ATGCAT, ATGCATCG). With capping, only the full-length DNA keeps growing. The short fragments stop permanently and are removed during purification.

**Chemical summary:**

| Step | Chemical | Job |
|------|----------|-----|
| Detritylation | Acid (TCA) | Removes the DMT protecting group from the 5'-OH |
| Coupling | Activated phosphoramidite | Adds the next nucleotide |
| Oxidation | I₂ + H₂O | Converts unstable phosphite triester into stable phosphodiester bond |
| Capping | Acetic anhydride | Permanently blocks failed DNA chains |

**Exam flow:**
DNA Chain → 1. Detritylation (remove DMT with acid) → 2. Coupling (add activated phosphoramidite) → 3. Oxidation (I₂ + H₂O) → 4. Capping (acetic anhydride blocks failures) → Repeat until complete.

**One thing to remember for exams:** Many lecturers say "3 steps" because detritylation, coupling, and oxidation are the reactions required to build the DNA strand. Capping is considered an industrial/process optimization — it does not extend the DNA chain, but it greatly improves purity. That is why some notes say 3 steps theoretically and 4 steps in practice.

## c-rna-synthesis
RNA synthesis requires 2'-OH protection using TBDMS (t-butyldimethylsilyl), removed by fluoride ion treatment after synthesis.

## c-rna-synthesis:summary
2'-OH is reactive and makes RNA susceptible to degradation. TBDMS is stable during synthesis but selectively removed with fluoride (TBAF). Critical difference from DNA synthesis.

## c-dna-methylation
DNA methylation adds methyl groups to DNA as an epigenetic mechanism. Catalyzed by DNMTs transferring methyl from SAM to cytosine, forming 5-methylcytosine.

## c-dna-methylation:summary
### Stage 8 — DNA Methylation: How Cells Control Genes Without Changing DNA

So far: DNA stores information, replicates, can be cut, and can be built artificially. Now: **If every cell in your body contains the same DNA, why is a brain cell different from a liver cell?** The answer: **Not every gene is active in every cell.** Cells control which genes are turned ON or OFF. One of the most important ways they do this is through **DNA methylation**.

#### The Big Idea

DNA methylation is an **epigenetic modification** — changes that affect gene expression without changing the DNA sequence itself. Think of your DNA as a book. The letters never change. Instead, the cell places **sticky notes** on certain pages saying "Don't read this page." The words remain unchanged, but they are no longer used.

#### What is DNA Methylation?

The addition of a **methyl group (-CH₃)** to DNA, attached mainly to the **5th carbon of cytosine**. The modified base is called **5-methylcytosine (5mC)**.

#### Where Does Methylation Occur?

Most DNA methylation in humans occurs at **CpG sites** — where C is followed by G (the "p" stands for the phosphate linking them). Regions containing many CpG sites are called **CpG islands**, commonly found near **gene promoters** (where RNA polymerase binds to begin transcription).

#### The Enzyme Responsible

**DNA methyltransferase (DNMT)** transfers a methyl group from **SAM (S-adenosylmethionine)** to cytosine, producing **SAH (S-adenosylhomocysteine)**. Think of SAM as a delivery truck carrying methyl groups.

#### What Happens After DNA is Methylated?

Methyl groups near promoters prevent RNA polymerase and transcription factors from binding effectively. So methylation generally **reduces or silences gene expression**. The DNA sequence itself is unchanged — only a small chemical tag has been added. That is why methylation is considered **epigenetic**, not genetic.

#### Examples in the Human Body

**Brain cell:** Genes for nerve function are active; muscle-specific genes are mostly inactive. **Muscle cell:** Muscle genes are active; neuron-specific genes are methylated and inactive. **Liver cell:** Liver genes are active; brain genes are largely inactive. Even though all these cells contain the **same DNA**, they behave differently because they express different sets of genes.

#### Biological Roles

- **Gene Regulation:** Controls which genes are turned on or off.
- **Embryonic Development:** Different cells acquire different methylation patterns, helping cells become neurons, muscle cells, blood cells, etc.
- **X-Chromosome Inactivation:** Females have two X chromosomes; one is largely inactivated through epigenetic mechanisms including DNA methylation, preventing an overdose of X-linked gene products.
- **Genomic Imprinting:** For a small number of genes, only the copy inherited from the mother OR father is expressed. Methylation helps determine which copy remains active.
- **Chromosome Stability:** Methylation suppresses repetitive DNA sequences and helps maintain genome stability.

#### DNA Methylation and Disease

**Hypermethylation:** Too much methylation. A tumor suppressor gene becomes heavily methylated → turned OFF → cells divide uncontrollably → cancer. **Hypomethylation:** Too little methylation → activation of harmful genes, chromosomal instability, increased mutation rates. Abnormal methylation patterns are associated with cancer, imprinting disorders, and some neurological diseases.

#### Is DNA Methylation Permanent?

Not always. Some methylation marks are maintained for long periods, especially during cell division. Others can be removed or altered in response to development or environmental signals. Gene expression can change without altering the DNA sequence.

#### The Flow

DNA stores information → DNA replicates → DNA can be cut → DNA can be synthesized → DNA activity must now be controlled → DNA methylation turns genes ON or OFF.

#### Key Takeaways

- **DNA methylation** is the addition of a methyl (-CH₃) group to the **5th carbon of cytosine**.
- It occurs mainly at **CpG sites**, especially within **CpG islands** near gene promoters.
- The enzyme **DNMT** transfers the methyl group from **SAM** to cytosine, producing **SAH**.
- DNA methylation usually **reduces gene expression** by preventing transcription factors and RNA polymerase from effectively initiating transcription.
- Methylation does **not change the DNA sequence**, making it an **epigenetic** modification.
- DNA methylation is essential for normal development, cell differentiation, X-chromosome inactivation, genomic imprinting, and chromosome stability.
- Abnormal methylation patterns are linked to diseases such as cancer and certain developmental disorders.

## c-cpg-islands
CpG islands are regions with consecutive C-G dinucleotides. DNMTs methylate the 5th carbon of cytosine using SAM, creating 5-methylcytosine.

## c-cpg-islands:summary
Methylation is symmetrical at CpG islands. DNMT1 maintains methylation patterns during replication. CpG islands are often near gene promoters, linking methylation to gene regulation.

## c-methylation-disease
Abnormal methylation patterns cause cancer, muscular dystrophy, and defects in imprinting, X-inactivation, and chromosome stability.

## c-methylation-disease:summary
Hypermethylation silences tumor suppressors (unchecked growth). Hypomethylation activates oncogenes. Methylation is both a cancer biomarker and therapeutic target.

## c-nucleic-acid-phosphorylation
Phosphorylation adds phosphate groups to nucleic acids. T4 PNK transfers gamma phosphate from ATP to 5'-OH ends. Essential for ligation, labeling, and repair.

## c-nucleic-acid-phosphorylation:summary
### Stage 9 — Nucleic Acid Phosphorylation: Preparing DNA for Repair and Ligation

This is the final stage. By now you've learned what DNA and RNA are, how they fold, how they replicate, how they are cut, how scientists build them, and how cells regulate them. Now: **After DNA is cut, how does the cell join it back together?** The answer involves **phosphorylation**.

#### The Big Idea

DNA is like a broken railway track. You cannot reconnect two pieces unless the ends are prepared correctly. Before DNA ligase can join DNA fragments together, the DNA ends must have the correct chemical groups — one of the most important is a **5'-phosphate group (5'-PO₄²⁻)**.

#### What is Phosphorylation?

Adding a phosphate group (PO₄³⁻) to a molecule. For nucleic acids, this usually means adding a phosphate to the **5' end** of DNA or RNA (5'-OH → 5'-PO₄).

#### Why is a 5'-Phosphate Important?

DNA ligase forms a phosphodiester bond between the **5'-phosphate** of one DNA fragment and the **3'-OH** of another. Without a 5'-phosphate, DNA ligase cannot seal the break. Think of trying to glue two wooden boards together when one board has no glue — the joint simply won't form.

#### The Enzyme: T4 Polynucleotide Kinase (T4 PNK)

In the laboratory, the most commonly used enzyme for phosphorylation. It transfers the **γ (gamma) phosphate** from ATP to the 5'-OH of DNA or RNA. ATP is the phosphate donor; the terminal phosphate is transferred.

#### Why Is T4 PNK Important?

Many DNA fragments produced in the laboratory have a free **5'-OH** instead of a **5'-phosphate**. These fragments cannot be ligated directly. T4 PNK solves this problem by adding the missing phosphate.

#### PCR Products

Standard PCR products have 5'-OH. If you want to insert them into a plasmid, they need 5'-PO₄. This can be achieved by using T4 PNK after PCR, or by designing PCR primers already synthesized with a 5'-phosphate.

#### DNA Repair in Living Cells

Phosphorylation happens naturally too. DNA is constantly damaged by radiation, UV light, reactive oxygen species, and chemicals. Damage may create DNA ends with 5'-OH instead of 5'-phosphate. Before DNA ligase can repair the break, enzymes must restore the proper chemical ends. Polynucleotide kinases help perform this task.

#### What Happens if DNA Cannot Be Repaired?

DNA damage → Replication problems → Mutations → Cell cycle arrest → **Apoptosis (programmed cell death)**. DNA repair is essential for cell survival.

#### Phosphorylation in Molecular Biology

Scientists deliberately phosphorylate DNA for many experiments: DNA cloning (preparing fragments for ligation into plasmids), recombinant DNA technology (joining DNA from different organisms), DNA labeling (radioactive or fluorescent phosphates for detection), and next-generation sequencing (some library preparation methods require phosphorylated ends before adapter ligation).

#### Important Distinction

**Nucleic Acid Phosphorylation:** Phosphate added to DNA or RNA. Mainly involved in DNA repair and laboratory techniques. **Histone Phosphorylation:** Phosphate added to histone proteins. Alters chromatin structure and influences gene expression. Both involve phosphate groups, but they target **different molecules** and serve **different purposes**.

#### The Complete Story

Stage 1: What is the manual made of? Stage 2: How does RNA read and use it? Stage 3: How do unusual base pairings create specialized structures? Stage 4: How is the manual folded and packed? Stage 5: How is the manual copied? Stage 6: How can the manual be cut? Stage 7: How can scientists write a new manual? Stage 8: How does the cell decide which pages to read? Stage 9: How are torn pages repaired and rejoined? Together, these topics explain how genetic information is **stored, maintained, expressed, repaired, and manipulated**.

#### Key Takeaways

- **Phosphorylation** is the addition of a phosphate group to DNA or RNA.
- DNA ligase requires a **5'-phosphate** and a **3'-OH** to seal DNA breaks.
- **T4 PNK** transfers the γ-phosphate from ATP to the 5'-OH end of DNA or RNA.
- Phosphorylation is essential for DNA repair, molecular cloning, recombinant DNA technology, and many sequencing workflows.
- Histone phosphorylation is different from nucleic acid phosphorylation and should not be confused with it.
- DNA repair prevents mutations and maintains genome stability.

## c-tna-pnk
T4 PNK is the standard enzyme for nucleic acid phosphorylation, transferring the gamma phosphate from ATP to 5'-OH termini of DNA or RNA.

## c-tna-pnk:summary
Has both 5'-kinase and 3'-phosphatase activities. Essential for preparing PCR products for ligation (Taq polymerase leaves 5'-OH unless phosphorylated primers used). Also used for end-labeling with radioactive or fluorescent tags.

## c-phosphorylation-repair
Phosphorylation is critical for DNA damage repair. Polynucleotide kinase phosphorylates broken 5'-OH ends to enable ligation by Ligase IV.

## c-phosphorylation-repair:summary
Without phosphorylation, repair machinery cannot recognize damage. Unrepaired damage triggers DNA damage response and apoptosis. Cells use phosphorylation status to distinguish human from viral nucleic acids (innate immunity). Histone phosphorylation is a separate epigenetic modification.
