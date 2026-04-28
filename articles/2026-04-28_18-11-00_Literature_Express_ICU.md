# 2026年4月29日 - 专业文献速递

本期速递为您整理了最新的科研文献及AI评价，每一篇文献都包含了详细的元数据、原文摘要、中文翻译和AI的专业点评，敬请参考。

---

## 1. 上皮SLC39A1通过锌介导的自噬转录激活预防雄性小鼠急性肺损伤

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/42045244)
**期刊：** Nature communications
**PMID：** 42045244
**DOI：** 10.1038/s41467-026-72403-x

### 第一部分 原文与翻译

**英文原标题：** Epithelial SLC39A1 prevents acute lung injury through zinc-mediated transcriptional activation of autophagy in male mice.

> **英文摘要：**
> Zinc transporters regulate intracellular zinc homeostasis, but their role in acute lung injury (ALI) or acute respiratory distress syndrome (ARDS) remains underexplored. Here, we show that the zinc transporter SLC39A1 is highly upregulated in alveolar type II (AT2) cells from male murine ALI models and patients with ARDS. AT2-specific Slc39a1 deletion or zinc chelation exacerbates lung injury, whereas overexpression or zinc supplementation attenuates it. Notably, zinc supplementation fails to rescue Slc39a1-deficient mice, indicating SLC39A1 governs zinc uptake to control ALI. Zinc likely directly binds to and activates TFEB, TFE3, and MITF, inducing transcriptional activation of autophagy to eliminate damaged mitochondria and suppress apoptosis/pyroptosis in AT2 cells. Lc3b- or Tfe3-deficient mice show heightened lung injury, which remain unmitigated by zinc supplementation. Importantly, administration of AAV-shLc3b to AT2 Slc39a1-deficient mice did not further aggravate lung injury beyond that caused by either intervention alone. This epistatic relationship places SLC39A1 upstream of autophagy activation within a linear pathway. Collectively, we define an essential role for epithelial SLC39A1 in host defense against ALI/ARDS, which is mediated by a protective zinc-autophagy axis.

> **中文摘要：**
> 锌转运体调节细胞内锌稳态，但其在急性肺损伤（ALI）或急性呼吸窘迫综合征（ARDS）中的作用仍有待深入研究。在此，我们展示了在雄性小鼠ALI模型和ARDS患者的肺泡II型（AT2）细胞中，锌转运体SLC39A1表达显著上调。AT2特异性Slc39a1缺失或锌螯合会加剧肺损伤，而过表达或补充锌则能减轻损伤。值得注意的是，补充锌无法挽救Slc39a1缺陷小鼠，这表明SLC39A1通过控制锌吸收来调节ALI。锌可能通过直接结合并激活TFEB、TFE3和MITF，诱导自噬的转录激活，从而清除受损线粒体并抑制AT2细胞中的细胞凋亡/焦亡。Lc3b或Tfe3缺陷小鼠表现出更严重的肺损伤，且补充锌无法缓解。重要的是，对AT2 Slc39a1缺陷小鼠施用AAV-shLc3b并未在单一干预引起的损伤基础上进一步加剧肺损伤。这种上位性关系表明，在一条线性通路中，SLC39A1位于自噬激活的上游。总之，我们阐明了上皮SLC39A1在宿主防御ALI/ARDS中的重要作用，该作用由受保护的“锌-自噬”轴介导。

### 第二部分 AI 大师评价

该研究深入探讨了锌转运体SLC39A1在急性肺损伤（ALI/ARDS）中的关键保护作用。通过一系列严谨的体内外实验，揭示了SLC39A1在肺泡II型细胞中通过介导锌离子吸收，进而转录激活TFEB/TFE3/MITF并诱导自噬，以此清除受损线粒体并抑制细胞凋亡与焦亡。研究通过上位性分析确立了“SLC39A1-锌-自噬”这一线性的保护性信号轴。这一发现不仅深化了对微量元素稳态在呼吸系统防御机制中的科学认识，也为ALI/ARDS的临床治疗提供了潜在的干预靶点。

---

## 2. 一个用于赋能心血管疾病预测和遗传因素发现的自监督心电图基础模型。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/42045241)
**期刊：** Nature communications
**PMID：** 42045241
**DOI：** 10.1038/s41467-026-72436-2

### 第一部分 原文与翻译

**英文原标题：** A self-supervised electrocardiogram foundation model for empowering cardiovascular disease prediction and genetic factor discovery.

