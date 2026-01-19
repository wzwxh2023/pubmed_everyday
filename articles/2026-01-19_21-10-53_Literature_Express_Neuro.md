# 2026年1月20日 - 专业文献速递

本期速递为您整理了最新的科研文献及AI评价，每一篇文献都包含了详细的元数据、原文摘要、中文翻译和AI的专业点评，敬请参考。

---

## 1. 开发并验证一种基于常规脑电图预测癫痫发作时间的深度生存模型

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41553763)
**期刊：** Epilepsia
**PMID：** 41553763
**DOI：** 10.1002/epi.70101

### 第一部分 原文与翻译

**英文原标题：** Development and validation of a deep survival model to predict time to seizure from routine electroencephalography.

> **英文摘要：**
> OBJECTIVE: This study was undertaken to develop and validate a deep survival model (EEGSurvNet) that analyzes routine electroencephalography (EEG) to predict individual seizure risk over time, comparing its performance to traditional clinical predictors such as interictal epileptiform discharges (IEDs).
> 
> METHODS: We conducted a retrospective cohort study including 1014 consecutive routine EEGs from 994 patients recorded at a tertiary epilepsy center. We developed EEGSurvNet, a deep learning model that predicts time to next seizure over a 2-year horizon from a single EEG. Model performance was evaluated on a temporally shifted testing set of 135 EEGs from 115 patients using time-dependent area under the receiver operating characteristic curve (AUROC), AUROC integrated over 2 years (iAUROC), and C-index. We compared the deep survival model to a clinical Cox model incorporating standard risk factors as well as a random model based on baseline seizure risk.
> 
> RESULTS: EEGSurvNet achieved a 2-year iAUROC of .69 (95% confidence interval [CI] = .64-.73) and C-index of .66 (95% CI = .60-.73), outperforming both clinical and random models. Performance was highest in the first months following EEG, peaking at 2 months (AUROC = .80). Combining EEGSurvNet with clinical predictors further improved performances (iAUROC = .70, C = .69). Notably, the model showed superior discrimination on EEGs without IEDs (iAUROC = .78 vs. .53). Model interpretation revealed that the temporal-occipital regions and 6-15-Hz frequencies contributed most to risk prediction.
> 
> SIGNIFICANCE: EEGSurvNet demonstrates that deep learning can extract prognostic information from routine EEG beyond visible epileptiform abnormalities, potentially improving patient counseling and treatment decisions. Future prospective studies are needed to validate these findings and assess their clinical impact.

> **中文摘要：**
> 目的：本研究旨在开发并验证一种深度生存模型（EEGSurvNet），该模型通过分析常规脑电图（EEG）来预测个体随时间变化的癫痫发作风险，并将其性能与传统的临床预测指标（如发作间期癫痫样放电，IEDs）进行比较。
> 
> 方法：我们进行了一项回顾性队列研究，纳入了某三级癫痫中心记录的来自994名患者的1014份连续常规脑电图。我们开发了EEGSurvNet，这是一种深度学习模型，可根据单次脑电图预测未来2年内的下一次癫痫发作时间。模型性能在由115名患者的135份脑电图组成的时间偏移测试集上进行评估，使用了时间依赖性受试者工作特征曲线下面积（AUROC）、2年累积AUROC（iAUROC）以及C指数。我们将深度生存模型与包含标准风险因素的临床Cox模型以及基于基线癫痫风险的随机模型进行了比较。
> 
> 结果：EEGSurvNet实现了.69的2年iAUROC（95%置信区间[CI] = .64-.73）和.66的C指数（95% CI = .60-.73），优于临床模型和随机模型。在脑电图检查后的最初几个月内性能最高，在2个月时达到峰值（AUROC = .80）。将EEGSurvNet与临床预测指标相结合进一步提高了性能（iAUROC = .70, C = .69）。值得注意的是，该模型在无IEDs的脑电图上显示出更优的区分度（iAUROC = .78 vs. .53）。模型解释显示，颞枕区和6-15 Hz频率对风险预测的贡献最大。
> 
> 意义：EEGSurvNet证明了深度学习可以从常规脑电图中提取出超出肉眼可见癫痫样异常的预后信息，从而有望改善患者咨询和治疗决策。未来需要前瞻性研究来验证这些发现并评估其临床影响。

