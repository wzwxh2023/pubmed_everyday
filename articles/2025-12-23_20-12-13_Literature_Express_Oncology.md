# 2025年12月24日 - 专业文献速递

本期速递为您整理了最新的科研文献及AI评价，每一篇文献都包含了详细的元数据、原文摘要、中文翻译和AI的专业点评，敬请参考。

---

## 1. MPCutter：基于蛋白质语言模型的蛋白酶特异性底物切割位点预测

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41433056)
**期刊：** Genomics, proteomics & bioinformatics
**PMID：** 41433056
**DOI：** 10.1093/gpbjnl/qzaf130

### 第一部分 原文与翻译

**英文原标题：** MPCutter: Predicting Protease-specific Substrate Cleavage Sites Using a Protein Language Model.

> **英文摘要：**
> Proteases can cleave peptide bonds of target substrate proteins. Their controlled proteolysis is vital for protein degradation, recycling, and physiological processes. Understanding the hydrolytic mechanisms of proteases is crucial, particularly for identifying their specific substrates and cleavage sites. Bioinformatics approaches can predict novel protease-substrate cleavage events with high accuracy using sequence and structural information. However, existing tools for cleavage site prediction face several limitations, including restricted accuracy due to limited data and cumbersome training processes that impede timely updates. To address these challenges, we developed MPCutter, which was created by fine-tuning a general-purpose protein sequence language model. This method combined the extensive knowledge of the general model with the targeted optimization of fine-tuning, providing a powerful tool for protease-substrate cleavage prediction. MPCutter offers optimized cleavage site prediction models with enhanced performance and broader coverage across proteases, encompassing four major protease families including 62 distinct proteases. Benchmarking experiments using independent test datasets demonstrated that MPCutter outperformed existing generic tools. In our case study and experiments, MPCutter precisely recognized the majority of cleavage sites and validated five caspase-3 cleavage sites crucial for cellular physiology. Notably, its application to the 10,260-protein human proteome and specific cancer pathways revealed potential new target substrates and provided insights into key biochemical behaviors of proteases. MPCutter is expected to serve as a powerful tool for high-throughput prediction of protease-specific substrates and to facilitate hypothesis-driven exploration of protease proteolytic events. The MPCutter code and associated data are freely available at https://github.com/2053798680wang/MPCutter.git.

> **中文摘要：**
> 蛋白酶可以切割其靶底物蛋白的肽键。它们的受控蛋白水解对蛋白质降解、循环利用以及生理过程至关重要。理解蛋白酶的水解机制尤其重要，特别是在鉴定其特异性底物和切割位点方面。利用序列和结构信息的生物信息学方法可以高精度预测新的蛋白酶-底物切割事件。然而，现有的切割位点预测工具存在若干局限性，包括由于数据有限导致的精度受限以及繁琐的训练过程阻碍了模型的及时更新。为应对这些挑战，我们开发了 MPCutter，该模型通过微调一个通用的蛋白质序列语言模型而构建。此方法将通用模型的丰富知识与微调的定向优化相结合，提供了一个强大的蛋白酶-底物切割预测工具。MPCutter 提供了经过优化的切割位点预测模型，在性能和蛋白酶覆盖范围上均得到提升，涵盖包括 62 种不同蛋白酶在内的四大主要蛋白酶家族。使用独立测试数据集的基准实验表明，MPCutter 的表现优于现有的通用工具。在我们的案例研究和实验中，MPCutter 精确识别了大多数切割位点，并验证了五个对细胞生理至关重要的半胱天冬酶-3 切割位点。值得注意的是，将其应用于含有 10,260 个蛋白的人类蛋白质组以及特定的癌症通路时，揭示了潜在的新靶底物，并为理解蛋白酶的关键生化行为提供了新见解。MPCutter 有望成为进行高通量蛋白酶特异性底物预测的有力工具，并促进基于假设驱动的蛋白酶水解事件探索。MPCutter 的代码和相关数据可在 https://github.com/2053798680wang/MPCutter.git 免费获取。

### 第二部分 AI 大师评价

该研究旨在通过微调蛋白质语言模型，开发出能够高精度预测蛋白酶特异性底物切割位点的工具 MPCutter。方法上创新性地融合了通用模型的知识与针对特定任务的精细优化，从而克服了传统预测工具训练复杂、精度受限的问题。实验结果显示，MPCutter 在多个蛋白酶家族的预测中表现优异，并能够揭示新的潜在底物与生理相关切割事件。其在大规模蛋白质组分析中的可扩展性为探索蛋白酶功能提供了强大支持，但仍需进一步在多样化数据集上验证其广泛适用性。

---

## 2. 去除纤维蛋白原可抑制胰腺导管腺癌原发瘤的生长及其转移。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41432649)
**期刊：** Gastroenterology
**PMID：** 41432649
**DOI：** 10.1053/j.gastro.2025.09.024

### 第一部分 原文与翻译

**英文原标题：** Depletion of Fibrinogen Suppresses Growth of Primary Tumors and Metastasis of Pancreatic Ductal Adenocarcinoma.

> **英文摘要：**
> BACKGROUND & AIMS: Pancreatic ductal adenocarcinoma (PDAC) is an aggressive, highly metastatic disease that provokes dysregulation of the coagulation system. Patients exhibit significantly elevated circulating levels of blood clotting protein fibrin(ogen). Extravascular fibrin deposits contribute to the complex tumor microenvironment in PDAC.
> 
> METHODS: We depleted fibrinogen in 3 PDAC patient-derived xenograft models using technology platforms that are currently being tested clinically (antisense oligonucleotide or lipid nanoparticles containing small interfering RNAs) and monitored tumor growth and metastasis. Proteomics and spatial transcriptomics were used to interrogate the mechanisms behind the in vivo work.
> 
> RESULTS: The role of fibrin on tumor progression was evaluated in vitro and in vivo and reduction of fibrin led to decreased tumor cell proliferation in vitro and significantly suppressed primary orthotopic tumor growth. Fibrin depletion provoked a significant shift in extracellular matrix-associated proteins and serine protease inhibitors, suggesting a decrease in the activity of serine proteases known to be responsible for extracellular matrix remodeling and metastatic dissemination. Spatial transcriptomics revealed that tumors from fibrinogen-depleted mice exhibit significantly increased presence of stromal components, including tumor-restraining cancer-associated fibroblasts. Congruently, fibrinogen knockdown in a metastatic orthotopic model markedly impaired spontaneous metastasis to the liver. However, fibrinogen knockdown did not affect liver colonization in an intrasplenic injection model, which recapitulates the late stages of metastasis.
> 
> CONCLUSIONS: These data suggest that fibrin(ogen) reprograms the primary tumor microenvironment to support growth and promote early, but not late, metastatic steps. Our findings support prospective evaluation of a novel clinical approach involving the integration of fibrin(ogen)-targeting or depleting agents into chemotherapy regimens to control the spread of pancreatic cancer.

> **中文摘要：**
> 背景与目的：胰腺导管腺癌（PDAC）是一种侵袭性强、转移性高的疾病，会引发凝血系统失调。患者表现出显著升高的循环性凝血蛋白纤维（原）水平。血管外纤维蛋白沉积物有助于形成PDAC复杂的肿瘤微环境。
> 
> 方法：我们在3种来源于PDAC患者的异种移植模型中，利用目前正在临床测试的技术平台（反义寡核苷酸或含有小干扰RNA的脂质纳米颗粒）耗竭纤维蛋白原，并监测肿瘤的生长和转移。利用蛋白质组学和空间转录组学方法探究了体内实验背后的机制。
> 
> 结果：我们在体内及体外评估了纤维蛋白在肿瘤进展中的作用，结果发现减少纤维蛋白可降低体外肿瘤细胞增殖，并显著抑制原位原发肿瘤的生长。纤维蛋白耗竭引发了细胞外基质相关蛋白和丝氨酸蛋白酶抑制剂的显著变化，提示丝氨酸蛋白酶活性下降，这类酶已知负责细胞外基质重塑及转移播散。空间转录组学分析显示，纤维蛋白原耗竭小鼠的肿瘤中基质成分显著增加，其中包括具有抑制肿瘤功能的癌相关成纤维细胞。与此一致的是，在转移性原位模型中，敲低纤维蛋白原显著削弱了肝脏的自发性转移。然而，在模仿转移晚期阶段的脾内注射模型中，纤维蛋白原敲低并未影响肝脏的定植。
> 
> 结论：这些数据提示纤维（原）可重塑原发肿瘤微环境以支持肿瘤生长，并促进早期而非晚期的转移步骤。我们的研究结果支持将靶向或去除纤维（原）的新型治疗策略与化疗方案相结合，用于控制胰腺癌扩散的前瞻性临床评估。

### 第二部分 AI 大师评价

该研究揭示了纤维蛋白（原）在胰腺导管腺癌生长和早期转移中的关键调控作用。作者通过患者来源的异种移植模型，利用反义寡核苷酸和小干扰RNA技术精准耗竭纤维蛋白原，并结合蛋白质组学和空间转录组学揭示其对肿瘤微环境的重塑效应。结果显示，纤维蛋白原减少显著抑制肿瘤生长与早期转移，但不影响转移晚期阶段，提示其在肿瘤进展中的阶段性作用。该研究为整合靶向纤维蛋白（原）的治疗策略提供了实验依据，但仍需进一步评估其临床安全性和疗效。

---

## 3. 利用仿生共递送辛伐他汀和犬尿氨酸酶调控肿瘤代谢重编程以增强免疫治疗效应

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41432057)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41432057
**DOI：** 10.1002/advs.202508107

### 第一部分 原文与翻译

**英文原标题：** Regulating Tumor Metabolic Reprogramming with Biomimetic Co-Delivery of Simvastatin and Kynureninase for Immunotherapy.

> **英文摘要：**
> The metabolic reprogramming of immunosuppressive tumor microenvironment (ITME) greatly influences the anti-tumor immunity. Bioinformatic analysis demonstrates that indoleamine 2,3-dioxygenase 1 and 3-hydroxy-3-methylglutaryl coenzyme A reductase (key enzymes of kynurenine (Kyn) and cholesterol metabolism, respectively), are overexpressed in human colon adenocarcinoma tissues. Herein, biomimetic and pH/ROS dual-responsive nanoparticles (PTSK@CRM) loaded with simvastatin and kynureninase (KYNase) are prepared to regulate Kyn and cholesterol metabolism, thereby enhancing the immunotherapeutic efficacy of PD-1 antibody (αPD-1). The monodisperse spherical PTSK@CRM is stable at pH 7.4, while it can release simvastatin and KYNase under low pH and high HO concentration. PTSK@CRM achieves excellently homologous tumor targeting to CT26 cells and induces cell apoptosis more effectively than PTSK. Moreover, PTSK@CRM significantly reduces the contents of Kyn and cholesterol and decreases the activation of the Kyn-AhR pathway in tumor metabolism. In vivo experiments show that PTSK@CRM possesses a favorable tumor-targeting ability to effectively suppress tumor growth and increase the infiltration of immune cells, including CD8 T cells, CD4 T cells, M1-like macrophages, and mature dendritic cells. Further, PTSK@CRM reduces the infiltration of immunosuppressive cells, thereby reversing ITME to improve the therapeutic efficacy of αPD-1. Overall, this immune-metabolic therapeutic strategy provides a potential route for remodeling ITME to enhance tumor immunotherapy.

> **中文摘要：**
> 免疫抑制性肿瘤微环境（ITME）的代谢重编程对抗肿瘤免疫具有深远影响。生物信息学分析表明，吲哚胺2,3-双加氧酶1和3-羟基-3-甲基戊二酰辅酶A还原酶（分别为犬尿氨酸（Kyn）和胆固醇代谢的关键酶）在人体结肠腺癌组织中过度表达。在此基础上，本研究制备了负载辛伐他汀与犬尿氨酸酶（KYNase）的仿生pH/ROS双响应纳米颗粒（PTSK@CRM），以调控Kyn和胆固醇代谢，从而增强程序性死亡受体-1抗体（αPD-1）的免疫治疗效果。单分散球形的PTSK@CRM在pH 7.4条件下稳定，而在低pH和高H₂O₂浓度条件下可释放辛伐他汀和KYNase。PTSK@CRM对CT26细胞表现出优异的同源性肿瘤靶向能力，并能较PTSK更有效地诱导细胞凋亡。此外，PTSK@CRM显著降低了Kyn和胆固醇含量，并抑制了肿瘤代谢中的Kyn-AhR通路活化。体内实验表明，PTSK@CRM具有良好的肿瘤靶向能力，可有效抑制肿瘤生长并增加免疫细胞的浸润，包括CD8 T细胞、CD4 T细胞、M1样巨噬细胞和成熟树突状细胞。此外，PTSK@CRM可减少免疫抑制性细胞的浸润，从而逆转ITME并提升αPD-1的治疗效果。总体而言，该免疫-代谢联合治疗策略为重塑ITME以增强肿瘤免疫治疗提供了潜在途径。

### 第二部分 AI 大师评价

该研究针对免疫抑制性肿瘤微环境的代谢重编程问题，通过设计负载辛伐他汀与犬尿氨酸酶的仿生双响应纳米颗粒，协同调控犬尿氨酸与胆固醇代谢，从而增强PD-1抗体的免疫治疗效果。实验结果显示该系统不仅在体外有效诱导肿瘤细胞凋亡，也在体内改善免疫细胞浸润，显著抑制肿瘤生长。研究的创新性在于整合代谢干预与免疫治疗，重塑肿瘤微环境，提供了一种可拓展的免疫-代谢耦合治疗思路。然而，其长期安全性与临床可转化性尚需进一步研究。

---

## 4. Wedelolactone：一种新型TLR2激动剂，促进中性粒细胞分化并改善中性粒细胞减少症——基于多组学的作用机制解析

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41432050)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41432050
**DOI：** 10.1002/advs.202509807

### 第一部分 原文与翻译

**英文原标题：** Wedelolactone, a Novel TLR2 Agonist, Promotes Neutrophil Differentiation and Ameliorates Neutropenia: A Multi-Omics Approach to Unravel the Mechanism.

> **英文摘要：**
> Neutropenia, a common complication in cancer patients undergoing radiotherapy, heightens the risk of infection and mortality, with limited treatment options. This study investigates wedelolactone (WED), a natural coumarin, as a potential therapeutic agent. WED is found to promote neutrophil differentiation and enhance bactericidal function in vitro. Its in vivo efficacy is validated in radiation-induced neutropenic mouse and zebrafish models, where it facilitates rapid recovery of leukocyte and neutrophil levels. An integrated approach using the GEO database, RNA sequencing, molecular docking, and Drug Affinity Responsive Target Stability (DARTS) assays identifies TLR2 and its downstream MAPK signaling pathway as essential for WED's anti-neutropenic effects. DARTS confirms significant binding of WED to TLR2. Knockdown of TLR2 with siRNA or inhibition of TLR2 with C29 reduces WED-induced neutrophil differentiation, MEK1/2 and ERK1/2 phosphorylation, and expression of transcription factors (PU.1, CEBPβ). Similarly, ERK1/2 inhibition by SCH772984 impairs WED-induced neutrophil differentiation and bactericidal activity, decreasing PU.1 and CEBPβ expression without affecting TLR2 levels. These findings position TLR2 as a key therapeutic target for neutropenia, with WED effectively promoting neutrophil differentiation via TLR2 and MEK/ERK pathway activation. This study highlights the therapeutic potential of targeting TLR2 to alleviate neutropenia and underscores the utility of a multi-omics approach in uncovering drug mechanisms.

> **中文摘要：**
> 中性粒细胞减少症是接受放射治疗的癌症患者中常见的并发症，会增加感染和死亡风险，且可用的治疗选择有限。本研究探讨了天然香豆素化合物Wedelolactone（WED）作为潜在治疗药物的作用。结果发现，WED在体外可促进中性粒细胞分化并增强其杀菌功能。其在体内的疗效通过放射诱导的中性粒细胞减少小鼠和斑马鱼模型得到验证，表现为白细胞和中性粒细胞水平的快速恢复。研究基于GEO数据库、RNA测序、分子对接及药物亲和响应靶标稳定性（DARTS）等多组学整合分析，鉴定出TLR2及其下游MAPK信号通路在WED的抗中性粒细胞减少作用中起关键作用。DARTS实验确认了WED与TLR2之间的显著结合。利用siRNA敲低TLR2或使用抑制剂C29阻断TLR2后，WED诱导的中性粒细胞分化、MEK1/2与ERK1/2磷酸化以及转录因子（PU.1、CEBPβ）的表达均明显减少。同样，ERK1/2抑制剂SCH772984可削弱WED诱导的中性粒细胞分化和杀菌活性，降低PU.1和CEBPβ的表达，而不影响TLR2水平。这些发现表明TLR2是中性粒细胞减少症的重要治疗靶点，WED通过激活TLR2和MEK/ERK通路有效促进中性粒细胞分化。本研究强调了靶向TLR2缓解中性粒细胞减少的治疗潜力，并突出了多组学研究在揭示药物机制中的重要价值。

### 第二部分 AI 大师评价

该研究聚焦于放疗相关中性粒细胞减少的干预，创新性地发现天然香豆素化合物Wedelolactone可作为TLR2激动剂促进中性粒细胞分化。作者通过多组学结合体内外实验，从分子、信号通路到动物模型系统性揭示了WED通过激活TLR2-MEK/ERK通路发挥作用的机制。研究不仅拓展了中性粒细胞减少症的治疗思路，也为TLR2靶向药物开发提供了新证据。其局限性在于仍需在临床模型中进一步验证药效与安全性。

---

## 5. 镁基结构-功能一体化平台用于时空多模态治疗：在前列腺癌中联合激素治疗与免疫治疗

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41432021)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41432021
**DOI：** 10.1002/advs.202515235

### 第一部分 原文与翻译

**英文原标题：** Magnesium Structure-Function Integration Platform for Spatiotemporal Multi-Modality Therapy: Combining Hormonotherapy and Immunotherapy in Prostate Cancer.

> **英文摘要：**
> Metal-based immunotherapy represents a promising strategy for enhancing antitumor efficacy; however, its clinical application is limited by challenges such as inefficient drug delivery, low specificity, and suboptimal therapeutic outcomes. In this study, a therapeutic platform is constructed on a magnesium (Mg) surface utilizing self-healing thiolated hyaluronic acid (HA-SH) and cell membrane-derived vesicle (CMV) drug system, which improves structural stability, enables spatiotemporal drug release, and facilitates immune-hormone combination therapy for prostate cancer. CMV with phospholipid bilayers promotes HA-SH disulfide bond interactions through weak hydrophobic interactions, mitigating corrosion and ensuring structural integrity. Additionally, HA-SH exhibits glutathione (GSH)-responsive drug release within the tumor microenvironment. CMV facilitates pH-sensitive drug delivery and enables efficient cytoplasmic entry via membrane fusion mechanisms, ensuring precise spatiotemporal control. Through drug library screening, ginsenoside Rb1 is identified as a key therapeutic agent, competitively inhibiting androgen receptor signaling. Coupled with hydrogen release from Mg, it induces immunogenic cell death and promotes the formation of tertiary lymphoid structures (TLS) via inhibiting the PI3K-AKT pathway, achieving synergistic androgen deprivation therapy and immune activation. This implantable drug delivery system effectively tackles mechanical stability, local drug delivery, and systemic immune activation concerns, demonstrating substantial translational promise for various malignancies to improve treatment effectiveness and reduce structural failure risks.

> **中文摘要：**
> 金属基免疫治疗代表了一种有前景的策略，可增强抗肿瘤疗效；然而，其临床应用受到药物递送效率低、特异性差及治疗效果不理想等挑战的限制。本研究在镁（Mg）表面构建了一个利用自修复型巯基化透明质酸（HA-SH）与细胞膜来源囊泡（CMV）药物系统的治疗平台，该平台可改善结构稳定性，实现时空可控的药物释放，并促进前列腺癌的免疫-激素联合治疗。具有磷脂双分子层的CMV通过弱疏水相互作用促进HA-SH二硫键的相互作用，从而降低腐蚀并确保结构完整性。此外，HA-SH在肿瘤微环境中表现出谷胱甘肽（GSH）响应的药物释放特性。CMV可实现pH敏感的药物递送，并通过膜融合机制促进药物高效进入细胞质，从而实现精确的时空控制。通过药物库筛选，确定了人参皂苷Rb1作为关键治疗因子，可竞争性抑制雄激素受体信号通路。结合镁释放的氢气，它可诱导免疫原性细胞死亡，并通过抑制PI3K-AKT通路促进三级淋巴结构（TLS）的形成，从而实现雄激素剥夺治疗与免疫激活的协同效应。该可植入药物递送系统有效解决了机械稳定性、局部药物递送及系统性免疫激活等问题，展现出显著的转化潜力，有望用于多种恶性肿瘤以提高治疗效果并降低结构失效风险。

### 第二部分 AI 大师评价

本研究开发了一种镁基自修复药物递送平台，通过HA-SH与CMV的协同结构设计，实现了针对前列腺癌的激素-免疫联合治疗。研究利用材料化学与生物膜工程结合，达成了时空可控的药物释放与结构稳定性优化。人参皂苷Rb1的筛选与镁释放氢气的免疫增强作用共同实现了双重治疗机制。该平台的创新点在于融合了金属材料、可响应性聚合物及生物膜系统，但其长期生物安全性及在复杂肿瘤环境中的可控性仍需进一步验证。

---

## 6. 用于衰老调控免疫激活的仿生纳米药物可增强肝细胞癌免疫治疗效果

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41432006)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41432006
**DOI：** 10.1002/advs.202517792

### 第一部分 原文与翻译

**英文原标题：** Biomimetic Nanomedicine for Senescence-Modulated Immune Activation Enhances Immunotherapy Efficacy in Hepatocellular Carcinoma.