> **英文摘要：**
> Electrocardiogram (ECG) has been widely used in the diagnosis of cardiovascular disease (CVD). Current deep learning methods for CVD prediction using ECG often lack generalizability and interpretability, resulting in limited performance. Here, we have developed a self-supervised Electrocardiogram Large-scale Foundation Model (ECG-LFM) through pre-training over ten million 12-lead ECGs from multiple ECG datasets. To enhance ECG representation, ECG-LFM integrates contrastive learning with masked language modeling in a self-supervised manner, enabling the model to capture both global contextual information and fine-grained patterns within ECG signals. It was fine-tuned to predict eight types of CVDs and achieved an average area under the receiver operating characteristic curve (AUROC) of 0.930 from multiple datasets, which demonstrates improved performance compared to existing methods. The important ECG-LFM derived features (EDFs) are able to represent known CVD biomarkers, indicating the high interpretability of ECG-LFM. Applications of the EDFs in genome-wide association study identified 24 significant single nucleotide polymorphisms (SNPs) (P-value < 5×10, LD r < 0.01) associated with ECG, including 8 novel findings. The genetic causal effects of EDFs on the CVDs were evaluated by Mendelian randomization, indicating 2 CVDs and 4 EDFs having causal relationships. Overall, ECG-LFM provides accurate prediction for CVDs and novel genetic insights for ECG.

> **中文摘要：**
> 心电图（ECG）已广泛用于心血管疾病（CVD）的诊断。当前使用ECG进行CVD预测的深度学习方法通常缺乏泛化性和可解释性，导致性能受限。在此，我们通过对来自多个ECG数据集的超过一千万份12导联ECG进行预训练，开发了一个自监督的心电图大规模基础模型（ECG-LFM）。为增强ECG的表征能力，ECG-LFM以自监督的方式整合了对比学习和掩码语言建模，使模型能够捕捉ECG信号中的全局上下文信息和细粒度模式。该模型经过微调以预测八种类型的CVD，并从多个数据集中获得了0.930的平均受试者工作特征曲线下面积（AUROC），这表明其性能优于现有方法。ECG-LFM衍生的重要特征（EDFs）能够代表已知的CVD生物标志物，表明了ECG-LFM的高度可解释性。将EDFs应用于全基因组关联研究，鉴定出24个与ECG相关的显著单核苷酸多态性（SNPs）（P值<5×10-8, LD r<0.01），其中包括8个新发现。通过孟德尔随机化评估了EDFs对CVD的遗传因果效应，表明2种CVD和4种EDFs之间存在因果关系。总体而言，ECG-LFM为CVD提供了准确的预测，并为ECG提供了新的遗传学见解。

### 第二部分 AI 大师评价

该研究旨在解决当前心电图深度学习模型在心血管疾病（CVD）预测中泛化性与可解释性不足的问题。研究团队通过在千万级心电图数据上进行自监督预训练，创新性地结合对比学习与掩码语言建模，构建了一个大规模基础模型（ECG-LFM）。该模型不仅在多种CVD预测任务上展现了卓越的性能，其衍生的特征还具有良好的生物学可解释性。更具开创性的是，研究将这些深度学习特征与全基因组关联研究及孟德尔随机化分析相结合，成功发现了新的遗传位点和潜在的因果关系，为连接AI模型与遗传学研究提供了范例。

---

## 3. 膳食摄入与支链氨基酸代谢通过KDM4A介导的表观遗传重塑在雄性小鼠中调控肺纤维化。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/42045225)
**期刊：** Nature communications
**PMID：** 42045225
**DOI：** 10.1038/s41467-026-72273-3

### 第一部分 原文与翻译

**英文原标题：** Dietary intake and BCAA metabolism regulate pulmonary fibrosis through KDM4A-mediated epigenetic remodeling in male mice.

> **英文摘要：**
> Idiopathic pulmonary fibrosis is a progressive and fatal disorder characterized by abnormal activation of alveolar fibroblasts. However, the metabolic reprogramming of alveolar fibroblasts during lung injury remains unclear. Here we show that uptake of branched-chain amino acids is increased, whereas their catabolism is significantly impaired in fibrotic lung fibroblasts and mouse lung tissues. Branched-chain amino acids promote lung fibroblast activation and bleomycin-induced lung fibrosis. Genetic inactivation of branched-chain amino acid transaminase 2 exacerbates fibrosis, whereas inhibition of the corresponding transporter SLC7A5 or enhancement of catabolism attenuates pulmonary fibrosis in male mice. Mechanistically, ATF4 and PPARγ regulate the expression of SLC7A5 and BCAA catabolic genes, respectively. We identify KDM4A as a key mediator of the epigenetic regulation of fibrotic genes. Notably, dysregulated BCAA metabolism is associated with disease severity in patients, suggesting that targeting BCAA metabolism may serve as a promising therapeutic strategy for idiopathic pulmonary fibrosis.

> **中文摘要：**
> 特发性肺纤维化是一种以肺泡成纤维细胞异常活化为特征的进展性、致死性疾病。然而，肺损伤过程中肺泡成纤维细胞的代谢重编程机制尚不清楚。在此，我们发现纤维化肺成纤维细胞和小鼠肺组织中支链氨基酸的摄取增加，而其分解代谢则显著受损。支链氨基酸会促进肺成纤维细胞活化和博莱霉素诱导的肺纤维化。支链氨基酸转氨酶2的基因失活会加剧纤维化，而在雄性小鼠中，抑制其相应的转运蛋白SLC7A5或增强其分解代谢则能减轻肺纤维化。从机制上讲，ATF4和PPARγ分别调控SLC7A5和支链氨基酸分解代谢基因的表达。我们确定KDM4A是纤维化基因表观遗传调控的关键介质。值得注意的是，支链氨基酸代谢失调与患者的疾病严重程度相关，这表明靶向支链氨基酸代謝可能成为一种有前景的特发性肺纤维化治疗策略。

