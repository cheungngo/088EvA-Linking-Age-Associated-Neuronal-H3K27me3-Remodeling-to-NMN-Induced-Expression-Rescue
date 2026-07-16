# **CPT2 as a Convergent Node Linking Age-Associated Neuronal H3K27me3 Remodeling to NMN-Induced Expression Rescue in Metabolic Tissues**

Ngo Cheung

Published: N/A (see history)

DOI: 10.7759/cureus.

Cite this article as: Cheung N (N/A) CPT2 as a Convergent Node Linking Age-Associated Neuronal H3K27me3 Remodeling to NMN-Induced Expression Rescue in Metabolic Tissues. Cureus (): e. doi:10.7759/cureus.

## **Abstract**

Age-related decline in mitochondrial function and disruption of epigenetic regulation are two closely connected features of biological aging. In neurons, age-associated remodeling of repressive H3K27me3 chromatin may constrain genes needed for metabolic, synaptic, and stress-adaptive maintenance. In parallel, nicotinamide mononucleotide (NMN), an NAD+ precursor, has been reported to mitigate age-associated physiological and transcriptional changes in peripheral metabolic tissues. However, direct links between neuronal epigenetic aging programs and NMN-responsive transcriptional rescue remain unclear.

Here, we performed a secondary integrative analysis of two public datasets: GSE190102, focused on age-associated neuronal H3K27me3 targets mapped through an activity-by-contact-style region-gene framework, and GSE85718, a long-term NMN transcriptomic dataset from skeletal muscle, liver, and white adipose tissue in mice. The analysis identified 23 genes shared between 21,155 aging H3K27me3-associated targets and 35 robust NMN-rescue genes. Because the aging target set was extremely broad, gene-level overlap was not statistically persuasive, and pathway-level convergence was absent. Under repressive-mark direction logic, 14 of the 23 shared genes were concordant, meaning that the NMN expression effect opposed the expected consequence of age-associated H3K27me3 remodeling.

**Objectives were to quantify overlap between neuronal age-associated H3K27me3 targets and robust NMN-responsive genes in peripheral metabolic tissues, classify shared genes by directional concordance under repressive chromatin logic, and identify high-priority mechanistic candidates. The analysis supports limited global convergence and nominates CPT2 as the leading convergent node for targeted validation.**

CPT2 emerged as the leading candidate. It showed age-associated H3K27me3 gain, a large K27me3 log-fold change of \+3.504, NMN-induced expression increase in old animals, a positive NMN interaction coefficient of \+0.201, and membership in the mitochondrial fatty-acid oxidation pathway. Within the downstream shared-gene mitochondrial analysis, CPT2 was the only mitochondrial-core gene, with nominal enrichment only. These findings do not support broad reversal of neuronal epigenetic aging by NMN. Instead, they identify CPT2 as a biologically coherent and experimentally tractable candidate linking age-related repressive chromatin remodeling to NMN-responsive mitochondrial metabolism.

## **Introduction**

### **Clinical/Translational Hook**

Aging of the nervous system is not driven by one pathway. It reflects a gradual loss of cellular flexibility, including reduced mitochondrial reserve, impaired stress responses, altered chromatin regulation, and declining synaptic maintenance. These processes are relevant to cognitive aging, neurodegenerative vulnerability, and psychiatric states in which energy metabolism and stress adaptation are impaired. In clinical practice, this matters because many age-associated brain conditions are treated symptomatically, while the underlying metabolic and epigenetic constraints remain largely unaddressed.

Mitochondrial dysfunction has been placed among the major hallmarks of aging, alongside genomic instability, epigenetic alterations, altered nutrient sensing, and loss of proteostasis \[1\]. Studies of the aging human brain have also shown that genes involved in synaptic plasticity, vesicular transport, mitochondrial function, and neuronal survival are vulnerable during aging \[2\]. NAD+ biology has drawn attention because NAD+ is not only a redox metabolite but also a substrate for enzymes that regulate chromatin, stress responses, mitochondrial adaptation, and DNA repair \[3-5\]. These links make NAD+ metabolism attractive for translational work, but they also make it easy to overstate the implications. The present analysis was designed to stay narrow: it asks whether a small set of NMN-responsive transcriptional changes intersects with genes linked to neuronal H3K27me3 aging, and whether any candidate is strong enough to justify direct validation.

### **Epigenetic Aging Context**

H3K27me3 is a repressive histone mark closely associated with Polycomb-mediated gene silencing. Polycomb group proteins are transcriptional repressors that help regulate gene expression during development and cell-state maintenance, and PRC2 is a major enzymatic complex involved in H3K27 methylation \[6,7\]. When H3K27me3 increases at regulatory regions, the expected direction is reduced transcriptional accessibility or reduced ability of a gene to respond to demand. In the context of aging neurons, this can be interpreted as a form of focal repression that may affect genes involved in neuronal identity, synaptic maintenance, and metabolic resilience. The related preprint by Cheung framed this process as focal Polycomb-mediated repression of neuronal identity and synaptic maintenance genes in aging neurons \[8\].

In this study, H3K27me3 gain was interpreted as increased repression, while H3K27me3 loss was interpreted as relative de-repression. This directionality is central. A simple gene overlap is not enough, because a gene can be shared between datasets while moving in a biologically contradictory direction. A more informative question is whether NMN changes expression in the direction that would oppose the inferred chromatin constraint.

### **NMN Biology & Rationale**

NMN is an intermediate in NAD+ biosynthesis. Long-term NMN administration in mice has been reported to mitigate age-associated physiological decline and to prevent some age-associated transcriptional changes in metabolic tissues \[9\]. Broader reviews of NMN and nicotinamide riboside describe these molecules as NAD+ intermediates with potential biological and therapeutic relevance, while also emphasizing that translation to humans remains incomplete and context-dependent \[10\]. In a human trial, NMN increased muscle insulin sensitivity in prediabetic women, but such findings should not be generalized to all aging outcomes or to brain aging without additional evidence \[11\].

Mechanistically, NAD+ can influence sirtuin activity. AMPK has been shown to increase cellular NAD+ and thereby enhance SIRT1 activity, leading to deacetylation of downstream targets such as PGC-1alpha and FOXO transcription factors \[12\]. SIRT1 can interact with PGC-1alpha, a regulator of mitochondrial biogenesis and oxidative metabolism \[13,14\]. SIRT3 is localized to mitochondria and regulates mitochondrial protein acetylation, including metabolic pathways important for energy homeostasis \[15,16\]. These mechanisms provide a plausible bridge between NAD+ repletion, mitochondrial function, and chromatin-linked metabolic regulation, but they do not prove that NMN directly erases H3K27me3 at specific genes.

The related preprint by Cheung identified mechanistic leads from NMN-associated transcriptional drift, including RAB11A-linked trafficking and CPT2-linked fatty-acid oxidation \[17\]. The current manuscript builds from that logic but uses a stricter interpretation: the strongest claim is not that NMN reverses epigenetic aging, but that some NMN-responsive genes may overlap with chromatin-constrained aging targets in a way that points to testable candidates.

### **Study Rationale & Gap**

