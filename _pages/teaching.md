---
layout: page
permalink: /teaching/
title: teaching
description: Materials for courses you taught. Replace this text with your description.
nav: true
nav_order: 6
---

<div id="dfo" class="project-container" style="margin-top: 0px">
  <img src="{{ site.baseurl }}/assets/img/picture1.jpg" alt="Background image for Making Decisions for Other People. Two inversed mountains in front of a starry blue sky." title="Photo by Mark Basarab on Unsplash." style="width: 100%;">
  <div class="project-title" style="color: #007cbe">Neuro-AI Integrated Diagnostic and Interventional Platform (NAIDIP)</div>
</div>
### **神经人工智能集成诊断与干预平台（NAIDIP）**

**基于开源平台的技术整合**
The Neuro-AI Integrated Diagnostic and Interventional Platform (NAIDIP) revolutionizes neurological healthcare by integrating edge AI computing, multimodal neuroimaging, and AI-driven clinical decision support with traditional Chinese medicine (TCM). Designed for precision diagnostics, disease prediction, and personalized interventions, NAIDIP addresses the need for accessible, low-cost solutions in modern medicine.

神经人工智能集成诊断与干预平台（NAIDIP）通过融合边缘 AI 计算、多模态神经影像、AI 驱动临床决策支持与传统中医（TCM），彻底革新了神经疾病医疗模式。该平台专为精准诊断、疾病预测及个性化干预设计，致力于解决现代医学中对可及性、低成本解决方案的需求。

**技术架构与分布式计算框架**
NAIDIP utilizes a distributed computing framework with NVIDIA Jetson AGX Orin (275 TOPS AI performance) for high-intensity tasks, such as multimodal image fusion and deep learning inference, and Jetson Orin Nano (67 TOPS) for localized edge processing. Raspberry Pi acts as an ultra-low-power node for sensor integration (e.g., vital sign monitoring) in resource-constrained settings. This architecture ensures real-time analysis, data privacy (compliant with HIPAA), and scalability for remote or rural deployments.

NAIDIP 采用分布式计算架构，该架构确保实时分析、数据隐私（符合 HIPAA 标准），并支持远程或农村地区的规模化部署：
- **高性能任务处理**：搭载 NVIDIA Jetson AGX Orin（275 TOPS AI 算力），用于多模态图像融合与深度学习推理；
- **边缘本地化处理**：Jetson Orin Nano（67 TOPS）负责边缘计算任务；
- **低功耗节点**：树莓派作为超低功耗节点，集成传感器（如生命体征监测），适用于资源受限场景。

Built on the 3D Slicer platform, NAIDIP integrates open-source tools:

NAIDIP 以 3D Slicer 平台为基础，社区驱动的创新与 BSD 许可机制降低了研发成本，集成以下开源工具：

- **SlicerDMRI/fMRIEngine**: Enables diffusion tensor imaging (DTI), white matter tractography, and functional brain activation mapping.
- **DeepInfer/MONAI Label**: Deploys AI models for image segmentation and tumor detection.
- **OpenIGTLink** facilitates real-time neuro-navigation for interventions such as deep brain stimulation (DBS).
- This ecosystem reduces R&D costs via community-driven innovation and BSD licensing for commercial use.

- **SlicerDMRI/fMRIEngine**：支持扩散张量成像（DTI）、白质纤维束成像及脑功能激活映射；
- **DeepInfer/MONAI Label**：部署 AI 模型实现图像分割与肿瘤检测；
- **OpenIGTLink**：为深部脑刺激（DBS）等干预提供实时神经导航。

**AI 驱动的多模态分析与临床决策**

NAIDIP combines dMRI/fMRI analysis with brain atlases (e.g., EBRAINS Julich-Brain) to map structural and functional brain networks. The DeepSeek large language model (LLM) analyzes clinical data, imaging results, and literature to deliver personalized diagnostics, treatment recommendations, and disease progression predictions. Edge-deployed small models enable low-latency inference, while cloud-based large language models (LLMs) handle complex reasoning.