> **英文摘要：**
> Tumor senescence, a double-edged sword, can suppress tumor growth but also promote immune evasion if not properly cleared. Herein, a cell membrane-coated ZIF-8@MnOx nanoplatform co-loaded with doxorubicin (DOX) and piperlongumine (PL), termed mPDZM, is developed to remodel the senescence-mediated immune response in hepatocellular carcinoma. PL synergizes with DOX to amplify intracellular oxidative stress, which promotes both the killing of tumor cells and the clearance of senescent cells. The biomimetic ZIF-8@MnOx nanoplatform potentiates the efficacy of DOX and PL by integrating targeted delivery, hypoxia relief, and redox homeostasis disruption. mPDZM remodels the immunosuppressive microenvironment by regulating SASP release, inducing immunogenic cell death, and activating the STING signaling pathway. In vivo, mPDZM exhibits preferential tumor accumulation and minimal systemic toxicity. mPDZM treatment leads to significant tumor suppression both in the senescent and non-senescent tumor models. Moreover, mPDZM effectively promotes CD8 T cell and NK cell infiltration, while reducing immunosuppressive Treg cells and M2-like macrophages. In combination with anti-PD-L1 therapy, mPDZM further potentiates antitumor immunity and induces a robust abscopal effect against distant tumors. Collectively, these findings unveil a new paradigm that integrates senescence modulation with immune activation via a biomimetic nanotherapeutic platform and offers a promising combinatorial approach to overcome immune resistance in solid tumors.

> **中文摘要：**
> 肿瘤细胞衰老是一把双刃剑，既可抑制肿瘤生长，也可能在未被及时清除时促进免疫逃逸。本研究构建了一种细胞膜包覆的ZIF-8@MnOx纳米平台，同时负载多柔比星（DOX）和胡椒长春碱（PL），称为mPDZM，用于重塑肝细胞癌中衰老介导的免疫反应。PL与DOX协同作用以增强细胞内氧化应激，从而促进肿瘤细胞的杀伤及衰老细胞的清除。仿生ZIF-8@MnOx纳米平台通过整合靶向递送、缓解缺氧和破坏氧化还原稳态等机制，增强DOX和PL的治疗效能。mPDZM通过调节SASP释放、诱导免疫原性细胞死亡并激活STING信号通路，有效重塑免疫抑制性微环境。在体内实验证明，mPDZM表现出优先的肿瘤富集性及极低的全身毒性。mPDZM治疗在衰老型和非衰老型肿瘤模型中均显著抑制肿瘤生长。此外，mPDZM可有效促进CD8 T细胞和NK细胞浸润，同时减少免疫抑制性Treg细胞及M2型样巨噬细胞。当与抗PD-L1治疗联合时，mPDZM进一步增强抗肿瘤免疫反应，并对远处肿瘤诱导出强大的旁效应。总体而言，这些研究结果揭示了一种融合衰老调控与免疫激活的仿生纳米治疗新范式，为克服实体瘤免疫耐受提供了有前景的联合治疗策略。

### 第二部分 AI 大师评价

本研究旨在通过仿生纳米平台调控肿瘤细胞衰老相关免疫反应，从而提升肝细胞癌免疫治疗的疗效。作者设计的mPDZM纳米载体实现了药物协同、靶向递送及微环境调控的多重功能，显著强化了抗肿瘤免疫反应。该研究通过STING信号通路激活和SASP调控揭示了衰老与免疫之间的新联系，并展示出与免疫检查点抑制剂联用的巨大潜力。创新性体现在衰老调控与免疫激活的整合思路，但未来仍需在临床转化和长期安全性方面得到进一步验证。

---

## 7. CAR-T细胞免疫治疗中的GPCRs：拓展靶点版图与增强治疗效能

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41432000)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41432000
**DOI：** 10.1002/advs.202517188

### 第一部分 原文与翻译

**英文原标题：** GPCRs in CAR-T Cell Immunotherapy: Expanding the Target Landscape and Enhancing Therapeutic Efficacy.

> **英文摘要：**
> Chimeric Antigen Receptor T cell (CAR-T) therapy has shown significant efficacy in treating hematologic malignancies. However, its application in solid tumors is still challenged by a scarcity of specific targets and the immunosuppressive tumor microenvironment. G protein-coupled receptors (GPCRs), due to their wide distribution and diverse signaling cascades in tumorigenesis, have emerged as promising targets for CAR-T therapy. This review systematically integrates recent advances of GPCR CAR-T therapy for cancer immunotherapy, with a particular emphasis on current targeting strategies and optimization approaches. This includes the identification of GPCRs as novel tumor-associated antigens to expand CAR-T therapeutic applications, co-expressi on of chemokine receptors to enhance tumor infiltration, and utilization ofGPCR signaling pathways to improve CAR-T cell persistence and cytotoxic efficacy. Potential future research directions include application of AI(Artificial Intelligence) to expedite the development of GPCR antibodies, creation of precision therapies targeting GPCR complexes, modulation of GPCR dimerization networks to maintain homeostasis of membrane antigen expression, employment of nanobody platform to enhance targeting specificity, and design of GPCR allosteric modulators as molecular switches for CAR-T cells. Additionally, this review also examines the application of specific antibodies and other immunotherapeutic approaches of GPCRs in oncology. Overall, this review aims to provide novel scientific and therapeutic perspectives for CAR-T cell therapy in treating mutiple types of human cancers.

> **中文摘要：**
> 嵌合抗原受体T细胞（CAR-T）疗法在治疗血液系统恶性肿瘤中已显示出显著疗效。然而，其在实体瘤中的应用仍受到特异性靶点稀缺和免疫抑制性肿瘤微环境的制约。G蛋白偶联受体（GPCRs）因其在肿瘤发生中的广泛分布及多样化信号级联反应，被认为是CAR-T治疗的有前景靶点。本综述系统整合了GPCR CAR-T治疗在癌症免疫治疗中的最新进展，特别关注当前的靶向策略与优化方法。这包括将GPCR识别为新的肿瘤相关抗原以拓展CAR-T疗法的适用范围，共表达趋化因子受体以增强肿瘤浸润，以及利用GPCR信号通路提高CAR-T细胞的持久性和细胞毒效应。潜在的未来研究方向包括应用人工智能（AI）加速GPCR抗体的开发，构建靶向GPCR复合物的精准治疗，调控GPCR二聚体化网络以维持膜抗原表达的稳态，利用纳米抗体平台提高靶向特异性，以及设计GPCR别构调节剂作为CAR-T细胞的分子开关。此外，本综述还探讨了特异性抗体及其他GPCR相关免疫治疗策略在肿瘤学中的应用。总体而言，本综述旨在为多种人类癌症的CAR-T细胞治疗提供新的科学与治疗视角。

### 第二部分 AI 大师评价

本文综述了GPCR在CAR-T细胞免疫治疗领域中的潜力与最新进展，重点探讨了靶点拓展、治疗优化及信号调控等策略。作者从分子层面到工程方法系统梳理了GPCR介导的靶向机制，并展望了AI、纳米抗体以及别构调节剂在精准免疫治疗中的应用前景。该研究的创新性在于提出了将GPCR网络生物学与CAR-T工程相结合的跨界思路。然而，目前相关研究仍处早期阶段，其在不同肿瘤模型中的安全性与有效性尚待验证。

---

## 8. METTL5通过调控趋化因子mRNA翻译促进肝癌免疫逃逸

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41431992)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41431992
**DOI：** 10.1002/advs.202512528

### 第一部分 原文与翻译

**英文原标题：** METTL5 Enables Immune Evasion of Liver Cancer via Chemokine mRNA Translation Regulation.

> **英文摘要：**
> The liver microenvironment is essential to immune surveillance and liver cancer progression. Here, the aim is to identify the role of METTL5, the 18S rRNA mA methyltransferase, in regulating the liver immune microenvironment to promote cancer progression. Liver-specific Mettl5 knockout (cKO) in mice exhibits increased immune cell infiltration, especially CD3 and CD4 T cells. Loss of Mettl5 inhibits intrahepatic cholangiocarcinoma (ICC) progression. By scRNA-seq analysis, it is found that ICC from both cKO mice and human METTL5 low expression group correlates with increased CD8 T cells but decreased macrophages, which is associated with better survival. Adoptive transfer of macrophages significantly promotes ICC progression. scRNA-seq and scTCR-seq analysis show that cKO mice exhibit reduced immunosuppressive Ms4a7C1qa tumor-associated macrophages (TAMs) but increased intratumoral IFN-γCD8 T cell infiltration and expansion. Mechanistically, METTL5-mediated 18S rRNA mA modification downregulates the mRNA translation of CXCL16 to exclude CD8 T cells. Knockout of Mettl5 significantly increases CD8 T cell infiltration in vivo. Combined METTL5 targeting using lipid nanoparticle-encapsulated siRNA and PD-1 blockade provokes anti-tumor immunity to eradicate ICC tumors. Additionally, METTL5 human ICC correlates with responsiveness to immunotherapy. The study highlights the strong immuno-evasive ability of METTL5 as a promising therapeutic target in ICC.

> **中文摘要：**
> 肝脏微环境对于免疫监视和肝癌进展至关重要。本研究旨在阐明18S rRNA mA甲基转移酶METTL5在调控肝脏免疫微环境并促进肝癌进展中的作用。小鼠中肝脏特异性敲除Mettl5（cKO）导致免疫细胞浸润增加，尤其是CD3和CD4 T细胞。Mettl5的缺失抑制了肝内胆管癌（ICC）的进展。通过单细胞RNA测序（scRNA-seq）分析发现，无论是cKO小鼠还是人类METTL5低表达组的ICC，都表现出CD8 T细胞增多而巨噬细胞减少的特征，这与更好的生存相关。巨噬细胞的被动转移显著促进ICC进展。scRNA-seq和单细胞TCR测序（scTCR-seq）结果显示，cKO小鼠中免疫抑制型Ms4a7C1qa肿瘤相关巨噬细胞（TAMs）减少，而肿瘤内IFN-γ阳性CD8 T细胞浸润及扩增增加。在机制上，METTL5介导的18S rRNA mA修饰可下调CXCL16 mRNA的翻译，从而排斥CD8 T细胞。Mettl5敲除显著增加体内CD8 T细胞的浸润。将脂质纳米颗粒包裹的siRNA靶向METTL5联合PD-1阻断可激活抗肿瘤免疫反应，从而清除ICC肿瘤。此外，人类ICC中METTL5水平与免疫治疗反应性相关。本研究揭示了METTL5的强大免疫逃逸作用，提示其为ICC的潜在治疗靶点。

### 第二部分 AI 大师评价

本研究聚焦METTL5在肝内胆管癌免疫微环境调控中的关键作用。作者通过小鼠肝特异性基因敲除模型与单细胞多组学分析，揭示METTL5通过18S rRNA甲基化影响趋化因子CXCL16翻译，从而调控CD8 T细胞浸润和免疫逃逸。实验进一步证实联合METTL5干扰和PD-1阻断可显著增强抗肿瘤免疫反应。该研究在肿瘤免疫调控机制和治疗策略层面均具有创新意义，但对METTL5在其他肿瘤类型中的作用仍需进一步验证。

---

## 9. 新生连接蛋白基因转录介导生理性与癌性上皮系统中的胞质流体交换及群集转变

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41431893)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41431893
**DOI：** 10.1002/advs.202508648

### 第一部分 原文与翻译

**英文原标题：** De Novo Gene Transcription of Connexin Mediates Cytoplasmic Fluid Exchange and Flocking Transitions in Physiological and Cancerous Epithelial Systems.

> **英文摘要：**
> The initial invasion of tumors requires a transition from a solid, jammed state to a fluid-like, flocking, unjammed state that enables collective migration. Here, we show that de novo gene transcription is essential for the emergence of flocking in epithelial tissues and identify connexins (Cx) as key mediators of this transition. Using quiescent HaCaT keratinocytes, tumorigenic A431 epidermoid carcinoma cells, primary bronchial epithelial explants, and vocal fold carcinoma (VFC) cells, we find that flocking induction depends on transcriptional programs activated downstream of epidermal growth factor (EGF). EGF stimulation upregulates Cx26 and Cx31 and enhances gap-junctional intercellular communication (GJIC), which is necessary-though not sufficient-to generate the large-scale cell-volume fluctuations and density heterogeneity that accompany unjamming. Sustained signaling through extracellular signal-regulated kinase 1/2 (ERK1/2) and AKT serine/threonine kinase (AKT) downstream of the EGF receptor (EGFR) is required for connexin induction, linking mechanical state transitions to extracellular cues. Pharmacological inhibition and CRISPR-Cas9 (clustered regularly interspaced short palindromic repeats-CRISPR associated protein 9) knockout of connexins block unjamming and collective motility. VFC cells display constitutively elevated connexins and persistent flocking that is highly sensitive to connexin inhibition. Consistently, high Cx26 expression correlates with reduced survival across carcinomas. These findings reveal a transcriptionally controlled, connexin-dependent mechanism that enables tissue fluidization and collective invasion.

> **中文摘要：**
> 肿瘤的初始侵袭需要从一种固态、拥挤状态转变为类似流体的、成群运动的、非拥挤状态，以实现集体迁移。本文显示，新生基因转录对于上皮组织中群集现象的出现至关重要，并确定连接蛋白（Cx）是该转变的关键介质。通过使用静息的HaCaT角质形成细胞、致瘤性的A431表皮癌细胞、原代支气管上皮外植体及声带癌（VFC）细胞，我们发现群集的诱导依赖于表皮生长因子（EGF）下游激活的转录程序。EGF刺激上调Cx26和Cx31的表达，并增强缝隙连接的细胞间通信（GJIC），这对于生成伴随非拥挤化的、大尺度细胞体积波动及密度异质性是必需的——尽管并非充分条件。EGF受体（EGFR）下游持续激活的细胞外信号调节激酶1/2（ERK1/2）和丝氨酸/苏氨酸激酶AKT信号通路对于连接蛋白的诱导是必需的，从而将机械状态转变与细胞外信号联系起来。药理性抑制及CRISPR-Cas9（成簇规律间隔短回文重复序列-相关蛋白9）敲除连接蛋白可阻断非拥挤化及集体运动。VFC细胞表现出持续升高的连接蛋白水平和持续的群集运动，对连接蛋白抑制高度敏感。与此一致，高Cx26表达在多种癌症中与较差的生存率相关。这些发现揭示了一种受转录控制的、依赖连接蛋白的机制，使组织流体化及集体侵袭成为可能。

### 第二部分 AI 大师评价

本研究揭示了上皮组织从致密固态向流动群集状态转变的分子基础，指出新生转录及连接蛋白在该过程中起关键作用。通过多种细胞模型与信号通路实验，研究者阐明EGF-ERK/AKT轴驱动连接蛋白上调，从而介导细胞间流体性交流与群集迁移。其创新性在于首次建立了机械状态变化与转录程序的直接联系，并揭示连接蛋白作为组织非拥挤化的核心枢纽。研究为理解肿瘤集体侵袭机制提供了新视角，但仍需进一步验证其在体内环境中的普适性及调控靶点的可行性。

---

## 10. Mac-/乳糖神经酰胺通过促进 Notch 信号调控肠道稳态及分泌细胞命运承诺。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41431871)
**期刊：** eLife
**PMID：** 41431871
**DOI：** 10.7554/eLife.106184

### 第一部分 原文与翻译

**英文原标题：** Mac-/Lactosylceramide regulates intestinal homeostasis and secretory cell fate commitment by facilitating Notch signaling.

> **英文摘要：**
> Cell-to-cell communication via Delta-Notch signaling is widely used in various tissues and organs to regulate development and patterning; however, the mechanisms regulating Notch signaling for precise cell fate decisions remain poorly understood. Similar to mammals, the intestinal stem cells in the adult  midgut generate both absorptive and secretory cell progeny, guided by differential levels of Notch activation. Here we performed a forward genetic screen in  and identified glucosylceramide synthase (GlcT), a rate-limiting enzyme for glycosphingolipid (GSL) production, whose mutation causes the development of secretory cell tumors. Genetic analysis of the GSL synthesis pathway, combined with metabolite rescue experiments, revealed that the tumor formation is linked to a deficiency in Mactosylceramide/Lactosylceramide. This deficiency impaired the endocytic recycling of the Delta, subsequently reducing Notch signaling activation. Conditional knockout of , the mammalian ortholog of , in mouse small intestine caused an excessive differentiation of goblet cells, phenotypes similar to these caused by Notch inhibition. Our study suggests an evolutionarily conserved role for a specific GSL metabolite in modulating Notch signaling during stem cell fate decisions and provides a molecular connection between ceramide metabolism and Notch signaling in regulating tissue homeostasis and tumor formation.

> **中文摘要：**
> 细胞间通过 Delta-Notch 信号通路的交流在多种组织和器官中普遍用于调控发育与模式形成；然而，调节 Notch 信号以实现精确细胞命运决定的机制仍不清楚。与哺乳动物相似，成体中肠的肠干细胞在不同程度的 Notch 激活调控下，可以生成吸收性和分泌性细胞后代。在此，我们在模型生物中进行了正向遗传筛选，鉴定出葡萄糖基神经酰胺合酶（GlcT），它是合成糖鞘脂（GSL）的限速酶，其突变会导致分泌细胞肿瘤的形成。通过对 GSL 合成途径的遗传分析以及代谢产物补救实验，我们发现肿瘤形成与 Mac-/乳糖神经酰胺缺乏有关。这种缺乏损害了 Delta 的内吞循环，进而降低了 Notch 信号的激活。在小鼠小肠中有条件敲除哺乳动物同源基因后，观察到杯状细胞过度分化的现象，与 Notch 抑制所致表型相似。本研究表明，特定的 GSL 代谢物在调控干细胞命运决定过程中具有进化上保守的功能，并揭示了神经酰胺代谢与 Notch 信号之间在调控组织稳态和肿瘤形成中的分子联系。

### 第二部分 AI 大师评价

本研究通过遗传筛选揭示了特定糖鞘脂代谢物（Mac-/乳糖神经酰胺）在调控肠道干细胞命运和维持组织稳态中的关键作用。作者发现该代谢物缺乏会削弱 Delta 内吞循环和 Notch 信号，从而导致分泌细胞异常增殖。研究创新地建立了神经酰胺代谢与 Notch 通路之间的分子关联，拓展了我们对代谢调控信号通路的理解。其局限性主要在于模型系统的跨物种差异及其他代谢通路可能的协同作用尚需进一步研究。

---

## 11. MARPLE：一种由近距离触发的CRISPR-Cas13超灵敏抗体检测平台

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41431195)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41431195
**DOI：** 10.1002/advs.202517799

### 第一部分 原文与翻译

**英文原标题：** MARPLE: A Proximity-Triggered CRISPR-Cas13 Platform for Ultrasensitive Antibody Detection.

> **英文摘要：**
> Monitoring clinically relevant antibodies-as biomarkers of disease or therapeutic response-is essential for informed clinical decision-making. Traditional immunoassays like ELISA offer reliable quantification but often involve multistep workflows and limited point-of-care utility. New approaches coupling antibody recognition with signal amplification are therefore highly desirable. The CRISPR-Cas13 system, known for its potent collateral cleavage activity, has emerged as a powerful diagnostic tool for nucleic acid detection. However, its application to protein biomarkers such as antibodies remains underdeveloped. Here, we introduce MARPLE (Modular Antibody Recognition via Proximity-triggered Linker Exchange), a modular CRISPR-Cas13-based platform for ultrasensitive antibody detection. MARPLE harnesses antibody-induced proximity to trigger a strand displacement reaction that releases a sequestered RNA target, activating Cas13-mediated collateral cleavage of fluorescent RNA reporters. This cascade enables detection of antibodies at femtomolar concentrations. We demonstrate MARPLE's versatility across diverse targets-including anti-digoxigenin, anti-cholesterol, anti-HA, trastuzumab, and anti-MUC1-highlighting applications in infectious disease monitoring, cancer diagnostics, and therapeutic drug tracking. The assay is isothermal, one-pot, and retains robust performance in complex matrices such as human serum. These features establish MARPLE as a promising tool for immunodiagnostics, extending CRISPR-based sensing beyond nucleic acids to protein biomarker detection.

> **中文摘要：**
> 监测临床相关抗体——作为疾病或治疗反应的生物标志物——对于做出有信息支撑的临床决策至关重要。传统免疫分析如ELISA可提供可靠的定量结果，但通常涉及多步骤流程且在即时检测中的应用受限。因此，结合抗体识别与信号放大的新方法备受期待。以其强大伴随切割活性而闻名的CRISPR-Cas13系统，已成为核酸检测的有力诊断工具。然而，其在蛋白质生物标志物（如抗体）中的应用仍处于发展初期。本文介绍了MARPLE（基于近距离触发的模块化抗体识别桥接交换机制），这是一种基于CRISPR-Cas13的模块化超灵敏抗体检测平台。MARPLE利用抗体诱导的空间接近性触发链置换反应，从而释放被封存的RNA靶标，继而激活Cas13介导的荧光RNA报告分子的伴随切割反应。该级联反应能够检测到飞摩尔级浓度的抗体。我们展示了MARPLE在多种靶标（包括抗地高辛、抗胆固醇、抗HA、曲妥珠单抗和抗MUC1）中的广泛适用性，突出其在传染病监测、癌症诊断及治疗药物追踪中的潜力。该检测体系具备等温、单管操作特性，并在诸如人血清等复杂基质中仍保持稳定性能。这些特点确立了MARPLE作为一种有前景的免疫诊断工具的地位，将CRISPR技术的检测能力从核酸拓展至蛋白质生物标志物领域。

### 第二部分 AI 大师评价

该研究开发了MARPLE平台，将CRISPR-Cas13系统与近距离触发机制结合，实现了超高灵敏度的抗体检测。其核心创新在于利用抗体介导的空间接近性引发链置换反应，从而释放RNA并激活Cas13的伴随切割，实现飞摩尔级检测灵敏度。相比传统ELISA，该方法具有单管、等温反应和高通量潜力，适用于复杂生物样本。然而，进一步提升通用性与临床标准化验证仍是未来发展方向。

---

## 12. 渗透张力不对称通过PDLIM7极化的微丝协调驱动乳腺癌细胞的趋电迁移

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41431193)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41431193
**DOI：** 10.1002/advs.202515246

### 第一部分 原文与翻译

**英文原标题：** Osmotic Tension Asymmetry Drives Electrotactic Migration via PDLIM7-Polarized Microfilament Coordination in Breast Cancer Cells.