The unresolved question is whether genes linked to neuronal age-associated H3K27me3 remodeling overlap with genes whose age-associated expression trajectories are reversed by NMN in metabolic tissues. This is not a direct test of NMN action in neurons. The comparison crosses tissue, assay type, age range, and molecular layer. It is therefore best understood as candidate discovery.

This indirect design still has value. If a gene is linked to increased repressive chromatin in aging neurons and is also transcriptionally rescued by NMN in old metabolic tissues, that gene may sit near a shared aging axis. The strongest candidates would be genes with directional coherence, plausible biology, and feasible experimental readouts. The present analysis identified CPT2 as the clearest example.

### **Objectives**

**The four objectives were:**

**1\. To quantify overlap between neuronal H3K27me3 aging targets and transcriptomic rescue genes from non-neuronal metabolic tissues, specifically skeletal muscle, liver, and white adipose tissue.**

**2\. To classify shared genes by directional concordance under repressive H3K27me3 logic.**

**3\. To identify the strongest mechanistic candidate, with particular attention to CPT2.**

**4\. To discuss translational implications and a validation roadmap while preserving the analytical limitations and candidate-discovery scope of the study.**

## **Materials & Methods**

### **Data Sources**

This study used secondary analysis of public datasets and pipeline outputs derived from them (Figure 1). The aging epigenetic program was based on GSE190102, analyzed as neuronal H3K27me3 signal across age groups, with 3-month and 24-month mice serving as the main young-versus-old contrast. The NMN-rescue program was based on GSE85718, corresponding to long-term NMN administration in C57BL/6N mice. The NMN dataset included skeletal muscle, liver, and white adipose tissue, with 6-month and 12-month age groups and control or NMN treatment. Each tissue, age, and treatment cell had four samples. The original long-term NMN mouse study used oral NMN and reported mitigation of age-associated physiological decline and tissue-dependent transcriptional effects \[9\].

**A complete tabulated master overview is provided in the accompanying Supplementary Appendix, “Combined 088EvA Appendix.docx.” Appendix Table A1 corresponds to manuscript Table 6, and Appendix Table A2 corresponds to manuscript Table 7\.**

### **Integrative-secondary-analysis-pipeline-linking-neuronal-H3K27me3-aging-targets-to-NMN-responsive-transcription**

**Figure 1: Integrative secondary-analysis pipeline linking neuronal H3K27me3 aging targets to NMN-responsive transcription**

(a) The nicotinamide mononucleotide transcriptomic dataset Gene Expression Omnibus Series GSE85718 was **processed from the raw expression matrix through probe-to-gene collapse; because values were treated as already compressed, log2 transformation was skipped and quantile normalization was applied**, followed by per-tissue ordinary-least-squares modeling of expression as a function of age, treatment, and their interaction; rescue genes were defined by an age-associated change accompanied by a sign-reversing nicotinamide mononucleotide interaction and retained if recurrent in at least two tissues. (b) The neuronal histone H3 lysine 27 trimethylation dataset Gene Expression Omnibus Series GSE190102 was processed from bigWig signal tracks into consensus regions, differentially tested for the 24-month-versus-3-month contrast, clustered by age trajectory into progressive-gain and progressive-loss sets, and linked to protein-coding genes using an activity-by-contact-style region-gene framework, yielding directionally labeled aging target genes. (c) The two gene programs were intersected; each shared gene was assigned an aging-mark direction and a nicotinamide mononucleotide interaction sign, and a concordance call was made under repressive-mark logic: histone H3 lysine 27 trimethylation gain is expected to be opposed by a nicotinamide mononucleotide-induced expression increase, and loss by a nicotinamide mononucleotide-induced decrease. This was followed by pathway enrichment and a curated mitochondrial-core test. (d) Shared genes were scored by a composite priority combining directional concordance, cross-tissue recurrence, region-gene support, interaction magnitude, and mitochondrial membership, refined with a protein-protein interaction network, and mapped onto a tiered experimental validation roadmap. This figure depicts the analytical workflow only; no results are shown. Credits to Ngo Cheung; created using PowerPoint; no artificial intelligence used.

### **Aging Epigenetic Targets**

For the aging analysis, H3K27me3 bigWig files were processed to define consensus regions and quantify age-associated signal. The detected histone mark was K27me3, treated as a repressive mark rather than an active enhancer mark. Differential selection used a relaxed threshold of p \< 0.01 when stricter criteria produced too few regions. The pipeline identified 9,752 age-associated regions, of which 6,402 progressive gain or loss regions were carried into region-gene assignment. The activity-by-contact-style framework was used to link regions to protein-coding genes, producing 427,099 region-gene pairs and 21,155 target genes. **The numerical ABC-style score cutoff used to retain these region-gene pairs will be reported in the deposited parameter file; the aggregate tabulated results establish the retained-pair and target-gene counts but do not permit that cutoff to be inferred.** Because H3K27me3 is repressive, “activity” in this context should be read as mark intensity at Polycomb-associated or heterochromatin-like loci, not as enhancer activation. The activity-by-contact model itself is a general enhancer-promoter prediction framework based on regulatory activity and contact frequency \[18\].

**The complete aging parameter summary and mitochondrial-core list are provided in Appendix Tables A6-A7, corresponding to manuscript Tables 11-12.**

### **NMN-Rescue Genes**

For GSE85718, 25,697 probes were collapsed to 18,120 genes. Values were already compressed, so log2 transformation was skipped and quantile normalization was applied. Within each tissue, the model was expression as a function of age, treatment, and age-by-treatment interaction. No genes reached FDR \< 0.05 for the age effect, NMN effect at 6 months, or interaction term in any tissue. Because of this, the rescue definition used relaxed nominal criteria: a gene had to show an age-associated expression change in control animals and a sign-reversing NMN interaction. Genes were considered robust if they appeared in at least two tissues. This produced 421 rescue genes in skeletal muscle, 355 in liver, 397 in white adipose tissue, and 35 robust cross-tissue rescue genes. No gene was rescued in all three tissues.

**The exact nominal p-value thresholds used for the relaxed rescue calls will be specified in the deposited parameter table and analysis scripts. The detailed tissue-level and cross-tissue NMN outputs are reported in Appendix Tables A3-A5, corresponding to manuscript Tables 8-10.**

### **Overlap & Directionality Analysis**

The primary overlap compared the 21,155 aging H3K27me3-associated target genes with the 35 robust NMN-rescue genes. Directionality was interpreted according to repressive H3K27me3 logic. A gene with H3K27me3 gain with age was expected to be more repressed; therefore, an NMN-associated expression increase in old animals was classified as concordant. A gene with H3K27me3 loss with age was expected to be less repressed; therefore, an NMN-associated expression decrease in old animals was classified as concordant. Other combinations were classified as discordant.

**The overlap metrics are also tabulated in Appendix Table A8, corresponding to manuscript Table 13\.**

### **Mitochondrial Analysis**

A curated mitochondrial and energy gene core was used to test whether shared genes were enriched for mitochondrial biology. This core included oxidative phosphorylation genes, tricarboxylic-acid-cycle genes, mitochondrial dynamics genes, fatty-acid oxidation genes, NAD-related mitochondrial regulators, and related energy metabolism genes. Hypergeometric testing was applied, but results were interpreted cautiously because the target universe and gene-selection procedure were not ideal for formal enrichment claims.