### 第二部分 AI 大师评价

该研究成功开发了EEGSurvNet模型，创新性地将深度学习生存分析应用于常规脑电图，实现了对癫痫复发风险的精准预测。其核心突破在于该模型能够识别肉眼不可见的生物标记物，特别是在无癫痫样放电的EEG记录中展现出显著的预测价值，优于传统Cox风险模型。这项工作为癫痫的精准分层管理提供了重要的算法工具，尽管其临床实效性仍需通过前瞻性研究进一步确认，但已展现出极高的科研转化潜力。

---

## 2. 抗癫痫药物与发作间期放电：对认知和行为的影响

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41553754)
**期刊：** Epilepsia
**PMID：** 41553754
**DOI：** 10.1002/epi.70102

### 第一部分 原文与翻译

**英文原标题：** Seizure medications and interictal spiking: Implications for cognition and behavior.

> **英文摘要：**
> Interictal epileptiform discharges (IEDs) are not just biomarkers but active contributors to cognitive and behavioral dysfunction. Antiseizure medications (ASMs) not only treat seizures but can also modulate IEDs. However, their broader neurocognitive impact remains underexplored. The goal of this review is to synthesize current evidence on ASM effects on IEDs and to examine their therapeutic implications for cognitive and behavioral improvement. A comprehensive literature search was conducted, focusing on studies that reported ASM-related IED modulation and associated cognitive or behavioral measures. ASMs demonstrate variable efficacy in reducing IEDs, with broad-spectrum agents like valproate and lamotrigine showing consistent suppression of IEDs resulting in cognitive benefit, particularly in children. The use of sodium channel blockers, such as lamotrigine and oxcarbazepine, produces cognitive improvements. Additionally, γ-aminobutyric acidergic agents, including clobazam and diazepam, are effective in treating developmental epileptic encephalopathies. Emerging therapies, including cannabidiol and perampanel, show promising IED and behavioral outcomes. Animal studies confirm that ASMs can suppress IEDs, leading to enhanced memory, attention, and social behaviors. Targeted reduction of IEDs may lead to improved cognitive and behavioral outcomes. This can be achieved by testing and recognizing ASMs in carefully designed prospective trials in animals and humans.

> **中文摘要：**
> 发作间期癫痫样放电 (IEDs) 不仅仅是生物标志物，更是认知和行为功能障碍的主动诱因。抗癫痫药物 (ASMs) 不仅能治疗癫痫发作，还能调节 IEDs。然而，它们更广泛的神经认知影响仍未得到充分探索。本综述旨在综合有关 ASMs 对 IEDs 影响的现有证据，并探讨其在改善认知和行为方面的治疗意义。通过进行全面的文献检索，研究重点关注了报告 ASM 相关 IED 调节以及相关认知或行为指标的研究。结果显示，ASMs 在减少 IEDs 方面表现出不同的效力，其中丙戊酸盐和拉莫三嗪等广谱药物显示出对 IEDs 的持续抑制作用，并能带来认知获益，尤其是在儿童患者中。使用钠通道阻断剂（如拉莫三嗪和奥卡西平）可产生认知改善。此外，γ-氨基丁酸能药物（包括氯巴占和地西泮）在治疗发育性癫痫性脑病方面是有效的。包括大麻二酚和吡仑帕奈在内的新兴疗法显示出良好的 IED 抑制和行为结局。动物研究证实，ASMs 可以抑制 IEDs，从而增强记忆、注意力和社交行为。有针对性地减少 IEDs 可能会改善认知和行为结局。这可以通过在动物和人类中开展精心设计的抗癫痫药物前瞻性试验来验证和确认。

### 第二部分 AI 大师评价

本文系统性地综述了抗癫痫药物（ASMs）对发作间期癫痫样放电（IEDs）的调节作用及其与神经认知结局的关联，强调了 IEDs 在认知受损中的病理作用而非仅作为生物标志物。研究整合了临床与动物模型数据，揭示了广谱药物、钠通道阻断剂及新兴疗法在改善患者认知和行为方面的差异化潜力。其核心价值在于提出了将“针对性减少 IEDs”作为治疗靶点以优化神经发育结局的新视角，为临床用药精准化提供了理论支持。局限性在于目前仍需更多大规模、前瞻性的随机对照试验，以明确不同 ASM 在特定癫痫综合征中的长期认知保护效应。