> **英文摘要：**
> Directional migration of tumor cells depends on mechanical forces generated by intracellular asymmetry. This study establishes an electric field-induced directional migration model using fluorescence tension probes to visualize microfilament forces and intracellular osmotic pressure dynamics. Electric fields induce protein kinase A (PKA)-dependent PDLIM7 recruitment, polarizing microfilament tension at cell edges via site-specific phosphorylation at serine 190. Concurrently, the electric field induces asymmetric changes in membrane potential, driven by protein nanoparticles and calcium ions, regulating osmotic tension. Leading-edge depolarization activates TMEM16A channel, while trailing-edge hyperpolarization activates the small conductance calcium-activated potassium (SK) channel. Chloride influx and potassium efflux create differential ion diffusion, resulting in leading-edge hypertonic expansion and trailing-edge contraction, thereby dictating the directionality of electrotactic migration. Osmotic pressure asymmetry further modulates PKA polarity, amplifying directional migration cues. This study elucidates the coordinated interplay between osmotic tension and membrane potential in cellular electromechanics, revealing a mechanistic framework where osmotic tension asymmetry orchestrates tumor cell migration through polarized PDLIM7-microfilament tension regulation.

> **中文摘要：**
> 肿瘤细胞的定向迁移依赖于由细胞内不对称性产生的机械力。本研究建立了一个由电场诱导的定向迁移模型，利用荧光张力探针可视化微丝的力学变化及细胞内渗透压动态。电场诱导蛋白激酶A（PKA）依赖性的PDLIM7募集，通过在丝氨酸190位点的特异性磷酸化，使细胞边缘的微丝张力极化。同时，电场引起膜电位的不对称变化，该过程由蛋白纳米颗粒和钙离子驱动，从而调节渗透张力。前缘去极化激活TMEM16A通道，而后缘过极化则激活小电导钙激活钾通道（SK通道）。氯离子内流和钾离子外流造成离子扩散差异，导致前缘高渗膨胀、后缘收缩，从而决定趋电迁移的方向。渗透压不对称性进一步调控PKA极性，放大定向迁移信号。本研究阐明了细胞电机械过程中渗透张力与膜电位的协调作用，揭示了一个渗透张力不对称通过极化的PDLIM7-微丝张力调控来主导肿瘤细胞迁移的机制框架。

### 第二部分 AI 大师评价

该研究通过构建电场诱导的乳腺癌细胞定向迁移模型，揭示了细胞渗透张力与膜电位在电机械耦合中的协同作用。研究采用荧光张力探针动态监测微丝张力与渗透压变化，发现PDLIM7在PKA依赖性磷酸化调控下实现微丝极化，并由离子通道驱动形成渗透压差，从而决定细胞迁移方向。该机制阐明了渗透力学与电信号间的耦合新模式，为电场诱导肿瘤细胞运动提供了理论依据。研究创新性强，但仍需在体模型中进一步验证其生理相关性。

---

## 13. 电化学发光驱动的体内光动力治疗

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41431192)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41431192
**DOI：** 10.1002/advs.202512027

### 第一部分 原文与翻译

**英文原标题：** Electrochemiluminescence Drives Photodynamic Therapy In Vivo.

> **英文摘要：**
> Electrochemiluminescence (ECL) holds significant promise in the biomedical field, but remains a challenge for in vivo photodynamic therapy (PDT). Herein, a wearable light source of ECL to drive PDT (ECL-PDT) is developed, in which a flexible ECL device (ECLD) is fabricated using an ECL gel containing Ru(bpy)Cl as the light-emitting layer positioned between two transparent indium tin oxide-coated substrates. By applying alternating current voltage, Ru(bpy)  and Ru(bpy)  are alternately generated within the ECLDs, and then collide to produce excited species, followed by high-efficiency and stable ECL emission. The ECLDs can further activate photosensitizers to produce reactive oxygen species through a resonance energy transfer process, ultimately leading to oxidative damage of cancer cells. As a result, such ECLDs demonstrate excellent antitumor efficacy on cells, and tumor growth is distinctly inhibited in a tumor-bearing mouse model. This work not only provides a convenient and effective ECL-PDT strategy for cancer treatment, but also expands the application of ECLD as a wearable photonic healthcare device.

> **中文摘要：**
> 电化学发光（ECL）在生物医学领域具有巨大潜力，但在体内光动力治疗（PDT）中仍面临挑战。本文开发了一种可穿戴的ECL光源用于驱动PDT（ECL-PDT），其中采用含有Ru(bpy)Cl的ECL凝胶作为发光层，将其置于两片透明氧化铟锡（ITO）电极基底之间，制备出柔性的ECL器件（ECLD）。通过施加交流电压，在ECLD中交替生成Ru(bpy)和Ru(bpy)离子，它们相互碰撞生成激发态物种，继而产生高效且稳定的ECL发射。ECLD还可通过共振能量转移过程激活光敏剂，生成活性氧物种，从而最终导致癌细胞的氧化性损伤。结果表明，该ECLD在细胞水平表现出优异的抗肿瘤效果，并在荷瘤小鼠模型中显著抑制肿瘤生长。本研究不仅为癌症治疗提供了一种简便且有效的ECL-PDT策略，还拓展了ECLD作为可穿戴光子健康设备的应用前景。

### 第二部分 AI 大师评价

该研究旨在解决电化学发光用于体内光动力治疗的技术瓶颈，提出了一种基于柔性ECL器件的可穿戴ECL-PDT系统。作者利用Ru(bpy)基发光层实现交变电驱动的稳定ECL发射，并通过能量共振转移激活光敏剂以杀伤癌细胞。在细胞及动物模型中，该系统展示出显著的抗肿瘤效果。研究的创新性在于将ECL技术与可穿戴光疗结合，为非侵入性肿瘤治疗提供了新方向，但后续仍需评估其在复杂体内环境下的长期稳定性与安全性。

---

## 14. 成纤维/脂肪生成前体细胞中RUNX2的激活促进肌营养不良中的肌肉纤维化

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41431178)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41431178
**DOI：** 10.1002/advs.202510850

### 第一部分 原文与翻译

**英文原标题：** RUNX2 Activation in Fibro/Adipogenic Progenitors Promotes Muscle Fibrosis in Muscular Dystrophy.

> **英文摘要：**
> Clinical evidence indicates concurrent muscle inflammation and fibrosis in muscular dystrophies (MDs); however, the molecular mechanisms underlying inflammation-mediated fibrosis in skeletal muscle remain inadequately understood. This study revealed a molecular link between macrophages and fibro-adipogenic progenitors (FAPs) in both human subjects and mice via the transforming growth factor-beta (TGF-β)-RUNX family transcription factor-2 (RUNX2) axis. RUNX2 mRNA levels correlated positively with both the expression of fibrotic genes and the fibrosis area of MD patients. We demonstrated that specific ablation of RUNX2 in FAPs alleviated muscle fibrosis in an animal model of MD. Mechanistically, injured myofibers activated the transcription of chemokine genes, enhancing macrophage recruitment and the release of TGF-β, which subsequently triggered RUNX2-mediated transcription of fibrogenic genes in FAPs, promoting muscle fibrosis. Additionally, we demonstrated that CADD522, a RUNX2 inhibitor, protects against muscle fibrosis in both dystrophic and denervated mice. Importantly, the anti-inflammatory drug prednisolone alleviated muscle fibrosis in MD patients by inhibiting inflammatory cytokine-mediated RUNX2 activation. Collectively, our findings indicated that the TGF-β-RUNX2 axis is a viable target for alleviating muscle fibrosis and related diseases, highlighting potential future research directions.

> **中文摘要：**
> 临床证据表明，在肌营养不良（MD）中，肌肉炎症与纤维化常同时存在；然而，炎症介导的骨骼肌纤维化的分子机制仍然了解不足。本研究揭示了在人类和小鼠中，巨噬细胞与成纤维-脂肪生成前体细胞（FAPs）之间通过转化生长因子β（TGF-β）-RUNX家族转录因子2（RUNX2）轴存在分子联系。RUNX2 mRNA水平与MD患者的纤维化相关基因表达及纤维化面积呈正相关。我们证明，在FAPs中特异性敲除RUNX2可缓解MD动物模型中的肌肉纤维化。从机制上看，受损的肌纤维可激活趋化因子基因的转录，增强巨噬细胞的募集及TGF-β的释放，进而触发FAPs中由RUNX2介导的成纤维基因转录，促进肌肉纤维化。此外，我们发现RUNX2抑制剂CADD522可防止营养不良及去神经化小鼠的肌肉纤维化。更重要的是，抗炎药泼尼松可通过抑制炎性细胞因子介导的RUNX2激活，缓解MD患者的肌肉纤维化。综上所述，我们的研究结果表明，TGF-β-RUNX2轴是缓解肌肉纤维化及相关疾病的可行治疗靶点，并为未来研究方向提供了新的启示。

### 第二部分 AI 大师评价

该研究旨在阐明肌营养不良中肌肉炎症与纤维化之间的分子联系，重点探讨TGF-β-RUNX2信号轴在成纤维/脂肪生成前体细胞中的作用。通过人源与小鼠模型相结合，作者揭示RUNX2是促进肌肉纤维化的关键转录因子，其敲除显著减轻纤维化。研究还发现RUNX2抑制剂CADD522及抗炎药泼尼松可阻断该信号轴，具有潜在治疗价值。该研究创新性地揭示了免疫与成纤维细胞群互作的关键分子机制，但其临床转化仍需进一步验证。

---

## 15. IL4I1⁺ 巨噬细胞与 TDO2⁺ 肌成纤维母细胞在实体型优势的肺腺癌中通过 AhR 介导的免疫抑制与铁死亡耐受机制发挥作用。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41431173)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41431173
**DOI：** 10.1002/advs.202513606

### 第一部分 原文与翻译

**英文原标题：** IL4I1⁺ Macrophages and TDO2⁺ Myofibroblasts Drive AhR-Mediated Immunosuppression and Ferroptosis Resistance in Solid Predominant Lung Adenocarcinoma.

> **英文摘要：**
> Lung adenocarcinoma (LUAD) displays marked intratumoral heterogeneity with distinct histological patterns. The solid pattern representing poorly differentiated LUAD is linked to poor prognosis and therapeutic resistance. To uncover underlying mechanisms, we integrate bulk and single-cell RNA sequencing and identify a preferential enrichment of interleukin 4 induced 1 (IL4I1)-expressing tumor-associated macrophages (TAMs) and tryptophan 2,3-dioxygenase (TDO2)-expressing myofibroblastic cancer-associated fibroblasts (myCAFs) in a solid pattern of LUAD. Spatial transcriptomics reveals their co-localization in peritumoral stroma, forming an immune-excluded niche. Mechanistically, TDO2⁺ myCAFs promoted monocyte-to-IL4I1⁺ TAM differentiation via the kynurenine-aryl hydrocarbon receptor (AhR) axis. Tryptophan metabolomic landscapes confirm that IL4I1⁺ TAMs and TDO2⁺ myCAFs enhance tryptophan degradation and accumulation of AhR ligands (e.g., kynurenine, indole-3-carboxaldehyde), contributing to CD8⁺ T cell exhaustion and anti-PD-1 therapeutic resistance. IL4I1⁺ TAMs and TDO2⁺ myCAFs conformably mediate ferroptosis resistance through the AhR-NRF2-GPX4-SLC7A11 pathway. Notably, AhR antagonist CH-223191 restores ferroptosis sensitivity of tumor cells. A triple therapy combining CH-223191, ferroptosis inducer (Imidazole ketone erastin or RSL3), and anti-PD-1 agent demonstrates superior efficacy and safety in vivo. Together, our findings demonstrate that IL4I1⁺ TAMs and TDO2⁺ myCAFs synergistically establish an immunosuppressive, ferroptosis-resistant niche via AhR signaling in solid predominant LUAD and offer promising therapeutic strategies to reprogram the tumor microenvironment.

> **中文摘要：**
> 肺腺癌（LUAD）表现出显著的肿瘤内异质性，具有不同的组织学模式。代表低分化 LUAD 的实体型与预后不良和治疗抵抗相关。为揭示潜在机制，我们整合了整体和单细胞 RNA 测序，发现实体型 LUAD 中富集了表达白细胞介素4诱导酶1（IL4I1）的肿瘤相关巨噬细胞（TAMs）及表达色氨酸2,3-双加氧酶（TDO2）的肌成纤维样癌相关成纤维母细胞（myCAFs）。空间转录组学显示它们在肿瘤周围基质中共定位，形成免疫排斥性生态位。在机制上，TDO2⁺ myCAFs 通过犬尿氨酸–芳香烃受体（AhR）通路促进单核细胞向 IL4I1⁺ TAM 的分化。色氨酸代谢组图谱证实，IL4I1⁺ TAMs 与 TDO2⁺ myCAFs 增强了色氨酸降解和 AhR 配体（如犬尿氨酸、吲哚-3-甲醛）的积累，导致 CD8⁺ T 细胞功能衰竭和抗 PD-1 治疗耐受。IL4I1⁺ TAMs 与 TDO2⁺ myCAFs 还通过 AhR–NRF2–GPX4–SLC7A11 通路介导铁死亡耐受。值得注意的是，AhR 拮抗剂 CH-223191 能恢复肿瘤细胞对铁死亡的敏感性。将 CH-223191 与铁死亡诱导剂（咪唑酮 Erastin 或 RSL3）及抗 PD-1 药物联合的三联治疗在体内表现出更优的疗效与安全性。综合来看，我们的研究表明 IL4I1⁺ TAMs 和 TDO2⁺ myCAFs 在实体型优势 LUAD 中通过 AhR 信号通路协同建立免疫抑制和铁死亡耐受生态位，并提供了重塑肿瘤微环境的潜在治疗策略。

### 第二部分 AI 大师评价

该研究围绕实体型优势肺腺癌的免疫抑制与铁死亡耐受机制展开，利用整合组学和空间转录组学揭示 IL4I1⁺ 巨噬细胞和 TDO2⁺ 肌成纤维母细胞的代谢串联及其通过 AhR 通路介导的免疫排斥作用。机制实验证实它们在色氨酸代谢和 AhR 激活中形成正反馈，促使 CD8⁺ T 细胞衰竭并增强铁死亡抵抗。进一步通过药理干预验证了 AhR 拮抗剂与铁死亡诱导剂及免疫治疗的协同效果。研究创新性地提出了针对肿瘤免疫代谢共生体的新型组合疗法，为精准治疗提供了重要思路，但仍需临床验证其安全性与有效性。

---

## 16. 在光声成像引导下用于强化聚焦超声治疗的刚性空心微粒。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41431153)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41431153
**DOI：** 10.1002/advs.202512337

### 第一部分 原文与翻译

**英文原标题：** Rigid Hollow Microparticles for Enhanced Focused Ultrasound Treatment Under Optoacoustic Guidance.

> **英文摘要：**
> The efficacy and safety of focused ultrasound (FUS) treatments can be significantly enhanced with microbubbles, but the common ultrasound contrast agents suffer from limited stability, short circulation times, and risks associated with inertial cavitation and jetting. Here, we demonstrate that rigid hollow microparticles enable controlled, targeted thermal treatments of deep tissues via FUS. These acoustically responsive agents exhibit properties comparable to microbubbles yet possess superior mechanical stability, prolonged circulation, and enhanced responsiveness. Characterized by a negative acoustic contrast factor, the hollow microparticles amplify FUS-induced effects-particularly localized hyperthermia-enabling precise, robust, and controllable thermal therapy. Tissue ablation experiments under optoacoustic imaging guidance demonstrate strong responsiveness to FUS, with histological analyses confirming a threefold increase in ablation volume compared with microparticle-free controls. Experimental and numerical results indicate that this enhanced efficacy arises from first-order acoustic effects and secondary mechanisms, including acoustic scattering and stable particle-to-particle interactions. Unlike microbubbles, hollow microparticles rely on non-cavitational heating, enabling predictable, dose-dependent thermal responses that improve safety and efficacy. The frequency-dependent response further highlights their multifunctional potential under varying acoustic conditions. These findings establish rigid hollow microparticles as stable, versatile acoustic agents that significantly advance the therapeutic scope and clinical utility of FUS therapies.

> **中文摘要：**
> 聚焦超声（FUS）治疗的疗效与安全性可通过微泡显著增强，但常用的超声造影剂存在稳定性有限、循环时间短，以及与惯性空化和喷射相关的风险。本文表明，刚性空心微粒能够通过FUS实现对深部组织的可控、靶向热治疗。这些声学响应性试剂具有与微泡相当的特性，但具备更高的机械稳定性、更长的循环时间以及更强的响应能力。由于其具有负声学对比因子，这些空心微粒可放大FUS诱导效应——尤其是局部热疗效应——从而实现精确、稳健且可控的热治疗。在光声成像引导下的组织消融实验表明，微粒对FUS具有强烈响应，组织学分析确认，相较于无微粒对照组，消融体积增加了三倍。实验与数值结果表明，这种增强疗效来源于一阶声学效应和次级机制，包括声散射及稳定的粒子间相互作用。与微泡不同，空心微粒依赖于非空化加热，从而实现可预测的、剂量依赖的热响应，改善了治疗的安全性与有效性。其频率依赖性响应进一步突显了在不同声学条件下的多功能潜力。这些研究结果确立了刚性空心微粒作为稳定、多用途声学试剂的重要地位，显著拓展了FUS治疗的应用范围与临床价值。

### 第二部分 AI 大师评价

本研究旨在开发一种刚性空心微粒，以克服传统微泡在聚焦超声治疗中稳定性和安全性方面的不足。通过光声成像引导与实验和数值模拟，研究团队验证了该类微粒可实现深部组织的精确热疗，并显著提升组织消融效率。其基于非空化机制的控温特性展现出剂量依赖性与较高安全性。该工作在FUS治疗媒介的设计上具有创新性，但未来仍需评估其在体长期代谢与临床可转化性。

---

## 17. 肝细胞 Mettl3 缺失通过胆管上皮细胞-巨噬细胞相互作用促进原发性硬化性胆管炎和肝纤维化的发生。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41431138)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41431138
**DOI：** 10.1002/advs.202512799

### 第一部分 原文与翻译

**英文原标题：** Hepatocyte Mettl3 Deficiency Drives Primary Sclerosing Cholangitis and Liver Fibrosis via Cholangiocyte-Macrophage Crosstalk.

> **英文摘要：**
> Effective therapies for primary sclerosing cholangitis (PSC), a progressive cholestatic liver disease characterized by biliary inflammation and fibrotic damage, remain limited due to an incomplete elucidation of its underlying molecular mechanisms. Although N6-methyladenosine (m6A) RNA methylation has been implicated in hepatic pathophysiology, its role in PSC remains undefined. Here, we demonstrate that hepatocyte-specific deletion of Mettl3, a critical m6A methyltransferase, induces spontaneous PSC-like pathology characterized by ductular reaction and peribiliary fibrosis. Therapeutic restoration of Mettl3 through genetic knock-in or AAV8-mediated hepatocyte-specific overexpression significantly attenuated 3,5-diethoxycarbonyl-1,4-dihydrocollidine (DDC)-induced PSC progression. Integrated single-cell and bulk transcriptomic profiles revealed an expansion of Trem2 macrophages that interact with Spp1 cholangiocytes via the Cd44-Spp1 axis. Genetic ablation of Trem2 or cholangiocyte-specific deletion of Spp1 significantly suppressed DDC-induced biliary injury. Mechanistically, Mettl3-deficient hepatocytes secreted higher levels of macrophage-recruiting cytokines (such as Mif and Csf1), facilitating the recruitment of Trem2 macrophage, which subsequently activated cholangiocytes through Cd44-Spp1 signaling, exacerbated biliary inflammation and fibrosis. Notably, pharmacological activation of Mettl3 in adult hepatocytes substantially mitigated PSC progression and liver fibrosis. Collectively, our findings establish hepatocyte Mettl3 deficiency as a pivotal driver of PSC pathogenesis and highlight the therapeutic potential of targeting the m6A epitranscriptome in cholestatic liver diseases.

> **中文摘要：**
> 针对原发性硬化性胆管炎（PSC）这一以胆道炎症和纤维化损伤为特征的进行性胆汁淤积性肝病，目前有效的治疗手段仍然有限，主要原因在于其潜在分子机制尚未完全阐明。虽然 N6-甲基腺苷（m6A）RNA 甲基化已被证明与肝脏病理生理密切相关，但其在 PSC 中的作用仍不明确。本研究显示，特异性敲除肝细胞中关键的 m6A 甲基转移酶 Mettl3，会诱导自发性 PSC 样病理变化，其特征包括胆管反应和胆管周围纤维化。通过基因敲入或 AAV8 介导的肝细胞特异性过表达恢复 Mettl3，可显著减轻由 3,5-二乙氧羰基-1,4-二氢可啶（DDC）诱导的 PSC 进展。综合单细胞和整体转录组分析揭示，Trem2 巨噬细胞群体扩增，并通过 Cd44-Spp1 轴与 Spp1 胆管上皮细胞相互作用。Trem2 基因敲除或胆管上皮细胞特异性缺失 Spp1 均能显著抑制 DDC 诱导的胆道损伤。在分子机制上，Mettl3 缺失的肝细胞分泌更多的巨噬细胞募集相关细胞因子（如 Mif 和 Csf1），促进 Trem2 巨噬细胞的招募，而后者通过 Cd44-Spp1 信号活化胆管上皮细胞，从而加剧胆道炎症和纤维化。值得注意的是，药理性激活成年肝细胞中的 Mettl3 可明显缓解 PSC 进展及肝纤维化。综上所述，本研究确定肝细胞 Mettl3 缺失是 PSC 发病机制的重要驱动因素，并提示靶向 m6A 表观转录组学是治疗胆汁淤积性肝病的潜在新策略。

### 第二部分 AI 大师评价

本研究系统揭示了肝细胞 Mettl3 缺失在原发性硬化性胆管炎发病中的致病作用，并通过多组学整合分析明确了胆管上皮细胞与 Trem2 巨噬细胞之间的关键通信轴。其利用遗传和病毒介导的功能恢复实验，验证了 Mettl3 的保护性作用，且药理性激活实验进一步强调其治疗潜力。研究的最大创新在于将 m6A 表观转录调控与胆汁淤积性疾病联系起来。然而，该研究主要基于动物模型，临床可转化性仍需进一步验证。

---

## 18. 基于电化学纳米传感器的单细胞半胱氨酸定量用于预测肿瘤二硫失活敏感性

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41431121)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41431121
**DOI：** 10.1002/advs.202523478

### 第一部分 原文与翻译

**英文原标题：** Quantification of Single-Cell Cysteine Using an Electrochemical Nanosensor for Predicting Tumor Disulfidptosis Susceptibility.