### **Enrichment**

Gene-set enrichment was performed using Enrichr libraries, including Gene Ontology Biological Process, KEGG Mouse, Reactome, MSigDB Hallmark, and MGI Mammalian Phenotype terms. Enrichr was applied to the full aging target set, the robust NMN set, the shared-gene set, and the concordant and discordant subsets. Enrichr is a widely used web-based gene-list enrichment tool, but the lack of a custom background universe is an important limitation in this setting \[19,20\].

### **Statistical Considerations**

Several statistical constraints were present from the start. The aging target list contained 21,155 genes, nearly the full eligible protein-coding space in the analysis. This makes gene-level overlap difficult to interpret, because almost any small gene list will overlap with such a broad set. In addition, the stated hypergeometric universe in the master pipeline was 20,000, which was smaller than the aging target count. That made the reported hypergeometric p-value invalid and produced NaN. The correct interpretation is not that the overlap is formally significant or formally non-significant under that test, but that it is not interpretable as compelling evidence of convergence under the current universe definition. A better universe would be the intersection of genes measurable in GSE85718 and genes eligible for GSE190102 ABC-style mapping.

**The attempted universe, NaN result, and related statistical constraints are summarized in Appendix Table A16, corresponding to manuscript Table 21\.**

### **Data and Code Availability**

**The public source datasets are available through GEO under GSE190102 and GSE85718. Annotated R/Python scripts will be provided as Supplementary Materials upon acceptance. These scripts will cover probe-to-gene collapse, guarded normalization procedures, per-tissue age-by-treatment modeling, H3K27me3 region processing, ABC-style region-gene integration, overlap and concordance calculations, composite priority scoring, enrichment preparation, and hypergeometric testing.**

**The supplementary parameter file will specify every numerical threshold used in the analysis, including the H3K27me3 selection criterion of p \< 0.01, the FDR criterion of FDR \< 0.05, the relaxed nominal thresholds used for rescue calls, the mitochondrial-core test parameters, and the ABC-style score cutoff used to retain 427,099 region-gene pairs and generate 21,155 aging target genes. The tabulated appendix reports the retained-pair and target-gene counts but does not state the numerical ABC cutoff; that value should be copied from the original pipeline parameter file and should not be inferred from the downstream CPT2 score of 0.0698.**

**The full mitochondrial-core gene list, all 35 robust NMN-rescue genes, and the 23 shared genes will be deposited as machine-readable supplementary tables, together with intermediate output files needed to reproduce the reported Jaccard index, enrichment results, and invalid hypergeometric result. The attempted universe of 20,000 genes and the 21,155-gene aging target count will be documented explicitly, including the reason the hypergeometric calculation returned NaN. Where journal policy permits, editable workflow source files for Figures 1 and 2 will also be included.**

**For cross-reference, Appendix Table A1 corresponds to manuscript Table 6; Appendix Table A2 to Table 7; Appendix Table A3 to Table 8; Appendix Table A4 to Table 9; Appendix Table A5 to Table 10; Appendix Table A6 to Table 11; Appendix Table A7 to Table 12; Appendix Table A8 to Table 13; Appendix Table A9 to Table 14; Appendix Table A10 to Table 15; Appendix Table A11 to Table 16; Appendix Table A12 to Table 17; Appendix Table A13 to Table 18; Appendix Table A14 to Table 19; Appendix Table A15 to Table 20; Appendix Table A16 to Table 21; and Appendix Table A17 to Table 22\.**

## **Results**

The key input datasets, processing outputs, and interpretive constraints are summarized in Table 1\. **Detailed master-analysis outputs are also provided in Appendix Tables A1-A2, corresponding to manuscript Tables 6-7.**

| Component | Result | Interpretation |
| ----- | ----- | ----- |
| Aging dataset | GSE190102 | Neuronal H3K27me3 aging signal; 24M versus 3M contrast; ABC-style region–gene mapping |
| NMN dataset | GSE85718 | Long-term oral NMN, 300 mg/kg/day; C57BL/6N mice; skeletal muscle, liver, and white adipose tissue; 6M and 12M |
| Aging stage | Completed | Aging H3K27me3 target construction completed |
| NMN stage | Completed | NMN-rescue transcriptomic analysis completed |
| Main interpretation | Limited global convergence | No shared significant pathway terms; 23 shared genes identified |
| Top validation candidate | CPT2 | Concordant, mitochondrial, K27me3 gain, NMN-induced expression increase in old animals |
| Broad aging target set | 21,155 genes | Weakens binary overlap interpretation |
| Relaxed NMN-rescue criteria | Used because no FDR-significant tissue-specific effects were detected | Supports candidate discovery rather than formal rescue claims |
| Primary conclusion | Candidate discovery | Supports CPT2-focused validation rather than broad claims that NMN reverses neuronal epigenetic aging |

**Table 1: Master analysis overview and principal constraints**

Master analysis overview and principal constraints. Abbreviations: NMN, nicotinamide mononucleotide; H3K27me3, histone H3 lysine 27 trimethylation; K27me3, histone H3 lysine 27 trimethylation; GSE, Gene Expression Omnibus series; ABC, activity-by-contact; CPT2, carnitine palmitoyltransferase 2; FDR, false discovery rate.

### **Gene-Level Overlap & Limitations**

**Objective 1: Gene-level overlap analysis compared the neuronal H3K27me3 target set with the transcriptomic rescue set from non-neuronal metabolic tissues.** The aging H3K27me3 analysis produced 21,155 target genes. The robust NMN-rescue analysis produced 35 genes present in at least two tissues. The intersection contained 23 genes: ACD, APBA2, BCHE, CMA2, CPT2, DUSP11, FMO2, GALR1, HS3ST6, MAP2K2, MYO15, MYOM2, OLFR508, PKNOX1, PSME3, RAB11A, RANGAP1, SLC13A5, SPG21, SYNGR2, TRP53INP2, WAP, and ZFAND2B.

The NMN-rescue transcriptomic program and cross-tissue filtering are summarized in Table 2, and the aging H3K27me3 program is summarized in Table 3\. **The corresponding detailed appendix outputs are provided in Appendix Tables A3-A7, corresponding to manuscript Tables 8-12.**

| Tissue or category | Age/treatment design | n | Differential genes at FDR \< 0.05 | Relaxed NMN-rescue result |
| ----- | ----- | ----- | ----- | ----- |
| Liver | 6M control, 6M NMN, 12M control, 12M NMN | 4 per cell | Age effect: 0; NMN at 6M: 0; age × treatment interaction: 0 | 355 |
| Skeletal muscle | 6M control, 6M NMN, 12M control, 12M NMN | 4 per cell | Age effect: 0; NMN at 6M: 0; age × treatment interaction: 0 | 421 |
| White adipose tissue | 6M control, 6M NMN, 12M control, 12M NMN | 4 per cell | Age effect: 0; NMN at 6M: 0; age × treatment interaction: 0 | 397 |
| Probe-to-gene processing | 25,697 probes collapsed to genes | — | — | 18,120 genes |
| Robust rescue genes | Present in at least two tissues | — | — | 35 |
| Rescued in all three tissues | Present in liver, skeletal muscle, and white adipose tissue | — | — | 0 |
| NMN mitochondrial annotation | CPT2, CS, NDUFV1, POLG, SUCLA2, TFB2M | — | — | 6 genes |

