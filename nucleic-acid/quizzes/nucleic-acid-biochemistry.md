---
format_version: 1
type: quiz_set
set: Nucleic Acid Biochemistry
questions:
  # ── DNA/RNA STRUCTURE ──
  - id: na-q001
    concept_id: c-dna-rna-structure
    type: mcq
    question: "Which form of DNA is the predominant form in vivo under normal physiological conditions?"
    options:
      - "A-DNA"
      - "B-DNA"
      - "Z-DNA"
      - "All forms are equally common"
    answer: 2
    explanation: "B-DNA is the predominant form in vivo under normal physiological conditions. A-DNA occurs in RNA-DNA hybrids and Z-DNA is found only in short regions."
    tags: [DNA, structure]

  - id: na-q002
    concept_id: c-z-dna
    type: mcq
    question: "What is the handedness of Z-DNA?"
    options:
      - "Right-handed"
      - "Left-handed"
      - "Both right and left-handed"
      - "Neither"
    answer: 2
    explanation: "Z-DNA is a left-handed helix, unlike B-DNA and A-DNA which are both right-handed."
    tags: [DNA, Z-form]

  - id: na-q003
    concept_id: c-b-dna
    type: fill_blank
    question: "The vertical rise per base pair in B-DNA is ______ Angstroms."
    answer: "3.4"
    explanation: "B-DNA has a vertical rise of 3.4 Angstroms per base pair, with a rotation of +36° per base pair and a diameter of ~20 Å."
    tags: [DNA, B-form]

  - id: na-q004
    concept_id: c-z-dna
    type: fill_blank
    question: "The rotation per base pair in Z-DNA is ______ degrees."
    answer: "-30"
    explanation: "Z-DNA has a rotation of -30° per base pair (left-handed), with a vertical rise of 3.7 Angstroms."
    tags: [DNA, Z-form]

  - id: na-q005
    concept_id: c-rna-structure
    type: true_false
    question: "RNA is always single-stranded and cannot form double-stranded structures."
    answer: false
    explanation: "RNA is usually single-stranded but can assume double-stranded structures and fold back on itself, as seen in tRNA."
    tags: [RNA, structure]

  - id: na-q006
    concept_id: c-rna-structure
    type: mcq
    question: "What percentage of total RNA is tRNA?"
    options:
      - "1-5%"
      - "10-20%"
      - "50-60%"
      - "80-90%"
    answer: 2
    explanation: "tRNA constitutes 10-20% of total RNA and has a molecular weight of about 25,000."
    tags: [RNA, tRNA]

  # ── RNA CONFORMATION ──
  - id: na-q007
    concept_id: c-riboswitches
    type: mcq
    question: "What are riboswitches?"
    options:
      - "DNA sequences that code for switch proteins"
      - "mRNA domains that change structure upon binding small molecules to regulate gene expression"
      - "Protein complexes that regulate transcription"
      - "RNA polymerase subunits"
    answer: 2
    explanation: "Riboswitches are mRNA domains that change structure upon binding small molecules, turning gene expression on or off."
    tags: [RNA, riboswitches]

  - id: na-q008
    concept_id: c-pseudoknots
    type: true_false
    question: "Pseudoknots are found only in mRNA."
    answer: false
    explanation: "Pseudoknots can be found in mRNA, tRNA, and RNA viruses. They affect translation and RNA replication."
    tags: [RNA, pseudoknots]

  - id: na-q009
    concept_id: c-pseudoknots
    type: mcq
    question: "What structures make up a pseudoknot?"
    options:
      - "Three hairpins and two loops"
      - "Two stems (helices) and two loops"
      - "One stem and four loops"
      - "Four stems and no loops"
    answer: 2
    explanation: "A pseudoknot consists of two stems which form a helix and two loops, created when a loop hairpin pairs with another part of the nucleic acid."
    tags: [RNA, pseudoknots]

  # ── NON-CANONICAL BASE PAIRING ──
  - id: na-q010
    concept_id: c-noncanonical-pairing
    type: mcq
    question: "Which of the following is NOT a type of non-canonical base pairing?"
    options:
      - "Reverse Watson-Crick"
      - "Wobble"
      - "Hoogsteen"
      - "Complementary"
    answer: 4
    explanation: "Complementary base pairing (Watson-Crick A-T and G-C) is the standard, canonical pairing. Reverse Watson-Crick, wobble, and Hoogsteen are all non-canonical."
    tags: [base-pairing, non-canonical]

  - id: na-q011
    concept_id: c-wobble-pairing
    type: fill_blank
    question: "G-U wobble pairing is a naturally occurring noncanonical base pair that does NOT require ______."
    answer: "tautomerization"
    explanation: "G-U wobble pairing does not require tautomerization, although rare tautomeric forms of bases can generate other mismatched base pairs."
    tags: [wobble, base-pairing]

  - id: na-q012
    concept_id: c-tautomerism
    type: mcq
    question: "Which glycosidic orientation allows Hoogsteen base pairing?"
    options:
      - "Anti"
      - "Syn"
      - "Para"
      - "Meta"
    answer: 2
    explanation: "The syn orientation allows Hoogsteen base pairing. The normal anti orientation allows Watson-Crick base pairing."
    tags: [tautomerism, Hoogsteen]

  - id: na-q013
    concept_id: c-reverse-watson-crick
    type: true_false
    question: "In reverse Watson-Crick pairing, the pyrimidine rotates 180° in its plane."
    answer: true
    explanation: "In reverse Watson-Crick pairing, the pyrimidine rotates 180° in its plane to align hydrogen bond donors with acceptors."
    tags: [base-pairing, reverse]

  # ── DNA CONFORMATIONS ──
  - id: na-q013b
    concept_id: c-dna-supercoiling
    type: mcq
    question: "What is the primary cause of DNA supercoiling?"
    options:
      - "Intercalating drugs"
      - "Naturally arises during replication and transcription, regulated by topoisomerases"
      - "Only during cell division"
      - "Environmental temperature changes"
    answer: 2
    explanation: "DNA supercoiling naturally arises during replication and transcription and is regulated by topoisomerases. Intercalating drugs can alter it but are not the primary cause."
    tags: [DNA, supercoiling]

  - id: na-q014
    concept_id: c-cruciform
    type: mcq
    question: "What type of DNA sequence can form cruciform structures?"
    options:
      - "Random sequences"
      - "Palindromic or inverted repeat sequences"
      - "Poly-A sequences"
      - "GC-rich sequences only"
    answer: 2
    explanation: "Cruciform DNA forms from palindromic or inverted repeat sequences that create two hairpin-like arms joined at a four-way junction."
    tags: [DNA, cruciform]

  - id: na-q015
    concept_id: c-triplex-dna
    type: mcq
    question: "In triplex DNA, where does the third strand bind?"
    options:
      - "In the minor groove"
      - "In the major groove"
      - "Between the base pairs"
      - "On the phosphate backbone"
    answer: 2
    explanation: "The third strand binds in the major groove of B-DNA, with its bases forming Hoogsteen hydrogen bonds with purines."
    tags: [DNA, triplex]

  # ── DNA REPLICATION ──
  - id: na-q016
    concept_id: c-dna-replication
    type: mcq
    question: "In which phase of the cell cycle does DNA replication occur?"
    options:
      - "G1 phase"
      - "S phase"
      - "G2 phase"
      - "M phase"
    answer: 2
    explanation: "DNA replication occurs in the S phase (synthesis phase) of the cell cycle."
    tags: [DNA, replication]

  - id: na-q017
    concept_id: c-semi-conservative
    type: true_false
    question: "In semi-conservative replication, each daughter DNA molecule contains two newly synthesized strands."
    answer: false
    explanation: "In semi-conservative replication, each daughter molecule contains one original (parental) strand and one newly synthesized strand."
    tags: [DNA, replication]

  - id: na-q018
    concept_id: c-dna-replication
    type: fill_blank
    question: "DNA replication proceeds in the ______ to ______ direction."
    answer: "5' to 3'"
    explanation: "DNA is synthesized exclusively in the 5' to 3' direction, which is why the lagging strand is synthesized discontinuously."
    tags: [DNA, replication, direction]

  - id: na-q019
    concept_id: c-denaturation-renaturation
    type: mcq
    question: "What does Tm (melting temperature) represent?"
    options:
      - "The temperature at which DNA completely denatures"
      - "The temperature at which 50% of base pairs are denatured"
      - "The temperature at which DNA begins to denature"
      - "The temperature at which renaturation is complete"
    answer: 2
    explanation: "Tm is the temperature at which 50% of the base pairs are denatured (strands separated)."
    tags: [DNA, Tm]

  # ── HYDROLYSIS & ENZYMES ──
  - id: na-q020
    concept_id: c-nucleic-acid-hydrolysis
    type: mcq
    question: "Why is RNA more susceptible to alkaline hydrolysis than DNA?"
    options:
      - "RNA has more base pairs"
      - "RNA has a 2'-hydroxyl group that is susceptible to hydrolytic attack"
      - "RNA is single-stranded"
      - "RNA has a different backbone"
    answer: 2
    explanation: "RNA has a 2'-hydroxyl group in its ribose sugar, which is susceptible to hydrolytic attack in basic solution. DNA lacks this group."
    tags: [hydrolysis, RNA]

  - id: na-q021
    concept_id: c-nucleic-acid-hydrolysis
    type: fill_blank
    question: "Alkaline hydrolysis of RNA produces ______ and ______ derivatives."
    answer: "2',3'-cyclic monophosphate and 2'-monophosphate"
    explanation: "The 2'-OH attacks the adjacent phosphodiester bond, forming a 2',3'-cyclic monophosphate intermediate, which is then hydrolyzed to 2'-monophosphate."
    tags: [hydrolysis, RNA, alkaline]

  - id: na-q022
    concept_id: c-restriction-enzymes
    type: mcq
    question: "What recognition sequence does BamHI cut?"
    options:
      - "5'-GAATTC-3'"
      - "5'-GGATCC-3'"
      - "5'-AAGCTT-3'"
      - "5'-CCCGGG-3'"
    answer: 2
    explanation: "BamHI recognizes 5'-GGATCC-3' and cuts between the two Gs on each strand."
    tags: [restriction-enzyme, BamHI]

  - id: na-q023
    concept_id: c-restriction-enzymes
    type: true_false
    question: "Restriction endonucleases were first isolated from bacteria."
    answer: true
    explanation: "Restriction enzymes were first isolated from bacteria, where they serve as a defense mechanism against foreign DNA (bacteriophages)."
    tags: [restriction-enzyme, bacteria]

  - id: na-q024
    concept_id: c-exonucleases
    type: mcq
    question: "How are exonucleases classified?"
    options:
      - "By the type of bond they cleave"
      - "By their molecular weight"
      - "As 3' or 5' specific based on which end they degrade from"
      - "By the organism they come from"
    answer: 3
    explanation: "Exonucleases are classified as 3' or 5' specific depending on which end of the polynucleotide chain they cleave from."
    tags: [nuclease, exonuclease]

  # ── CHEMICAL SYNTHESIS ──
  - id: na-q025
    concept_id: c-chemical-synthesis
    type: mcq
    question: "In which direction does chemical synthesis of nucleic acids occur?"
    options:
      - "5' to 3' (same as biological synthesis)"
      - "3' to 5' (opposite to biological synthesis)"
      - "Both directions simultaneously"
      - "Random direction"
    answer: 2
    explanation: "Chemical synthesis occurs in the 3' to 5' direction, which is opposite to the natural 5' to 3' direction of biological synthesis."
    tags: [synthesis, direction]

  - id: na-q026
    concept_id: c-synthesis-cycle
    type: mcq
    question: "Which step is NOT part of the phosphoramidite synthesis cycle?"
    options:
      - "Detritylation"
      - "Coupling"
      - "Polymerization"
      - "Oxidation"
    answer: 3
    explanation: "The four steps are: Detritylation, Coupling, Oxidation, and Capping. Polymerization is not a step in this cycle."
    tags: [synthesis, cycle]

  - id: na-q027
    concept_id: c-synthesis-cycle
    type: fill_blank
    question: "The fourth step of the synthesis cycle, ______, is added in industrial practice to prevent accumulation of short oligomers."
    answer: "Capping"
    explanation: "Capping blocks unreacted 5'-OH groups with acetic anhydride to prevent them from reacting in subsequent cycles."
    tags: [synthesis, capping]

  - id: na-q028
    concept_id: c-rna-synthesis
    type: fill_blank
    question: "The 2'-OH protecting group used in RNA synthesis is ______, removed by fluoride ion."
    answer: "TBDMS"
    explanation: "t-Butyldimethylsilyl (TBDMS) protects the 2'-OH during RNA synthesis and is removed by fluoride ion (TBAF)."
    tags: [RNA, synthesis, TBDMS]

  - id: na-q029
    concept_id: c-chemical-synthesis
    type: mcq
    question: "What protecting group is used in phosphoramidite chemistry?"
    options:
      - "Fmoc"
      - "Boc"
      - "DMT (4,4'-dimethoxytrityl)"
      - "TMS"
    answer: 3
    explanation: "DMT (4,4'-dimethoxytrityl) is the standard protecting group used for the 5'-OH in phosphoramidite synthesis."
    tags: [synthesis, DMT]

  # ── DNA METHYLATION ──
  - id: na-q030
    concept_id: c-dna-methylation
    type: mcq
    question: "What is the methyl donor in DNA methylation?"
    options:
      - "NADH"
      - "FADH2"
      - "S-Adenosylmethionine (SAM)"
      - "ATP"
    answer: 3
    explanation: "SAM (S-adenosylmethionine) is the methyl donor. The byproduct is SAH (S-adenosylhomocysteine)."
    tags: [methylation, SAM]

  - id: na-q031
    concept_id: c-dna-methylation
    type: mcq
    question: "What product is formed when DNMT methylates cytosine?"
    options:
      - "6-methylcytosine"
      - "5-methylcytosine"
      - "3-methylcytosine"
      - "N-methylcytosine"
    answer: 2
    explanation: "DNMT transfers a methyl group to the 5th carbon of cytosine, forming 5-methylcytosine."
    tags: [methylation, 5-methylcytosine]

  - id: na-q032
    concept_id: c-cpg-islands
    type: true_false
    question: "CpG islands are often found near gene promoters."
    answer: true
    explanation: "CpG islands are frequently located near gene promoters, which is why methylation at these sites can silence gene expression."
    tags: [CpG, promoters]

  - id: na-q033
    concept_id: c-methylation-disease
    type: mcq
    question: "How does hypermethylation contribute to cancer?"
    options:
      - "It activates oncogenes"
      - "It silences tumor suppressor genes"
      - "It increases DNA repair"
      - "It stabilizes chromosomes"
    answer: 2
    explanation: "Hypermethylation of tumor suppressor gene promoters silences them, preventing them from controlling cell growth, leading to unchecked tumor growth."
    tags: [methylation, cancer]

  # ── PHOSPHORYLATION ──
  - id: na-q034
    concept_id: c-tna-pnk
    type: mcq
    question: "What is the most widely used enzyme for nucleic acid phosphorylation?"
    options:
      - "DNA polymerase"
      - "RNA polymerase"
      - "T4 polynucleotide kinase (T4 PNK)"
      - "Ligase IV"
    answer: 3
    explanation: "T4 PNK is the most widely used enzyme. It transfers the gamma phosphate from ATP to 5'-OH termini of DNA or RNA."
    tags: [phosphorylation, T4-PNK]

  - id: na-q035
    concept_id: c-nucleic-acid-phosphorylation
    type: mcq
    question: "Why must PCR products be phosphorylated before ligation?"
    options:
      - "To increase their size"
      - "To make them single-stranded"
      - "Taq polymerase leaves 5'-OH, so they need phosphorylation for ligation"
      - "To denature them"
    answer: 3
    explanation: "Taq polymerase leaves 5'-OH on PCR products (unless phosphorylated primers were used). They must be phosphorylated by T4 PNK before ligation into a vector."
    tags: [phosphorylation, PCR, ligation]

  - id: na-q036
    concept_id: c-phosphorylation-repair
    type: true_false
    question: "Unrepaired DNA damage triggers apoptosis."
    answer: true
    explanation: "If DNA damage cannot be recognized or repaired, the DNA damage response is triggered, leading to apoptosis (programmed cell death)."
    tags: [DNA-repair, apoptosis]

  - id: na-q037
    concept_id: c-nucleic-acid-phosphorylation
    type: mcq
    question: "How does phosphorylation function in innate immunity?"
    options:
      - "It destroys viral DNA"
      - "Viral RNAs bearing 5'-triphosphates activate RIG-I signaling"
      - "It activates complement"
      - "It produces antibodies"
    answer: 2
    explanation: "Cells recognize nucleic acids through phosphorylation status. Viral RNAs bearing 5'-triphosphates activate RIG-I-mediated innate immune signaling."
    tags: [phosphorylation, innate-immunity]

  # ── MIXED ──
  - id: na-q038
    concept_id: c-dna-rna-structure
    type: mcq
    question: "What are the approximate diameters of B-DNA, A-DNA, and Z-DNA?"
    options:
      - "All are approximately 19 Å"
      - "B-DNA ~20 Å, A-DNA ~26 Å, Z-DNA ~18 Å"
      - "B-DNA ~18 Å, A-DNA ~20 Å, Z-DNA ~26 Å"
      - "B-DNA ~26 Å, A-DNA ~18 Å, Z-DNA ~20 Å"
    answer: 2
    explanation: "B-DNA has ~20 Å diameter, A-DNA is widest at ~26 Å, and Z-DNA is narrowest at ~18 Å."
    tags: [DNA, structure]

  - id: na-q039
    concept_id: c-chemical-synthesis
    type: mcq
    question: "Which is NOT an application of synthetic nucleic acids?"
    options:
      - "PCR primers"
      - "DNA sequencing primers"
      - "Protein synthesis"
      - "Gene synthesis"
    answer: 3
    explanation: "Applications include PCR primers, sequencing primers, gene synthesis, and modified vaccines. Protein synthesis is not a direct application."
    tags: [synthesis, applications]

  - id: na-q040
    concept_id: c-noncanonical-pairing
    type: mcq
    question: "What are the two types of tautomerism that enable noncanonical base pairing?"
    options:
      - "Alpha and beta"
      - "Amino-imino and keto-enol"
      - "Positive and negative"
      - "Strong and weak"
    answer: 2
    explanation: "Amino-imino tautomerism and keto-enol tautomerism allow bases to shift forms, enabling Hoogsteen and wobble base pairing."
    tags: [tautomerism, base-pairing]
---