> **英文摘要：**
> Disulfidptosis, a newly identified form of programmed cell death, has emerged as a promising therapeutic target for tumors. However, the current research in this field is hindered by the absence of precise and quantifiable biomarkers to accurately predict and monitor its occurrence and progression. Research has demonstrated a strong correlation between disulfidptosis and cysteine metabolism. To elucidate the relationship, this study pioneers the development of a novel carbon fiber nanoelectrode (CFNE) enhanced with platinum nanoparticles and poly(p-coumaric acid) (PPCA) for precise cysteine detection in living single-cells, thereby overcoming cellular heterogeneity. The nanosensor reveals that the increased original intracellular cysteine production levels, particularly those exceeding 400 amol s, serve as a reliable predictor of high susceptibility to disulfidptosis. The relationship between the cell signaling pathway of cysteine metabolism with disulfidptosis is demonstrated by the nanosensor, which is further substantiated through a comprehensive analysis of diverse tumor cell lines and primary tumor cells in a mouse model. This study proposes a new indicator of disulfidptosis, and the developed nanosensor is poised to become an indispensable tool for both disulfidptosis research and the evaluation of tumor therapeutic strategies.

> **中文摘要：**
> 二硫失活是一种新近确定的程序性细胞死亡形式，已成为肿瘤治疗中具有前景的靶点。然而，目前该领域的研究受到缺乏精确且可量化的生物标志物的限制，难以准确预测和监测其发生与进展。研究显示，二硫失活与半胱氨酸代谢存在密切相关性。为阐明这一关系，本研究率先开发了一种新型的碳纤维纳米电极（CFNE），并通过铂纳米颗粒和对香豆酸聚合物（PPCA）增强，用于活体单细胞中精确检测半胱氨酸，从而克服细胞异质性问题。该纳米传感器揭示，细胞内原始半胱氨酸生成水平的升高，尤其是超过400 amol/s的水平，可作为高二硫失活敏感性的可靠预测指标。纳米传感器进一步阐明了半胱氨酸代谢的信号通路与二硫失活之间的关系，并在多种肿瘤细胞系及小鼠原代肿瘤细胞中得到验证。该研究提出了一种新的二硫失活指标，所开发的纳米传感器有望成为二硫失活研究及肿瘤治疗策略评估中不可或缺的工具。

### 第二部分 AI 大师评价

该研究聚焦于二硫失活这一新型细胞死亡途径，旨在解决缺乏可靠预测指标的难题。研究团队创新性地构建了铂纳米颗粒与对香豆酸聚合物增强的碳纤维纳米电极，实现单细胞水平的半胱氨酸高灵敏检测。结果表明，半胱氨酸生成速率超过400 amol/s可预测细胞的高二硫失活敏感性。该方法突破了细胞异质性限制，揭示了半胱氨酸代谢信号与二硫失活的内在联系，为精准肿瘤治疗提供了新工具。尽管应用前景广阔，但其在临床样本中的稳定性和通用性仍需进一步验证。

---

## 19. 用于精确靶向蛋白降解的生物正交声动力即插即用靶向嵌合体（SDPTAC）

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41431111)
**期刊：** Advanced science (Weinheim, Baden-Wurttemberg, Germany)
**PMID：** 41431111
**DOI：** 10.1002/advs.202520975

### 第一部分 原文与翻译

**英文原标题：** Bioorthogonal Sonodynamic Plug-and-Play Targeting Chimeras (SDPTAC) for Precise Targeted Protein Degradation.

> **英文摘要：**
> Targeted protein degradation (TPD) offers powerful therapeutic opportunities but is limited by poor tissue penetration and E3 ligase dependence. Herein, we develop Sonodynamic Plug-and-Play Targeting Chimeras (SDPTAC), an ultrasound (US)-activated, bioorthogonal strategy for in situ protein degradation. SDPTAC assembles via an inverse electron-demand Diels-Alder (IEDDA) click reaction between a sonosensitizer and tetrazine-tagged ligands, generating reactive oxygen species (ROS) upon US to degrade bound proteins. This modular platform enabled efficient degradation of nuclear (bromodomain-containing protein 4, BRD4), cytosolic (nicotinamide phosphoribosyl transferase, NAMPT), and membrane (discoidin domain receptor 1, DDR1) targets, suppressed oncogenic signaling, and achieved nearly complete tumor growth inhibition in vivo with negligible toxicity. SDPTAC thus establishes a versatile, deep-penetrating, and clinically translatable approach for noninvasive protein modulation.

> **中文摘要：**
> 靶向蛋白降解（TPD）提供了强大的治疗潜力，但受限于组织穿透能力差及对E3连接酶的依赖。在本研究中，我们开发了一种超声（US）激活的生物正交策略——声动力即插即用靶向嵌合体（SDPTAC），用于原位蛋白降解。SDPTAC通过声敏剂与四嗪标记配体之间的逆电子需求Diels-Alder（IEDDA）点击反应自组装而成，在超声作用下产生活性氧（ROS）以降解结合的蛋白质。该模块化平台实现了对核内（含溴结构域蛋白4，BRD4）、胞质（烟酰胺磷酸核糖转移酶，NAMPT）及膜上（盘状结构域受体1，DDR1）靶点的高效降解，抑制了致癌信号通路，并在体内实现了几乎完全的肿瘤生长抑制且毒性极低。因此，SDPTAC建立了一种多功能、深度穿透且具有临床转化潜力的非侵入性蛋白调控新策略。

### 第二部分 AI 大师评价

该研究提出了创新性的声动力即插即用靶向嵌合体（SDPTAC）体系，通过生物正交化学与超声激活相结合，突破了传统靶向蛋白降解依赖E3连接酶及组织穿透受限的难题。其模块化设计实现了广谱的蛋白靶向降解，包括核内、胞质及膜上蛋白，展现出优越的抗肿瘤效果和低毒性。此方法在深部组织靶向降解与非侵入性治疗领域具有显著创新性，同时未来需评估其在复杂生理环境中的稳定性与特异性。

---

## 20. METTL3–YTHDC1 轴通过调控结构性 RNA 的 m6A 修饰来影响 MLLr⁺ 急性髓系白血病基因组中染色质 TADs 的完整性。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41430607)
**期刊：** Molecular cancer
**PMID：** 41430607
**DOI：** 10.1186/s12943-025-02545-x

### 第一部分 原文与翻译

**英文原标题：** The METTL3-YTHDC1 axis mediates architectural RNA mA modification to modulate the integrity of chromatin TADs in MLLr + AML genome.

> **英文摘要：**
> No abstract available.

> **中文摘要：**
> 无可用摘要。

### 第二部分 AI 大师评价

该研究揭示了 METTL3–YTHDC1 轴在 MLLr⁺ 急性髓系白血病（AML）中通过结构性 RNA 的甲基化修饰影响染色质拓扑相关结构域（TADs）完整性的分子机制。尽管目前尚无摘要细节，但从题目可推测该工作结合表观转录组学与染色质构象组学的方法，揭示 RNA 修饰与染色质空间组织之间的关联。这一研究可能为理解 AML 的表观调控机制及靶向 RNA 修饰通路的治疗策略提供新思路。

---

## 21. 白血病驱动的Ⅲ型固有淋巴细胞扩增促进急性髓系白血病的促肿瘤性微环境形成

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41430399)
**期刊：** Leukemia
**PMID：** 41430399
**DOI：** 10.1038/s41375-025-02829-7

### 第一部分 原文与翻译

**英文原标题：** Leukemia-driven expansion of type 3 innate lymphoid cell facilitates a pro-tumoral microenvironment in acute myeloid leukemia.

> **英文摘要：**
> Acute myeloid leukemia (AML) is an aggressive hematologic malignancy with poor overall survival. Understanding how dysregulated immunity contributes to the development and progression of AML is an active area of investigation. Prior work has demonstrated functional defects in natural killer (NK) cells; however, the role of non-NK innate lymphoid cells (ILCs) in AML is incompletely understood. Conventional ILC3s are non-cytotoxic and regulate mucosal immunity through cytokine secretion. In this study, we discovered an expansion of ILC3s in both a murine model of AML and in AML patients. The transcription factor, aryl hydrocarbon receptor (AHR) is required for ILC3 development and function, and AML blasts have been shown to secrete AHR ligands. Modeling studies demonstrated ILC3 expansion was mediated by AHR activation in ILC precursors. ILC3s developed in leukemic settings had increased cytokine production, and co-culture of ILC3s significantly increased AML colony formation, which was mediated by ILC3-derived TNFα and GM-CSF. Furthermore, co-transfer of ILC3s with AML led to more rapid disease progression in vivo and human ILC3 frequency was associated with adverse risk stratification in AML patients. These data support a model in which AML promotes ILC3 expansion and function via an AHR-dependent mechanism to aid AML growth and survival.

> **中文摘要：**
> 急性髓系白血病（AML）是一种侵袭性血液恶性肿瘤，其总体生存率较低。理解免疫失调如何促进AML的发生与进展是当前研究的活跃领域。既往研究已证实自然杀伤（NK）细胞存在功能缺陷，然而非NK型固有淋巴细胞（ILCs）在AML中的作用尚不完全清楚。传统的Ⅲ型ILC（ILC3）为非细胞毒性细胞，通过分泌细胞因子调节黏膜免疫。在本研究中，我们发现无论在AML小鼠模型还是在AML患者中，ILC3均出现扩增。转录因子芳香烃受体（AHR）对于ILC3的发育和功能是必需的，而AML原始细胞被证实可分泌AHR配体。模型研究表明，ILC3的扩增由ILC前体中AHR的激活介导。在白血病环境中发育的ILC3具有增强的细胞因子产生能力，且与ILC3共培养可显著增加AML的集落形成，这一作用由ILC3来源的TNFα和GM-CSF介导。此外，将ILC3与AML共同移植可加速体内疾病进展，而在人类AML患者中，ILC3频率与不良风险分层相关。这些数据支持这样一种模型：AML通过AHR依赖性机制促进ILC3的扩增与功能，从而有助于AML的生长与存活。

### 第二部分 AI 大师评价

该研究旨在探讨非NK型固有淋巴细胞，特别是Ⅲ型ILC（ILC3）在急性髓系白血病中的作用机制。研究通过小鼠模型及患者样本发现ILC3显著扩增，并揭示了AHR信号通路在其中的关键调控作用。功能实验显示，ILC3通过分泌TNFα和GM-CSF促进AML细胞生长与集落形成，进而加速疾病进展。该发现为AML免疫微环境研究提供了新的视角，揭示了白血病细胞与先天免疫系统间的促瘤互作机制。局限性在于其仍需进一步验证AHR依赖通路在临床样本中的普适性和可干预性。

---

## 22. 结构化全身MRI揭示复发/难治性多发性骨髓瘤的临床相关疾病模式变化

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41430398)
**期刊：** Leukemia
**PMID：** 41430398
**DOI：** 10.1038/s41375-025-02834-w

### 第一部分 原文与翻译

**英文原标题：** Structured whole-body MRI highlights clinically relevant disease pattern changes in relapsed/refractory multiple myeloma.

> **英文摘要：**
> Whole-body imaging plays a critical role in assessing multiple myeloma (MM). The structured scoring systems MY-RADS and KIM score have primarily been developed for newly diagnosed patients (NDMM). However, their application and prognostic significance in relapsed/refractory multiple myeloma (RRMM) remains uncertain. To clarify this, we evaluated whole body magnetic resonance imaging (MRI) data from 46 RRMM patients and compared findings to 68 NDMM patients from the GMMG-HD7 trial using both scoring systems. Despite similar overall disease burden, RRMM patients showed significant differences, characterized by increased paramedullary and extramedullary disease and reduced diffuse marrow infiltration compared to NDMM. Both MY-RADS and KIM scores independently correlated with progression-free and overall survival in RRMM. These results highlight distinct biological patterns in RRMM, emphasizing a shift towards bone marrow-independent growth. Our findings suggest that in RRMM, iliac crest biopsies may underestimate disease burden, underlining the importance of imaging complementing bone marrow diagnostics.

> **中文摘要：**
> 全身影像学在评估多发性骨髓瘤（MM）中发挥着关键作用。结构化评分系统MY-RADS和KIM评分主要是为新诊断的患者（NDMM）开发的。然而，它们在复发/难治性多发性骨髓瘤（RRMM）中的应用及其预后意义仍不确定。为澄清这一点，我们评估了46例RRMM患者的全身磁共振成像（MRI）数据，并使用这两种评分系统将结果与GMMG-HD7试验中68例NDMM患者进行比较。尽管总体疾病负担相似，与NDMM相比，RRMM患者表现出显著差异，其特征为副髓和髓外疾病增加，而弥漫性骨髓浸润减少。MY-RADS和KIM评分在RRMM中均与无进展生存期和总体生存期独立相关。这些结果突出了RRMM中不同的生物学模式，强调了其向骨髓非依赖性生长的转变。我们的研究结果提示，在RRMM中，髂嵴活检可能低估疾病负担，强调了影像检查在骨髓诊断中的重要补充作用。

### 第二部分 AI 大师评价

本研究通过比较复发/难治性多发性骨髓瘤与新诊断患者的全身MRI表现，验证了结构化评估系统MY-RADS及KIM评分在RRMM中的应用价值。研究发现RRMM患者表现出更多的副髓和髓外病变，提示疾病生物学特征的改变及向骨髓非依赖性生长的转变。两种评分均与重要生存结局相关，具有独立的预后价值。该研究创新地强调了影像学在RRMM评估中的补充作用，但样本量相对有限，仍需进一步多中心验证。

---

## 23. 选择性编辑扩增癌基因的基因组可诱导免疫原性细胞死亡与肿瘤重塑

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41430241)
**期刊：** Molecular cancer
**PMID：** 41430241
**DOI：** 10.1186/s12943-025-02542-0

### 第一部分 原文与翻译

**英文原标题：** Selective genome editing of amplified oncogenes triggers immunogenic cell death and tumor remodeling.

> **英文摘要：**
> Oncogene amplifications fuel some of the most lethal, therapy‑refractory cancers, yet remain clinically untargeted. We report a single‑guide CRISPR/Cas9 strategy that converts the sheer copy‑number excess of oncogene amplicons into an Achilles' heel. A solitary intronic double‑strand break is innocuous in diploid genomes but collapses oncogene amplification‑positive cells across neuroblastoma, small‑cell lung and colorectal carcinoma models, driving > 90% loss of viability, G₂/M blockade and catastrophic DNA‑damage signalling. Amplified‑locus cleavage rewires transcription toward cell death activation, necroptosis and cGAS-STING-mediated immunogenic cell death, enabling dendritic‑cell cross‑priming and T‑cell activation and proliferation. In xenografts, delivery of the intronic sgRNA shrinks tumours by 90%, prolongs survival and remodels the innate tumour microenvironment. Deep sequencing confirms negligible off‑target editing, and combination with doxorubicin achieves supra‑additive killing. These findings establish amplification density, not sequence content, as a tractable, tumour‑exclusive target and unveil a dual‑action platform that is simultaneously cytotoxic and immunostimulatory. Editing of tumor amplifications therefore offers a blueprint for translating copy‑number aberrations into precision genome‑editing therapies for treatment‑resistant cancers.

> **中文摘要：**
> 癌基因扩增推动了一些最致命且对治疗具耐受性的癌症，但目前仍缺乏临床上的直接靶向策略。我们报告了一种单导RNA CRISPR/Cas9策略，可将癌基因扩增拷贝数的巨大过剩转化为致命弱点。在二倍体基因组中，一个孤立的内含子双链断裂是无害的，但在神经母细胞瘤、小细胞肺癌和结直肠癌模型中会导致癌基因扩增阳性细胞崩溃，引起超过90%的细胞活力丧失、G₂/M期阻滞以及灾难性的DNA损伤信号。扩增位点的切割会重编程转录，倾向于激活细胞死亡、程序性坏死以及经由cGAS-STING通路介导的免疫原性细胞死亡，从而促进树突状细胞的交叉启动以及T细胞的激活与增殖。在异种移植模型中，递送该内含子sgRNA可使肿瘤体积缩小90%，延长生存时间，并重塑先天性肿瘤微环境。深度测序结果证实脱靶编辑极其微弱，并且与阿霉素联合使用时产生超加成的杀伤效应。这些发现确立了“扩增密度”而非“序列内容”作为可操控且肿瘤特异的治疗靶点，并揭示出一种同时具备细胞毒性与免疫刺激作用的双重功能平台。因此，对肿瘤扩增区域的编辑为将拷贝数异常转化为治疗耐药癌症的精确基因编辑疗法提供了蓝图。

### 第二部分 AI 大师评价

本研究旨在突破癌基因扩增型肿瘤长期缺乏靶向治疗的困境，提出以单导CRISPR/Cas9切割内含子扩增区域的新策略。研究发现，该策略可特异性诱导扩增癌基因细胞死亡并激活免疫反应，在动物模型中有效缩小肿瘤和延长生存。其创新性在于首次将“拷贝数密度”概念转化为可操作的治疗靶点，实现同时具细胞毒与免疫激活的双重效应。但其临床可行性与安全性仍需在更复杂体系中验证。

---

## 24. 更正：环状RNA ACVR2A通过 miR-626/EYA4 轴抑制膀胱癌细胞的增殖和转移。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41430233)
**期刊：** Molecular cancer
**PMID：** 41430233
**DOI：** 10.1186/s12943-025-02528-y

### 第一部分 原文与翻译

**英文原标题：** Correction: Circular RNA ACVR2A suppresses bladder cancer cells proliferation and metastasis through miR-626/EYA4 axis.

> **英文摘要：**
> No abstract available.

> **中文摘要：**
> 暂无摘要可用。

### 第二部分 AI 大师评价

本更正文献涉及一项关于环状RNA ACVR2A在膀胱癌进展中作用机制的研究。原研究揭示该环状RNA可通过 miR-626/EYA4 信号轴抑制膀胱癌细胞的增殖与转移，提示其具有潜在的肿瘤抑制功能。本次更正可能针对实验数据或分析结果进行了修订，以确保研究结论的准确性和严谨性。尽管缺少摘要，研究主题在非编码RNA调控肿瘤领域具有一定创新意义。

---

## 25. 联合放化疗与免疫检查点抑制剂治疗过程中与免疫相关不良反应相关的免疫细胞动态特征差异

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41430079)
**期刊：** Nature communications
**PMID：** 41430079
**DOI：** 10.1038/s41467-025-67689-2

### 第一部分 原文与翻译

**英文原标题：** Distinct immune cell dynamics associated with immune-related adverse events during combined chemoradiation and immune checkpoint inhibitor therapy.

> **英文摘要：**
> Combining chemoradiotherapy with immunotherapy increases the risk of immune-related adverse events (irAEs), but the underlying mechanisms remain poorly understood. To address this, we conducted a longitudinal single-cell multi-omics analysis of patients with locally advanced cervical cancer. Here we show that the proportions of CD4 and CD8 terminally differentiated effector memory or effector T cells are elevated in patients with irAEs. Chemoradiotherapy reduces B cell clonality while increasing the abundance and somatic hypermutation frequencies of IgA and IgG B cells in irAE patients. In the myeloid compartment, combined treatment expands specific monocyte subclusters associated with irAEs. Spatial transcriptomics and immunofluorescence analyses further reveal that these irAE-associated immune cells aggregate within the tumor microenvironment. Finally, we develop the predictive models for irAEs and integrate them, along with all datasets, into a user-friendly data portal. Our findings suggest that chemoradiotherapy and immunotherapy exert distinct effects on different immune cells, contributing to irAE development.

> **中文摘要：**
> 将放化疗与免疫治疗联合应用会增加免疫相关不良事件（irAE）的风险，但其潜在机制仍不清楚。为此，我们对局部晚期宫颈癌患者进行了纵向单细胞多组学分析。结果显示，在出现irAE的患者中，终末分化的效应记忆或效应CD4和CD8 T细胞的比例升高。放化疗可降低B细胞的克隆性，同时在irAE患者中增加IgA和IgG B细胞的丰度及体细胞高突变频率。在髓系细胞群中，联合治疗扩增了与irAE相关的特定单核细胞亚群。空间转录组学和免疫荧光分析进一步揭示，这些与irAE相关的免疫细胞在肿瘤微环境中呈聚集分布。最后，我们建立了预测irAE的模型，并将其与全部数据集整合到一个用户友好的数据门户中。研究结果表明，放化疗与免疫治疗对不同的免疫细胞产生不同影响，共同促进irAE的发生。

### 第二部分 AI 大师评价

该研究针对联合放化疗与免疫检查点抑制剂治疗引发的免疫相关不良反应进行了系统性探究，利用纵向单细胞多组学技术揭示了免疫细胞群体动态变化与irAE的关联。结果发现，不同T细胞与B细胞亚群及髓系细胞在irAE患者中呈现特异性变化，并通过空间转录组学验证其肿瘤微环境聚集特征。作者进一步开发预测模型并提供开放数据门户，具有较强的应用潜力。创新性在于多层次单细胞整合分析，但局限在于样本量及癌种特异性，仍需进一步验证。

---

## 26. 致编辑的通信：关于“RAB25-GCN1 非经典通路在酒精性肝病中的机制洞察——RAB25/GCN1 信号通过诱导内质网应激促进酒精相关性肝病进展”的讨论

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41430053)
**期刊：** Clinical and molecular hepatology
**PMID：** 41430053
**DOI：** 10.3350/cmh.2025.1397

### 第一部分 原文与翻译

**英文原标题：** Correspondence to editorial "Mechanistic Insights into a Noncanonical RAB25-GCN1 axis in ALD: on RAB25/GCN1 signaling promotes ER stress to mediate alcohol-associated liver disease progression".

> **英文摘要：**
> No abstract available.

> **中文摘要：**
> 无可用摘要。

### 第二部分 AI 大师评价

该篇通信文章是作者对先前关于 RAB25-GCN1 非经典信号通路与酒精性肝病（ALD）进展关系研究的回应或补充。尽管未提供摘要，但标题表明其聚焦于探讨该信号轴在诱导内质网应激及疾病机制中的作用。此类通信通常旨在对研究方法、数据解释或生物学机制提出进一步观点。研究价值在于深化对肝细胞应激反应与信号调控网络的理解，但受限于篇幅和实验数据缺乏，结论的外推仍需更多实证验证。

---

