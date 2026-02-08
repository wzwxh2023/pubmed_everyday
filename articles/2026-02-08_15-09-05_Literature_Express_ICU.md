# 2026年2月8日 - 专业文献速递

本期速递为您整理了最新的科研文献及AI评价，每一篇文献都包含了详细的元数据、原文摘要、中文翻译和AI的专业点评，敬请参考。

---

## 1. 联合噬菌体与抗生素治疗肺炎克雷伯菌所致难治性腹膜透析相关腹膜炎

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41654550)
**期刊：** Nature communications
**PMID：** 41654550
**DOI：** 10.1038/s41467-026-69154-0

### 第一部分 原文与翻译

**英文原标题：** Combined bacteriophage and antibiotic therapy for refractory peritoneal dialysis-related peritonitis caused by Klebsiella pneumoniae.

> **英文摘要：**
> Phage therapy is emerging as a promising alternative to antibiotics for treating various infections. However, there have been no prior studies on using bacteriophages for peritonitis in patients undergoing peritoneal dialysis. This report presents the successful treatment of refractory peritonitis in a 71-year-old male peritoneal dialysis patient using bacteriophages combined with antibiotics. The patient has a history of refractory and repeat peritonitis caused by Staphylococcus haemolyticus, which was resolved through simultaneous catheter replacement (SCR). Subsequently, the patient experiences another episode of refractory peritonitis due to Klebsiella pneumoniae. Although this strain is found to be susceptible to amikacin and imipenem, a 14-day course of treatment with these antibiotics in the abdominal cavity fails to resolve the peritonitis. Combined with antibiotic therapy, the patient is successfully treated with intraperitoneal phage therapy targeting his bacterial isolate. We monitor the longitudinal progression of phage loads, phage-neutralizing antibodies, interleukin-6 levels, and lipopolysaccharide concentrations in the dialysate effluent during the bacteriophage therapy. The combination of a phage cocktail and imipenem (IPM) demonstrates a greater effect in killing bacteria than either treatment alone, which indicates that a synergistic effect exists between the phage cocktail and IPM. Intraperitoneal IPM is discontinued after a 3-week course of treatment. At the same time, oral fluconazole is given to prevent fungal infections. The patient is discharged without any antibiotics. After this round of treatment, the patient remains healthy during the one-month follow-up. Our study suggests that personalized phage therapy combined with sensitive antibiotics can play a significant role in managing refractory peritonitis in patients undergoing peritoneal dialysis, showing promise for future applications.

> **中文摘要：**
> 噬菌体疗法正成为治疗多种感染的一种有前景的抗生素替代方案。然而，此前尚无关于使用噬菌体治疗腹膜透析患者腹膜炎的研究。本报告介绍了一例71岁男性腹膜透析患者，通过联合使用噬菌体和抗生素成功治疗难治性腹膜炎。该患者既往有溶血葡萄球菌引起的难治性、复发性腹膜炎病史，并通过同步导管更换（SCR）得以解决。随后，该患者因肺炎克雷伯菌再次发生难治性腹膜炎。尽管该菌株对阿米卡星和亚胺培南敏感，但在腹腔内使用这些抗生素进行为期14天的治疗未能缓解腹膜炎。在抗生素治疗的基础上，针对其分离菌株进行腹腔内噬菌体治疗，患者获得成功治愈。我们在噬菌体治疗期间，监测了透析流出液中噬菌体载量、噬菌体中和抗体、白细胞介素-6水平和脂多糖浓度的纵向变化。噬菌体鸡尾酒与亚胺培南（IPM）联合使用显示出比单独使用任一疗法更强的杀菌效果，这表明噬菌体鸡尾酒与IPM之间存在协同效应。腹腔内IPM在为期3周的治疗后停用。同时，给予口服氟康唑以预防真菌感染。患者出院时未使用任何抗生素。本轮治疗后，患者在一个月的随访期间保持健康。我们的研究表明，个性化噬菌体疗法联合敏感抗生素可在管理腹膜透析患者的难治性腹膜炎中发挥重要作用，显示出未来的应用前景。

### 第二部分 AI 大师评价

本研究旨在探索噬菌体-抗生素联合疗法在腹膜透析相关难治性腹膜炎中的临床应用。其核心方法是对一例肺炎克雷伯菌感染患者实施腹腔内个性化噬菌体鸡尾酒联合敏感抗生素（亚胺培南）的治疗，并纵向监测多项生物学指标。研究发现，联合疗法表现出协同杀菌效应，成功治愈了常规抗生素治疗失败的病例，且患者短期预后良好。本案例的创新性在于首次将噬菌体疗法应用于腹膜透析腹膜炎这一特定临床场景，并提供了治疗过程中详细的免疫与微生物学动态数据，为未来研究提供了重要参考；其局限性在于仅为单病例报告，结论的普适性有待更大样本的临床研究验证。

---

## 2. 通过基于预训练与微调的小样本学习流程发现靶向鲍曼不动杆菌的抗菌肽。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41654506)
**期刊：** Nature communications
**PMID：** 41654506
**DOI：** 10.1038/s41467-026-69306-2

### 第一部分 原文与翻译

**英文原标题：** Discovery of antimicrobial peptides targeting Acinetobacter baumannii via a pre-trained and fine-tuned few-shot learning-based pipeline.