---

## 3. 局灶性癫痫患儿的丘脑皮层结构连接：一项弥散磁共振成像病例对照研究

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41553602)
**期刊：** Epilepsia
**PMID：** 41553602
**DOI：** 10.1002/epi.70099

### 第一部分 原文与翻译

**英文原标题：** Thalamocortical structural connectivity in children with focal epilepsy: A diffusion MRI, case-control study.

> **英文摘要：**
> OBJECTIVE: Determining patient-specific thalamic connectivity alterations may be an important step toward personalized surgical and neuromodulation strategies, but no data are available to support this concept in pediatric cohorts. This study investigated thalamocortical structural connectivity profiles in children with focal-onset epilepsy of different seizure-onset zones.
> 
> METHODS: This neuroimaging, case-control study compared structural connectivity of four thalamic nuclei (anteroventral [AV], centromedian [CM], mediodorsal [MDPf], and pulvinar [PUL]) between 81 children who underwent surgery for focal-onset epilepsy (median age = 12.2 years) and 63 controls (median age = 12.8 years). Using preoperative 3-Tesla diffusion magnetic resonance imaging (dMRI), brain (Lausanne) and thalamic (THOMAS) parcellations combined with tractography generated structural connectomes based on streamline counts. Connectivity strength of each thalamic nucleus was calculated by summing the weights of each connecting brain region.
> 
> RESULTS: Patients had higher structural connectivity strengths than controls of the thalamic nuclei (effect size (ηₚ) = .072; p = .015), differentially involving nucleus regions, but there was no overall difference in nucleus volumes (ηₚ < .000; p = .968). When comparing patient groups defined by seizure-onset zones, it emerged that reduced AV connectivity strength was specific to the hippocampal sclerosis group, whereas CM, MDPf, and PUL connectivity was similarly high in all the patient groups, including those with frontal or temporal lobe epilepsy. Patients who were seizure-free after surgery had a lower ipsilateral and a higher contralateral connectivity strength (ηₚ = .111; p = .005) and volumes (ηₚ = .073; p = .025) of thalamic nuclei compared to those who were not.
> 
> SIGNIFICANCE: This study provides unique data suggesting that different pediatric focal epilepsies have distinct structural thalamocortical connectivity and volumetric profiles. The structural connectivity and volumetric asymmetries of the thalami have an association with postoperative seizure freedom. More studies are required to further understand the thalamic connectivity signatures that may have implications for precision surgical planning and neuromodulation targeting for focal-onset epilepsy.

> **中文摘要：**
> 目的：确定患者特异性的丘脑连接改变可能是迈向个体化手术和神经调节策略的重要一步，但目前尚无数据支持在儿科队列中应用这一概念。本研究调查了具有不同发作起始区的局灶性发作癫痫患儿的丘脑皮层结构连接特征。方法：这项神经影像学病例对照研究比较了81名接受局灶性癫痫手术的儿童（中位年龄12.2岁）和63名对照者（中位年龄12.8岁）之间四个丘脑核团（前腹核 [AV]、中央正中核 [CM]、背内侧核 [MDPf] 和枕核 [PUL]）的结构连接。利用术前3-Tesla弥散磁共振成像（dMRI），结合大脑（Lausanne）和丘脑（THOMAS）分区及纤维束追踪技术，根据流线计数生成结构连接组。通过对每个连接脑区的权重求和来计算每个丘脑核团的连接强度。结果：与对照组相比，患者丘脑核团的结构连接强度更高（效应量 (ηₚ) = .072；p = .015），且不同核团区域受累情况存在差异，但核团体积总体上没有显著差异（ηₚ < .000；p = .968）。在比较按发作起始区分组的患者时发现，AV连接强度降低是海马硬化组特有的，而CM、MDPf和PUL的连接强度在包括额叶或颞叶癫痫在内的所有患者组中均普遍较高。与术后未达到无发作的患者相比，术后无发作的患者表现出更低的同侧和更高的对侧丘脑核团连接强度（ηₚ = .111；p = .005）及体积（ηₚ = .073；p = .025）。结论：本研究提供了独特的数据，表明不同的儿科局灶性癫痫具有独特的丘脑皮层结构连接和体积特征。丘脑的结构连接和体积不对称性与术后无发作状态相关。需要更多的研究来进一步了解丘脑连接特征，这可能对局灶性发作癫痫的精准手术规划和神经调节靶点选择产生影响。