## 27. 基于 Charité 血浆蛋白质组学开放标准（OSPP）的跨平台临床蛋白质组学研究

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41430040)
**期刊：** Nature communications
**PMID：** 41430040
**DOI：** 10.1038/s41467-025-67264-9

### 第一部分 原文与翻译

**英文原标题：** Cross-platform clinical proteomics using the Charité open standard for plasma proteomics (OSPP).

> **英文摘要：**
> The role of plasma and serum proteomics in characterizing human disease, identifying biomarkers, and advancing diagnostic technologies is rapidly increasing. However, there is an ongoing need to improve proteomic workflows in terms of accuracy, reproducibility, and cost-effectiveness, and to achieve cross-platform transferability. Based on large serum and plasma proteome studies, we generate the Charité Open Peptide Standard for Plasma Proteomics (OSPP), an open, versatile peptide internal standard for targeted and untargeted mass spectrometry-based proteomic studies. The OSPP includes 211 concentration-matched stable-isotope-labeled peptides selected for consistent quantification across a large number of plasma and serum proteome studies, and synthetic accessibility. We show they are consistently quantified across serum and EDTA, citrate, and heparin plasma using multiple LC-MS platforms. Despite being selected for technical parameters, the OSPP peptides represent proteins that function in a wide range of biological processes, are used in routine clinical tests, or are targets of FDA-approved drugs, making OSPP able to serve as an expandable clinical marker panel. We demonstrate the utility of OSPP in a COVID-19 inpatient cohort study for improving analytical performances, for cross-platform alignment of proteomic data, disease stratification, and biomarker discovery.

> **中文摘要：**
> 血浆和血清蛋白质组学在表征人类疾病、识别生物标志物及推动诊断技术发展中的作用正迅速增强。然而，目前仍需在准确性、重复性和成本效益方面改进蛋白质组学工作流程，并实现跨平台可转移性。基于大规模血清和血浆蛋白质组研究，我们建立了 Charité 血浆蛋白质组学开放肽段标准（OSPP），这是一种开放且多用途的肽段内标，可用于基于靶向和非靶向质谱分析的蛋白质组学研究。OSPP 包含 211 条浓度匹配的稳定同位素标记肽，这些肽因其在大量血浆和血清蛋白质组研究中的一致定量性能以及易于合成而被选出。我们证明，这些肽在血清以及EDTA、柠檬酸盐和肝素抗凝血浆中，使用多种 LC-MS 平台均可实现一致的定量。尽管这些肽是根据技术参数选择的，但其对应蛋白广泛参与多种生物学过程，被用于常规临床检测，或是 FDA 批准药物的靶点，因此 OSPP 可作为可扩展的临床标志物面板。我们在一项 COVID-19 住院患者队列研究中展示了 OSPP 的实用性，其可提升分析性能，实现蛋白质组数据的跨平台校准、疾病分层及生物标志物发现。

### 第二部分 AI 大师评价

该研究旨在解决临床蛋白质组学跨平台分析的一致性与可比性问题。作者构建了一个包含 211 条稳定同位素标记肽的开放标准 OSPP，用于提高血浆与血清蛋白质组学定量的标准化与转移性。结果表明，无论样本类型或 LC-MS 平台，此标准均表现出良好的重复性和技术适应性。其创新性在于提供了可广泛应用、可扩展并适合临床使用的质谱定量参考框架，但仍需进一步验证其在不同疾病和实验条件下的鲁棒性与普适性。

---

## 28. 树突状细胞在肿瘤微环境中的新兴作用：从抗原呈递到靶向免疫治疗

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41430039)
**期刊：** Cell death & disease
**PMID：** 41430039
**DOI：** 10.1038/s41419-025-08180-0

### 第一部分 原文与翻译

**英文原标题：** The emerging role of dendritic cells in the tumor microenvironment: from antigen presentation to targeted immunotherapy.

> **英文摘要：**
> Dendritic cells (DCs), as pivotal antigen-presenting cells (APCs), play crucial roles in initiating T cell-mediated antitumor immune responses, bridging innate and adaptive immunity while maintaining immune tolerance. With an in-depth understanding of DC biology and functions, numerous DC-targeted therapeutic approaches have been developed. An enhanced understanding of DC heterogeneity and DC cross-talk with other cells within the tumor microenvironment (TME), along with functional and metabolic remodeling mechanisms, may optimize DC-based cancer immunotherapies. This review focuses on the heterogeneity of the individual occurrence and function of DCs in tumors, elucidates the cross-talk between DCs and other cells in the TME, provides an in-depth understanding of the dysfunction and metabolic reprogramming of DCs in the TME, and summarizes existing DC-based anticancer therapies and novel therapeutic strategies, with the aim of providing new insight into the emerging role of DCs in future cancer immunotherapy.

> **中文摘要：**
> 树突状细胞（DCs）作为关键的抗原呈递细胞（APCs），在启动T细胞介导的抗肿瘤免疫反应中发挥至关重要的作用，同时在连接固有免疫与适应性免疫的过程中维持免疫耐受。随着对DC生物学特性与功能的深入理解，已有多种以DC为靶点的治疗策略被开发出来。对DC异质性以及DC与肿瘤微环境（TME）中其他细胞之间的相互作用的深入认识，结合其功能与代谢重塑机制的研究，可能有助于优化基于DC的癌症免疫治疗。本综述重点探讨了肿瘤中DC个体分布及功能的异质性，阐明了DC与TME中其他细胞之间的相互交流，深入剖析了DC在TME中的功能障碍及代谢重编程机制，并总结了现有的DC相关抗癌治疗及新型治疗策略，旨在为未来DC在癌症免疫治疗中的新兴作用提供新见解。

### 第二部分 AI 大师评价

该综述系统阐述了树突状细胞在肿瘤微环境中的多层次作用，从抗原呈递到免疫调控，全面展示了DC在抗肿瘤免疫中的核心地位。作者整合了关于DC异质性、功能障碍及代谢重编程的最新研究，并探讨了其与免疫微环境内多种细胞的复杂互作。文章的创新性在于提出以DC功能重塑为核心的免疫治疗优化策略。然而，该综述主要基于现有文献，仍需后续实验和临床研究进一步验证这些机制与疗效。

---

## 29. TRIM24通过介导NRBP1泛素化促进胃癌的增殖与转移

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41430038)
**期刊：** Cell death & disease
**PMID：** 41430038
**DOI：** 10.1038/s41419-025-08346-w

### 第一部分 原文与翻译

**英文原标题：** TRIM24 promotes proliferation and metastasis of gastric cancer via mediating NRBP1 ubiquitination.

> **英文摘要：**
> The early detection and precise treatment of gastric cancer (GC) remain critical challenges worldwide. In this work, we screened and identified a subset of highly aggressive GC cell lines that exhibit elevated expression of TRIM24 using transwell assays and animal models. TRIM24 showed enhanced expression in GC cells and gastric carcinoma tissue samples in comparison with gastric noncancerous tissues. Importantly, elevated TRIM24 levels correlated with advanced tumor stage and poorer clinical outcomes. Functionally, TRIM24 acted as an oncogene, driving GC proliferation, invasion, and metastasis both in cell culture and animal experiments. Notably, TRIM24 knockdown markedly inducted apoptosis in GC cells through the modulation of NRBP1, a known context-specific tumor suppressor. Mechanistically, TRIM24 bound to NRBP1, enhancing its ubiquitination and subsequent degradation. Further mechanistic insights revealed that NRBP1 phosphorylation at residue S42 was crucial for TRIM24-mediated ubiquitination, with residue K430 identified as the specific ubiquitination site targeted by TRIM24. Jointly, the above findings unveil a critical role for TRIM24 in GC tumorigenesis and metastatic progression, thereby positioning TRIM24 as a promising therapeutic target in GC management.

> **中文摘要：**
> 胃癌（GC）的早期检测和精准治疗依然是全球面临的关键挑战。在本研究中，我们利用跨膜实验和动物模型筛选并鉴定出一组具有高侵袭性的GC细胞系，这些细胞系表现出TRIM24的高表达。与胃部非癌组织相比，TRIM24在GC细胞和胃癌组织样本中均显示出增强的表达。重要的是，TRIM24水平升高与肿瘤分期的进展及较差的临床预后显著相关。从功能上看，TRIM24作为癌基因，在细胞培养及动物实验中驱动了GC的增殖、侵袭和转移。值得注意的是，敲低TRIM24可通过调控NRBP1——一种已知的环境依赖性肿瘤抑制因子——显著诱导GC细胞凋亡。从机制上看，TRIM24可与NRBP1结合，促进其泛素化及随后降解。进一步的机制研究表明，NRBP1在S42位点的磷酸化对TRIM24介导的泛素化过程至关重要，而K430残基被确定为TRIM24特异性靶向的泛素化位点。总体而言，这些发现揭示了TRIM24在GC肿瘤发生和转移进展中的关键作用，从而将TRIM24定位为GC治疗管理中的一个潜在治疗靶点。

### 第二部分 AI 大师评价

本研究旨在阐明TRIM24在胃癌发生发展中的生物学作用及分子机制。作者通过细胞实验与动物模型结合的方式发现，TRIM24高表达与胃癌的侵袭性增强和不良预后密切相关。机制研究揭示TRIM24通过与NRBP1结合，促进其S42位点磷酸化依赖的泛素化及K430位点降解，从而发挥促癌效应。该研究创新性地揭示了TRIM24–NRBP1轴在胃癌中的调控机制，并为靶向TRIM24治疗提供了潜在思路。然而，临床验证及靶向干预的可行性仍需进一步研究。

---

## 30. 单细胞RNA测序揭示ZBP1依赖的机制在口腔鳞状细胞癌进展中的作用

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41430036)
**期刊：** Cell death & disease
**PMID：** 41430036
**DOI：** 10.1038/s41419-025-08349-7

### 第一部分 原文与翻译

**英文原标题：** Single-cell RNA sequencing identifies ZBP1-dependent mechanisms in OSCC progression.

> **英文摘要：**
> Oral squamous cell carcinoma (OSCC) is a highly aggressive head and neck malignancy with a poor prognosis associated with its complex tumor microenvironment. Cancer-associated fibroblasts (CAFs) contribute to tumor progression by secreting various signaling molecules. This study investigates the molecular mechanism through which Z-DNA-binding protein 1 (ZBP1) promotes OSCC development through CAF regulation. To this end, orthotopic MOC1 transplantation and 4NQO-induced carcinogenesis OSCC models were established with Zbp1 mice. Single-cell RNA sequencing (scRNA-seq) analyzed cellular heterogeneity and signaling network alterations in the tumor microenvironment. An in vitro CAF induction model combined with a Transwell co-culture system clarified the molecular mechanism of ZBP1. Finally, the role of the ZBP1-CCL7/CCR1 signaling axis in promoting OSCC progression was evaluated via in vivo recombinant CCL7 protein rescue and CCR1 antagonist (BX471) intervention. ZBP1 is highly expressed in OSCC tissues, while its deficiency inhibits tumor growth and proliferation. Proliferation-related pathways (e.g., E2F targets, MYC targets, cell cycle) are downregulated while immune activation signatures (e.g., interferon response, p53 pathway, TNF-α/NF-κB signaling) are upregulated in Zbp1 tumor cells. Cellular interaction analysis and ligand-receptor network profiling demonstrated significant attenuation of the CCL7-CCR1 signaling axis between CAFs and tumor cells. ZBP1 deficiency reduces CCL7 expression in CAFs, diminishing their ability to promote tumor cell proliferation, migration, and invasion via the CCL7/CCR1 axis. Exogenous CCL7 supplementation partially restores tumor growth in Zbp1 mice, indicating that ZBP1 bridges CAF-tumor cell communication through the CCL7-CCR1 axis. This study highlights ZBP1 as crucial for OSCC progression by regulating CCL7 expression in CAFs to activate CCR1 signaling in tumor cells. This provides insights into the regulatory mechanisms within the OSCC microenvironment, offering a potential therapeutic strategy for targeted interventions.

> **中文摘要：**
> 口腔鳞状细胞癌（OSCC）是一种高度侵袭性的头颈部恶性肿瘤，其复杂的肿瘤微环境与预后不良密切相关。癌相关成纤维细胞（CAFs）通过分泌多种信号分子促进肿瘤进展。本研究探讨Z-DNA结合蛋白1（ZBP1）通过调控CAFs促进OSCC发展的分子机制。为此，研究者利用Zbp1小鼠建立了原位MOC1移植模型和4NQO诱导的OSCC癌变模型。通过单细胞RNA测序（scRNA-seq）分析肿瘤微环境中的细胞异质性及信号网络变化。结合Transwell共培养体系的体外CAFs诱导模型进一步阐明了ZBP1的分子机制。最后，通过体内重组CCL7蛋白补救实验和CCR1拮抗剂（BX471）干预，评估了ZBP1-CCL7/CCR1信号轴在促进OSCC进展中的作用。结果显示，ZBP1在OSCC组织中高表达，其缺失可抑制肿瘤生长和增殖。与增殖相关的通路（如E2F靶基因、MYC靶基因及细胞周期）下调，而免疫活化特征（如干扰素反应、p53通路、TNF-α/NF-κB信号）在Zbp1肿瘤细胞中上调。细胞互作分析和配体-受体信号网络分析表明，CAFs与肿瘤细胞间的CCL7-CCR1信号轴显著减弱。ZBP1缺失导致CAFs中CCL7表达降低，从而削弱其通过CCL7/CCR1轴促进肿瘤细胞增殖、迁移与侵袭的能力。外源性补充CCL7可部分恢复Zbp1小鼠的肿瘤生长，提示ZBP1通过CCL7-CCR1轴在CAFs与肿瘤细胞间发挥桥接作用。本研究强调ZBP1通过调控CAFs中CCL7表达以激活肿瘤细胞中的CCR1信号，在OSCC进展中发挥关键作用，为深入理解OSCC微环境的调控机制及靶向干预策略提供了新思路。

### 第二部分 AI 大师评价

该研究利用单细胞RNA测序结合动物模型和体外共培养体系，系统揭示了ZBP1通过调控CAFs中CCL7表达、激活肿瘤细胞CCR1信号轴促进OSCC进展的分子机制。实验设计严谨，涵盖体内外验证，明确了ZBP1在肿瘤-基质互作中的关键作用。研究创新性在于揭示ZBP1-CCL7/CCR1信号桥梁的机制，为靶向干预口腔癌微环境提供了新的潜在策略。其局限在于尚需进一步验证该机制在临床样本及患者预后中的应用价值。

---

## 31. 无残痕环状mRNA CAR-T细胞疗法展现更优异的抗肿瘤疗效

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41430032)
**期刊：** Signal transduction and targeted therapy
**PMID：** 41430032
**DOI：** 10.1038/s41392-025-02512-4

### 第一部分 原文与翻译

**英文原标题：** Scarless circular mRNA-based CAR-T cell therapy elicits superior antitumor efficacy.

> **英文摘要：**
> Messenger RNA (mRNA)-based transient expression of chimeric antigen receptors (CARs) results in optimal safety profiles and provides promising opportunities to address existing challenges associated with viral vector-based CAR-T-cell therapies and to meet emerging medical needs for noncancerous indications. Conventional linear mRNAs, however, are intrinsically unstable and typically support short-lived protein expression, which can constrain therapeutic activity. Here, we engineered a high-efficiency permuted intron exon (PIE) platform to synthesize scarless circular mRNAs (cmRNAs) that drive robust CAR expression with extended durability. The scarless design avoids extraneous junction sequences, streamlining manufacturability and potentially reducing innate immune sensing. Compared with linear mRNAs, cmRNAs significantly increased both the magnitude and duration of anti-CD19 CAR and anti-GPRC5D CAR expression in primary human T cells. Functionally, cmRNA-based CAR-T cells elicited superior antitumor efficacy over their linear mRNA counterparts, as demonstrated by parallel lines of evidence, including in vitro antigen-specific cytotoxicity, cytokine release, and transcriptomics patterns consistent with sustained activation and absence of exhaustion signatures, as well as in vivo models demonstrating tumor elimination and prolonged survival benefits. Collectively, these findings position cmRNA as a next-generation mRNA modality for potent and controllable CAR expression, thereby providing a robust platform to unleash the full potential of mRNA technologies in cellular immunotherapy and precision medicine.

> **中文摘要：**
> 以信使RNA（mRNA）为基础的短暂嵌合抗原受体（CAR）表达可实现最佳安全性，并为解决病毒载体介导的CAR-T细胞治疗相关的既有挑战以及满足非肿瘤性适应症的新兴医疗需求提供了有前景的机会。然而，传统线性mRNA本质上不稳定，通常只能维持短暂的蛋白表达，这限制了其治疗活性。本研究构建了一种高效的“重组内含子-外显子”（PIE）平台，用于合成无残痕环状mRNA（cmRNA），该分子能够驱动持续且强劲的CAR表达。无残痕设计避免了多余的连接序列，简化了生产流程，并可能降低先天免疫感知。与线性mRNA相比，cmRNA在原代人T细胞中显著增强了抗CD19 CAR和抗GPRC5D CAR的表达强度与持续时间。在功能上，基于cmRNA的CAR-T细胞较其线性mRNA对应物表现出更优的抗肿瘤效力，这一点可通过多条证据链验证，包括体外抗原特异性细胞毒性、细胞因子释放、转录组学特征（显示持续激活且无疲竭迹象），以及体内模型中实现的肿瘤清除与显著延长的生存获益。总体而言，这些发现确立了cmRNA作为新一代mRNA形式在实现高效且可控CAR表达方面的重要地位，为释放mRNA技术在细胞免疫疗法与精准医学中的全部潜力提供了坚实平台。

### 第二部分 AI 大师评价

本研究旨在突破传统线性mRNA的稳定性限制，开发无残痕环状mRNA平台以提升CAR-T细胞的表达效率与持久性。研究团队通过PIE系统实现了高效合成的环状mRNA，并在抗CD19和GPRC5D CAR-T模型中证实其可显著增强抗肿瘤活性。该方法在安全性、生产简化和免疫耐受方面展现优势，为非病毒载体CAR-T疗法提供新路径。其创新性在于结构优化与功能稳定性的兼顾，但仍需临床级验证以评估长期安全与可扩展性。

---

## 32. 揭示子宫颈癌中 ZNF384-INTS13-hnRNPC 轴作为治疗靶点的潜在脆弱性

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429980)
**期刊：** Cell death & disease
**PMID：** 41429980
**DOI：** 10.1038/s41419-025-08374-6

### 第一部分 原文与翻译

**英文原标题：** Unveiling the ZNF384-INTS13-hnRNPC axis as a therapeutic vulnerability in cervical cancer.

> **英文摘要：**
> Cervical cancer remains a major global health burden, necessitating the identification of novel therapeutic targets to overcome the limitations of current treatments. Here, we comprehensively investigated the role of integrator complex subunit 13 (INTS13) in cervical cancer progression. Our analysis of publicly available The Cancer Genome Atlas (TCGA) datasets revealed that INTS13 is significantly overexpressed in cervical cancer tissues across various histological subtypes, correlating with advanced tumor T-stage and predicting poorer overall survival. Single-cell RNA sequencing further localized INTS13 expression predominantly to malignant epithelial cells within the tumor microenvironment, where its expression correlated with genes involved in critical cellular processes. Furthermore, elevated expression has been observed in cervical cancer tissues from surgically-treated patients and in various primary human cervical cancer cells. In vitro functional studies demonstrated that genetic silencing or CRISPR/Cas9-mediated knockout of INTS13 significantly inhibited the proliferation, migration, and invasion of primary cervical cancer cells, while selectively inducing apoptosis. Conversely, ectopic INTS13 overexpression markedly enhanced these malignant phenotypes. Mechanistically, we identified heterogeneous nuclear ribonucleoprotein C (hnRNPC) as a critical downstream effector, with INTS13 regulating hnRNPC expression, and the restoration of hnRNPC effectively reversing the anti-cervical cancer effects observed upon INTS13 silencing. Furthermore, the transcription factor ZNF384 (zinc finger protein 384) was identified as an upstream regulator that directly binds to and positively governs INTS13 expression. Finally, in vivo animal models confirmed that targeted silencing of INTS13 significantly impeded cervical cancer xenograft growth in nude mice, reduced cellular proliferation, and augmented apoptosis, consistently accompanied by a reduction in hnRNPC expression. These findings collectively establish INTS13 as a crucial precancerous gene in cervical cancer, promoting malignant phenotypes primarily through the ZNF384-INTS13-hnRNPC signaling axis.

> **中文摘要：**
> 宫颈癌仍然是全球主要的健康负担之一，因此迫切需要识别新的治疗靶点，以克服现有治疗的局限性。本研究全面探讨了整合酶复合物亚基13（integrator complex subunit 13，INTS13）在宫颈癌进展中的作用。我们对公开的癌症基因组图谱（TCGA）数据库进行分析发现，INTS13在不同组织学亚型的宫颈癌组织中均显著高表达，该高表达与肿瘤 T 分期的进展相关，并可预测较差的总体生存率。单细胞RNA测序进一步显示，INTS13的表达主要局限于肿瘤微环境中的恶性上皮细胞，其表达与参与关键细胞过程的基因呈相关性。此外，在接受手术治疗的宫颈癌患者组织及多种人原发性宫颈癌细胞中，也观察到INTS13的高表达。体外功能实验表明，基因沉默或CRISPR/Cas9介导的INTS13敲除可显著抑制原发性宫颈癌细胞的增殖、迁移和侵袭，同时选择性地诱导细胞凋亡。相反，外源性过表达INTS13显著增强了这些恶性表型。在机制层面，我们鉴定出异质性核糖核蛋白C（hnRNPC）为关键下游效应分子，INTS13可调控hnRNPC的表达，而hnRNPC的恢复可有效逆转INTS13沉默后表现出的抗宫颈癌效应。此外，我们发现转录因子ZNF384（zinc finger protein 384）是上游调控因子，可直接结合并正向调控INTS13的表达。最终，在体内动物模型中证实，针对INTS13的特异性沉默显著抑制了裸鼠宫颈癌异种移植瘤的生长，降低了细胞增殖，并增强了凋亡，同时伴随hnRNPC表达的减少。这些结果共同确立了INTS13在宫颈癌中的关键致癌作用，其主要通过ZNF384-INTS13-hnRNPC信号轴促进恶性表型的形成。