> **英文摘要：**
> Acinetobacter baumannii, a robust Gram-negative bacterium known for causing nosocomial infections, exhibiting multidrug resistance, and lacking antimicrobial peptides that target it, remains hard to treat. Here, we report a few-shot learning pipeline integrating classification, ranking, and regression modules. Each module is trained via a few-shot learning strategy involving pre-training and multiple fine-tuning steps, incorporating similar and true data for fine-tuning, to identify potent AMPs against Acinetobacter baumannii. This pipeline effectively scans complete libraries of hexapeptides, heptapeptides, and octapeptides (encompassing tens of billions of candidates) despite the extreme scarcity of training data. Results show it discovers AMPs active against Acinetobacter baumannii and Candida albicans, with low off-target toxicity and negligible drug resistance susceptibility. Additionally, EME7(7) controls Acinetobacter baumannii pneumonia in mice without kidney injury, a contrast to the observed effects of polymyxin B. This work provides a paradigm for addressing challenges of limited data availability.

> **中文摘要：**
> 鲍曼不动杆菌是一种强健的革兰氏阴性菌，以引起院内感染、表现出多重耐药性且缺乏靶向它的抗菌肽而闻名，因此仍然难以治疗。在此，我们报告了一种集成分类、排序和回归模块的小样本学习流程。每个模块都通过一种涉及预训练和多个微调步骤的小样本学习策略进行训练，并整合相似数据和真实数据进行微调，以识别针对鲍曼不动杆菌的有效抗菌肽。尽管训练数据极度稀缺，该流程仍能有效扫描完整的六肽、七肽和八肽库（包含数百亿个候选肽）。结果显示，它发现了对鲍曼不动杆菌和白色念珠菌具有活性的抗菌肽，且脱靶毒性低，耐药性倾向可忽略不计。此外，EME7(7)能在不引起肾损伤的情况下控制小鼠的鲍曼不动杆菌肺炎，这与观察到的多粘菌素B的效果形成对比。这项工作为解决数据可用性有限的挑战提供了一个范例。

### 第二部分 AI 大师评价

本研究旨在解决针对多重耐药鲍曼不动杆菌的抗菌肽发现难题。其核心创新在于开发了一个结合分类、排序和回归模块的小样本学习流程，通过预训练与多步微调策略，在训练数据极少的情况下，实现了对数百亿级肽库的高效筛选。研究发现的新型抗菌肽不仅对目标菌有效，且展现出低毒性与低耐药性倾向，其中候选肽EME7(7)在动物模型中显示出优于多粘菌素B的安全性。该方法为数据稀缺场景下的药物发现提供了新范式，但其实际应用效果与泛化能力仍需更广泛的实验验证。

---

## 3. 区室化的支链氨基酸代谢通过UMP-波形蛋白轴调控结直肠癌的播散。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41653924)
**期刊：** Cell metabolism
**PMID：** 41653924
**DOI：** 10.1016/j.cmet.2026.01.007

### 第一部分 原文与翻译

**英文原标题：** Compartmentalized branched-chain amino acid metabolism orchestrates colorectal cancer dissemination via an UMP-vimentin axis.

> **英文摘要：**
> The role of metabolic compartmentalization in cancer metastasis is unexplored. Here, we identified that compartmentalized branched-chain amino acid (BCAA) metabolism modulates colorectal cancer (CRC) metastasis. Cytosolic BCAA transaminase (BCAT1) promotes epithelial-to-mesenchymal transition (EMT) and cancer spread of CRC cells, whereas the mitochondrial isoform (BCAT2) exerted opposite effects. The location of BCAT is critical, as mitochondria-targeted BCAT1 and cytosolic BCAT2 demonstrated opposite functions in EMT and cell migration, compared with their wild-type counterparts. Mechanistically, cytosolic BCAT promotes nitrogen flux from BCAA to glutamate, aspartate, and uridine monophosphate (UMP), whereas mitochondrial BCAT activity diverts nitrogen flux via glutamate dehydrogenase (GDH) to give NH. UMP binds to vimentin and protects it against ubiquitination-proteasome degradation. Dietary BCAA restriction or blockade of UMP biosynthesis impaired cancer spread of BCAT1-high CRC, and BCAT1-to-BCAT2 expression ratio is an independent prognostic factor in CRC and pan-cancer cohorts, highlighting translational relevance of BCAA metabolic compartmentalization in cancer metastasis.

> **中文摘要：**
> 代谢区室化在癌症转移中的作用尚未被探索。本研究揭示了区室化的支链氨基酸（BCAA）代谢调控结直肠癌（CRC）转移。胞质BCAA转氨酶（BCAT1）促进CRC细胞的上皮-间质转化（EMT）和癌症播散，而线粒体亚型（BCAT2）则发挥相反作用。BCAT的定位至关重要，因为线粒体靶向的BCAT1和胞质定位的BCAT2在EMT和细胞迁移中表现出与其野生型对应物相反的功能。从机制上讲，胞质BCAT促进氮流从BCAA流向谷氨酸、天冬氨酸和尿苷一磷酸（UMP），而线粒体BCAT活性则通过谷氨酸脱氢酶（GDH）将氮流转向生成NH。UMP与波形蛋白结合，保护其免受泛素化-蛋白酶体降解。饮食限制BCAA或阻断UMP生物合成可损害BCAT1高表达CRC的癌症播散，并且BCAT1与BCAT2的表达比是CRC及泛癌队列中的一个独立预后因素，这凸显了BCAA代谢区室化在癌症转移中的转化相关性。