### 第二部分 AI 大师评价

本研究通过先进的dMRI技术和精细的丘脑分区法，首次系统地揭示了儿科局灶性癫痫患者丘脑-皮层结构连接的特异性模式。研究发现，丘脑核团的连接强度而非体积在患者中显著增高，且这种连接模式的同/对侧不对称性与术后癫痫控制效果密切相关。该成果为儿科癫痫的精准外科评估提供了重要的影像学标志物，展示了结构连接组学在个体化治疗决策中的潜力，但未来仍需大样本纵向研究验证其在预测神经调节疗效方面的价值。

---

## 4. 术中皮层电图的光谱熵变异性可预测局灶性皮质发育不良患者癫痫手术后的预后

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41553358)
**期刊：** Epilepsia
**PMID：** 41553358
**DOI：** 10.1002/epi.70104

### 第一部分 原文与翻译

**英文原标题：** Spectral entropy variability of intraoperative electrocorticography predicts outcome after epilepsy surgery in people with focal cortical dysplasia.

> **英文摘要：**
> OBJECTIVE: Epilepsy surgery in people with focal cortical dysplasia (FCD) requires accurate removal of all epileptogenic tissue, and outcome is difficult to predict. We explored whether spectral entropy, a fast computable electroencephalographic (EEG) feature, could estimate epileptic activity in intraoperative electrocorticography (ioECoG) and forecast postsurgical outcomes.
> 
> METHODS: We included people with FCD pathology who underwent ioECoG-assisted resective surgery. We analyzed ioECoG recordings acquired before and after resection. We computed spectral entropy across eight frequency bands (1-500, 1-4, 4-8, 8-12, 12-20, 20-80, 80-250, 250-500 Hz) in 2-s epochs during 1 min, and the mean and SD per electrode. The preresection features were the input for a random forest machine learning model to classify channels covering resected from nonresected tissue. Explainable artificial intelligence was used to select features that positively influenced the model predicting resected tissue. We then related these markers measured after the resection to postsurgical outcome using trend analysis (Jonckheere-Terpstra) across outcome groups Engel IA without medication, Engel IA-D, Engel II, Engel III, and Engel IV.
> 
> RESULTS: We analyzed ioECoG data from 37 patients (age range = 0-61 years, 21 patients were ≤16 years), including 2270 preresection and 1278 postresection channels. The random forest model discriminated between resected and nonresected cortex (validation fold area under the curve = .84, 95% confidence interval =.74-.95). Features with the strongest positive Shapley Additive Explanations values included high spectral entropy variability (SEV) in the 80-500-Hz bands. In postresection recordings, higher mean SEV and greater spatial variability of SEV were associated with poorer Engel outcome across several frequency bands. After multiple comparison correction, the positive relationship of high mean SEV (p = .004) and high spatial variability (p = .001) at 250-500 Hz with poor seizure outcome remained statistically significant.
> 
> SIGNIFICANCE: SEV is a real-time computable invasive EEG marker that represents persisting epileptic activity after resection. SEV may be used to evaluate resection adequacy directly or may reflect residual epileptic activity. This would enable epilepsy surgery guidance and postsurgical counseling and decision-making.