### 第二部分 AI 大师评价

该研究系统揭示了INTS13在宫颈癌发生发展中的关键作用，并阐明了上游调控因子ZNF384与下游效应分子hnRNPC的信号连接。研究采用了TCGA分析、单细胞测序、体外功能实验及体内动物模型等多层验证，具有较强的证据链与科研深度。结果显示ZNF384-INTS13-hnRNPC轴在推动宫颈癌恶性进展中发挥核心作用，为靶向干预提供了新的潜在治疗靶点。创新性在于揭示了此前未被报道的分子轴，但仍需在更大样本和临床环境中进一步验证其治疗价值。

---

## 33. 靶向 TRBC2 的抗体-药物偶联物用于 T 细胞癌的治疗

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429932)
**期刊：** Nature cancer
**PMID：** 41429932
**DOI：** 10.1038/s43018-025-01069-z

### 第一部分 原文与翻译

**英文原标题：** TRBC2-targeting antibody-drug conjugates for the treatment of T cell cancers.

> **英文摘要：**
> Antibody-drug conjugates (ADCs) have been remarkably successful in treating solid and hematological malignancies. Generation of ADCs for T cell cancers is challenging because the ADCs must selectively target cancerous T cells while sparing some normal T cells necessary for immune function. T cells express one of two TRBC alleles: TRBC1 or TRBC2. Normal T cells are composed of about 40% TRBC1-expressing and 60% TRBC2-expressing cells. In contrast, T cell malignancies are characterized by the clonal expression of either TRBC1 or TRBC2. Selective targeting of TRBC1 or TRBC2 enables the killing of cancer cells but preserves about 60-40% of the normal T cells. To enable such a therapy for cancers expressing TRBC2, here we developed a high-affinity anti-TRBC2 antibody. An ADC generated with this antibody and a pyrrolobenzodiazepine dimer payload showed specific killing of TRBC2 cancers in vitro and in mouse models. The anti-TRBC2 ADC provides a promising, off-the-shelf therapy for patients with T cell cancers.

> **中文摘要：**
> 抗体-药物偶联物（ADCs）在治疗实体瘤和血液恶性肿瘤中取得了显著成功。为 T 细胞肿瘤开发 ADCs 具有挑战性，因为此类 ADCs 必须选择性地靶向癌变 T 细胞，同时保留部分维持免疫功能所需的正常 T 细胞。T 细胞表达两种 TRBC 等位基因之一：TRBC1 或 TRBC2。正常 T 细胞约由 40% 的 TRBC1 表达细胞和 60% 的 TRBC2 表达细胞组成。相比之下，T 细胞恶性肿瘤的特征是单克隆表达 TRBC1 或 TRBC2。选择性靶向 TRBC1 或 TRBC2 可实现对癌细胞的杀伤，同时保留约 60-40% 的正常 T 细胞。为了实现针对表达 TRBC2 的癌症的此类治疗，我们开发了一种高亲和力的抗 TRBC2 抗体。利用该抗体并结合吡咯苯并二氮卓二聚体载荷生成的 ADC 在体外及小鼠模型中表现出对 TRBC2 癌细胞的特异性杀伤作用。抗 TRBC2 ADC 为 T 细胞癌患者提供了一种有前景的即用型治疗方案。

### 第二部分 AI 大师评价

本研究旨在针对 T 细胞癌开发选择性靶向 TRBC2 的抗体-药物偶联物，以实现对恶性 T 细胞的精准清除并保留正常免疫功能。作者通过构建高亲和力抗 TRBC2 抗体，并与吡咯苯并二氮卓二聚体载荷偶联，成功获得特异性杀伤 TRBC2 癌细胞的 ADC。该方案在体外与小鼠模型中均显示出显著的疗效。研究创新性地利用 TCR β 链恒定区的等位基因差异作为安全治疗靶点，展现出临床转化潜力。但后续仍需评估其长期安全性及免疫重塑影响。

---

## 34. 程序性坏死信号调控胶质母细胞瘤的恶性进程并增强替莫唑胺反应

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429922)
**期刊：** Cell death & disease
**PMID：** 41429922
**DOI：** 10.1038/s41419-025-08377-3

### 第一部分 原文与翻译

**英文原标题：** Necroptotic signaling orchestrates glioblastoma malignancy and potentiates temozolomide response.

> **英文摘要：**
> Glioblastoma (GBM), a highly aggressive form of glioma, poses serious harm to patients due to its extremely poor prognosis and severe resistance to chemotherapeutic agents. Although programmed necrosis (necroptosis) has been implicated in GBM progression, its precise function and biological significance in GBM remain incompletely defined. Here, we show that elevated expression of key necroptotic machinery proteins, including RIPK1 and MLKL, is positively associated with disease progression and predicts poor prognosis in glioma patients. Functionally, RIPK1 promotes glioblastoma cell proliferation, migration, and invasion. Genetic ablation of RIPK1 induces cell-cycle arrest and suppresses tumor growth in subcutaneous xenograft models, whereas pharmacological inhibition of RIPK1 with necrostatin-1 fails to restrict GBM cell expansion, suggesting that RIPK1 exerts oncogenic effects independent of its canonical necroptotic role. Notably, dual apoptosis- and necroptosis-inducing agents, ZZW115 and citronellol, synergize with temozolomide (TMZ)-the first-line chemotherapy for GBM-to enhance glioma cell death and increase tumor clearance in an orthotopic mouse glioma model. Collectively, these findings identify RIPK1 as a critical driver of glioma malignancy and underscore the therapeutic potential of activating necroptosis to augment TMZ efficacy, providing a framework for novel prognostic and treatment strategies in glioma.

> **中文摘要：**
> 胶质母细胞瘤（GBM）是一种高度侵袭性的胶质瘤类型，由于其极差的预后和对化疗药物的严重耐受性，对患者造成了严重危害。尽管程序性坏死（necroptosis）已被认为与GBM的进展有关，但其在GBM中的精确功能和生物学意义仍未被完全阐明。本研究显示，包括RIPK1和MLKL在内的关键坏死性凋亡机制蛋白的高表达与疾病进展呈正相关，并预示着胶质瘤患者的不良预后。在功能层面，RIPK1促进了胶质母细胞瘤细胞的增殖、迁移和侵袭。RIPK1基因缺失会引起细胞周期停滞，并在皮下异种移植模型中抑制肿瘤生长；然而，用坏死抑制剂-1（necrostatin-1）对RIPK1进行药理学抑制却未能限制GBM细胞扩增，这表明RIPK1可能通过与其经典坏死性凋亡功能无关的途径发挥致瘤作用。值得注意的是，双重诱导细胞凋亡和坏死的化合物ZZW115和香茅醇（citronellol）与胶质母细胞瘤一线化疗药物替莫唑胺（TMZ）协同作用，能够增强胶质瘤细胞死亡，并在原位小鼠胶质瘤模型中提高肿瘤清除效率。总体而言，这些发现确定了RIPK1作为胶质瘤恶性进展关键驱动因子的地位，并强调了通过激活坏死性凋亡来增强TMZ疗效的治疗潜力，为胶质瘤的新型预后评估与治疗策略提供了理论框架。

### 第二部分 AI 大师评价

本文旨在揭示程序性坏死信号在胶质母细胞瘤进展与药物反应中的作用机制。研究者发现RIPK1不仅促进肿瘤生长，还在独立于其经典坏死性通路的情况下展现出致瘤特性。通过联合诱导坏死与凋亡的药物增强替莫唑胺疗效，实验验证了坏死性途径在改善治疗反应中的潜力。该研究创新性地提出激活坏死通路可作为胶质瘤治疗新策略，但仍需进一步研究安全性与临床可行性。

---

## 35. TPI1通过激活Beclin-1促进自噬，从而增强膀胱癌对吉西他滨的耐药性

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429797)
**期刊：** Cell death & disease
**PMID：** 41429797
**DOI：** 10.1038/s41419-025-08368-4

### 第一部分 原文与翻译

**英文原标题：** TPI1 enhances gemcitabine resistance in bladder cancer by promoting autophagy through activating Beclin-1.

> **英文摘要：**
> The persistent issues of drug resistance and tumor recurrence remain major challenges in bladder cancer (BCa) treatment, severely impacting patient outcomes. In this study, we found that Triosephosphate isomerase 1 (TPI1) plays a crucial role in influencing gemcitabine (Gem) resistance in BCa. TPI1 is significantly upregulated in Gem-resistant BCa tissues, and the knockdown of TPI1 markedly increases Gem sensitivity and chemotherapy-induced apoptosis both in vivo and in vitro. Meanwhile, the same was validated in Gem-resistant strains. Mechanistically, transcriptome sequencing and transmission electron microscopy, among others, revealed that TPI1 promoted Gem-associated autophagy. Furthermore, mass spectrometry and co-immunoprecipitation assays demonstrated that TPI1 directly binds to the BH3 domain of Beclin-1. This interaction competitively disrupts the binding between Bcl-2 and Beclin-1, thereby relieving Bcl-2-mediated inhibition of Beclin-1. Furthermore, the interaction between TPI1 and Beclin-1 promotes the formation of PIK3C3-C1, which in turn enhances the interaction between PIK3C3-C1 and the ULK1 complex, thereby increasing the phosphorylation of Beclin-1 at Ser15. In addition, TPI1 also enhanced mitochondrial autophagy induced by Gem in BCa cells and tissues. Importantly, a transcription factor, c-Myc, that regulates TPI1 expression was also identified, and dual luciferase and Chromatin immunoprecipitation-quantitative PCR (ChIP-qPCR) analysis showed that c-Myc binds primarily to the promoter region of TPI1. Our results suggest that TPI1 plays an important role in regulating the formation of autophagic complexes, and that promoting autophagy significantly increased Gem resistance in BCa.

> **中文摘要：**
> 药物耐药性和肿瘤复发的持续存在仍是膀胱癌（BCa）治疗中的主要挑战，严重影响患者预后。在本研究中，我们发现磷酸丙糖异构酶1（TPI1）在调控BCa对吉西他滨（Gem）耐药性中发挥关键作用。TPI1在吉西他滨耐药的BCa组织中显著上调，而敲低TPI1可在体内外显著提高对吉西他滨的敏感性并增强化疗诱导的细胞凋亡。同时，这一结果也在吉西他滨耐药株中得到验证。在机制上，通过转录组测序和透射电镜等方法揭示TPI1可促进吉西他滨相关的自噬。此外，质谱和共免疫沉淀实验表明，TPI1可直接结合于Beclin-1的BH3结构域。该相互作用竞争性地破坏了Bcl-2与Beclin-1之间的结合，从而解除Bcl-2介导的对Beclin-1的抑制作用。进一步研究发现，TPI1与Beclin-1的相互作用可促进PIK3C3-C1复合物的形成，进而增强PIK3C3-C1与ULK1复合物之间的相互作用，从而增加Beclin-1在Ser15位点的磷酸化。此外，TPI1还增强了吉西他滨在BCa细胞及组织中诱导的线粒体自噬。值得注意的是，研究还鉴定到一个调控TPI1表达的转录因子c-Myc，并通过双荧光素酶及染色质免疫沉淀定量PCR（ChIP-qPCR）分析发现，c-Myc主要结合于TPI1启动子区域。我们的结果表明，TPI1在调控自噬复合物形成中发挥重要作用，而自噬的促进显著增强了BCa对吉西他滨的耐药性。

### 第二部分 AI 大师评价

本研究聚焦于TPI1在膀胱癌吉西他滨耐药中的作用机制，利用分子生物学、蛋白互作及功能实验系统阐明了TPI1通过Beclin-1介导的自噬途径增强耐药性。研究首次揭示了TPI1与Beclin-1 BH3结构域的直接结合，并阐述了其对Bcl-2/Beclin-1相互作用及自噬信号复合物形成的调控机制。结果显示TPI1既调控细胞也调控线粒体自噬，同时受c-Myc转录调控。该研究在探索代谢酶与肿瘤耐药信号网络交叉方面具有创新性，但仍需在临床样本和药物干预验证方面进一步拓展。

---

## 36. 优化肾功能受损患者的来那度胺治疗：可移植新诊断多发性骨髓瘤患者前瞻性 REMNANT 研究中的肾脏反应分析

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429779)
**期刊：** Blood cancer journal
**PMID：** 41429779
**DOI：** 10.1038/s41408-025-01407-5

### 第一部分 原文与翻译

**英文原标题：** Optimizing lenalidomide therapy in renal impairment: analysis of renal response in the prospective REMNANT study in transplant-eligible newly diagnosed multiple myeloma.

> **英文摘要：**
> Renal impairment (RI) is a serious complication in multiple myeloma (MM), linked to poor survival and early mortality. Rapid renal recovery improves outcomes, yet patients with RI have been excluded from most key trials in transplant-eligible newly diagnosed (TE-ND) MM. REMNANT is an ongoing, academic, multicenter phase 2/3 study in TE-NDMM patients aged 18-75, regardless of baseline renal function. Here, we report a subanalysis of the non-randomized phase 2 component. All patients received four 21-day cycles of induction with bortezomib, lenalidomide, and dexamethasone. Lenalidomide was dosed higher than the recommended standard of care: 25 mg/day for eGFR ≥30 mL/min/1.73 m² and 15 mg/day for eGFR <30. Between August 2020 and September 2024, 382 patients were enrolled; 81 (21%) had RI, including seven (2%) on dialysis during cycle 1. Renal response was achieved in 77%, with complete renal response in 57%. Five dialysis-dependent patients became dialysis-independent. Overall response rates were similar, and adverse events were comparable between RI and non-RI groups, except for higher rates of anemia and thrombocytopenia in the RI cohort. Four RI patients (5%) experienced worsening renal function; two cases were possibly related to lenalidomide, both reversible. These findings support the safety and efficacy of increased lenalidomide-dosing during induction in TE-NDMM patients with RI, including those with severe impairment.

> **中文摘要：**
> 肾功能损害（RI）是多发性骨髓瘤（MM）的一种严重并发症，与较差的生存率和早期死亡率相关。快速的肾功能恢复能改善结局，但在可行干细胞移植的新诊断（TE-ND）MM患者的主要临床试验中，RI患者大多被排除在外。REMNANT 是一项正在进行中的学术性多中心 II/III 期研究，纳入18至75岁、无论基线肾功能如何的 TE-NDMM 患者。在此，我们报告该研究非随机 II 期部分的一个亚组分析。所有患者均接受了四个为期21天的诱导治疗周期，药物包括硼替佐米、来那度胺和地塞米松。来那度胺剂量高于标准推荐剂量：当 eGFR ≥30 mL/min/1.73 m² 时为25 mg/天，eGFR <30时为15 mg/天。2020年8月至2024年9月期间，共入组382例患者，其中81例（21%）存在 RI，包括7例（2%）在第1个周期接受透析。77%的患者获得了肾功能反应，其中57%达到完全肾功能反应。5例透析依赖患者恢复至非透析状态。RI组与非RI组的总体应答率相似，不良事件总体可比，但 RI 组贫血和血小板减少的发生率更高。4例 RI 患者（5%）出现肾功能恶化，其中2例可能与来那度胺有关，且均可逆。这些结果支持在包括重度肾功能受损的 TE-NDMM 患者中，于诱导治疗阶段提高来那度胺剂量的安全性与有效性。

### 第二部分 AI 大师评价

本研究旨在探索在肾功能受损的可移植新诊断多发性骨髓瘤患者中，提高来那度胺剂量的安全性与疗效。研究分析了REMNANT II期部分的数据，结果显示高剂量来那度胺诱导治疗可实现较高的肾功能恢复率和总体应答率，且不良事件总体与非RI患者相当。五例透析依赖患者成功脱离透析，提示剂量优化可能改善预后。研究的创新点在于纳入了肾功能显著受损甚至透析依赖人群，其局限性在于非随机设计及随访时间有限。

---

## 37. 溶瘤腺病毒递送新抗原使低突变肿瘤对抗PD-1治疗敏感并抑制转移

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429778)
**期刊：** Signal transduction and targeted therapy
**PMID：** 41429778
**DOI：** 10.1038/s41392-025-02511-5

### 第一部分 原文与翻译

**英文原标题：** Oncolytic adenovirus delivery of neoantigens sensitizes low-mutation tumors to anti-PD-1 therapy and prevents metastasis.

> **英文摘要：**
> Neoantigen vaccines and oncolytic viruses are emerging immunotherapies that can reshape the tumor microenvironment (TME). However, tumors with low mutation burdens often respond poorly to immunotherapies because of their limited immunogenicity. Developing effective immunotherapy strategies for these types of tumors remains a significant challenge. In this study, we engineered oncolytic adenoviruses to accurately amplify neoantigen expression within tumor cells, which demonstrated superior efficacy compared to synthetic long peptide vaccines and showed enhanced effectiveness in a low mutation burden intrahepatic cholangiocarcinoma model. Building on this, we further developed NeoViron, which coexpresses neoantigens and Flt3L, a dendritic cell growth factor, to promote antigen presentation and T-cell infiltration simultaneously. NeoViron significantly inhibited tumor growth and prevented metastasis in intrahepatic cholangiocarcinoma animal models. Mechanistically, NeoViron enhanced the cytotoxicity of CD8+ T cells and promoted the expansion of CD69+ CD8+ tissue-resident memory T cells and TCF1+ CD8+ stem-like T cells to promote anti-tumor immunity and immune memory. When combined with anti-PD-1, it further enhances the cytotoxicity of tissue-resident memory T cells to eradicate solid tumors. These findings demonstrate that NeoViron can effectively sensitize low-mutation tumors to immunotherapy by increasing neoantigen expression and antigen-presentation efficacy, offering a promising strategy for cancer treatment, particularly for tumors with scarce neoantigens.

> **中文摘要：**
> 新抗原疫苗和溶瘤病毒是新兴的免疫治疗手段，能够重塑肿瘤微环境（TME）。然而，突变负荷较低的肿瘤由于免疫原性有限，通常对免疫治疗反应不佳。针对这类肿瘤开发有效的免疫治疗策略仍然是一项重大挑战。在本研究中，我们设计了溶瘤腺病毒，以精确增强肿瘤细胞内新抗原的表达，与合成长肽疫苗相比表现出更优的疗效，并在低突变负荷的肝内胆管癌模型中显示了更高的治疗效果。在此基础上，我们进一步开发了NeoViron，其共表达新抗原与树突状细胞生长因子Flt3L，以同时促进抗原呈递和T细胞浸润。NeoViron在肝内胆管癌动物模型中显著抑制了肿瘤生长并防止了转移。从机制上看，NeoViron增强了CD8+ T细胞的细胞毒性，并促进了CD69+ CD8+组织驻留记忆T细胞和TCF1+ CD8+干样T细胞的扩增，从而增强抗肿瘤免疫及免疫记忆。当与抗PD-1联合使用时，它进一步提高了组织驻留记忆T细胞的细胞毒性，有助于清除实体肿瘤。这些发现表明，NeoViron通过提高新抗原表达和抗原呈递效率，可有效增强低突变肿瘤对免疫治疗的敏感性，为尤其是新抗原稀少的肿瘤提供了一种有前景的治疗策略。

### 第二部分 AI 大师评价

该研究旨在解决低突变负荷肿瘤对免疫治疗反应不佳的问题，创新性地利用溶瘤腺病毒实现新抗原的体内强化表达，并通过共表达Flt3L进一步促进抗原呈递与T细胞浸润。通过在肝内胆管癌模型中的验证，NeoViron显著抑制了肿瘤生长并防止转移，联合抗PD-1疗法更显示协同效应。研究机制层面揭示其通过增强CD8+ T细胞效应与记忆形成来改善免疫应答，体现出较高的转化潜力。其局限性可能在于跨癌种验证及长期安全性仍需进一步研究。

---

## 38. 肺泡驻留巨噬细胞对RIPK1/RIPK3介导的程序性坏死高度易感，并促进高效的肺部免疫应答。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429777)
**期刊：** Cell death & disease
**PMID：** 41429777
**DOI：** 10.1038/s41419-025-08372-8

### 第一部分 原文与翻译

**英文原标题：** Resident alveolar macrophages are highly susceptible to the induction of RIPK1/RIPK3-mediated necroptosis which promote efficient pulmonary immune response.

> **英文摘要：**
> Alveolar macrophages (AMs) play a crucial role in protecting the lungs from pathogens by inducing immunogenic cell death (ICD). However, the type of cell death that effectively induces protective immunity remains to be fully understood. In our investigation of the mechanisms regulating AM activation and lung immune responses, we found that AMs are highly susceptible to necroptosis, a form of ICD. Treatment with pan-caspase inhibitors, such as emricasan or benzyloxycarbonyl-Val-Ala-Asp(OMe)-fluoromethyl ketone (ZVAD-fmk), directly induced cell death in AMs, resulting in the release of interleukin (IL)-1α in the lungs. This phenomenon was not observed in mouse lung fibroblasts or bone marrow-derived macrophages, indicating a cell type-specific sensitivity. The process was mediated by receptor-interacting protein kinase (RIPK)1 and RIPK3, and notably occurred without any additional necroptosis triggers such as tumor necrosis factor (TNF) or second mitochondria-derived activator of caspase (SMAC) mimetics. Moreover, activation of the RIPK1-RIPK3 signaling pathway not only triggered necroptosis but also promoted IL-1α production and release. These responses were absent in AMs lacking functional RIPK1 kinase activity or deficient in RIPK3. Importantly, RIPK1/RIPK3-mediated cell death and IL-1α release were sufficient to trigger lung immune responses, as shown by increased antigen-specific IgG and IgA production, which was significantly decreased in mice deficient in necroptosis or lacking the IL-1 receptor. Taken together, these findings demonstrate that the pan-caspase inhibitor emricasan induces necroptotic cell death in AMs and may act as a promising AM-targeted adjuvant to enhance lung-specific acquired immunity.