### 第二部分 AI 大师评价

本研究旨在探索代谢区室化在癌症转移中的未知作用，聚焦于支链氨基酸代谢。其核心方法是通过对比胞质与线粒体BCAT亚型的功能，并结合基因定位、代谢流分析及体内外模型，揭示了代谢酶亚细胞定位决定其促癌或抑癌功能的机制。研究发现，胞质BCAT1通过驱动氮流合成UMP，进而稳定波形蛋白促进EMT和转移，而线粒体BCAT2则通过不同氮流途径拮抗此过程，并首次提出了BCAT1/BCAT2表达比作为跨癌种的预后标志物。其创新性在于将经典的代谢重编程概念深化至亚细胞区室层面，并建立了从代谢酶定位到下游信号轴（UMP-波形蛋白）的完整机制链条，为靶向代谢区室化治疗转移提供了新思路；局限性在于摘要未提及该机制在其它癌症类型中的普适性验证深度，以及靶向此轴的具体药理策略和潜在毒性。

---

## 4. 对“应用机器学习生存分析预测接受连续性肾脏替代治疗的急性肾损伤患者肾脏疾病进展：一项基于LINKA数据库的分析”的述评

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41653868)
**期刊：** Journal of critical care
**PMID：** 41653868
**DOI：** 10.1016/j.jcrc.2026.155457

### 第一部分 原文与翻译

**英文原标题：** Comment on "Machine learning survival analysis for predicting kidney disease progression in patients with acute kidney injury undergoing continuous kidney replacement therapy: An analysis of the LINKA database".

> **英文摘要：**
> No abstract available.

> **中文摘要：**
> 无摘要。

### 第二部分 AI 大师评价

本文是一篇针对已发表研究的述评文章，其核心目的是对一项应用机器学习生存分析预测连续性肾脏替代治疗患者肾脏结局的研究进行讨论与评价。由于摘要缺失，无法直接获知其具体评价内容。此类述评通常旨在探讨原研究的方法学严谨性、临床应用的可行性、结果的解读或潜在的局限性，从而为该领域提供更深入的见解或引发进一步的学术讨论。其价值在于通过专家视角，促进对新兴研究方法（如机器学习在临床预测中的应用）的理解与审慎评估。

---

## 5. 二肽基肽酶-3预测COVID-19住院患者呼吸结局：一项多中心随机试验的二次分析

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41653867)
**期刊：** Journal of critical care
**PMID：** 41653867
**DOI：** 10.1016/j.jcrc.2026.155478

### 第一部分 原文与翻译

**英文原标题：** Dipeptidyl peptidase-3 to predict respiratory outcomes in patients hospitalized with COVID-19: A secondary analysis of a multicenter randomized trial.

> **英文摘要：**
> No abstract available.

> **中文摘要：**
> 无摘要。

### 第二部分 AI 大师评价

本研究旨在探讨生物标志物二肽基肽酶-3（DPP3）对COVID-19住院患者呼吸结局的预测价值。研究采用二次分析方法，利用一项多中心随机试验的数据集，评估DPP3水平与呼吸结局（如是否需要机械通气）之间的关联。其创新性在于聚焦于DPP3这一相对较新的生物标志物在COVID-19预后评估中的应用，为风险分层提供了潜在工具。然而，作为二次分析，其结论可能受限于原始试验的设计和样本量，且摘要信息缺失，无法评估具体的研究发现和方法学细节。

---

## 6. 同一质粒上bla基因变体的异质多拷贝增强临床肺炎克雷伯菌的进化适应性。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41651860)
**期刊：** Nature communications
**PMID：** 41651860
**DOI：** 10.1038/s41467-026-69266-7

### 第一部分 原文与翻译

**英文原标题：** Heterogeneous multicopy of bla variants on the same plasmid enhances evolutionary adaptability in clinical Klebsiella pneumoniae.

> **英文摘要：**
> Pathogenic bacteria continually evolve under antimicrobial pressure through acquired resistance genes, making it crucial to understand their evolutionary strategies. We identify a clinical Klebsiella pneumoniae isolate resistant to ceftazidime/avibactam (CZA), harboring heterogeneous multicopy bla, among which a bla variant mediates CZA resistance. Both bla and its closely related allele bla are dominant within the clonal population and are located at two loci on the same plasmid, with their proportions shifting under antibiotic pressure. Using experimental and mathematical models, we demonstrate that the heterogeneous arrangement of bla variants on the same plasmid confers greater stability and competitive advantage than that across separate plasmids, particularly during drug switching. Re-analysis of large genomic datasets supports the universality of this phenomenon. Our findings reveal an evolutionary strategy in which β-lactamase genes, through multicopy heterogeneity on a single plasmid, ensure stable inheritance of resistance and enhance bacterial adaptability under fluctuating clinical antibiotic pressures.