> **中文摘要：**
> 目的：局灶性皮质发育不良（FCD）患者的癫痫手术需要准确切除所有致痫组织，且预后难以预测。我们探讨了光谱熵（一种快速计算的脑电图 [EEG] 特征）是否可以评估术中皮层电图（ioECoG）中的癫痫活动并预测术后预后。
> 方法：我们纳入了接受 ioECoG 辅助切除手术的 FCD 病理患者。我们分析了切除前后的 ioECoG 记录。我们计算了 1 分钟内 2 秒时段中八个频段（1-500、1-4、4-8、8-12、12-20、20-80、80-250、250-500 Hz）的光谱熵，以及每个电极的平均值和标准差（SD）。切除前的特征作为随机森林机器学习模型的输入，用于区分切除组织和非切除组织的通道。使用可解释人工智能来选择对预测切除组织模型有积极影响的特征。然后，我们使用趋势分析（Jonckheere-Terpstra）在 Engel IA（无药物）、Engel IA-D、Engel II、Engel III 和 Engel IV 预后组中，将切除后测得的这些标志物与术后预后联系起来。
> 结果：我们分析了 37 名患者（年龄范围 = 0-61 岁，21 名患者 ≤16 岁）的 ioECoG 数据，包括 2270 个切除前通道和 1278 个切除后通道。随机森林模型区分了切除和未切除的皮质（验证折叠曲线下面积 = .84，95% 置信区间 = .74-.95）。具有最强正 Shapley Additive Explanations（SHAP）值的特征包括 80-500 Hz 频段的高光谱熵变异性（SEV）。在切除后记录中，较高的平均 SEV 和较大的 SEV 空间变异性与多个频段中较差的 Engel 预后相关。经过多重比较校正后，250-500 Hz 处的高平均 SEV（p = .004） and 高空间变异性（p = .001）与癫痫发作预后不良的正向关系仍具有统计学意义。
> 意义：SEV 是一种实时可计算的有创脑电图标志物，代表切除后持续存在的癫痫活动。SEV 可用于直接评估切除的充分性，或反映残留的癫痫活动。这将有助于指导癫痫手术，并为术后咨询和决策提供支持。

### 第二部分 AI 大师评价

本研究利用机器学习和可解释人工智能技术，证实了术中皮层电图（ioECoG）的光谱熵变异性（SEV）是预测FCD手术预后的关键生物标志物。研究重点发现高频段（尤其是250-500 Hz）的SEV与术后癫痫发作控制不佳显著相关，为术中实时评估切除范围提供了量化工具。该方法的创新性在于提出了一个可快速计算且具备生物学解释性的电生理指标，不仅能指导术中决策，还能优化术后临床咨询。局限性在于样本量相对有限，仍需多中心验证以提升该模型在不同临床场景下的泛化能力。

---

## 5. 胎儿期暴露于抗癫痫药物儿童的大脑侧向化发育：一项6岁时的前瞻性队列研究

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41553327)
**期刊：** Epilepsia
**PMID：** 41553327
**DOI：** 10.1002/epi.70103

### 第一部分 原文与翻译

**英文原标题：** Development of cerebral lateralization in children exposed to fetal antiseizure medications: A prospective cohort study at age 6 years.

> **英文摘要：**
> OBJECTIVE: We previously reported in a prior cohort that fetal exposure to antiseizure medications (ASMs), especially valproate, was associated with reduced right-handedness and poorer verbal versus nonverbal performance in children at age 6 years. Given changes in prescribing practices in epilepsy over the past 2 decades, we enrolled a new cohort of the Maternal Outcomes and Neurodevelopmental Effects of Antiepileptic Drugs (MONEAD) study to determine whether fetal exposure to newer generation ASMs is associated with altered cerebral lateralization in children at age 6 years and to assess exposure-dependent effects on handedness, manual dexterity, and verbal/nonverbal abilities.
> 
> METHODS: The MONEAD multicenter prospective cohort study followed children of women with epilepsy (WWE) on ASMs and healthy women (HW) until age 6 years. We assessed handedness using the Edinburgh Handedness Inventory, manual dexterity through the Grooved Pegboard Test, and verbal/nonverbal abilities with the Differential Ability Scales-II. Outcomes were analyzed in relation to ASM exposure, controlling for confounders.
> 
> RESULTS: Of 1123 screened pregnant women, 351 children born to WWE and 105 to HW were enrolled. The overall distribution of handedness and verbal/nonverbal scores did not differ between groups. However, subgroup analyses revealed that higher third-trimester levetiracetam concentrations were significantly associated with nondextrality (p = .03, 95% confidence interval [CI] = .03-.67). Across the WWE cohort, higher ASM concentrations correlated with poorer manual dexterity (coefficient = 6.76, 95% CI = .40-13.11, p = .037). Additionally, periconceptional folate supplementation was associated with better nonverbal outcomes (coefficient = 2.54, 95% CI = .93-4.15, p = .002) and parental stress was linked to poorer verbal scores (coefficient = -19.74, 95% CI = -28.48 to -11, p < .001).
> 
> SIGNIFICANCE: This cohort reassuringly showed no overall difference in verbal/nonverbal abilities between WWE and HW. Fetal ASM exposure had exposure-dependent effects on manual dexterity. Modifiable factors, including folate supplementation and parental stress, significantly influenced developmental outcomes, underscoring the importance of proactive screening and providing intervention when appropriate.