> **中文摘要：**
> 肺泡巨噬细胞（AMs）通过诱导免疫原性细胞死亡（ICD）在防御病原体、保护肺部中发挥关键作用。然而，哪种类型的细胞死亡能有效诱导保护性免疫尚未完全阐明。在我们对调控AM活化与肺部免疫反应机制的研究中，发现AM对坏死性凋亡（一种ICD形式）高度敏感。使用广谱caspase抑制剂（如emricasan或苄氧羰基-Val-Ala-Asp(OMe)-氟甲基酮（ZVAD-fmk））处理可直接诱导AM细胞死亡，并导致肺内白介素（IL）-1α释放。这一现象未在小鼠肺成纤维细胞或骨髓来源的巨噬细胞中观察到，提示其具有细胞类型特异性的敏感性。该过程由受体相互作用蛋白激酶（RIPK）1和RIPK3介导，且在无肿瘤坏死因子（TNF）或第二线粒体源性caspase激活因子（SMAC）模拟物等额外坏死性凋亡诱导信号的情况下即可发生。此外，RIPK1-RIPK3信号通路的活化不仅触发坏死性凋亡，还促进IL-1α的生成和释放。在缺乏功能性RIPK1激酶活性或RIPK3缺陷的AM中，这些反应均未出现。更重要的是，RIPK1/RIPK3介导的细胞死亡及IL-1α释放足以引发肺部免疫应答，这体现在抗原特异性IgG与IgA生成的增加；而在坏死性凋亡缺失或IL-1受体缺乏的小鼠中，这种效应显著降低。综上所述，这些发现表明，广谱caspase抑制剂emricasan可诱导AMs发生坏死性凋亡，并可能作为一种有前景的AM靶向肺部免疫佐剂以增强肺特异性获得性免疫。

### 第二部分 AI 大师评价

本研究揭示肺泡巨噬细胞对RIPK1/RIPK3介导的坏死性凋亡高度敏感，且该过程能通过IL-1α释放有效激发肺部免疫应答。作者通过药理抑制和基因缺失实验阐明RIPK1-RIPK3信号在AMs中无需外源刺激即可诱导免疫原性死亡。研究创新地提出广谱caspase抑制剂emricasan或可作为靶向肺泡巨噬细胞的免疫佐剂，为肺部免疫增强提供了新的思路。其局限性在于需进一步验证在人源AM及临床模型中的可转化性。

---

## 39. pH 与氧化还原状态变化诱导的 AQP3 通道关闭的结构机制揭示其自我调控的分子机制

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429774)
**期刊：** Nature communications
**PMID：** 41429774
**DOI：** 10.1038/s41467-025-67144-2

### 第一部分 原文与翻译

**英文原标题：** Structural insights into AQP3 channel closure upon pH and redox changes reveal an autoregulatory molecular mechanism.

> **英文摘要：**
> Regulation of intracellular levels of reactive oxygen species (ROS) remains poorly understood. Aquaporin 3 (AQP3) facilitates the membrane transport of hydrogen peroxide (HO), a key ROS signaling molecule. Here we elucidate the molecular mechanism of AQP3 and show that its regulatory properties are both pH dependent and autoregulated by HO. Using single particle cryo-electron microscopy, we present open and closed conformations of human AQP3. At pH 8.0, the channel adopts an open state, while acidic pH or exposure to HO promotes closure via a large conformational rearrangement of extracellular loop E. These findings reveal a mechanism for autoregulation of HO transport and establish AQP3 as a key modulator of redox homeostasis in human pancreatic β-cells.

> **中文摘要：**
> 细胞内活性氧（ROS）水平的调控机制仍然知之甚少。水通道蛋白3（AQP3）可促进过氧化氢（H₂O₂）这一关键ROS信号分子的膜转运。本研究揭示了AQP3的分子机制，并显示其调节特性既依赖于pH，又受H₂O₂的自我调控。通过单颗粒冷冻电镜分析，研究者获得了人AQP3的开放与关闭构象。在pH 8.0时，该通道呈开放状态，而酸性pH或暴露于H₂O₂时，会通过胞外环E的大幅构象重排而促使通道关闭。这些发现揭示了H₂O₂转运的自我调控机制，并确立了AQP3作为人胰岛β细胞氧化还原稳态关键调节因子的角色。

### 第二部分 AI 大师评价

本研究通过冷冻电镜解析了AQP3在不同pH和氧化还原状态下的构象变化，揭示了其对过氧化氢转运的自我调控机制。研究证明酸性条件和H₂O₂的氧化可诱导胞外环E重排导致通道关闭，从而实现对氧化还原状态的反馈调控。该工作首次从结构层面解释了AQP3的双重调控特性，拓展了对细胞ROS平衡与信号调控的理解。其创新之处在于揭示了H₂O₂作为自我调节因子参与AQP3功能调控，局限性则在于需要更多体内数据验证其生理相关性。

---

## 40. 黄病毒E蛋白疫苗的理性设计可优化免疫原性并降低抗体依赖性增强风险

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429771)
**期刊：** Nature communications
**PMID：** 41429771
**DOI：** 10.1038/s41467-025-67447-4

### 第一部分 原文与翻译

**英文原标题：** Rational design of flavivirus E protein vaccine optimizes immunogenicity and mitigates antibody dependent enhancement risk.

> **英文摘要：**
> Flaviviruses are a family of related viruses that cause substantial global morbidity and mortality. Vaccination against one flavivirus can sometimes exacerbate disease caused by related viruses through antibody-dependent enhancement (ADE) or interfere with the efficacy of subsequent vaccines. To address this challenge, we develop a vaccine strategy by introducing G5C/G102C mutations into the flavivirus envelope (E) glycoprotein. These mutations promote E dimerization through the formation of an inter-chain disulfide bond that conceals the immunodominant and ADE-prone fusion loop epitope (FLE). We validate this design on E proteins from multiple flaviviruses through biochemical, antigenic, and structural analyses. The resulting vaccine candidate, CC_FLE sE, derived from the Zika virus (ZIKV) and formulated with an advanced supramolecular adjuvant, provides significant protection in female mice challenged with ZIKV and prevents ADE caused by a related flavivirus, Dengue virus. In genetically modified mice expressing diverse human immunoglobulin loci, ZIKV CC_FLE sE induces robust neutralizing antibody responses targeting key ZIKV E protein epitopes, including the E-dimer-dependent epitope (EDE), indicating that ZIKV CC_FLE sE can elicit protective antibody responses within the human naïve B cell repertoire. Therefore, CC_FLE sE represents a promising strategy for developing flavivirus vaccines that minimize ADE risk while maintaining high protective efficacy.

> **中文摘要：**
> 黄病毒是一类相关病毒家族，在全球范围内造成显著的发病率和死亡率。针对某一种黄病毒的疫苗接种有时可能通过抗体依赖性增强（ADE）加重由其他相关病毒引起的疾病，或干扰后续疫苗的效力。为应对这一挑战，我们通过在黄病毒包膜（E）糖蛋白中引入G5C/G102C突变，开发了一种疫苗策略。这些突变通过形成链间二硫键促进E蛋白二聚化，从而掩蔽免疫优势且易诱导ADE的融合环表位（FLE）。我们通过生化、抗原性和结构分析在多种黄病毒E蛋白上验证了这一设计。最终得到的疫苗候选物CC_FLE sE来源于寨卡病毒（ZIKV），并与一种先进的超分子佐剂配制，能够在雌性小鼠寨卡病毒攻击模型中提供显著保护，并防止由相关黄病毒登革病毒引起的ADE。在表达多种人免疫球蛋白基因座的转基因小鼠中，ZIKV CC_FLE sE可诱导针对关键ZIKV E蛋白表位（包括E二聚体依赖性表位，EDE）的强效中和抗体反应，表明ZIKV CC_FLE sE能够在人体初始B细胞库中诱导保护性抗体反应。因此，CC_FLE sE代表了一种有前景的黄病毒疫苗开发策略，可在维持高保护效力的同时最大限度降低ADE风险。

### 第二部分 AI 大师评价

本研究旨在通过结构理性设计优化黄病毒E蛋白疫苗的安全性与免疫原性。作者引入关键二硫键形成突变以稳定E蛋白二聚体，从而遮蔽易引发ADE的融合环表位。经多层次实验验证，该疫苗在动物模型中显示出良好的保护效果并避免ADE发生，尤其对寨卡病毒表现出显著免疫防护。该策略为黄病毒疫苗设计提供了新思路，其创新点在于结构导向的免疫优化，但仍需在人类临床层面进一步验证长期安全性与交叉保护效果。

---

## 41. Capicua 调控出生后海马中 Cajal-Retzius 细胞的生存。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429770)
**期刊：** Cell death & disease
**PMID：** 41429770
**DOI：** 10.1038/s41419-025-08206-7

### 第一部分 原文与翻译

**英文原标题：** Capicua regulates the survival of Cajal-Retzius cells in the postnatal hippocampus.

> **英文摘要：**
> Programmed cell death is crucial for organ morphogenesis and tissue homeostasis. Understanding programmed cell death in the developing brain is essential for comprehending both normal brain development and neurological disorders. In this study, we utilize Cajal-Retzius (CR) cells, transient neurons that populate the embryonic cortex and are predominantly eliminated in early postnatal stages, as a model to investigate the regulation of programmed cell death. While many CR cells typically undergo postnatal cell death, some persist into adulthood in the hippocampus, influencing local circuits and behaviors. Here, we show that the loss of capicua (CIC), a transcriptional repressor implicated in a rare neurodevelopmental syndrome and multiple cancers, results in aberrant survival of CR cells in the adult hippocampus. Altered cell survival is mediated by the cell-autonomous function of CIC in hippocampal CR cells. Surprisingly, the atypical persistence of CR cells following CIC loss does not impact hippocampal-dependent behaviors or susceptibility to kainic acid-induced seizures. Single-cell transcriptomic analysis unveils previously unrecognized heterogeneity among hippocampal CR cells and suggests a role of CIC in repressing Fgf1 expression. Additionally, we reveal that FGF1 and BCL2 serve as pivotal regulators enhancing CR cell survival in the postnatal hippocampus. Our findings shed light on a previously unacknowledged role of CIC upstream of FGF signaling and elucidate the apoptosis mechanism governing developmental programmed CR cell death.

> **中文摘要：**
> 程序性细胞死亡对于器官形态发生和组织稳态具有至关重要的作用。理解发育中脑内的程序性细胞死亡对于揭示正常脑发育及神经系统疾病的机制至关重要。在本研究中，我们利用 Cajal-Retzius（CR）细胞这一模型进行研究。这些细胞是存在于胚胎皮层的短暂神经元，主要在出生后早期阶段被清除。虽然大多数 CR 细胞通常在出生后经历细胞死亡，但仍有部分细胞在海马中持续存活至成年期，进而影响局部神经回路及行为表现。我们发现，capicua（CIC）这一转录抑制因子（一种与罕见神经发育综合征和多种癌症相关的蛋白）的缺失，会导致成年海马中 CR 细胞的异常存活。这种细胞存活变化由 CIC 在海马 CR 细胞中的细胞自律性功能介导。出乎意料的是，CIC 缺失后 CR 细胞的异常持续存在并未影响依赖海马的行为表现或对海人酸诱导的癫痫发作易感性。单细胞转录组分析揭示了海马 CR 细胞先前未被识别的异质性，并提示 CIC 在抑制 Fgf1 表达中发挥作用。此外，我们还发现 FGF1 和 BCL2 是促进出生后海马 CR 细胞存活的重要调控因子。我们的研究揭示了 CIC 在 FGF 信号通路上游的先前未被认识的作用，并阐明了调控 CR 细胞发育性程序性死亡的凋亡机制。

### 第二部分 AI 大师评价

该研究探讨了转录抑制因子 Capicua（CIC）在出生后海马 Cajal-Retzius 细胞生存中的调控机制，揭示其通过细胞自律性途径维持细胞命运平衡。作者利用单细胞转录组学揭示了 CR 细胞的异质性，并发现 CIC 可通过抑制 Fgf1 的表达影响 FGF 信号及下游凋亡通路。研究还指出 FGF1 和 BCL2 是促进 CR 细胞存活的关键因子，拓展了对神经发育期细胞死亡调控机制的理解。该成果在连接发育神经生物学与疾病机制方面具有创新性，但其生理功能和病理意义仍需进一步研究。

---

## 42. 利用单域抗体靶向固有无序核蛋白1（NUPR1）可在体内缓解三阴性乳腺癌（TNBC）的进展。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429768)
**期刊：** Cell death & disease
**PMID：** 41429768
**DOI：** 10.1038/s41419-025-08332-2

### 第一部分 原文与翻译

**英文原标题：** Targeting intrinsically disordered nuclear protein 1 (NUPR1) with single-domain antibodies alleviates triple-negative breast cancer (TNBC) progression in vivo.

> **英文摘要：**
> Triple-negative breast cancer (TNBC) is a highly aggressive subtype that currently lacks effective targeted therapies. Transcriptional co-regulator nuclear protein 1 (NUPR1) has been identified as a key stress-adaptive disordered protein that promotes tumor progression and therapy-induced resistance. In this study, we developed a robust high-throughput platform integrating in situ proximity ligation assay followed by DNA sequencing (isPLA-seq), NanoBiT assays, and C-degron degradation validation to screen for functional single-domain antibodies (sdAbs) targeting NUPR1. Consequently, sdAb#07.81 emerged as a lead candidate, demonstrating strong binding affinity and the ability to degrade endogenous NUPR1 in TNBC cells. Functional assays confirmed that sdAb#07.81 suppressed TNBC cell growth, induced premature senescence, and derepressed ferroptosis. In vivo validation using a 4T1 cell-derived fully immunocompetent murine model further established its therapeutic efficacy, with significant reductions in tumor size, NUPR1 expression, and cell proliferation. These findings highlight sdAb#07.81 as a promising therapeutic agent and validate the platform's effectiveness for addressing intracellular disordered targets like NUPR1. This work underscores the potential of sdAbs as a cancer therapeutic and provides a foundation for advancing sdAb#07.81 into preclinical and clinical development to address the critical unmet needs of TNBC treatment.

> **中文摘要：**
> 三阴性乳腺癌（TNBC）是一种高度侵袭性的亚型，目前缺乏有效的靶向治疗手段。转录共调节因子核蛋白1（NUPR1）被确定为一种关键的应激适应性无序蛋白，能够促进肿瘤进展并介导治疗诱导的耐药性。在本研究中，我们建立了一个稳健的高通量筛选平台，结合原位邻近连接检测后续DNA测序（isPLA-seq）、NanoBiT分析和C-degron降解验证，用于筛选能够靶向NUPR1的功能性单域抗体（sdAbs）。结果显示，sdAb#07.81脱颖而出，表现出较强的结合亲和力，并能够降解TNBC细胞内源性NUPR1。功能实验进一步证实，sdAb#07.81能够抑制TNBC细胞生长，诱导早衰，并解除对铁死亡的抑制。通过采用4T1细胞来源的完全免疫健全小鼠模型进行的在体验证表明，该抗体具有显著的治疗效果，可显著降低肿瘤体积、NUPR1表达水平及细胞增殖。上述结果表明，sdAb#07.81是一种具有潜力的新型治疗剂，同时验证了该筛选平台在研究如NUPR1等细胞内无序靶点方面的有效性。本研究强调了单域抗体作为癌症治疗策略的潜力，并为推动sdAb#07.81进入临床前和临床开发以满足TNBC治疗的关键未满足需求奠定了重要基础。

### 第二部分 AI 大师评价

本研究以NUPR1为靶点，创新性地利用高通量整合平台筛选单域抗体，成功获得可降解内源性NUPR1并抑制TNBC发展的候选抗体sdAb#07.81。研究设计系统，验证了从分子、细胞至动物层面的抗肿瘤效果，体现了对细胞内无序蛋白靶点精准干预的可行性。其创新性在于首次将单域抗体用于无序核蛋白的功能性靶向与降解，为难治性乳腺癌提供了新的治疗思路。未来需进一步评估其药代动力学和安全性，以推动临床转化。

---

## 43. 泛素E3连接酶KPC1通过蛋白酶体介导的ZEB1降解调控间质型转移性黑色素瘤的重编程。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429767)
**期刊：** Cell death & disease
**PMID：** 41429767
**DOI：** 10.1038/s41419-025-08262-z

### 第一部分 原文与翻译

**英文原标题：** Ubiquitin E3 ligase KPC1 governs mesenchymal metastatic melanoma reprogramming via proteasomal degradation of ZEB1.

> **英文摘要：**
> Metastatic melanoma (MM) displays remarkable phenotypic plasticity, allowing tumor cells to transition reversibly between proliferative and mesenchymal (MES)-like states. This dynamic switching is strongly associated with therapeutic resistance and poor prognosis. Although transcriptional and epigenetic mechanisms driving these transitions have been extensively studied, the role of post-translational regulation, particularly the ubiquitin-proteasome system, remains poorly understood. Here, we identify the ubiquitin E3 ligase RNF 123 (KPC1) as a key post-translational suppressor of MES reprogramming in MM. Integrative analyses of bulk and single-cell transcriptomic datasets revealed that KPC1 expression is inversely correlated with the expression of core mesenchymal markers such as ZEB1, CDH2, and AXL, and positively associated with epithelial and melanocytic lineage genes, including CDH1 and MITF. Deconvolution of TCGA-SKCM RNA-seq data confirmed that this inverse correlation is specific to malignant melanoma cells and strongest in tumors enriched for mesenchymal gene signatures. Single-cell trajectory and enrichment analyses further demonstrated that decreasing KPC1 expression accompanies MES-like switch. Mechanistically, KPC1 binds and promotes the ubiquitination and proteasomal-mediated degradation of ZEB1, thereby suppressing cadherin switching and cell motility. Loss of KPC1 in melanoma cells prevented ZEB1 proteasomal-mediated degradation, increased expression of mesenchymal markers, and enhanced MM cells migration. Clinically, low KPC1 protein levels were associated with increased expression of ZEB1 and CDH2 and poorer overall survival. Furthermore, combined assessment of KPC1, ZEB1, and CDH2 expression improved patient stratification, suggesting the potential utility of multi-marker signatures for prognostic modeling. These findings establish KPC1 as a central post-translational regulator of melanoma cell state plasticity through targeted degradation of ZEB1. This study highlights a novel mechanism regulating MES-like transition and highlights KPC1 as a potential theragnostic target in MM.

> **中文摘要：**
> 转移性黑色素瘤（MM）表现出显著的表型可塑性，使肿瘤细胞能够在增殖型和间质样（MES样）状态之间可逆转换。这种动态转换与治疗耐药性和预后不良密切相关。尽管驱动这些转变的转录和表观遗传机制已被广泛研究，但翻译后调控，尤其是泛素-蛋白酶体系统的作用仍了解不足。在本研究中，我们鉴定出泛素E3连接酶RNF123（又称KPC1）是MM中抑制MES重编程的关键翻译后调控因子。整合的整体及单细胞转录组分析显示，KPC1的表达与核心间质标志物ZEB1、CDH2和AXL的表达呈负相关，而与上皮及黑色素细胞谱系相关基因（如CDH1和MITF）的表达呈正相关。对TCGA-SKCM RNA测序数据的去卷积分析证实，这种负相关关系特异性地存在于恶性黑色素瘤细胞中，并且在富含间质基因特征的肿瘤中最为显著。单细胞轨迹及富集分析进一步表明，KPC1表达的降低伴随MES样状态的转变。在机制上，KPC1可结合并促进ZEB1的泛素化及蛋白酶体介导的降解，从而抑制钙黏蛋白转换及细胞运动。缺失KPC1的黑色素瘤细胞中，ZEB1的蛋白酶体降解受阻，间质标志物表达升高，且MM细胞迁移能力增强。在临床上，低水平的KPC1蛋白与ZEB1和CDH2的高表达及较差的总体生存相关。此外，联合评估KPC1、ZEB1和CDH2的表达可改进患者分层，提示多标志物特征在预后模型中的潜在应用价值。这些发现确立了KPC1通过特异性降解ZEB1而成为调控黑色素瘤细胞状态可塑性的核心翻译后调节因子。本研究揭示了一种调控MES样转变的新机制，并提示KPC1可作为MM的潜在治疗及诊断靶点。

### 第二部分 AI 大师评价

该研究揭示了KPC1作为翻译后调控因子在抑制黑色素瘤间质样重编程中的关键作用，阐明了其通过泛素化并促进ZEB1蛋白降解的机制。研究结合大规模转录组与单细胞分析，系统揭示了KPC1在表型转换中的动态关联。结果不仅深化了对黑色素瘤可塑性及耐药机制的理解，也为预后分层和治疗靶点提供了新的研究方向。其创新性在于首次将KPC1确立为ZEB1降解的直接调控者，但仍需进一步验证其在体内模型中的治疗可行性。

---

## 44. 抑制 mTORC2 通过激活 STAT1 并增强抗 PD-L1 治疗反应来减少肿瘤负担

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429766)
**期刊：** Cell death & disease
**PMID：** 41429766
**DOI：** 10.1038/s41419-025-08367-5

### 第一部分 原文与翻译

**英文原标题：** mTORC2 inhibition reduces tumor burden via STAT1 activation and enhanced response to anti-PD-L1 therapy.

> **英文摘要：**
> Although melanoma treatment has progressed considerably in recent years, increasing patient response rates remains a significant challenge. The interferon pathway is known to promote immune recognition, but its sustained activation can contribute to adaptive immune exhaustion. In this study, we demonstrate that myeloid-specific deletion of Rictor in a mouse melanoma model enhances STAT1 signaling while reducing PD-L1 expression. Furthermore, IFN-γ-activated macrophages inhibited melanoma growth in a human skin organoid model. Notably, in vivo inhibition of AKT, in conjunction with anti-PD-L1 therapy, suppressed tumor progression. Mechanistically, we identified IFN-γ-mediated downregulation of IGF-1 as a key event during inflammation, and showed that supplementation with recombinant IGF-1 dampens STAT1 activation. Our findings reveal that targeting the Rictor-AKT axis induces a dual effect - boosting pro-inflammatory signaling while downregulating immunosuppressive factors such as PD-L1 and IGF-1. These results support the potential of AKT inhibitors to enhance the efficacy of immune checkpoint therapies in melanoma patients.

> **中文摘要：**
> 尽管近年来黑色素瘤的治疗已取得显著进展，但提高患者的应答率仍是一项重大挑战。干扰素通路已知可促进免疫识别，但其持续激活可能导致适应性免疫耗竭。在本研究中，我们证明了在小鼠黑色素瘤模型中，髓系特异性敲除 Rictor 可增强 STAT1 信号传导并降低 PD-L1 表达。此外，IFN-γ 激活的巨噬细胞在人体皮肤类器官模型中抑制了黑色素瘤的生长。值得注意的是，在体内联合使用 AKT 抑制剂与抗 PD-L1 疗法可抑制肿瘤进展。从机制上看，我们发现 IFN-γ 介导的 IGF-1 下调是炎症反应中的关键事件，并显示补充重组 IGF-1 会抑制 STAT1 激活。我们的研究结果揭示，靶向 Rictor-AKT 轴可产生双重效应——既增强促炎信号传导，又下调 PD-L1 和 IGF-1 等免疫抑制因子。这些结果支持 AKT 抑制剂在提高黑色素瘤患者免疫检查点治疗效果方面的潜力。