> **中文摘要：**
> 病原菌通过获得耐药基因在抗菌压力下持续进化，因此理解其进化策略至关重要。我们鉴定出一株对头孢他啶/阿维巴坦（CZA）耐药的临床肺炎克雷伯菌分离株，其携带异质多拷贝的bla基因，其中一个bla变体介导了CZA耐药。bla及其紧密相关的等位基因bla在克隆群体中占主导地位，并位于同一质粒上的两个位点，其比例在抗生素压力下发生改变。通过实验和数学模型，我们证明bla变体在同一质粒上的异质排列，相较于分布在多个质粒上，能赋予细菌更高的稳定性和竞争优势，尤其是在药物转换期间。对大规模基因组数据的重新分析支持了该现象的普遍性。我们的发现揭示了一种进化策略：β-内酰胺酶基因通过在同一质粒上形成多拷贝异质性，确保了耐药性的稳定遗传，并增强了细菌在波动的临床抗生素压力下的适应性。

### 第二部分 AI 大师评价

本研究旨在探究临床耐药菌应对抗生素压力的进化策略。研究者通过鉴定一株携带异质多拷贝bla基因的肺炎克雷伯菌，结合实验模型、数学模型及大规模基因组数据分析，揭示了同一质粒上bla基因变体的异质多拷贝排列是一种关键的进化适应机制。核心发现是，这种“同质粒异质多拷贝”策略比“多质粒分布”能更稳定地维持耐药性，并在药物转换时提供竞争优势，增强了细菌在动态临床环境中的适应性。该研究的创新性在于从质粒基因排布层面阐明了细菌耐药性稳定维持和快速适应的新机制，具有重要的理论价值；局限性在于主要基于肺炎克雷伯菌和bla基因的案例，其普适性及在其他菌种-耐药基因组合中的具体表现仍需进一步验证。

---

## 7. 微生物群衍生的吲哚-3-丙酸通过调节肠道HMGCS2介导的酮体生成促进黏膜愈合，从而保护机体免受结肠炎侵害。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41651833)
**期刊：** Nature communications
**PMID：** 41651833
**DOI：** 10.1038/s41467-026-69341-z

### 第一部分 原文与翻译

**英文原标题：** Microbiota-derived IPA protects against colitis by regulating intestinal HMGCS2-mediated ketogenesis to facilitate mucosal healing.

> **英文摘要：**
> The gut microbiota sustains intestinal homeostasis, yet how microbial metabolites direct epithelial repair remains unclear. Here we identify indole-3-propionic acid (IPA), a tryptophan-derived bacterial metabolite, as a key regulator of mucosal healing. IPA activates PPARα in intestinal epithelial cells, enhancing transcription of the ketogenic enzyme HMGCS2 and boosting β‑hydroxybutyrate (BHB) production. BHB in turn stimulates LGR5⁺ intestinal stem cells, accelerating epithelial regeneration. Using germ-free models and the IPA‑producer Peptostreptococcus russellii, we show that dietary tryptophan and specific commensals sustain luminal IPA levels, which are critical for recovery in colitis. Restoration of IPA or BHB attenuates inflammation and barrier defects, outlining a microbiota‑metabolite‑stem cell axis that could be therapeutically targeted in inflammatory bowel disease and other barrier disorders.

> **中文摘要：**
> 肠道微生物群维持肠道稳态，但微生物代谢物如何指导上皮修复尚不清楚。本研究鉴定出色氨酸衍生的细菌代谢物吲哚-3-丙酸是黏膜愈合的关键调节因子。IPA激活肠上皮细胞中的PPARα，增强生酮酶HMGCS2的转录并促进β‑羟基丁酸的产生。BHB进而刺激LGR5⁺肠道干细胞，加速上皮再生。通过使用无菌模型和IPA产生菌Peptostreptococcus russellii，我们证明膳食色氨酸和特定的共生菌维持了管腔IPA水平，这对结肠炎的恢复至关重要。恢复IPA或BHB可减轻炎症和屏障缺陷，从而勾勒出一条微生物群‑代谢物‑干细胞轴，该轴可作为炎症性肠病和其他屏障性疾病的治疗靶点。

### 第二部分 AI 大师评价

本研究旨在阐明肠道微生物代谢物在黏膜修复中的具体机制。通过结合无菌动物模型、特定菌株定植及分子生物学手段，研究发现色氨酸代谢物IPA通过激活PPARα/HMGCS2/BHB轴，促进肠道干细胞介导的上皮再生，从而驱动结肠炎后的黏膜愈合。其创新性在于系统解析了从膳食底物、特定菌群、关键代谢物到宿主细胞应答的完整信号通路，为炎症性肠病提供了新的治疗靶点。局限性在于研究主要基于动物模型，该轴在人类疾病中的确切作用及临床转化潜力仍需进一步验证。

---

## 8. 一种基于蒙脱石的肠道原位长效发酵系统可恢复肠道稳态。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41651824)
**期刊：** Nature communications
**PMID：** 41651824
**DOI：** 10.1038/s41467-026-69071-2

### 第一部分 原文与翻译

**英文原标题：** A montmorillonite-based oral fermentation system enables long-lasting in-situ biosynthesis to restore intestinal homeostasis.