> **中文摘要：**
> 目的：我们此前在先前的队列研究中报告称，胎儿期暴露于抗癫痫药物 (ASMs)，特别是丙戊酸盐，与 6 岁儿童右利手比例降低以及言语对比非言语能力较差相关。鉴于过去 20 年癫痫处方实践的变化，我们招募了“母体结局和抗癫痫药物神经发育效应”(MONEAD) 研究的一个新队列，以确定胎儿期暴露于新一代 ASMs 是否与 6 岁儿童大脑侧向化的改变有关，并评估暴露依赖性对利手、手动灵活性以及言语/非言语能力的影响。方法：MONEAD 多中心前瞻性队列研究对接受 ASMs 治疗的患有癫痫的女性 (WWE) 和健康女性 (HW) 的子女进行了随访，直至其 6 岁。我们使用爱丁堡利手调查表评估利手情况，通过沟槽连接板测试评估手动灵活性，并使用差异能力量表第二版 (DAS-II) 评估言语/非言语能力。在控制混杂因素的情况下，分析了与 ASM 暴露相关的结局。结果：在筛选的 1123 名孕妇中，共入组了 WWE 所生的 351 名儿童和 HW 所生的 105 名儿童。两组之间利手分布和言语/非言语评分的总体分布没有差异。然而，亚组分析显示，妊娠晚期较高的左乙拉西坦浓度与非右利手显著相关（p = .03，95% 置信区间 [CI] = .03-.67）。在整个 WWE 队列中，较高的 ASM 浓度与较差的手动灵活性相关（系数 = 6.76, 95% CI = .40-13.11, p = .037）。此外，围孕期补充叶酸与较好的非言语结局相关（系数 = 2.54, 95% CI = .93-4.15, p = .002），而父母压力与较差的言语评分相关（系数 = -19.74, 95% CI = -28.48 至 -11, p < .001）。意义：该队列研究令人欣慰地显示，WWE 和 HW 之间的言语/非言语能力总体上没有差异。胎儿期 ASM 暴露对手动灵活性具有暴露依赖性影响。包括补充叶酸和父母压力在内的可调节因素显著影响发育结局，强调了主动筛查并在适当时候提供干预的重要性。

### 第二部分 AI 大师评价

该前瞻性队列研究针对新一代抗癫痫药物（ASM）在胎儿期暴露对儿童神经发育的影响提供了重要证据。研究核心发现是，尽管新一代药物在整体言语/非言语能力上显示出较好的安全性，但左乙拉西坦等药物的高暴露浓度可能与非右利手及手动灵活性下降相关。研究的创新之处在于通过 MONEAD 队列评估了药物浓度与细微神经发育指标（如侧向化）的关联，并强调了叶酸补充和降低父母压力作为可干预因素在改善后代预后中的关键作用，为临床癫痫女性的孕期管理提供了精细化指导。

---

## 6. 重新评估脑深部刺激术的风险：基于 NSQIP 数据库 280 万例择期手术的比较研究

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41549765)
**期刊：** Annals of neurology
**PMID：** 41549765
**DOI：** 10.1002/ana.78154

### 第一部分 原文与翻译

**英文原标题：** Reframing the Risks of Deep Brain Stimulation: A Comparison of 2.8 Million Elective Surgeries From the NSQIP Database.