**Table 2: NMN-rescue transcriptomic program and robust cross-tissue filtering**

NMN-rescue transcriptomic program and robust cross-tissue filtering. Abbreviations: NMN, nicotinamide mononucleotide; FDR, false discovery rate.

| Parameter | Value | Note |
| ----- | ----- | ----- |
| Histone mark | K27me3 / H3K27me3 | Repressive mark; not treated as active enhancer signal |
| Samples per age | 3M: 5; 12M: 5; 24M: 5 | Age groups parsed from 15 K27me3 bigWig files |
| Consensus regions | 366,721 | Peak-union regions used for quantification |
| Differential mode | Relaxed p \< 0.01 | 24M versus 3M contrast |
| Age-associated regions | 9,752 | Regions selected for age-associated K27me3 change |
| Progressive loss clusters | 1, 4 | K27me3 signal progressively decreased with age |
| Progressive gain clusters | 0, 3 | K27me3 signal progressively increased with age |
| Regions carried to ABC | 6,402 | Progressive gain or loss regions used for region–gene scoring |
| Protein-coding genes | 21,674 | GENCODE vM25 protein-coding genes considered |
| ABC region–gene pairs | 427,099 | Predictions above the ABC-style score threshold |
| Aging K27me3 target genes | 21,155 | GAIN \= 9,178; LOSS \= 12,470 |
| Mitochondrial-core genes in aging target set | 66 | Included CPT2, CS, NDUFV1, POLG, SUCLA2, TFB2M, and other energy-core genes |

**Table 3: Aging H3K27me3 epigenetic program**

Aging H3K27me3 epigenetic program. Abbreviations: H3K27me3, histone H3 lysine 27 trimethylation; K27me3, histone H3 lysine 27 trimethylation; ABC, activity-by-contact; GENCODE, GENCODE gene annotation database.

At first glance, 23 of 35 robust NMN genes overlapping with the aging set appears large. However, the aging target set was so broad that the overlap was not statistically persuasive. The Jaccard index was only 0.0011. The hypergeometric p-value was reported as NaN because the predefined universe was 20,000, smaller than the 21,155 aging target genes. This invalidates the formal overlap test. The more accurate statement is that the exact gene overlap is hypothesis-generating but not strong evidence for shared biology. **These overlap metrics are tabulated in Appendix Table A8, corresponding to manuscript Table 13\.**

Pathway-level comparison was even more conservative. The aging target set produced 489 significant Enrichr terms at adjusted p \< 0.05, while the robust NMN set produced zero significant terms. Consequently, there were zero shared significant pathway terms. The top aging terms included ABC transporters, ion channel transport, adrenergic signaling in cardiomyocytes, ion transport by P-type ATPases, transport of small molecules, aldosterone synthesis and secretion, RHOA GTPase cycle, insulin receptor recycling, cGMP-PKG signaling, and O-glycosylation-related terms. These results support the view that the neuronal H3K27me3 aging program is broad and pathway-rich, while the robust NMN set is small and underpowered for enrichment. **The full pathway comparison and functional theme counts are provided in Appendix Tables A10-A12, corresponding to manuscript Tables 15-17.**

### **Directional Concordance**

**Objective 2: Directional concordance analysis classified 14 of the 23 shared genes as concordant and 9 as discordant under repressive H3K27me3 logic.**

The most informative part of the comparison was not the raw overlap but the direction of effect. Because H3K27me3 is a repressive mark, H3K27me3 gain with age suggests increased repression, while H3K27me3 loss suggests reduced repression. A rescue-like NMN effect should oppose the predicted expression consequence of that chromatin change.

Using this logic, 14 of the 23 shared genes were concordant and 9 were discordant. The concordant genes were ACD, APBA2, BCHE, CPT2, DUSP11, FMO2, GALR1, HS3ST6, MAP2K2, MYOM2, PKNOX1, SPG21, SYNGR2, and ZFAND2B. The discordant genes were CMA2, MYO15, OLFR508, PSME3, RAB11A, RANGAP1, SLC13A5, TRP53INP2, and WAP.

The shared genes and direction calls are shown in Table 4\. **The complete shared-gene direction table is also provided in Appendix Table A9, corresponding to manuscript Table 14\.**

| Gene | Aging K27me3 direction | NMN effect in old animals | NMN sign | Verdict |
| ----- | ----- | ----- | ----- | ----- |
| ACD | LOSS | NMN lowers old | \-1.0 | Concordant |
| APBA2 | GAIN | NMN raises old | \+1.0 | Concordant |
| BCHE | GAIN | NMN raises old | \+1.0 | Concordant |
| CMA2 | LOSS | NMN raises old | \+1.0 | Discordant |
| CPT2 | GAIN | NMN raises old | \+1.0 | Concordant |
| DUSP11 | LOSS | NMN lowers old | \-1.0 | Concordant |
| FMO2 | LOSS | NMN lowers old | \-1.0 | Concordant |
| GALR1 | GAIN | NMN raises old | \+1.0 | Concordant |
| HS3ST6 | GAIN | NMN raises old | \+1.0 | Concordant |
| MAP2K2 | LOSS | NMN lowers old | \-1.0 | Concordant |
| MYO15 | LOSS | NMN raises old | \+1.0 | Discordant |
| MYOM2 | LOSS | NMN lowers old | \-1.0 | Concordant |
| OLFR508 | GAIN | NMN lowers old | \-1.0 | Discordant |
| PKNOX1 | LOSS | NMN lowers old | \-1.0 | Concordant |
| PSME3 | LOSS | NMN raises old | \+1.0 | Discordant |
| RAB11A | LOSS | NMN raises old | \+1.0 | Discordant |
| RANGAP1 | LOSS | NMN raises old | \+1.0 | Discordant |
| SLC13A5 | LOSS | NMN raises old | \+1.0 | Discordant |
| SPG21 | LOSS | NMN lowers old | \-1.0 | Concordant |
| SYNGR2 | LOSS | NMN lowers old | \-1.0 | Concordant |
| TRP53INP2 | LOSS | NMN raises old | \+1.0 | Discordant |
| WAP | GAIN | NMN lowers old | \-1.0 | Discordant |
| ZFAND2B | LOSS | NMN lowers old | \-1.0 | Concordant |

**Table 4: Shared genes with direction and concordance classification**

Shared genes with direction and concordance classification. Abbreviations: K27me3, histone H3 lysine 27 trimethylation; NMN, nicotinamide mononucleotide.

This classification created a more useful validation framework than overlap alone. The concordant genes are candidates where the NMN expression effect is consistent with reversal of the inferred H3K27me3-associated expression constraint. The discordant genes should not be dismissed, because they may reflect tissue-specific regulation, indirect NMN effects, compensatory responses, or uncertainty in distal region-gene mapping. Still, the concordant set is more directly aligned with the rescue model.