> **英文摘要：**
> The disruption of intestinal homeostasis represents a hallmark of different diseases. Here, we report a montmorillonite-based oral fermentation system (MOFS) that achieves long-lasting in-situ preparation of beneficial bioproducts for intestinal homeostasis restoration. MOFS is fabricated by loading metabolic substrates in the lamellar structure of montmorillonite via cation replacement and adsorbing the substrate-related bacteria through electrostatic interactions. The water-impermeable property and mucoadhesive ability of montmorillonite endow MOFS with high oral availability and extended retention in the gut. The continuous release of loaded substrates and the formation of biofilms by carried bacteria enable long-term yet efficient synthesis of beneficial metabolites in the intestine, which comprehensively improve gut microbiota composition, suppress intestinal inflammation, and increase the integrity of the gut barrier. In murine models of imbalanced intestinal homeostasis, MOFS demonstrates superior efficacies by alleviating the associated symptoms, even in comparison to clinical therapeutics.

> **中文摘要：**
> 肠道稳态的破坏是多种疾病的标志。在此，我们报告了一种基于蒙脱石的口服发酵系统（MOFS），该系统能够实现有益生物产物的长效原位制备，以恢复肠道稳态。MOFS的制备方法是通过阳离子置换将代谢底物负载于蒙脱石的层状结构中，并通过静电相互作用吸附与底物相关的细菌。蒙脱石的疏水特性和黏膜粘附能力赋予MOFS较高的口服利用度和在肠道内的延长滞留时间。负载底物的持续释放以及携带细菌形成的生物膜，使得有益代谢物能够在肠道内长期且高效地合成，从而全面改善肠道菌群组成、抑制肠道炎症并增强肠道屏障完整性。在肠道稳态失衡的小鼠模型中，MOFS通过缓解相关症状显示出卓越的疗效，甚至优于临床疗法。

### 第二部分 AI 大师评价

本研究旨在开发一种新型口服递送系统，以解决肠道稳态失衡问题。其核心创新在于利用蒙脱石的层状结构和理化特性，构建了一个集底物负载、细菌吸附、肠道滞留与长效原位发酵于一体的多功能平台。该系统在动物模型中展现出通过调节菌群、抗炎和增强屏障等多重机制恢复肠道稳态的优越潜力，为活菌疗法和肠道疾病治疗提供了新思路。然而，摘要未提及人体试验数据、具体细菌种类或潜在的系统性副作用，其临床转化效果和长期安全性有待进一步验证。

---

## 9. 人脑干白质束的概率映射与自动分割。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41650217)
**期刊：** Proceedings of the National Academy of Sciences of the United States of America
**PMID：** 41650217
**DOI：** 10.1073/pnas.2509321123

### 第一部分 原文与翻译

**英文原标题：** Probabilistic mapping and automated segmentation of human brainstem white matter bundles.

> **英文摘要：**
> Brainstem white matter (WM) bundles are essential conduits for neural signals that modulate homeostasis and consciousness. Their architecture forms the anatomic basis for brainstem connectomics, subcortical circuit models, and deep brain navigation tools. However, their small size and complex morphology, compared to cerebral WM, makes mapping and segmentation challenging in neuroimaging. As a result, fundamental questions about brainstem modulation of human homeostasis and consciousness remain unanswered. We leverage diffusion MRI tractography to create BrainStem Bundle Tool (BSBT), which automatically segments eight WM bundles in the rostral brainstem. BSBT performs segmentation on a custom probabilistic fiber map using a convolutional neural network architecture tailored to detect small anatomic structures. We demonstrate BSBT's robustness across diffusion MRI acquisition protocols with in vivo scans of healthy subjects and ex vivo scans of human brain specimens with corresponding histology. BSBT also detected distinct brainstem bundle alterations in patients with Alzheimer's disease, Parkinson's disease, multiple sclerosis, and traumatic brain injury through tract-based analysis and classification tasks. Finally, we provide proof-of-principle evidence for the prognostic utility of BSBT in a longitudinal analysis of traumatic coma recovery. BSBT creates opportunities for scalable mapping of brainstem WM bundles and investigation of their role in a broad spectrum of neurological disorders.

> **中文摘要：**
> 脑干白质束是调节稳态和意识的神经信号的关键传导通路。其结构为脑干连接组学、皮层下环路模型和深部脑导航工具提供了解剖学基础。然而，与大脑白质相比，其体积小且形态复杂，使得在神经影像学中进行映射和分割具有挑战性。因此，关于脑干调节人体稳态和意识的基本问题仍未得到解答。我们利用弥散磁共振成像纤维束追踪技术，创建了脑干束工具（BSBT），该工具可自动分割头端脑干中的八个白质束。BSBT使用专为检测微小解剖结构而设计的卷积神经网络架构，在定制的概率性纤维图谱上进行分割。我们通过健康受试者的活体扫描和具有相应组织学的人脑标本的离体扫描，证明了BSBT在不同弥散磁共振成像采集协议间的稳健性。BSBT还通过基于纤维束的分析和分类任务，检测到了阿尔茨海默病、帕金森病、多发性硬化症和创伤性脑损伤患者中特异的脑干束改变。最后，我们通过对创伤性昏迷恢复的纵向分析，为BSBT的预后效用提供了原理性证据。BSBT为脑干白质束的可扩展性映射及其在广泛神经系统疾病中的作用研究创造了机会。

### 第二部分 AI 大师评价