NAIDIP 结合 dMRI/fMRI 分析与脑图谱（如 EBRAINS Julich-Brain），绘制脑结构与功能网络。通过 DeepSeek 大语言模型（LLM）分析临床数据、影像结果及文献，实现个性化诊断、治疗建议与疾病进展预测。边缘部署的小型模型确保低延迟推理，云端大模型处理复杂推理任务。

**中西医结合的独特优势**

NAIDIP uniquely merges Western neurology with TCM:

- **AI-Assisted TCM Diagnosis**: Deep learning analyzes tongue images for TCM pattern recognition (87.37% accuracy).
- **Neuroimaging for Acupuncture Research**: fMRI and dMRI visualize brain activation and white matter changes during acupuncture, validating its neural mechanisms.
- This integration enables the development of holistic treatment plans that combine DBS/TMS with acupuncture and herbal medicine.

- **AI 辅助中医诊断**：深度学习分析舌象，中医证型识别准确率达 87.37%；
- **针灸研究的神经影像验证**：通过 fMRI 与 dMRI 可视化针灸过程中脑激活与白质变化，佐证其神经机制；
- **整合治疗方案**：将 DBS/TMS 等西医手段与针灸、中药结合，形成整体化治疗策略。

**模块化设计与生态布局**

NAIDIP differentiates itself by integrating commercial solutions with the flexibility of open-source software. Its modular design supports rapid deployment and partnerships, while the open ecosystem (GitHub, community forums) accelerates innovation. Development phases include core platform integration (6–12 months), expansion of the AI-TCM module (12–24 months), and clinical validation (24–36+ months).

NAIDIP 融合商业解决方案与开源软件灵活性，模块化架构支持快速部署与合作开发。开放生态（GitHub、社区论坛）加速创新，开发阶段包括：核心平台集成（6-12 个月）、AI - 中医模块扩展（12-24 个月）及临床验证（24-36 + 个月）。

**革新价值与全球愿景**

NAIDIP redefines neurological care by enabling precision diagnostics, predictive analytics, and hybrid Western and Traditional Chinese Medicine (TCM) interventions. By democratizing advanced AI and neuroimaging through edge computing and open-source principles, it aims to improve outcomes globally, from urban hospitals to underserved regions.

NAIDIP 通过精准诊断、预测分析及中西医结合干预，重新定义神经疾病照护模式。借助边缘计算与开源原则，平台致力于将先进 AI 与神经影像技术平民化，从城市医院到医疗资源匮乏地区，全面改善全球医疗。

---
<div id="dfo" class="project-container" style="margin-top: 0px">
  <img src="{{ site.baseurl }}/assets/img/picture2.jpg" alt="Background image for Making Decisions for Other People. Two inversed mountains in front of a starry blue sky." title="Photo by Mark Basarab on Unsplash." style="width: 100%;">
  <div class="project-title" style="color: #000000">Diffusion MRI based Virtual Biopsy</div>
</div>
### **弥散磁共振虚拟活检成像**

Virtual biopsy is an innovative non-invasive technique for analyzing the microenvironmental heterogeneity of the human brain, offering promising applications in clinical practice and societal impact. A key challenge in this field is accurately characterizing diffusion characteristics related to multi-scale tissue structures to develop non-invasive detection models that reflect pathological states.

虚拟活检是一种创新性无创技术，用于分析人脑微环境异质性，在临床实践与社会影响层面展现出广阔应用前景。该领域的核心挑战在于：精准表征与多尺度组织结构相关的扩散特征，从而构建能反映病理状态的无创检测模型。

**High Spatiotemporal Resolution Diffusion MRI**  
**高时空分辨率扩散 MRI**

Researchers are focusing on continuous relaxation diffusion imaging sequences and non-centered diffusion gradient encoding to improve sensitivity and scanning efficiency. These advancements provide detailed information about water molecule relaxation processes in tissues and enhance sensitivity to small-scale structures, improving overall imaging quality.