### **CPT2 as the Leading Candidate**

**Objective 3: Candidate prioritization identified CPT2 as the leading validation candidate.**

CPT2 was the clearest candidate in the analysis. It appeared in the shared gene set, was classified as concordant, belonged to the curated mitochondrial core, and ranked first in the downstream validation priority score. Its aging-side signal was H3K27me3 gain, with a K27me3 log-fold change of \+3.504. Under repressive-mark logic, this suggests increased age-associated chromatin constraint at the CPT2 locus or linked regulatory region. Its NMN-side signal was a positive interaction coefficient of \+0.201, meaning that NMN increased CPT2 expression in old animals relative to the expected age effect. CPT2 was robust across two metabolic tissues, had a mean age-control coefficient of \-0.141, and had an ABC score of 0.0698 in the downstream target table.

CPT2-focused metrics and validation priorities are summarized in Table 5\. **The downstream shortlist and CPT2-focused metrics are provided in Appendix Tables A13-A14, corresponding to manuscript Tables 18-19.**

| Metric or validation item | CPT2 value or recommendation | Interpretation |
| ----- | ----- | ----- |
| Shared gene status | Shared | Present in both the aging K27me3 target set and the robust NMN-rescue set |
| Aging K27me3 direction | GAIN | Consistent with increased age-associated repressive chromatin signal |
| K27me3 LFC, 24M versus 3M | \+3.504 | Large positive age-associated K27me3 change |
| NMN effect | NMN raises old | Positive expression interaction in old animals, consistent with rescue under repressive-mark logic |
| Mean NMN interaction coefficient | \+0.201 | Expression increased with NMN in old animals |
| Mean age-control coefficient | \-0.141 | Age effect in control animals was negative on average |
| Number of NMN tissues | 2 | Met robust criterion of presence in at least two tissues |
| ABC score | 0.0698 | Region–gene support from the downstream aging target table |
| Mitochondrial-core status | Yes | Only mitochondrial-core gene in the strict 23-gene shared downstream set |
| Downstream priority score | 7.91 | Highest-ranked validation candidate |
| Priority 1 validation | qPCR and Western blot for CPT2 | Confirms whether CPT2 expression is reproducibly age-sensitive and NMN-responsive |
| Priority 2 validation | H3K27me3 ChIP-qPCR or CUT\&Tag-qPCR at implicated CPT2 regulatory regions | Tests whether age-associated K27me3 gain is reproducible and NMN-sensitive |
| Priority 3 validation | Fatty-acid oxidation assays using Seahorse flux or labeled palmitate, with and without NMN | Determines whether CPT2-linked expression changes correspond to altered fatty-acid oxidation capacity |
| Priority 4 validation | CPT2 knockdown or overexpression combined with NMN treatment | Tests whether CPT2 is required for, or sufficient to mimic, part of the NMN-associated metabolic response |
| Priority 5 validation | Concordant-gene qPCR panel | Assesses whether a small K27me3-coherent NMN-response signature can be replicated |
| Priority 6 validation | Recompute overlap using a valid universe and rank-based target selection | Improves formal interpretation of overlap, expected overlap, odds ratio, and enrichment |

**Table 5: CPT2-focused result summary and validation roadmap**

CPT2-focused result summary and validation roadmap. Abbreviations: CPT2, carnitine palmitoyltransferase 2; NMN, nicotinamide mononucleotide; K27me3, histone H3 lysine 27 trimethylation; LFC, log-fold change; ABC, activity-by-contact; qPCR, quantitative polymerase chain reaction; ChIP-qPCR, chromatin immunoprecipitation–quantitative polymerase chain reaction; CUT\&Tag, cleavage under targets and tagmentation. **The complete downstream validation outputs are provided in Appendix Tables 18-20.**

The biological fit is strong. CPT2 encodes carnitine palmitoyltransferase 2, a key enzyme of the mitochondrial carnitine shuttle. The carnitine shuttle is required for long-chain fatty acids to enter mitochondrial beta-oxidation, and CPT2 functions at the inner mitochondrial membrane side of this system \[21-23\]. Defects in this pathway impair fatty-acid oxidation and can cause clinically meaningful metabolic disease. In the present analysis, CPT2 was not simply a shared gene; it was the only gene in the downstream 23-gene shared set that belonged to the curated mitochondrial core. The mitochondrial enrichment among the shared genes was nominal, with hypergeometric p \= 0.0732, and therefore should be described as suggestive rather than significant.

There is a distinction between the broader mitochondrial analysis and the downstream shared-gene result. In the master pipeline, six mitochondrial-core genes overlapped between the full aging mitochondrial set and the broader NMN robust/union mitochondrial annotation: CPT2, CS, NDUFV1, POLG, SUCLA2, and TFB2M. In the stricter downstream shared robust set of 23 genes, only CPT2 remained as a mitochondrial-core candidate. This is why CPT2 is the cleanest mechanistic bridge, not because it proves a general mitochondrial overlap, but because it is the one mitochondrial gene that satisfies the strongest combined filters.

### **Broader Concordant & Discordant Patterns**

The downstream priority score weighted concordance, tissue recurrence, ABC rank, absolute NMN interaction strength, and mitochondrial membership. CPT2 ranked first with a score of 7.91. Other high-priority concordant genes included ACD, ZFAND2B, FMO2, SYNGR2, DUSP11, APBA2, MAP2K2, SPG21, HS3ST6, PKNOX1, MYOM2, GALR1, and BCHE. ACD and ZFAND2B ranked highly because of concordance and favorable ABC-related evidence. FMO2 is interesting because flavin-containing monooxygenases have been linked in some contexts to detoxification and stress resistance, although the effect size here was small. SYNGR2 and APBA2 point toward membrane or vesicle-associated biology, which may be relevant to neuronal maintenance but requires tissue-specific validation.

The discordant set showed the strongest enrichment signal. Concordant genes had zero significant enrichment terms, while the 9 discordant genes produced 38 significant GO terms. These terms were mostly related to succinate transport, response to lithium ion, neurotransmitter receptor transport from endosome to postsynaptic membrane or plasma membrane, plasma membrane-to-endosome transport, regulation of endosome size, astral microtubule organization, C4-dicarboxylate transport, and negative regulation of nucleocytoplasmic transport. Because the discordant group contained only 9 genes, this enrichment may be unstable. Still, it suggests that NMN-related effects may include adaptive trafficking and transport responses that do not map neatly onto direct reversal of neuronal H3K27me3 repression. **Representative discordant enrichment terms are listed in Appendix Table 20\.**

This pattern suggests that NMN may not act as a simple chromatin “reversal” agent. It may have at least two arms: a candidate direct or directionally coherent rescue arm, represented by genes such as CPT2, and an adaptive remodeling arm, represented by transport and trafficking terms in the discordant set. This distinction matters for translational work. A therapy that improves aging physiology may still produce tissue-specific or compensatory expression patterns that do not mirror the original aging mark.

### **Methodological Constraints**

The results must be read with caution. The aging target set was extremely broad. The NMN-rescue genes were defined using relaxed nominal criteria because no genes reached genome-wide FDR significance in the tissue-specific models. The two datasets differ in tissue, age range, assay modality, and molecular layer. The analysis therefore supports candidate discovery, not causal inference and not broad claims about NMN reversing neuronal epigenetic aging.