本研究旨在解决脑干白质束因体积小、形态复杂而难以在神经影像中精确映射和分割的挑战。其核心方法是开发了基于弥散磁共振纤维束追踪和卷积神经网络的自动化工具BSBT，实现了对头端脑干八个白质束的自动分割。研究发现，BSBT在不同采集协议下均表现稳健，并成功检测到多种神经系统疾病（如阿尔茨海默病、帕金森病）中特异的脑干束改变，初步证明了其在创伤性昏迷预后评估中的潜在价值。创新性在于首次提供了针对脑干白质束的、可扩展的自动化分割工具，为深入研究脑干在稳态、意识及多种疾病中的作用开辟了新途径；局限性在于目前主要针对头端脑干，且其临床预后价值仍需更大规模的纵向研究进一步验证。

---

## 10. 通过小分子调控TFAM抑制干扰素信号通路

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41649246)
**期刊：** eLife
**PMID：** 41649246
**DOI：** 10.7554/eLife.108742

### 第一部分 原文与翻译

**英文原标题：** Suppression of interferon signaling via small-molecule modulation of TFAM.

> **英文摘要：**
> The mitochondrial transcription factor A (TFAM) is essential for mitochondrial genome maintenance. It binds to mitochondrial DNA (mtDNA) and determines the abundance, packaging, and stability of the mitochondrial genome. Because its function is tightly associated with mtDNA, TFAM has a protective role in mitochondrial diseases, and supportive studies demonstrate reversal of disease phenotypes by TFAM overexpression. In addition, TFAM deficiency has been shown to cause release of mtDNA into the cytosol and activation of the cGAS/STING innate immune response pathway. As such, TFAM presents as a unique target for therapeutic intervention, but limited efforts for activators have been reported. Herein, we disclose novel TFAM small-molecule modulators with sub-micromolar activity. Our results demonstrate that these compounds result in an increase of TFAM protein levels and mtDNA copy number. This results in inhibition of a mtDNA stress-mediated inflammatory response by preventing mtDNA escape into the cytosol. Furthermore, we see beneficial effects in cellular疾病 models in which boosting TFAM activity has been advanced as a disease-modifying strategy including improved energetics in MELAS cybrid cells and a decrease of fibrotic markers in systemic sclerosis fibroblasts. These results highlight the therapeutic potential of using small-molecule TFAM activators in indications characterized by mitochondrial dysfunction.

> **中文摘要：**
> 线粒体转录因子A（TFAM）对于线粒体基因组的维持至关重要。它结合线粒体DNA（mtDNA），并决定线粒体基因组的丰度、包装和稳定性。由于其功能与mtDNA紧密相关，TFAM在线粒体疾病中具有保护作用，支持性研究表明通过TFAM过表达可以逆转疾病表型。此外，TFAM缺乏已被证明会导致mtDNA释放到细胞质中并激活cGAS/STING先天免疫反应通路。因此，TFAM成为一个独特的治疗干预靶点，但关于其激活剂的报道有限。在此，我们公开了具有亚微摩尔活性的新型TFAM小分子调节剂。我们的结果表明，这些化合物能提高TFAM蛋白水平和mtDNA拷贝数。这通过阻止mtDNA逃逸到细胞质中，从而抑制了mtDNA应激介导的炎症反应。此外，我们在细胞疾病模型中观察到了有益效果，在这些模型中，增强TFAM活性已被提出作为一种疾病修饰策略，包括改善MELAS胞质杂合细胞的能量代谢以及降低系统性硬化症成纤维细胞的纤维化标志物。这些结果突显了小分子TFAM激活剂在以线粒体功能障碍为特征的适应症中的治疗潜力。

### 第二部分 AI 大师评价

本研究旨在探索通过小分子药物调控线粒体转录因子A（TFAM）来抑制干扰素信号通路，为线粒体功能障碍相关疾病提供新疗法。研究者发现并报道了具有亚微摩尔活性的新型TFAM小分子调节剂，能有效提升TFAM蛋白与mtDNA拷贝数，从而抑制mtDNA应激介导的炎症反应。创新性地在MELAS和系统性硬化症细胞模型中验证了其改善能量代谢和减少纤维化的有益效果，凸显了其作为疾病修饰策略的潜力。然而，研究目前局限于细胞模型，其体内药效、药代动力学特性及潜在脱靶效应仍需进一步探索，这是迈向临床转化前必须解决的关键局限性。

---

## 11. 感染性心内膜炎中基线抗栓治疗与颅内出血风险：一项多中心前瞻性队列研究

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41643743)
**期刊：** Clinical infectious diseases : an official publication of the Infectious Diseases Society of America
**PMID：** 41643743
**DOI：** 10.1093/cid/ciag067

### 第一部分 原文与翻译

**英文原标题：** Baseline Antithrombotic Therapy and Intracranial Hemorrhage Risk in Infective Endocarditis: A Multicenter Prospective Cohort Study.