我们正聚焦于**连续弛豫扩散成像序列**与**非中心扩散梯度编码**技术，以提升敏感性与扫描效率。这些进展可提供组织中水分子弛豫过程的详细信息，增强对微观结构的敏感性，从整体上优化成像质量。

**Microstructural Spectrum Imaging**  
**微结构谱成像**

This component integrates microstructural features from intracellular and extracellular spaces to create a more accurate description of tissue microstructure. A learnable microstructural spectrum imaging model will be developed to identify patterns in diffusion data corresponding to different cell types, facilitating more precise diagnoses.

该模块整合细胞内与细胞外空间的微结构特征，以更精准地描绘组织微观结构。研究将开发可学习的微结构谱成像模型，用于识别扩散数据中对应不同细胞类型的模式，助力更精确的疾病诊断。

**Tractography within Intra- and Extra-Myelin Spaces**  
**髓鞘内外纤维束成像**

Using conformal geometric tracking informed by microstructural features, this research enhances the understanding of myelin-related tracts in the brain, which is crucial for diagnosing neurological disorders. This approach provides better information on nerve fiber connectivity and integrity, aiding early detection of diseases like multiple sclerosis.

通过结合微结构特征的共形几何追踪技术，该研究深化了对脑内髓鞘相关纤维束的认知 —— 这对神经疾病诊断至关重要。此方法可提供更完善的神经纤维连接性与完整性信息，辅助多发性硬化等疾病的早期检测。

**Pathological-Like Model**  
**类病理模型**

By synthesizing multi-scale graph embedding features, a pathological-scale non-invasive detection model will be established to identify subtle changes in the brain microenvironment similar to invasive examinations. This model can help detect early-stage tumor-related changes, improving early diagnosis and treatment planning.

通过合成多尺度图嵌入特征，研究将构建病理尺度的无创检测模型，以识别脑微环境中类似有创检查所见的细微变化。该模型可辅助检测肿瘤相关早期病变，提升疾病早诊率与治疗方案规划精度。

**研究价值与愿景**

Overall, this project aims to create a robust theoretical and methodological framework for non-invasive monitoring of brain changes, significantly benefiting patients with earlier and more accurate diagnoses and treatments.

整体而言，该项目致力于为脑内病变的无创监测建立坚实的理论与方法学框架。其核心意义在于通过更早、更精准的诊断与治疗，为患者带来显著临床获益。

---
<div id="dfo" class="project-container" style="margin-top: 0px">
  <img src="{{ site.baseurl }}/assets/img/picture3.jpg" alt="Background image for Making Decisions for Other People. Two inversed mountains in front of a starry blue sky." title="Photo by Mark Basarab on Unsplash." style="width: 100%;">
  <div class="project-title" style="color: #FFDD00">Diffusion MRI-based targeted fingerprinting of circuit regulation in neurological diseases</div>
</div>
### **面向神经疾病环路调控的靶向指纹技术** 

**Neurological diseases like Alzheimer's and Parkinson's present significant health challenges, complicating diagnosis and treatment.**  The complex nature of these conditions, often characterized by disruptions in neural circuits and brain connectivity, has made early diagnosis and effective treatment challenging. However, recent advancements in artificial intelligence, medical imaging, diffusion MRI, and large-scale models offer new opportunities to develop innovative approaches to address these issues.

**阿尔茨海默病、帕金森病等神经疾病构成重大健康挑战，其诊断与治疗存在显著复杂性。** 这类疾病常以神经环路破坏和脑连接异常为特征，复杂的病理机制导致早期诊断与有效干预难度极高。然而，人工智能、医学影像、扩散 MRI 及大规模模型的最新进展，为开发创新性解决方案提供了新契机。