## **Discussion**

### **Mechanistic Synthesis for CPT2**

The central finding is narrow but biologically coherent: CPT2 sits at the intersection of age-associated neuronal H3K27me3 gain and NMN-associated expression rescue in old metabolic tissues. The simplest model is that aging increases repressive Polycomb-linked chromatin at or near CPT2-associated regulatory regions, which may constrain CPT2 expression or reduce its responsiveness to metabolic demand. NMN, by increasing NAD+ availability and engaging sirtuin-linked metabolic programs, may partially restore expression in old tissue. This model is plausible but not yet proven (Figure 2).

### **Proposed-NAD+–Sirtuin–Polycomb-axis-coupling-epigenetic-ageing-to-mitochondrial-fatty-acid-oxidation**

**Figure 2: Proposed NAD+–Sirtuin–Polycomb axis coupling epigenetic ageing to mitochondrial fatty-acid oxidation**

(a) Proposed core axis: oral nicotinamide mononucleotide raises cellular nicotinamide adenine dinucleotide and the nicotinamide adenine dinucleotide/reduced nicotinamide adenine dinucleotide ratio, activating nicotinamide adenine dinucleotide-dependent sirtuins, including sirtuin 1 and sirtuin 3, hypothesized to restrain Polycomb repressive complex 2-mediated histone H3 lysine 27 trimethylation deposition and potentiate peroxisome proliferator-activated receptor gamma coactivator 1-alpha-driven mitochondrial biogenesis, relieving repressive constraint at the carnitine palmitoyltransferase 2 locus and supporting carnitine-dependent import of long-chain acyl-coenzyme A for mitochondrial beta-oxidation. (b) Directionality rule used to define coherent rescue under a repressive mark: age-associated histone H3 lysine 27 trimethylation gain increases silencing and is opposed by a nicotinamide mononucleotide-induced rise in aged-tissue expression, whereas loss is opposed by a nicotinamide mononucleotide-induced decrease; sign-matched genes are candidate convergent nodes, and sign-mismatched genes are compensatory or indirect. (c) Dual-arm model in which nicotinamide adenine dinucleotide elevation acts through a concordant arm that de-represses metabolic and mitochondrial loci, led by carnitine palmitoyltransferase 2 and fatty-acid oxidation, and through a discordant arm that remodels vesicular and endosomal trafficking, with both arms converging on restored bioenergetic flexibility. (d) Synthesis: the broad neuronal Polycomb-aging program and focused nicotinamide mononucleotide metabolic-rescue program intersect at a small number of convergent nodes, embedded in an epigenetic-metabolic feedback loop that nicotinamide adenine dinucleotide is proposed to tune selectively rather than reverse globally. **Prominent disclaimer: All molecular relationships, pathways, and proposed mechanisms shown are hypothesized predictive models derived from literature integration and the present secondary analysis. This study provides no direct experimental evidence that NMN alters H3K27me3 deposition at specific loci, nor any causal chromatin-level data. All proposed links, including NAD+–sirtuin–Polycomb and CPT2 regulation, remain unvalidated and require targeted experimental testing.** Credits to Ngo Cheung; created using PowerPoint; no artificial intelligence used.

Polycomb biology supports the epigenetic side of the model. PRC-associated systems help maintain transcriptional repression, and H3K27me3 is a major feature of Polycomb-linked chromatin states \[6,7\]. The neuronal aging preprint by Cheung extends this logic to aging neurons, proposing focal Polycomb-mediated repression of neuronal identity and synaptic maintenance genes \[8\]. In the present analysis, CPT2 showed H3K27me3 gain with age and a large K27me3 log-fold change of \+3.504. That makes it one of the clearest loci where a repressive aging mark and an NMN-rescue expression signal point in the same direction.

The metabolic side of the model is equally direct. CPT2 is part of the mitochondrial fatty-acid oxidation system. Long-chain fatty acids require the carnitine shuttle for mitochondrial entry and oxidation, and CPT2 is needed to regenerate long-chain acyl-CoA inside the mitochondrial compartment for beta-oxidation \[21-23\]. If CPT2 expression or regulation is constrained during aging, the cell may lose some flexibility in using fatty acids as energy substrates. This does not mean that CPT2 alone determines mitochondrial aging, but it does make CPT2 a practical readout of fatty-acid oxidative capacity.

The NMN side of the model likely involves NAD+ and sirtuins rather than direct action on H3K27me3. AMPK can increase NAD+ and enhance SIRT1 activity, leading to deacetylation of PGC-1alpha and FOXO targets \[12\]. SIRT1 interacts with PGC-1alpha, while SIRT3 is mitochondrial and influences acetylation of metabolic proteins \[13,15,16\]. NAD+ repletion has also been linked to mitochondrial and stress-response programs in aging models \[24,25\]. Thus, NMN may improve the metabolic context in which CPT2 is regulated. It may also indirectly affect chromatin modifier recruitment through redox state, acetylation state, mitochondrial stress signaling, or transcription factor activity. However, this analysis does not show that NMN removes H3K27me3 from CPT2. That remains a testable hypothesis.

A reasonable working model is therefore an epigenetic-metabolic feedback loop. Aging increases repressive chromatin pressure at CPT2-linked regions. This may reduce fatty-acid oxidation capacity or narrow metabolic flexibility. NMN raises NAD+ availability, supports sirtuin-linked mitochondrial programs, and increases CPT2 expression in old tissue. If validated, CPT2 would represent a specific node where chromatin aging and metabolic rescue meet.

### **Why Global Convergence Is Limited**

The analysis did not show broad convergence between neuronal H3K27me3 aging and NMN-induced transcriptional rescue. This is not surprising. The aging side was neuronal and chromatin-based, using H3K27me3 in a 24-month versus 3-month contrast. The NMN side was transcriptomic, measured in skeletal muscle, liver, and white adipose tissue, using 12-month versus 6-month animals and an age-by-treatment interaction model. These are different biological layers and different aging windows.

The gene-selection asymmetry was also substantial. The aging target set contained 21,155 genes, almost the entire eligible protein-coding space. This makes overlap almost unavoidable and weakens standard enrichment testing. The NMN robust set contained only 35 genes and was based on relaxed nominal p-value criteria, although the requirement for recurrence in at least two tissues added some protection against tissue-specific noise. Together, these features explain why exact overlap is not a strong finding and why pathway convergence was absent.

**Prior NMN omics literature also warrants a balanced reading. The original long-term mouse study reported physiological benefit but described tissue-dependent transcriptional effects \[9\]. Reviews of NMN and nicotinamide riboside emphasize that responses vary with tissue, age, dose, and experimental context, and that translation to humans remains incomplete \[10\]. The human study in prediabetic women demonstrated a defined metabolic benefit, not a universal transcriptomic or brain-aging rescue \[11\]. Published NMN-related work therefore does not establish a uniformly consistent rescue signature. The present findings are more consistent with a tissue-specific and context-dependent framework than with a model of universal transcriptional or chromatin normalization.**