> **英文摘要：**
> BACKGROUND: Infective endocarditis (IE) carries high morbidity and mortality, largely from neurological complications. The clinical significance of chronic antithrombotic therapy remains uncertain. We assessed whether baseline antithrombotic therapy influences intracranial hemorrhage (ICH) and mortality in left-sided IE. METHODS: We analyzed a prospective multicenter cohort (2008-2018) including all patients with definite left-sided IE. Patients were classified at diagnosis as receiving no therapy (NT), antiplatelet therapy (APT), anticoagulation (AC), or combined therapy (CAT). The primary outcome was 30-day ICH; secondary outcomes included ischemic stroke, embolic events, major bleeding, and all-cause mortality. Multivariable logistic and Cox regression models adjusted for confounders. RESULTS: Among 3,236 patients, 182 (5.6%) developed ICH, with the highest incidence in CAT (9.5%) and AC (6.8%). Compared with NT, baseline AC was independently associated with a higher frequency of ICH (adjusted risk ratio [aRR] 1.83, 95% CI 1.16-2.91), with the highest risk observed in CAT (aRR 2.45, 95% CI 1.55-3.87). APT was not associated with ICH. Ischemic stroke rates were similar across groups. CAT independently predicted higher 1-year死亡率 (adjusted hazard ratio [aHR] 1.21, 95% CI 1.02-1.43). Independent factors associated with ICH were Staphylococcus aureus and Candida spp. IE, extracranial embolism, prior cerebrovascular disease, and septic shock. CONCLUSIONS: These findings highlight the value of baseline antithrombotic exposure, together with microbiologic etiology and prior cerebrovascular disease, for early neurologic risk stratification at the time of IE diagnosis, informing neuroimaging decisions and multidisciplinary discussions involving infectious diseases specialists, neurologist, and cardiac surgeons among other specialists.

> **中文摘要：**
> 背景：感染性心内膜炎（IE）具有高发病率和高死亡率，主要源于神经系统并发症。慢性抗栓治疗的临床意义仍不明确。我们评估了基线抗栓治疗是否影响左侧IE患者的颅内出血（ICH）和死亡率。方法：我们分析了一个前瞻性多中心队列（2008-2018年），纳入了所有明确的左侧IE患者。患者在诊断时被分类为未接受治疗（NT）、抗血小板治疗（APT）、抗凝治疗（AC）或联合治疗（CAT）。主要结局是30天ICH；次要结局包括缺血性卒中、栓塞事件、大出血和全因死亡率。采用多变量logistic回归和Cox回归模型调整混杂因素。结果：在3，236名患者中，182人（5.6%）发生了ICH，其中CAT组（9.5%）和AC组（6.8%）发生率最高。与NT组相比，基线AC与更高的ICH发生率独立相关（调整后风险比[aRR] 1.83， 95% CI 1.16-2.91），其中CAT组风险最高（aRR 2.45， 95% CI 1.55-3.87）。APT与ICH无关。各组间缺血性卒中发生率相似。CAT独立预测更高的1年死亡率（调整后风险比[aHR] 1.21， 95% CI 1.02-1.43）。与ICH相关的独立因素包括金黄色葡萄球菌和念珠菌属IE、颅外栓塞、既往脑血管疾病和脓毒性休克。结论：这些发现强调了基线抗栓暴露情况，结合微生物学病因和既往脑血管疾病，对于IE诊断时进行早期神经系统风险分层具有价值，可为神经影像学决策以及涉及感染病专家、神经科医生和心脏外科医生等多学科讨论提供信息。

### 第二部分 AI 大师评价

本研究通过大型前瞻性队列，明确了基线抗凝及联合抗栓治疗是左侧感染性心内膜炎患者发生颅内出血的独立危险因素，并量化了其风险比。其核心创新在于将药物暴露、病原体类型和患者基础疾病整合，构建了实用的早期神经风险分层框架，直接指导临床影像学检查和多学科协作。然而，作为观察性研究，无法完全排除未测量的混杂因素，且未详细区分不同抗凝药物的风险差异，这是其局限性。

---

## 12. 真菌感染通过有氧糖酵解和一条替代性TCA循环旁路驱动上皮细胞代谢重编程。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41637517)
**期刊：** Science advances
**PMID：** 41637517
**DOI：** 10.1126/sciadv.aea0405

### 第一部分 原文与翻译

**英文原标题：** Fungal infection drives metabolic reprogramming in epithelial cells via aerobic glycolysis and an alternative TCA cycle shunt.

> **英文摘要：**
> -induced immunometabolic changes drive complex responses in immune cells. However, whether and how  causes remodeling of oral epithelial cell (OEC) metabolism is unclear. Here, we use in vitro experiments and patient biopsies to demonstrate that OECs undergo metabolic reprogramming when infected by  independently of candidalysin secretion, increasing glycolysis and decreasing tricarboxylic acid (TCA) cycle activity. Glycolysis and glucose transport inhibition show that these pathways support OEC cytokine release, highlighting the partial control of antifungal epithelial immunity by cellular metabolism. However, glucose supplementation disrupts OEC responses both in vitro and in vivo, suggesting that the fungus benefits from these metabolic shifts and that increased aerobic glycolysis in OECs is detrimental. Genome-scale metabolic modeling predicted a shutdown of the TCA cycle and a previously unidentified role for glutamic-oxaloacetic transaminase 1 (GOT1) in response to , which was subsequently shown to be important for OEC survival during infection. This study reveals a fundamental role for hexose metabolism and identifies a GOT1-mediated TCA cycle shunt in regulating OEC survival and immune responses during mucosal fungal infections.