**Diffusion MRI is a non-invasive imaging technique that reveals changes in neural connectivity by measuring the diffusion of water in the brain.** Diffusion MRI is a powerful, non-invasive imaging technique that provides detailed information about the microstructural properties of neural tissues, including the integrity of white matter tracts and the orientation of axons within them. By measuring the diffusion of water molecules in the brain, diffusion MRI can detect subtle changes in neural connectivity that may be associated with neurological diseases. In recent years, there has been growing interest in utilizing diffusion MRI to develop targeted fingerprints of the neural circuits involved in these conditions. These fingerprints can serve as biomarkers for early disease detection, prognosis prediction, and treatment monitoring.

**扩散 MRI：揭示神经连接变化的无创成像技术。** 扩散 MRI 是一种强大的无创成像手段，通过测量脑内水分子扩散特性，提供神经组织微观结构信息（如白质纤维束完整性及轴突走向）。该技术可检测与神经疾病相关的细微神经连接改变，近年来研究者正聚焦于利用扩散 MRI 构建疾病相关神经环路的靶向 “指纹图谱”。这些指纹可作为生物标志物，用于疾病早期检测、预后预测及治疗监测。

**AI enhances the analysis of diffusion MRI data, improving diagnosis and predicting disease progression.**  These techniques can automatically extract relevant features from large and complex datasets, enabling the identification of patterns and correlations that may not be apparent to human observers. For example, deep learning algorithms can be trained to recognize specific diffusion MRI patterns associated with various neurological diseases, allowing for more accurate and efficient diagnosis. Additionally, machine learning models can predict disease progression and treatment responses based on diffusion MRI data, providing valuable insights for personalized medicine.

**AI 赋能扩散 MRI 数据分析，提升诊断精度与疾病进展预测能力。** AI 技术能从庞大复杂的数据集中自动提取关键特征，识别肉眼难以察觉的模式与关联。例如，深度学习算法可训练识别特定神经疾病的扩散 MRI 特征模式，实现更精准高效的诊断；机器学习模型则能基于扩散 MRI 数据预测疾病进展与治疗反应，为个体化医疗提供重要依据。

**Combining diffusion MRI with other imaging methods provides a comprehensive view of the impacts on neural circuits, aiding in the development of new treatments.** By combining structural and functional information, researchers can gain a more comprehensive view of how neural circuits are affected by disease and how they respond to treatment. This multi-modal approach can also help identify novel therapeutic targets and develop more effective treatment strategies.

**多模态成像融合：全面解析神经环路影响，助力新疗法开发。** 通过整合结构与功能影像信息，研究者可更全面地揭示疾病对神经环路的影响及治疗响应机制。这种多模态方法还有助于发现新的治疗靶点，推动更高效治疗策略的研发。

**Large language models and other advanced computational tools can play a crucial role in this area of research.** These models can analyze and interpret large volumes of data from multiple sources, including clinical records, genetic data, and imaging data. By integrating this diverse information, researchers can create more accurate and comprehensive models of neurological diseases, informing the development of new diagnostic and therapeutic approaches.

**大语言模型与先进计算工具的关键作用。** 大语言模型可分析解读临床记录、基因数据、影像数据等多源信息，通过整合多元数据构建更精准全面的神经疾病模型，为新诊断与治疗方法的开发提供理论支撑。基于扩散 MRI 构建神经疾病环路调控靶向指纹图谱，是极具潜力的研究方向，有望显著提升我们对复杂神经疾病的认知、诊断与治疗水平。借助 AI、医学影像及大规模模型的技术突破，研究者可开发更早检测、更有效干预的创新方案，最终改善神经疾病患者的预后。

In conclusion, the development of diffusion MRI-based targeted fingerprints for regulating neural circuits in neurological diseases represents a promising research direction with the potential to significantly enhance our understanding, diagnosis, and treatment of these complex disorders. By leveraging advancements in artificial intelligence, medical imaging, and large-scale models, researchers can devise innovative approaches that may lead to earlier detection, more effective treatments, and ultimately better outcomes for patients with neurological diseases.