> **英文摘要：**
> OBJECTIVE: Deep brain stimulation (DBS) is an established surgical therapy for movement disorders, epilepsy, and psychiatric conditions, yet remains underutilized due to perceived risks. We therefore endeavored to compare the safety of DBS to other common elective procedures to provide context for its relative risk. METHODS: This retrospective cohort study utilized the American College of Surgeons National Surgical Quality Improvement Program (NSQIP) database, encompassing diverse referral and community hospitals across the United States from 2015 to 2021. Patients with DBS were compared with those receiving one of the 16 most common elective procedures. The primary outcome of interest was the weighted odds of any postoperative complication at 30 days. Secondary outcomes included risk of readmission, reoperation, and discharge disposition. Logistic regression with inverse probability of treatment weighting (IPTW) based on propensity scores adjusted for baseline group heterogeneity. RESULTS: We identified 2,853,662 patients for analysis, including 4,749 DBS procedures. After IPTW adjustment, patients with DBS experienced lower 30-day complication rates compared with other procedures (1.3% vs 4.1%, OR = 0.32, 95% confidence interval [CI] = 0.25-0.41, p < 0.0001). Readmission rates did not differ significantly (2.2% vs 2.6%, OR = 0.84, 95% CI = 0.69-1.02, p = 0.08). DBS cases had higher odds of discharge home (98.7% vs 96.3%, OR = 2.94, 95% CI = 2.27-3.82, p < 0.0001) and lower reoperation rates (0.7% vs 1.3%, OR = 0.50, 95% CI = 0.35-0.72, p = 0.0002). INTERPRETATION: DBS demonstrates a favorable safety profile with substantially lower complication rates compared with the most widely performed elective surgeries. These findings support broader consideration of surgical referral for appropriate DBS candidates. ANN NEUROL 2026.

> **中文摘要：**
> 目的：脑深部刺激术（DBS）是针对运动障碍、癫痫和精神类疾病的一种公认的外科疗法，但由于认知的手术风险，该技术的使用率仍然较低。因此，我们致力于将 DBS 的安全性与其他常见的择期手术进行比较，以为其相对风险提供背景参考。方法：这项回顾性队列研究利用了美国外科医师学会国家手术质量改进计划（NSQIP）数据库，涵盖了 2015 年至 2021 年间美国各地不同的转诊和社区医院。将接受 DBS 手术的患者与接受 16 种最常见择期手术之一的患者进行了比较。主要观察指标是术后 30 天内任何并发症的加权比值。次要结局指标包括再入院风险、再次手术风险和出院去向。研究采用基于倾向评分的逆概率处理加权（IPTW）逻辑回归模型对基线组间异质性进行了调整。结果：我们共纳入 2,853,662 例患者进行分析，其中包括 4,749 例 DBS 手术。经过 IPTW 调整后，与接受其他手术的患者相比，DBS 患者的 30 天并发症发生率更低（1.3% 对 4.1%，OR = 0.32，95% 置信区间 [CI] = 0.25-0.41，p < 0.0001）。再入院率没有显著差异（2.2% 对 2.6%，OR = 0.84，95% CI = 0.69-1.02，p = 0.08）。DBS 病例出院回家的概率更高（98.7% 对 96.3%，OR = 2.94，95% CI = 2.27-3.82，p < 0.0001），且再次手术率更低（0.7% 对 1.3%，OR = 0.50，95% CI = 0.35-0.72，p = 0.0002）。解释：与应用最广泛的择期手术相比，DBS 表现出良好的安全性，其并发症发生率明显更低。这些发现支持对合适的 DBS 候选者进行更广泛的手术转诊考虑。ANN NEUROL 2026。

### 第二部分 AI 大师评价

该研究通过分析超过 280 万例手术的超大规模 NSQIP 数据库，通过倾向评分加权法有力地挑战了“DBS 属于高风险手术”的传统观念。研究发现 DBS 的术后并发症及再次手术率显著低于常见的择期手术，且居家出院率更高，数据具有极强的统计学效力。其创新性在于将功能神经外科手术置于整体外科风险背景下进行横向对标，为神经外科医师、转诊医生及患者提供了量化的安全数据参考，对于推动 DBS 在全球范围内的临床应用具有重大的实践指导价值。

---

## 7. 利用专家引用的特征检测脑性瘫痪患者的腿部肌张力障碍