> **中文摘要：**
> 念珠菌诱导的免疫代谢变化驱动免疫细胞产生复杂反应。然而，念珠菌是否以及如何导致口腔上皮细胞代谢重塑尚不清楚。在此，我们利用体外实验和患者活检组织证明，OECs在感染念珠菌时会发生独立于念珠菌溶血素分泌的代谢重编程，表现为糖酵解增加和三羧酸循环活性降低。糖酵解和葡萄糖转运抑制实验表明，这些通路支持OEC的细胞因子释放，突显了细胞代谢对抗真菌上皮免疫的部分调控作用。然而，补充葡萄糖在体外和体内均会破坏OEC的反应，这表明真菌从这些代谢转变中获益，而OECs中有氧糖酵解的增加是有害的。基因组尺度代谢模型预测了TCA循环的关闭以及谷氨酸-草酰乙酸转氨酶1在应对念珠菌感染中的一个先前未知的作用，后续实验证明GOT1对于感染期间OEC的存活至关重要。本研究揭示了己糖代谢的基础性作用，并鉴定出一条GOT1介导的TCA循环旁路在调控黏膜真菌感染期间OEC存活和免疫反应中的作用。

### 第二部分 AI 大师评价

本研究旨在阐明念珠菌感染如何重塑口腔上皮细胞的代谢。通过结合体外实验、患者活检和基因组尺度代谢建模，研究发现感染诱导了独立于念珠菌溶血素的上皮细胞代谢重编程，其特征是糖酵解增强和TCA循环活性降低。核心创新在于揭示了这种代谢转变的双刃剑效应：它支持上皮细胞的免疫反应，但也可能被真菌利用，并首次鉴定出GOT1介导的替代性TCA循环旁路对于上皮细胞在感染中存活的关键作用。然而，研究主要聚焦于代谢通路本身，对于这些代谢变化如何精确调控下游免疫信号网络的具体分子机制，以及其在其他黏膜部位或不同真菌感染中的普适性，仍有待进一步探索。

---

## 13. 靶向NKG2A抑制性受体的单克隆抗体及双特异性衔接分子的发现与临床前评价

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41637511)
**期刊：** Science advances
**PMID：** 41637511
**DOI：** 10.1126/sciadv.adu0690

### 第一部分 原文与翻译

**英文原标题：** Discovery and preclinical evaluation of monoclonal antibodies and bispecific engagers targeting the NKG2A inhibitory receptor.

> **英文摘要：**
> NK and T cells are key effectors that eliminate cancer cells, but upregulation of the inhibitory receptor NKG2A on these cells attenuates antitumor immune responses. To counteract NKG2A inhibitory signaling, we identified two specific fully human monoclonal anti-NKG2A antibodies that block HLA-E ligand binding. These antibodies activated NK cells and enhanced antibody-dependent cellular cytotoxicity of tumor-targeting IgG1s both in vitro and in vivo. Bispecific engagers (BiNKs), generated by fusing NKG2A antibodies with tumor targeting binders, promoted immune synapse formation and directed cytotoxicity of NK and CD8 T cells toward cancer cells. In a human PBMC-engrafted NSG mouse xenograft lung cancer model, an anti-HER2 × anti-NKG2A BiNK markedly inhibited tumor growth as a monotherapy or in combination with pertuzumab. Cell depletion studies revealed that the BiNK enhanced antitumor activity of both NK and T cells. NKG2A blockade with potent and specific, fully human antibodies and BiNKs show promise for further development as cancer immunotherapeutics.

> **中文摘要：**
> 自然杀伤（NK）细胞和T细胞是清除癌细胞的关键效应细胞，但这些细胞上抑制性受体NKG2A的上调会削弱抗肿瘤免疫反应。为了对抗NKG2A的抑制信号，我们鉴定出两种特异性、全人源的单克隆抗NKG2A抗体，它们能够阻断HLA-E配体结合。这些抗体在体外和体内均能激活NK细胞，并增强靶向肿瘤的IgG1抗体的抗体依赖性细胞介导的细胞毒性作用。通过将NKG2A抗体与肿瘤靶向结合域融合构建的双特异性衔接分子（BiNKs），促进了免疫突触的形成，并引导NK细胞和CD8 T细胞对癌细胞产生定向杀伤作用。在人外周血单个核细胞（PBMC）重建的NSG小鼠肺癌异种移植模型中，一种抗HER2 × 抗NKG2A的BiNK，无论是作为单药治疗还是与帕妥珠单抗联合使用，均显著抑制了肿瘤生长。细胞清除研究表明，该BiNK增强了NK细胞和T细胞的抗肿瘤活性。使用强效、特异性的全人源抗体和BiNKs阻断NKG2A，显示出作为癌症免疫疗法进一步开发的前景。

### 第二部分 AI 大师评价

本研究旨在通过阻断NKG2A-HLA-E抑制轴来增强抗肿瘤免疫。核心方法包括筛选全人源抗NKG2A单抗，并进一步构建靶向NKG2A与肿瘤抗原（如HER2）的双特异性衔接分子（BiNKs）。研究发现，单抗和BiNKs均能有效激活NK/T细胞功能，并在临床前模型中显著抑制肿瘤生长，且BiNKs的疗效依赖于NK和T细胞的共同参与。其创新性在于开发了新型全人源抗体及双特异性分子平台，为克服免疫抑制提供了新策略；局限性在于研究仍处于临床前阶段，其在人体内的安全性、有效性及最佳应用场景（如联合疗法）尚需临床试验验证。

---

速递结束，祝您工作愉快！