### 第二部分 AI 大师评价

本研究探讨了通过抑制 mTORC2（特别是 Rictor-AKT 轴）来增强免疫治疗效果的新机制。研究者利用小鼠模型和人类皮肤类器官模型，揭示 Rictor 缺失可上调 STAT1 信号、降低 PD-L1 与 IGF-1，从而促进抗肿瘤免疫反应。联合 AKT 抑制与抗 PD-L1 治疗显著抑制了肿瘤进展，显示出协同疗效。该工作系统阐明了炎症-代谢通路在免疫调控中的关键联系，具有显著的创新性，但临床转化仍需进一步验证。

---

## 45. 肿瘤中自然杀伤细胞的多维可塑性

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429765)
**期刊：** Cell death & disease
**PMID：** 41429765
**DOI：** 10.1038/s41419-025-08361-x

### 第一部分 原文与翻译

**英文原标题：** Multidimensional plasticity of natural killer cells in tumours.

> **英文摘要：**
> Natural killer (NK) cells exhibit remarkable adaptability within the tumour microenvironment (TME), where dynamic shifts in phenotype, function and metabolism govern their dual roles in antitumour immunity and tumour immune evasion. In the TME, NK cells undergo receptor remodelling, which is characterised by upregulated inhibitory signals and suppressed activating receptors, leading to the formation of dysfunctional subsets, such as exhausted TIM-3⁺ NK cells or tissue-resident CD49a⁺ populations. Immunosuppressive factors within the TME drive a transition from cytotoxic activity to regulatory or senescent-like states, impairing tumour surveillance. Metabolic reprogramming further compromises NK cell effector functions, as nutrient deprivation and metabolic byproducts disrupt energy pathways and suppress immune responses. Therapeutic strategies targeting this plasticity include engineered natural killer (NK) cells with enhanced specificity, metabolic restoration approaches and microenvironment-modulating interventions. However, challenges persist because of TME heterogeneity and persistent dysfunctional states. Understanding these adaptive mechanisms provides a framework for developing NK cell-based therapies that leverage plasticity to counteract tumour resistance.

> **中文摘要：**
> 自然杀伤（NK）细胞在肿瘤微环境（TME）中表现出显著的适应性，在这里，其表型、功能和代谢的动态变化共同调控其在抗肿瘤免疫和肿瘤免疫逃逸中的双重作用。在TME中，NK细胞经历受体重塑，其特征是抑制性信号上调、激活性受体下调，从而形成功能障碍的亚群，如耗竭的TIM-3⁺ NK细胞或组织驻留的CD49a⁺群体。TME中的免疫抑制因子驱动NK细胞从细胞毒活性向调节性或类似衰老的状态转变，削弱了其对肿瘤的监视能力。代谢重编程进一步损害了NK细胞的效应功能，因为营养缺乏和代谢副产物会破坏能量通路并抑制免疫反应。针对这种可塑性的治疗策略包括工程化高特异性的NK细胞、代谢恢复方案以及微环境调节干预。然而，由于TME的异质性及持续的功能障碍状态，相关挑战仍然存在。理解这些适应机制为开发利用NK细胞可塑性以对抗肿瘤耐受的疗法提供了理论框架。

### 第二部分 AI 大师评价

本研究聚焦于肿瘤微环境中自然杀伤细胞的多维可塑性，揭示其表型、受体及代谢层面的动态重塑机制。文章系统总结了NK细胞由细胞毒性向调节或衰老样状态转变的免疫学过程，并讨论了由代谢重编程导致功能衰退的关键环节。作者进一步提出通过工程化NK细胞、代谢恢复及微环境调控等策略应对其功能障碍的可行思路。研究的创新性在于整合了多层次的可塑性视角，为基于NK细胞的肿瘤免疫治疗提供了新的思路。但其面临的主要局限来自TME的复杂异质性和持续的功能失活状态。

---

## 46. USP7通过稳定并去泛素化KDM4A促进膀胱癌中的化疗耐药和DNA损伤应答。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429764)
**期刊：** Cell death & disease
**PMID：** 41429764
**DOI：** 10.1038/s41419-025-08297-2

### 第一部分 原文与翻译

**英文原标题：** USP7 promotes chemotherapy resistance and DNA damage response through stabilizing and deubiquitinating KDM4A in bladder cancer.

> **英文摘要：**
> Bladder cancer is a common malignancy, and the insensitivity of advanced bladder cancer to cisplatin poses an imminent challenge to treatment. Our study aims to identify novel targets that mediate cisplatin responsiveness in bladder cancer. Accordingly, overexpression of the histone demethylase KDM4A in clinical cohorts was found in association with poor prognosis. Tissue culture and animal tests showed that KDM4A pis ro-proliferative in bladder cancer cells. Using co-immunoprecipitation and mass spectrometry methods, we identified that USP7 is an interacting partners in KDM4A protein complex, in which USP7 catalyzes KDM4A proteins deubiquitination that uncouples the proteasome-dependent degradation. In accordance, a positive correlation between USP7 and KDM4A protein expression was noted in bladder cancer clinical samples. Functional validation tests confirmed that USP7 and KDM4A act complementarily to drive bladder cancer cell proliferation. Importantly, cell and animal assays all evidenced that antagonizing the USP7-KDM4A axis would aggravate cisplatin-induced DNA damage and sensitize cisplatin responsiveness.

> **中文摘要：**
> 膀胱癌是一种常见的恶性肿瘤，而晚期膀胱癌对顺铂的不敏感性构成了治疗中的紧迫挑战。本研究旨在鉴定介导膀胱癌顺铂敏感性的新的靶点。研究发现，在临床队列中组蛋白去甲基化酶KDM4A的过度表达与较差的预后相关。组织培养和动物实验表明，KDM4A在膀胱癌细胞中具有促增殖作用。通过共免疫沉淀和质谱分析方法，我们鉴定出USP7是KDM4A蛋白复合物中的相互作用伙伴，其中USP7催化KDM4A蛋白的去泛素化，从而阻止其经蛋白酶体依赖性的降解。相应地，在膀胱癌的临床样本中观察到USP7与KDM4A蛋白表达呈正相关。功能验证实验证实，USP7和KDM4A协同作用以促进膀胱癌细胞的增殖。更为重要的是，细胞和动物实验均表明，拮抗USP7-KDM4A轴会加剧顺铂诱导的DNA损伤，并增强对顺铂的敏感性。

### 第二部分 AI 大师评价

该研究围绕膀胱癌顺铂耐药机制展开，揭示了去泛素化酶USP7通过稳定KDM4A促进肿瘤细胞的生长和化疗耐受。作者利用临床样本分析、共免疫沉淀、质谱及功能验证实验，系统阐明了USP7-KDM4A轴在DNA损伤应答及药物敏感性中的作用。研究创新性地提出靶向USP7-KDM4A轴有望成为提高顺铂疗效的新策略。其局限性可能在于临床验证样本数量及针对性干预策略的进一步转化研究仍需深入。

---

## 47. 在软组织肉瘤中，Th17样细胞和免疫抑制性巨噬细胞浸润处于不同成熟状态的三级淋巴结构。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429763)
**期刊：** Cell death & disease
**PMID：** 41429763
**DOI：** 10.1038/s41419-025-08376-4

### 第一部分 原文与翻译

**英文原标题：** Th17-like cells and immunosuppressive macrophages infiltrate tertiary lymphoid structures with distinct maturation status in soft-tissue sarcoma.

> **英文摘要：**
> Tertiary lymphoid structures (TLSs) have been associated with favorable clinical outcome and improved responses to immune checkpoint inhibitors in soft-tissue sarcomas (STSs). However, due to their rarity and high heterogeneity, information regarding the mechanisms involved in TLS formation and contribution to antitumor immunity in STS are extremely elusive. To address this gap, we integrated immunohistochemistry and transcriptomic analyses from 31 treatment-naïve STS specimens from an independent cohort of patients with primary or locally recurrent disease. Further validation was conducted using external bulk, single-cell and spatial transcriptomics data from 5 publicly available datasets. We found TLSs to be highly heterogeneous in terms of amount, localization, maturation status and cellular composition, and corroborated previous findings showing that their presence, along with B cells in the STS microenvironment, are good indicators of favorable prognosis. Transcriptomic analysis showed that high expression of germinal center (GC) B cell-related genes was associated with TLS presence and with an upregulation of signatures specific for T helper 17 (Th17) cells in STS and other cancer types. Conversely, genes signatures discriminating for immunosuppressive M2-like macrophages were enriched in tumors with low expression of GC B cell-related genes. Immunohistochemistry showed distinct spatial patterns for Th17-like cells and M2-like macrophages within TLS areas, with IL17A cells predominantly localized within intratumoral mature TLSs, and CD163 macrophages mainly observed in immature TLSs. Integrating these findings, we identified tumors with high expression of GC B cell- and Th17 cell-related signatures together with low fractions of M2-like macrophages, to have superior survival outcomes. Herein, our findings point out to two cellular players (Th17-like cells and M2-like macrophages) with potentially opposite roles in STS-associated TLS formation and maturation, thus providing the basis for future research efforts aiming at the development of therapeutic immunological interventions to enhance TLS-mediated antitumor immunity in STS.

> **中文摘要：**
> 三级淋巴结构（TLSs）在软组织肉瘤（STSs）中与良好的临床结局以及对免疫检查点抑制剂的改善反应相关。然而，由于TLS的稀少性和高度异质性，关于TLS形成机制及其对STS抗肿瘤免疫作用的相关信息仍非常有限。为弥补这一空白，我们整合了来自一项包含31例未经治疗的原发或局部复发STS患者标本的独立队列的免疫组织化学与转录组学分析结果。进一步的验证通过五个公开可用数据库中的总体、单细胞及空间转录组学数据进行。我们发现TLSs在数量、定位、成熟状态和细胞组成方面表现出高度异质性，并证实了先前的研究结果——TLS的存在及其与STS微环境中B细胞的共同出现是良好预后的指标。转录组分析显示，生发中心（GC）B细胞相关基因的高表达与TLS的存在相关，同时伴随着在STS及其他肿瘤类型中辅助性T细胞17（Th17）特异性基因特征的上调。相反，免疫抑制性M2样巨噬细胞相关的基因特征在GC B细胞相关基因低表达的肿瘤中富集。免疫组织化学显示，在TLS区域内，Th17样细胞与M2样巨噬细胞具有截然不同的空间分布模式，其中，IL17A阳性细胞主要定位于肿瘤内成熟的TLS，而CD163阳性巨噬细胞主要出现在未成熟TLS中。综合这些发现，我们确定同时具有高表达GC B细胞与Th17细胞相关基因特征、且M2样巨噬细胞比例较低的肿瘤患者，其生存结局更好。综上所述，本研究揭示了两种可能发挥对立作用的细胞类型（Th17样细胞与M2样巨噬细胞）在STS相关TLS形成与成熟中的重要性，为未来旨在增强TLS介导的抗肿瘤免疫的免疫学治疗干预研究提供了基础。

### 第二部分 AI 大师评价

该研究旨在揭示软组织肉瘤中三级淋巴结构形成及成熟的免疫细胞机制。作者整合免疫组织化学与多种转录组数据，全面分析TLS的异质性与免疫细胞组成。结果显示，Th17样细胞与M2样巨噬细胞在TLS成熟过程中呈现对立作用，高GC B细胞与Th17特征伴随优越预后。研究创新性地识别了TLS成熟的关键免疫参与者，为靶向TLS增强抗肿瘤免疫提供了潜在方向。尽管样本量有限，但结果具有重要的转化意义。

---

## 48. 星形母细胞瘤的分子与临床分层：三种融合基因定义的亚群揭示风险适应性治疗策略。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41429568)
**期刊：** Neuro-oncology
**PMID：** 41429568
**DOI：** 10.1093/neuonc/noaf283

### 第一部分 原文与翻译

**英文原标题：** Molecular and Clinical Stratification of Astroblastomas: Three distinct Fusion-Defined Groups Informing Risk-Adapted Treatment Strategies.

> **英文摘要：**
> BACKGROUND: Astroblastomas are rare brain tumors predominantly affecting children and young adults, for which molecular subtypes and clinical management remain undefined.
> 
> METHODS: We analyzed tumor samples, molecular profiles, and clinical data from 200 patients, classified as "Astroblastoma, MN1-altered" under WHO criteria, using DNA methylation profiling, DNA/RNA profiling/sequencing, and survival analyses.
> 
> RESULTS: DNA methylation analyses identified three groups: Group A (n = 143, characterized by MN1::BEND2 fusions, predominantly supratentorial location, with striking female predominance and favorable survival); Group B (n = 37, epigenetically and transcriptionally closely related to Group A, but characterized by EWSR1::BEND2 fusions, with spinal and infratentorial locations and poor prognosis); and Group C (n = 20, epigenetically and transcriptionally distinct, characterized by MN1::CXXC5 fusions, exclusively supratentorially located, with favorable survival). Progression-free and overall survival were significantly shorter in Group B (5-year PFS 14%; 10-year OS 54%) compared to A (5-year PFS 47%; 10-year OS 89%) and C (5-year PFS 75%; 10-year OS 89%). Radiotherapy improved PFS in Group B (hazard ratio 0.25), while no clear benefit was identified for Group A and C.
> 
> CONCLUSIONS: Astroblastoma, MN1-altered, comprises three molecularly and clinically distinct groups, characterized by different fusion genes, including those without MN1. These new insights, including identification of potential predictive biomarkers like 14q/16q loss, provide a framework for development of risk-stratified therapeutic approaches. Importantly, we identified a molecularly defined high-risk group that benefits from radiation therapy. Our findings redefine Astroblastoma as a molecularly diverse tumor type, propose a refined classification, support the development of risk-adapted therapeutic strategies and provide a rational standard of care.

> **中文摘要：**
> 背景：星形母细胞瘤是一种罕见的脑部肿瘤，主要见于儿童和青年人，其分子亚型与临床管理尚未明确。
> 
> 方法：我们采用DNA甲基化谱分析、DNA/RNA分析测序及生存分析，对根据WHO标准归类为“MN1改变型星形母细胞瘤”的200例患者的肿瘤样本、分子特征和临床资料进行了研究。
> 
> 结果：DNA甲基化分析确定了三种分子群：A组（n=143），特征为MN1::BEND2融合，主要位于幕上区，女性占多数，预后良好；B组（n=37），在表观遗传及转录水平上与A组密切相关，但具有EWSR1::BEND2融合，主要分布于脊髓及幕下区域，预后较差；C组（n=20），在表观遗传及转录层面上与前两组明显不同，特征为MN1::CXXC5融合，仅位于幕上区，生存预后亦良好。与A组（5年无进展生存率47%，10年总生存率89%）及C组（5年无进展生存率75%，10年总生存率89%）相比，B组的无进展生存期和总生存期明显较短（5年无进展生存率14%，10年总生存率54%）。放射治疗可改善B组的无进展生存（风险比0.25），而对A组和C组未观察到明显获益。
> 
> 结论：MN1改变型星形母细胞瘤由三种分子和临床上不同的亚群组成，其特征由不同的融合基因决定，部分病例甚至不含MN1。该研究的新发现——包括潜在预测性生物标志物（如14q/16q缺失）的鉴定——为风险分层治疗策略的建立提供了框架。值得注意的是，研究识别出一个可从放疗中获益的分子定义高风险群体。本研究结果重新定义了星形母细胞瘤的分子异质性，提出了更精细的分类方案，支持风险适应性治疗策略的开发，并为制定合理的标准治疗路径提供依据。

### 第二部分 AI 大师评价

本研究系统地揭示了MN1改变型星形母细胞瘤的分子与临床异质性，通过DNA甲基化及融合基因分析，将患者细分为三种具有不同预后的亚型。研究发现EWSR1::BEND2融合相关的B组为高风险群体且对放疗敏感，具有重要临床指导意义。其创新性在于提出了融合基因驱动的重新分类模型，为风险分层治疗提供依据。局限性在于尚需多中心验证和对潜在分子机制的进一步探索。

---

## 49. 基于分相变异支持的循环肿瘤DNA作为大B细胞淋巴瘤一线治疗后预后生物标志物：DIRECT研究的发现

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41428995)
**期刊：** Journal of clinical oncology : official journal of the American Society of Clinical Oncology
**PMID：** 41428995
**DOI：** 10.1200/JCO-25-01587

### 第一部分 原文与翻译

**英文原标题：** Phased Variant-Supported Circulating Tumor DNA as a Prognostic Biomarker After First-Line Treatment in Large B-Cell Lymphoma: Findings From the DIRECT Study.

> **英文摘要：**
> PURPOSE: Circulating tumor DNA (ctDNA) is emerging as a promising tool to monitor treatment response in large B-cell lymphoma (LBCL). Tracking tumor-specific phased variants (PVs) allows ultrasensitive detection of minimal residual disease (MRD) that may enhance the accuracy of response assessment. Previous studies have been constrained by small cohort size, retrospective design, or assays limited to a single commercial provider.
> 
> PATIENTS AND METHODS: DIRECT was a prospective, multisite study evaluating the utility of ctDNA in patients with LBCL. We developed a lymphoma-customized, open-source, ctDNA assay and pipeline that captured hundreds of PVs per patient. Using landmark analysis, we evaluated the prognostic impact of PV-supported MRD at the end of first-line therapy (EoT).
> 
> RESULTS: EoT PV-MRD status was available for 155 patients. After a median of 24.5 months, 2-year time to tumor progression (TTP) for patients with detectable versus undetectable PV-MRD was 42% versus 95%, respectively ( < .001; hazard ratio [HR], 13.7). When restricted to patients receiving full-dose anthracycline-based immunochemotherapy, 2-year TTP was 45% versus 96%, respectively ( < .001; HR, 15.4), outperforming conventional radiological response assessment (HRs, 6.9 for positron emission tomography  16.9 for PV-MRD). The limit of detection with 95% confidence (LoD95) varied by more than two orders of magnitude across patients, underscoring the need to report patient-specific LoD95. Persistent PV-MRD in the absence of relapse was noted, including three of four patients with transformed follicular lymphoma, highlighting a potential caveat when interpreting positive PV-MRD
> 
> CONCLUSION: EoT PV-MRD enables sensitive and clinically meaningful response assessment in LBCL. It provides independent prognostic information, enhancing EoT response assessment beyond conventional radiologic assessment. Our findings support the incorporation of PV-MRD into clinical trials and routine management of diffuse LBCL.

> **中文摘要：**
> 目的：循环肿瘤DNA（ctDNA）正逐渐成为用于监测大B细胞淋巴瘤（LBCL）治疗反应的有前景工具。追踪肿瘤特异性分相变异（PVs）可实现对微小残留病灶（MRD）的超灵敏检测，从而提高疗效评估的准确性。以往研究受限于队列规模较小、回顾性设计或检测方法依赖于单一商业供应商。
> 
> 患者与方法：DIRECT研究是一项前瞻性、多中心研究，用以评估ctDNA在LBCL患者中的应用价值。我们开发了一个针对淋巴瘤定制的开源ctDNA检测及分析流程，每位患者可捕获数百个PVs。通过里程碑分析，我们评估了一线治疗结束时（EoT）由PVs支持的MRD对预后的影响。
> 
> 结果：共有155名患者获得了EoT PV-MRD状态数据。中位随访24.5个月后，可检测与不可检测PV-MRD患者的2年肿瘤进展时间（TTP）分别为42%与95%（P < .001；风险比[HR] 13.7）。在仅限接受足量蒽环类免疫化疗的患者中，2年TTP分别为45%与96%（P < .001；HR 15.4），其预后区分能力优于常规影像学反应评估（HR分别为6.9用于正电子发射断层扫描，16.9用于PV-MRD）。不同患者的95%置信检测限（LoD95）可相差两个数量级以上，表明需报告个体化的LoD95。在无复发情况下仍存在持续的PV-MRD，包括4例转化性滤泡性淋巴瘤患者中的3例，提示解释阳性PV-MRD结果时应谨慎。
> 
> 结论：EoT PV-MRD能够在LBCL中实现敏感且具有临床意义的疗效评估。其提供了独立的预后信息，增强了一线治疗结束时较传统影像学更精确的反应评估。本研究结果支持将PV-MRD纳入弥漫性大B细胞淋巴瘤的临床试验与常规管理流程中。

### 第二部分 AI 大师评价

本研究通过DIRECT前瞻性多中心试验验证了基于分相变异支持的ctDNA在LBCL一线治疗后作为预后生物标志物的潜力。研究自建了开源检测体系，显著提高了MRD检测的灵敏性和独立预后价值。结果表明，EoT PV-MRD阳性与差的长期疗效密切相关，优于常规影像学评估。其创新性在于首创大样本、去商业依赖的ctDNA分相检测系统，但仍需在转化性淋巴瘤和假阳性解释方面进一步验证。

---

## 50. 心脏肿瘤学临床试验的挑战：在代替终点间导航并识别晚期心血管并发症高风险患者。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41428797)
**期刊：** Circulation
**PMID：** 41428797
**DOI：** 10.1161/CIRCULATIONAHA.125.077629

### 第一部分 原文与翻译

**英文原标题：** Challenges of Clinical Trials in Cardio-Oncology: Navigating Surrogate Outcomes and Identifying Patients at Risk of Late Cardiovascular Complications.

> **英文摘要：**
> No abstract available.

> **中文摘要：**
> 暂无摘要。

### 第二部分 AI 大师评价

本文着重讨论在心脏肿瘤学临床试验设计与实施中所面临的关键挑战，尤其是如何选取合适的代替终点以补偿长期随访的困难，并识别易发生晚期心血管并发症的患者人群。研究旨在推动心血管安全性在肿瘤治疗评估中的系统化整合。虽缺摘要，但从标题可推断其创新在于跨领域研究方法论的探讨，而局限性可能在于实践层面的证据尚不充分。

---

速递结束，祝您工作愉快！