The best framing is therefore not “NMN reverses neuronal epigenetic aging.” The data do not support that. A more defensible interpretation is that a small number of genes, especially CPT2, meet criteria for directional and biological plausibility across two aging-related programs. These genes are candidates for targeted validation.

### **Discordant Signal \- Compensatory vs Direct Rescue**

The discordant genes deserve attention because they may point to biology that is not captured by the simple rescue model. Discordance can occur when neuronal chromatin and metabolic-tissue expression are regulated differently. It can also occur when NMN affects a pathway indirectly, as part of a compensatory or homeostatic response. For example, improved mitochondrial function or altered NAD+/NADH balance could change endosomal trafficking, receptor recycling, or protein turnover without directly opposing a neuronal H3K27me3 mark.

The discordant group included SLC13A5, CMA2, WAP, TRP53INP2, PSME3, OLFR508, MYO15, RAB11A, and RANGAP1. These genes produced 38 significant GO terms, many related to endosome-to-plasma membrane transport, neurotransmitter receptor trafficking, microtubule organization, succinate transport, and C4-dicarboxylate transport. This was the most statistically visible enrichment in the downstream analysis, but the gene count was small. It should be treated as a lead, not as a stable pathway claim.

This pattern suggests that NMN may not act as a simple chromatin “reversal” agent. It may have at least two arms: a candidate direct or directionally coherent rescue arm, represented by genes such as CPT2, and an adaptive remodeling arm, represented by transport and trafficking terms in the discordant set. This distinction matters for translational work. A therapy that improves aging physiology may still produce tissue-specific or compensatory expression patterns that do not mirror the original aging mark.

### **Translational & Clinical Implications**

**Objective 4: Translational interpretation was limited to candidate prioritization, experimental validation, and future research directions; the current data were not used to infer clinical efficacy.**

The translational value of CPT2 lies in its specificity. Many aging interventions are discussed at the level of broad pathways: mitochondrial dysfunction, epigenetic drift, inflammation, oxidative stress, or NAD+ decline. These categories are useful but hard to validate clinically because they include many genes and mechanisms. CPT2 offers a narrower candidate. It has a defined mitochondrial role, a measurable transcript and protein, a functional assay through fatty-acid oxidation flux, and a chromatin hypothesis that can be tested by ChIP-qPCR or CUT\&Tag.

This is relevant to aging brain research because neurons and glia depend on metabolic flexibility, even if their substrate preferences differ across cell types and states. Bioenergetic limitation is also relevant to cognitive aging and neurodegenerative vulnerability. NAD+ biology has been discussed in relation to metabolism and neurodegeneration, but the field still needs markers that connect intervention response to specific cellular mechanisms \[5\]. CPT2 could serve as one such marker if its regulation is validated in the appropriate cells and tissues.

The psychiatric relevance should be stated carefully. **Any relevance to treatment-resistant depression, metabolic-psychiatric comorbidity, or broader neuropsychiatric conditions is speculative and represents a future research direction only. The current datasets contain no direct transcriptomic, epigenetic, behavioral, or clinical data linking CPT2 or the concordant gene set to psychiatric outcomes.** Treatment-resistant depression and metabolic-psychiatric comorbidity often raise questions about mitochondrial stress, inflammatory tone, and impaired adaptive plasticity, but this analysis did not test depression, behavior, or psychiatric phenotypes. **If CPT2 rescue is confirmed in neuronal or stress-relevant models, it could justify future disease-relevant experiments; it does not currently support a psychiatric treatment claim.**

CPT2 also has biomarker potential. A translational biomarker could include CPT2 mRNA, CPT2 protein, fatty-acid oxidation capacity, or H3K27me3 status at CPT2-linked regulatory regions. A stronger biomarker panel would combine CPT2 with secondary concordant genes such as ACD, ZFAND2B, FMO2, SYNGR2, DUSP11, APBA2, MAP2K2, SPG21, HS3ST6, and PKNOX1. However, because the concordant set had zero significant enrichment terms, it should be treated as a candidate panel rather than a pathway signature.

The clinical advantage of this approach is restraint. Instead of claiming that NMN is broadly anti-aging or that it reverses neuronal epigenetic aging, the analysis identifies one high-priority node with a clear validation path. That is more useful for translational work. It allows future experiments to ask specific questions: Does CPT2 expression decline or become constrained with age? Does NMN restore CPT2 expression in old tissues? Does H3K27me3 at CPT2-linked regions change with age and treatment? Does CPT2 modulation alter fatty-acid oxidation or cellular stress resilience? These are tractable questions.

### **Limitations & Future Directions**

The most important limitation is the size of the aging target set. With 21,155 target genes, the H3K27me3 program is too broad for simple binary overlap testing. Future work should use a more selective aging target set, such as the top 500, 1,000, or 2,000 genes ranked by ABC score multiplied by absolute K27me3 log-fold change. GAIN and LOSS genes should be tested separately, and promoter-proximal H3K27me3 should be evaluated separately from distal ABC-style assignments.

The second limitation is the NMN signal. No tissue-specific differential result reached FDR \< 0.05 for age, NMN at 6 months, or interaction. The rescue genes were therefore based on relaxed nominal criteria. The robust two-tissue filter helps, but it does not replace independent replication. Future NMN analyses should use larger sample sizes, RNA-seq where available, and models that can estimate tissue-specific and shared treatment effects more reliably.

The third limitation is cross-tissue inference. Neuronal chromatin aging cannot be assumed to map directly onto liver, muscle, or white adipose tissue expression. The present analysis should therefore be followed by direct testing in matched tissues or cell systems. For CPT2, the immediate validation steps are qPCR and Western blot in independent aging and NMN cohorts, K27me3 ChIP-qPCR or CUT\&Tag-qPCR at implicated CPT2 regulatory regions, and fatty-acid oxidation assays using Seahorse flux or labeled palmitate. Causal tests should include CPT2 knockdown or overexpression with and without NMN. Secondary validation can use a targeted panel of the top concordant genes.

**The ABC-style mapping introduces an additional source of uncertainty. The ABC model was developed primarily as a predictive enhancer-promoter framework \[18\], whereas the present pipeline used an ABC-style score to assign age-associated H3K27me3 regions, a repressive mark, to genes. Distal predictions can be false-positive, incomplete, or low-confidence, particularly when chromatin contact, cell-type specificity, or the regulatory effect of the mark is not directly measured. A predicted region-gene link should therefore not be treated as proof of direct regulation.**

**This uncertainty could contribute to directional discordance between the neuronal H3K27me3 dataset and the peripheral-tissue expression dataset. Some discordant calls may reflect tissue biology, indirect NMN responses, or compensatory regulation, but some may also be partly technical or artifactual consequences of low-confidence distal assignment. Locus-specific chromatin and expression assays in matched neuronal and peripheral models are needed to separate these possibilities.**

A final statistical improvement is to recompute overlap using a valid universe. The appropriate universe should include genes measured in the GSE85718 expression matrix and eligible for GSE190102 region-gene mapping. Permutation-based overlap and rank-based enrichment would be preferable to a simple hypergeometric test. Until those refinements are complete, all conclusions should remain hypothesis-generating.