### 第二部分 AI 大师评价

本研究旨在探讨膳食摄入与支链氨基酸（BCAA）代谢在肺纤维化进程中的作用及其分子机制。通过结合雄性小鼠模型与细胞实验，研究揭示了BCAA摄取增加而分解代谢受损是促进肺纤维化的关键因素。其核心创新在于，首次阐明了BCAA代谢紊乱通过关键表观遗传调控因子KDM4A介导的机制来驱动纤维化基因的表达，并发现了其与患者疾病严重程度的关联。这些发现不仅深化了对肺纤维化病理生理学的理解，还指明了靶向BCAA代谢通路可能成为一种极具潜力的临床治疗新策略。

---

## 4. 通过校正RNA降解，实现单细胞可变转录起始位点的精准分析。

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/42045202)
**期刊：** Nature communications
**PMID：** 42045202
**DOI：** 10.1038/s41467-026-72298-8

### 第一部分 原文与翻译

**英文原标题：** Accurate profiling of single-cell alternative transcript start sites by correcting RNA degradation.

> **英文摘要：**
> The generation of transcript variants via alternative utilisation of transcription start sites (TSSs) is a pivotal regulatory mechanism in physiological and pathological states. Recent advancements in 5' single-cell RNA sequencing (scRNA-seq) have enabled TSS analysis at the single-cell level. However, RNA degradation leads to non-uniform read coverage, posing a critical challenge that significantly compromises accurate TSS quantification of scRNA-seq data. To address RNA degradation and improve TSS quantification, we develop scATS (single-cell alternative transcription start site) to estimate RNA degradation at both isoform and sample levels, and provide TSS quantification with or without degradation correction. Application of scATS reveals dynamic and context-dependent regulation of TSSs in haematopoiesis and disease, providing additional information on TSS isoforms that aids cell clustering at a finer resolution. Furthermore, we establish a machine-learning pipeline, lung cancer relevance score (LRS), to identify TSSs associated with lung cancer. We analyse TSS isoforms of CCR6, CCR2 and RTKN2 in lung cancer cell lines and confirm that isoforms highly transcribed in lung cancer promote cell proliferation and migration. Combined, we present a robust tool to accurately quantify TSS by accounting for RNA degradation, a common issue that confounds transcript quantification, and experimentally demonstrate the important roles of TSS-mediated gene regulation in tumourigenesis.

> **中文摘要：**
> 通过可变利用转录起始位点（TSSs）生成转录本变体是生理和病理状态下的关键调控机制。5'端单细胞RNA测序（scRNA-seq）的最新进展使得在单细胞水平上进行TSS分析成为可能。然而，RNA降解导致读段覆盖不均一，构成了一个严重影响scRNA-seq数据TSS准确定量的关键挑战。为了解决RNA降解问题并提高TSS定量准确性，我们开发了scATS（单细胞可变转录起始位点）工具，用于在异构体和样本水平上估计RNA降解，并提供经过或未经降解校正的TSS定量结果。scATS的应用揭示了TSS在造血过程和疾病中动态且依赖于具体情境的调控机制，提供了有关TSS异构体的额外信息，有助于在更高分辨率下进行细胞聚类。此外，我们建立了一个机器学习流程——肺癌相关性评分（LRS），以识别与肺癌相关的TSS。我们分析了肺癌细胞系中CCR6、CCR2和RTKN2的TSS异构体，并证实了在肺癌中高表达的异构体能促进细胞增殖和迁移。综上，我们提出了一个通过校正RNA降解（一个干扰转录本定量的常见问题）来精确定量TSS的强大工具，并通过实验证明了TSS介导的基因调控在肿瘤发生中的重要作用。

### 第二部分 AI 大师评价

本研究的核心目的是开发一个名为scATS的计算工具，以解决5' scRNA-seq数据中因RNA降解导致的转录起始位点（TSS）定量不准确的关键技术难题。其主要方法是建立一个能够估计并校正RNA降解影响的模型，并结合机器学习流程（LRS）来识别与肺癌相关的TSS。研究发现，该工具能有效揭示TSS在造血和疾病中的动态调控，并实验性地证实了特定TSS异构体在驱动肺癌细胞增殖和迁移中的作用。这项工作的创新性在于直面并校正了单细胞转录组分析中的一个普遍存在的混杂因素，显著提升了TSS分析的精度和生物学意义的挖掘深度。

---

速递结束，祝您工作愉快！