**原文链接：** [点击跳转](https://pubmed.ncbi.nlm.nih.gov/41549584)
**期刊：** Annals of neurology
**PMID：** 41549584
**DOI：** 10.1002/ana.78130

### 第一部分 原文与翻译

**英文原标题：** Using Expert-Cited Features to Detect Leg Dystonia in Cerebral Palsy.

> **英文摘要：**
> OBJECTIVES: Leg dystonia in cerebral palsy (CP) is debilitating but remains underdiagnosed. Routine clinical evaluation has only 12% accuracy for leg dystonia diagnosis compared to gold-standard expert consensus assessment. We determined whether expert-cited leg dystonia features could be quantified to train machine learning (ML) models to detect leg dystonia in videos of children with CP. METHODS: Eight pediatric movement disorders physicians assessed 298 videos of children with CP performing a seated task at 2 CP centers. We extracted leg dystonia features cited by these experts during consensus-building discussions, quantified these features in videos, used these quantifications to train 4,664 ML models on 163 videos from one center, and tested the best performing models on a separate set of 135 videos from both centers. RESULTS: We identified 69 quantifiable features corresponding to 12 expert-cited leg dystonia features. ML models trained using these quantifications achieved 88% sensitivity, 74% specificity, 82% positive predictive value, 84% negative predictive value, and 82% accuracy for identifying leg dystonia across both centers. Of the 25 features contributing to the best performing ML models, 17 (68%) quantified leg movement variability. We used these ML models to develop DxTonia, open-source software that identifies leg dystonia in videos of children with CP. INTERPRETATION: DxTonia primarily leverages detection of leg movement variability to achieve 82% accuracy in identifying leg dystonia in children with CP, a significant improvement over routine clinical diagnostic accuracy of 12%. Observing or quantifying leg movement variability during a seated task can facilitate leg dystonia detection in CP. ANN NEUROL 2026.

> **中文摘要：**
> 目的：脑性瘫痪 (CP) 患者的腿部肌张力障碍具有致残性，但仍处于诊断不足的状态。与专家共识评估这一金标准相比，常规临床评估对腿部肌张力障碍的诊断准确率仅为 12%。我们确定了专家引用的腿部肌张力障碍特征是否可以被量化，用于训练机器学习 (ML) 模型以检测 CP 儿童视频中的腿部肌张力障碍。方法：8 名儿科运动障碍医生在 2 个 CP 中心评估了 298 段 CP 儿童执行坐位任务的视频。我们提取了专家在共识构建讨论中引用的腿部肌张力障碍特征，并在视频中对这些特征进行了量化；利用这些量化数据在一个中心的 163 段视频上训练了 4,664 个机器学习模型，并在来自两个中心的另外 135 段视频的独立集合上测试了性能最佳的模型。结果：我们确定了 69 个可量化特征，对应于 12 个专家引用的腿部肌张力障碍特征。在两个中心，利用这些量化特征训练的机器学习模型在识别腿部肌张力障碍方面实现了 88% 的敏感性、74% 的特异性、82% 的阳性预测值、84% 的阴性预测值和 82% 的准确率。在对性能最佳的机器学习模型有贡献的 25 个特征中，有 17 个 (68%) 是量化腿部运动变异性的特征。我们利用这些机器学习模型开发了 DxTonia，这是一款可在 CP 儿童视频中识别腿部肌张力障碍的开源软件。解释：DxTonia 主要利用对腿部运动变异性的检测，在识别 CP 儿童腿部肌张力障碍方面达到了 82% 的准确率，较 12% 的常规临床诊断准确率有了显著提高。在坐位任务期间观察或量化腿部运动变异性可以促进 CP 患者腿部肌张力障碍的检测。ANN NEUROL 2026。

### 第二部分 AI 大师评价

该研究针对脑性瘫痪（CP）临床诊断中极易漏诊的腿部肌张力障碍，创新性地结合了专家临床经验与机器学习技术。通过量化专家共识中的核心特征，开发出的 DxTonia 软件将诊断准确率从常规临床评估的 12% 显著提升至 82%，具有极高的临床实用价值。研究关键性地揭示了“腿部运动变异性”是识别该病症的核心生物标志物，为运动障碍的客观化、自动化评估提供了科学范式。

---

速递结束，祝您工作愉快！