## **Conclusions**

This integrative analysis found limited global convergence between age-associated neuronal H3K27me3 remodeling and cross-tissue NMN-rescue transcriptional changes. Although 23 genes were shared, the aging H3K27me3 target set was extremely broad, the initial hypergeometric universe was invalid, and no shared pathway enrichment was detected. These results do not support a claim that NMN broadly reverses neuronal epigenetic aging. The main value of the analysis is candidate discovery. Directional interpretation under repressive H3K27me3 logic identified 14 concordant genes. Among them, CPT2 stood out as the strongest candidate because it combined age-associated H3K27me3 gain, NMN-induced expression increase in old animals, mitochondrial fatty-acid oxidation biology, and the highest downstream validation priority score. The mitochondrial enrichment signal was only nominal, so CPT2 should be described as a focused mechanistic lead rather than proof of a broad mitochondrial program.

The next step is direct validation. CPT2 expression, protein abundance, fatty-acid oxidation function, and H3K27me3 status at CPT2-linked regions should be tested in independent aging and NMN models. If confirmed, CPT2 may provide a practical bridge between epigenetic aging and metabolic rescue, with potential relevance to aging-related bioenergetic decline and future translational work in metabolic conditions. **Any relevance to neuropsychiatric conditions remains speculative and requires direct disease-relevant testing; the present datasets do not establish such a link.**

## **References**

1. López-Otín C, Blasco MA, Partridge L, Serrano M, Kroemer G: The hallmarks of aging. Cell. 2013, 153:1194-1217. 10.1016/j.cell.2013.05.039

2. Lu T, Pan Y, Kao SY, Li C, Kohane I, Chan J, Yankner BA: Gene regulation and DNA damage in the ageing human brain. Nature. 2004, 429:883-891. 10.1038/nature02661

3. Cantó C, Auwerx J: NAD+ as a signaling molecule modulating metabolism. Cold Spring Harb Symp Quant Biol. 2011, 76:291-298. 10.1101/sqb.2012.76.010439

4. Imai S, Guarente L: NAD+ and sirtuins in aging and disease. Trends Cell Biol. 2014, 24:464-471. 10.1016/j.tcb.2014.04.002

5. Verdin E: NAD+ in aging, metabolism, and neurodegeneration. Science. 2015, 350:1208-1213. 10.1126/science.aac4854

6. Blackledge NP, Rose NR, Klose RJ: Targeting Polycomb systems to regulate gene expression: modifications to a complex story. Nat Rev Mol Cell Biol. 2015, 16:643-649. 10.1038/nrm4067

7. Müller J, Verrijzer P: Biochemical mechanisms of gene regulation by Polycomb group protein complexes. Curr Opin Genet Dev. 2009, 19:150-158. 10.1016/j.gde.2009.03.001

8. Cheung N: Focal Polycomb-mediated repression of neuronal identity and synaptic maintenance genes in aging neurons: mechanistic insights and translational opportunities. figshare. Preprint. 2026, 10.6084/m9.figshare.32531826.v1

9. Mills KF, Yoshida S, Stein LR, et al.: Long-term administration of nicotinamide mononucleotide mitigates age-associated physiological decline in mice. Cell Metab. 2016, 24:795-806. 10.1016/j.cmet.2016.09.013

10. Yoshino J, Baur JA, Imai S: NAD+ intermediates: the biology and therapeutic potential of NMN and NR. Cell Metab. 2018, 27:513-528. 10.1016/j.cmet.2017.11.002

11. Yoshino M, Yoshino J, Kayser BD, et al.: Nicotinamide mononucleotide increases muscle insulin sensitivity in prediabetic women. Science. 2021, 372:1224-1229. 10.1126/science.abe9985

12. Cantó C, Gerhart-Hines Z, Feige JN, et al.: AMPK regulates energy expenditure by modulating NAD+ metabolism and SIRT1 activity. Nature. 2009, 458:1056-1060. 10.1038/nature07813

13. Nemoto S, Fergusson MM, Finkel T: SIRT1 functionally interacts with the metabolic regulator and transcriptional coactivator PGC-1alpha. J Biol Chem. 2005, 280:16456-16460. 10.1074/jbc.M501485200

14. Hock MB, Kralli A: Transcriptional control of mitochondrial biogenesis and function. Annu Rev Physiol. 2009, 71:177-203. 10.1146/annurev.physiol.010908.163119

15. Onyango P, Celic I, McCaffery JM, Boeke JD, Feinberg AP: SIRT3, a human SIR2 homologue, is an NAD-dependent deacetylase localized to mitochondria. Proc Natl Acad Sci U S A. 2002, 99:13653-13658. 10.1073/pnas.222538099

16. Rardin MJ, Newman JC, Held JM, et al.: Label-free quantitative proteomics of the lysine acetylome in mitochondria identifies substrates of SIRT3 in metabolic pathways. Proc Natl Acad Sci U S A. 2013, 110:6601-6606. 10.1073/pnas.1302961110

17. Cheung N: NMN prevents age-associated transcriptional drift in a tissue-dependent manner: mechanistic leads from RAB11A-mediated trafficking and CPT2-linked fatty acid oxidation. figshare. Preprint. 2026, 10.6084/m9.figshare.32800638.v1

18. Fulco CP, Nasser J, Jones TR, et al.: Activity-by-contact model of enhancer-promoter regulation from thousands of CRISPR perturbations. Nat Genet. 2019, 51:1664-1669. 10.1038/s41588-019-0538-0

19. Chen EY, Tan CM, Kou Y, et al.: Enrichr: interactive and collaborative HTML5 gene list enrichment analysis tool. BMC Bioinformatics. 2013, 14:128. 10.1186/1471-2105-14-128

20. Kuleshov MV, Jones MR, Rouillard AD, et al.: Enrichr: a comprehensive gene set enrichment analysis web server 2016 update. Nucleic Acids Res. 2016, 44:90-97. 10.1093/nar/gkw377

21. McGarry JD, Brown NF: The mitochondrial carnitine palmitoyltransferase system: from concept to molecular analysis. Eur J Biochem. 1997, 244:1-14. 10.1111/j.1432-1033.1997.00001.x

22. Longo N, Frigeni M, Pasquali M: Carnitine transport and fatty acid oxidation. Biochim Biophys Acta. 2016, 1863:2422-2435. 10.1016/j.bbamcr.2016.01.023

23. Wanders RJA, Ruiter JPN, IJlst L, Waterham HR, Houten SM: The enzymology of mitochondrial fatty acid beta-oxidation and its application to follow-up analysis of positive neonatal screening results. J Inherit Metab Dis. 2010, 33:479-494. 10.1007/s10545-010-9104-8

24. Mouchiroud L, Houtkooper RH, Moullan N, et al.: The NAD+/sirtuin pathway modulates longevity through activation of mitochondrial UPR and FOXO signaling. Cell. 2013, 154:430-441. 10.1016/j.cell.2013.06.016

25. Zhang H, Ryu D, Wu Y, et al.: NAD+ repletion improves mitochondrial and stem cell function and enhances life span in mice. Science. 2016, 352:1436-1443. 10.1126/science.aaf2693

    

