<p align="center">
  <h1 align="center">A Collection of Radiology Report Generation Studies</h1>

This GitHub repository summarizes papers and resources related to the radiology report generation (RRG) task. 

If you have any suggestions about this repository, please feel free to [start a new issue](https://github.com/AlonzoLeeeooo/awesome-radiology-report-generation/issues/new) or [pull requests](https://github.com/AlonzoLeeeooo/awesome-radiology-report-generation/pulls).


<!-- omit in toc -->
# <span id="contents">Contents</span>
- [References](#references)
- [Papers](#papers)
- [Datasets](#datasets)
- [To-Do Lists](#to-do-lists)

<!-- omit in toc -->
# To-Do Lists
- Recent Papers
  - [ ] Update ACL 2024 Papers
  - [ ] Update CVPR 2024 Papers
  - [ ] Update AAAI 2024 Papers
    - [ ] Update PDFs and References
  - [ ] Update ICLR 2024 Papers
  - [ ] Update NeurIPS 2024 Papers
  - Regular Maintenance of Preprint arXiv Papers and Missed Papers
- Previous Papers
  - Published Papers on Conferences
    - [ ] Update ACL papers
    - [ ] Update EMNLP papers
    - [ ] Update CVPR papers
    - [ ] Update ICCV papers
    - [ ] Update ECCV papers
    - [ ] Update MICCAI papers
    - [ ] Update AAAI papers
    - [ ] Update NeurIPS papers
  - Published Papers on Journals
    - [ ] Update TMM papers
    - [ ] Update TMI papers


<!-- omit in toc -->
# Papers
- <span id="year-2024">**Year 2024**</span> 
  - **AAAI**
    - Bootstrapping Large Language Models for Radiology Report Generation [Paper] [[Code]](https://github.com/synlp/R2-LLM)
  - **TMM**
    - From Observation to Concept: A Flexible Multi-view Paradigm for Medical Report Generation [[paper]](https://ieeexplore.ieee.org/document/10356722)
  - **TMI**
    - Complex Organ Mask Guided Radiology Report Generation [[Paper]](https://arxiv.org/pdf/2311.02329.pdf) [[Code]](https://github.com/GaryGuTC/COMG_model)
- <span id="year-2023">**Year 2023**</span>
  - **ACL**  
    - ***ORGAN:*** Observation-Guided Radiology Report Generation via Tree Reasoning [[Paper]](https://aclanthology.org/2023.acl-long.451/) [[Code]](https://github.com/wjhou/ORGan)
    - ***Replace and Report:*** NLP Assisted Radiology Report Generation [[Paper]](https://aclanthology.org/2023.findings-acl.683.pdf)
  - **EACL**
    - ***KGVL-BART:*** Knowledge Graph Augmented Visual Language BART for Radiology Report Generation [[Paper]](https://aclanthology.org/2023.eacl-main.246/) [[Code]](https://github.com/yeliu918/KG-BART)
  - **EMNLP**
    - Style-Aware Radiology Report Generation with RadGraph and Few-Shot Prompting [[Paper]](https://arxiv.org/pdf/2310.17811v2.pdf) 
    - ***PhenotypeCLIP:*** Phenotype-based Contrastive Learning for Medical Imaging Report Generation [[Paper]](https://aclanthology.org/2023.emnlp-main.989.pdf)
    - ***RECAP:*** Towards Precise Radiology Report Generation via Dynamic Disease Progression Reasoning [[Paper]](https://aclanthology.org/2023.findings-emnlp.140.pdf) [[Code]](https://github.com/wjhou/recap)
  - **CVPR**
    - Dynamic Graph Enhanced Contrastive Learning for Chest X-ray Report Generation [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Dynamic_Graph_Enhanced_Contrastive_Learning_for_Chest_X-Ray_Report_Generation_CVPR_2023_paper.pdf) [[Code]](https://github.com/mlii0117/DCL)
    - ***RGRG:*** Interactive and Explainable Region-guided Radiology Report Generation [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Tanida_Interactive_and_Explainable_Region-Guided_Radiology_Report_Generation_CVPR_2023_paper.pdf) [[Code]](https://github.com/ttanida/rgrg)
    - ***KiUT:*** Knowledge-injected U-Transformer for Radiology Report Generation [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Huang_KiUT_Knowledge-Injected_U-Transformer_for_Radiology_Report_Generation_CVPR_2023_paper.pdf)
    - ***METransformer:*** Radiology Report Generation by Transformer with Multiple Learnable Expert Tokens [[Paper]](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_METransformer_Radiology_Report_Generation_by_Transformer_With_Multiple_Learnable_Expert_CVPR_2023_paper.pdf)
  - **ICCV**
    - Unify, Align and Refine: Multi-Level Semantic Alignment for Radiology Report Generation [[Paper]](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Unify_Align_and_Refine_Multi-Level_Semantic_Alignment_for_Radiology_Report_ICCV_2023_paper.pdf)
  - **MICCAI**
    - ***SGT:*** Scene Graph-Guided Transformer for Surgical Report Generation** [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-16449-1_48) [[Code]](https://github.com/ccccchenllll/SGT_master)
  - **ICASSP**
    - ***MvCo-DoT:*** Multi-View Contrastive Domain Transfer Network for Medical Report Generation [[Paper]](https://arxiv.org/pdf/2304.07465.pdf)
  - **ICIP**
    - Self Adaptive Global-Local Feature Enhancement for Radiology Report Generation [[Paper]](https://arxiv.org/pdf/2211.11380.pdf)
  - **WWW**
    - Auxiliary Signal‑guided Knowledge Encoder‑decoder for Medical Report Generation [[paper]](https://arxiv.org/abs/2006.03744) [[code]](https://github.com/mlii0117/COV-CTR)
  - **AMI**
    - Improving Chest X-ray Report Generation by Leveraging Warm Starting [[Paper]](https://arxiv.org/pdf/2201.09405.pdf) [[Code]](https://github.com/aehrc/cvt2distilgpt2)
  - **TMI**
    - Attributed Abnormality Graph Embedding for Clinically Accurate X-Ray Report Generation [[Paper]](https://ieeexplore.ieee.org/document/10045710/)
    - ***SGT++:*** Improved Scene Graph-guided Transformer for Surgical Report Generation [[Paper]](https://ieeexplore.ieee.org/document/10330637/)
    - Joint Embedding of Deep Visual and Semantic Features for Medical Image Report Generation [[paper]](https://ieeexplore.ieee.org/document/9606584)
    - Semi-supervised Medical Report Generation via Graph-guided Hybrid Feature Consistency [[paper]](https://ieeexplore.ieee.org/document/10119200)
  - **arXiv**
    - ***LLM-CXR:*** Instruction-Finetuned LLM for CXR Image Understanding and Generation [[Paper]](https://arxiv.org/abs/2305.11490) [[Code]](https://github.com/hyn2028/llm-cxr)
    - ***MAIRA-1:*** A Specialised Large Multimodal Model for Radiology Report Generation [[Paper]](https://arxiv.org/abs/2311.13668) [[Project]](https://www.microsoft.com/en-us/research/project/project-maira/)
    - ***MedXChat:*** Bridging CXR Modalities with a Unified Multimodal Large Model [[Paper]](https://arxiv.org/abs/2312.02233)
    - Pragmatic Radiology Report Generation [[paper]](https://arxiv.org/pdf/2311.17154.pdf)
    - ***RadLLM:*** A Comprehensive Healthcare Benchmark of Large Language Models for Radiology [[Paper]](https://arxiv.org/pdf/2307.13693.pdf) [[Project]](https://mohsenarjmandi.com/projects/)
    - ***RaDialog:*** A Large Vision-Language Model for Radiology Report Generation and Conversational Assistance [[Paper]](https://arxiv.org/pdf/2311.18681.pdf) [[Code]](https://github.com/ChantalMP/RaDialog)
    - Towards Generalist Biomedical AI [[Paper]](https://arxiv.org/abs/2307.14334) [[Reproduced Code]](https://github.com/kyegomez/Med-PaLM)
    - Towards Generalist Foundation Model for Radiology by Leveraging Web-scale 2D&3D Medical Data [[Paper]](https://arxiv.org/abs/2308.02463) [[Project]](https://chaoyi-wu.github.io/RadFM/) [[Code]](https://github.com/chaoyi-wu/RadFM?tab=readme-ov-file)
    - Cross-Modal Causal Intervention for Medical Report Generation [[Paper]](https://arxiv.org/pdf/2303.09117.pdf) [[Code]](https://github.com/WissingChen/VLCI)
    - Medical Report Generation based on Segment-Enhanced Contrastive Representation Learning [[Paper]](https://arxiv.org/pdf/2312.15869.pdf)
    - Radiology Report Generation Using Transformers Conditioned with Non-imaging Data [[Paper]](https://arxiv.org/pdf/2311.11097.pdf)
- <span id="year-2022">**Year 2022**</span> 
  - **AACL**
    - Multimodal Generation of Radiology Reports using Knowledge-Grounded Extraction of Entities and Relations [[Paper]](https://aclanthology.org/2022.aacl-main.47/)
  - **ACL**
    - Reinforced Cross-modal Alignment for Radiology Report Generation [[Paper]](https://aclanthology.org/2022.findings-acl.38/) [[Code]](https://github.com/synlp/R2GenRL)
  - **EMNLP**
    - Improving the Factual Correctness of Radiology Report Generation with Semantic Rewards [[Paper]](https://aclanthology.org/2022.findings-emnlp.319/) [[Code]](https://github.com/jbdel/vilmedic?tab=readme-ov-file)
    - Factual Accuracy is not Enough: Planning Consistent Description Order for Radiology Report Generation [[Paper]](https://aclanthology.org/2022.emnlp-main.480/)
  - **CVPR**
    - Cross-modal Clinical Graph Transformer for Ophthalmic Report Generation [[Paper]](https://ieeexplore.ieee.org/document/9879084)
  - **ECCV**
    - Cross-Modal Prototype Driven Network for Radiology Report Generation [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136950558.pdf)
  - **MICCAI**
    - ***RepsNet:*** Combining Vision with Language for Automated Medical Reports [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_68)
    - A Self-guided Framework for Radiology Report Generation [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-16452-1_56) [[Code]](https://github.com/LijunRio/A-Self-Guided-Framework)
    - A Medical Semantic-Assisted Transformer for Radiographic Report Generation [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-16437-8_63)
    - Lesion Guided Explainable Few Weak-Shot Medical Report Generation [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_59)
    - ***TranSQ:*** Transformer-Based Semantic Query for Medical Report Generation [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-16452-1_58) [[Code]](https://github.com/zjukongming/TranSQ)
  - **BMVC**
    - On the Importance of Image Encoding in Automated Chest X-Ray Report Generation [[Paper]](https://arxiv.org/ftp/arxiv/papers/2211/2211.13465.pdf) [[Code]](https://github.com/mudabek/encoding-cxr-report-gen)
  - **ICBB**
    - Clinically Coherent Radiology Report Generation with Imbalanced Chest X-rays [[Paper]](https://ieeexplore.ieee.org/document/9994871/)
  - **MIA**
    - Knowledge Matters: Chest Radiology Report Generation with General and Specific Knowledge [[Paper]](https://pdf.sciencedirectassets.com/272154/1-s2.0-S1361841522X00042/1-s2.0-S1361841522001578/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEFQaCXVzLWVhc3QtMSJGMEQCIFPdvXsyFRfWxMj7jhqb0f970F6Z4ob8tvvHZZFgZlFqAiBy5IiEQ4PlAir2yIwNA7JcWzUNL2TRxtu3sYh7y%2FoXDSq8BQjN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAUaDDA1OTAwMzU0Njg2NSIMbAYHoe7gNJJndbczKpAFMjLnJ6hkHKMbEX6fFEdWNQpY0sCwalqj8EXda%2B5sS86uDeKRlkUJeQWbUO8t1ufSC6aWd1V7SNHLUqgnLDqw7QGKPf07Xu5LSJtSOlTic1tMO%2B5HBQpunTtD3eeJFw%2FteLbzL4ZhClTjouaedBsNC8Qh0bDSjVVE5sdFCm%2Fifue7Ppobq2PCSU3XYSRpxxDloSQY4c0xZxbPlPxjB4rADrvDPefwPmT1MrlA74RYTRLmyE83f%2Bmqpah6Wj%2FH7%2FDBE4Qppv6C4ZNrZ9j1fs2JA%2Ful%2FMOd%2FJrffnIWpJDCFm6ZHTH7h%2Fef%2FuN5SMAUEjGNkP7d7UI3Q7CNpK8nlywWwLfEoK%2FDyt0%2F1gpSLfbl7%2FOisdRA%2BDRzemFQQnxBGAlXWyyB0F%2BMx6Jnrnm%2FaJhzw%2FlGCRrewLbDX6%2Fd8hHdEq1tnZaerP1O0N6JTH8A%2BhsB%2FXqETFmm3fal%2B2dpOyCCBvBQ%2F6H%2FtHqTRMFDJHclogE4YV3c3oUSww%2BzTBAAvxheuPC98ToQEYeZzk9tzhwIeJlSYNuQRmOOGpk9lL%2BnrwrNvRywI0g5Y0PIGrqxrtqnixt%2FWjCy5eq%2Bfr7gJIyufQBiKwxXOJHdAmiNRdueIidmU6HHCEAJdvKHBtKu95XQicIZW0s5tzpaH7JZ9TrePd3mkQfCXnnnOyifqKOHJcoCJwQGyX6OYty%2B1iDflrdvPHFKG9dSSVvLDEjtbxQ2pUZwPmk0rT777w7jtQcLofkdhgWaPy0XV3cZ3i3wF%2FYwazU0yUnlS%2F43Vi4m08Ii4J5WW1QVZ2V0f1Zmw6LwEOSVbIOW3t9mIP2rbLK7WAp16GrnHBw2Ibr2fHQ%2BMJWCeBHpvrw7vwqenKc2Dwrc%2BF4wx5yErAY6sgFrZ1xJ%2Ftc6v0oW48%2BDzNsaXNopwTfD5Mv8IXC3bXt%2FgWEarHdvGryQY1BH0ewnE5Nzea%2FyAGjO3docq3of%2B5581Dmv6oZ%2FePgzIPK0QQdp1HBYWhJRe0HG8hJ1LPgssqy3v1TH4YZx5zKF4lddQ4PO33vE6c%2BrxKHLsf4ZdPT7m2aramQkxiCEkCLJmroJtS3KRi1qVLtZwifqyQ06hZ2a5f7wWh79h%2BbEMjya1gjoD%2B2G&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20231219T042855Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYVICNITU7%2F20231219%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=b50b28cc347b877a7dc441b3225995171c0d6a9a3f9f068b131abd437436c586&hash=7744bcd1a019821bc513a15cd2cb8cf13676616438298545a5c9398d0235fb03&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S1361841522001578&tid=spdf-ec11110a-c807-441f-87d5-c1978b17d4fa&sid=533db39126ac0241317848c5289133cfb43bgxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=120d5b5c540c0557060406&rr=837ce6cdad98078f&cc=hk) [[Code]](https://github.com/LX-doctorAI1/GSKET)
  - **TMI**
    - Automated Radiographic Report Generation Purely on Transformer: A Multicriteria Supervised Approach [[Paper]](https://ieeexplore.ieee.org/document/9768661)
  - **arXiv**  
    - ***CAMANet:*** Class Activation Map Guided Attention Network for Radiology Report Generation [[Paper]](https://arxiv.org/pdf/2211.01412.pdf)
    - Hybrid Reinforced Medical Report Generation with M-Linear Attention and Repetition Penalty [[Paper]](https://arxiv.org/pdf/2210.13729.pdf)
    - ***DeltaNet:*** Conditional Medical Report Generation for COVID-19 Diagnosis [[Paper]](https://arxiv.org/pdf/2211.13229.pdf)
- <span id="year-2021">**Year 2021**</span>
  - **ACL**
    - Cross-modal Memory Networks for Radiology Report Generation [[Paper]](https://aclanthology.org/2021.acl-long.459.pdf) [[Code]](https://github.com/cuhksz-nlp/R2GenCMN)
  - **NAACL**
    - Improving Factual Completeness and Consistency of Image-to-Text Radiology Report Generation [[Paper]](https://aclanthology.org/2021.naacl-main.416.pdf) [[Code]](https://github.com/ysmiura/ifcc)
  - **COLING**
    - ***JPG*** - Jointly Learn to Align: Automated Disease Prediction and Radiology Report Generation [[Paper]](https://aclanthology.org/2022.coling-1.523/)
  - **EMNLP**
    - Automated Generation of Accurate & Fluent Medical X-ray Reports [[Paper]](https://aclanthology.org/2021.emnlp-main.288/) [[Code]](https://github.com/ginobilinie/xray_report_generation)
    - Progressive Transformer-Based Generation of Radiology Reports [[Paper]](https://aclanthology.org/2021.findings-emnlp.241/) [[Code]](https://github.com/uzh-dqbm-cmi/ARGON)
    - Weakly Supervised Contrastive Learning for Chest X-Ray Report Generation [[Paper]](https://aclanthology.org/2021.findings-emnlp.336.pdf) [[Code]](https://github.com/zzxslp/WCL)
  - **CVPR**
    - Exploring and Distilling Posterior and Prior Knowledge for Radiology Report Generation [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Exploring_and_Distilling_Posterior_and_Prior_Knowledge_for_Radiology_Report_CVPR_2021_paper.pdf)
    - A Self-boosting Framework for Automated Radiographic Report Generation [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_A_Self-Boosting_Framework_for_Automated_Radiographic_Report_Generation_CVPR_2021_paper.pdf)
  - **ICCV**
    - Visual-Textual Attentive Semantic Consistency for Medical Report Generation [[Paper]](https://openaccess.thecvf.com/content/ICCV2021/papers/Zhou_Visual-Textual_Attentive_Semantic_Consistency_for_Medical_Report_Generation_ICCV_2021_paper.pdf)
  - **MICCAI**
    - ***RATCHET:*** Medical Transformer for Chest X-ray Diagnosis and Reporting [[Paper]](https://miccai2021.org/openaccess/paperlinks/2021/09/01/390-Paper1026.html) [[Code]](https://github.com/farrell236/RATCHET)
    - ***Trust It or Not:*** Confidence-Guided Automatic Radiology Report Generation [[Paper]](https://arxiv.org/pdf/2106.10887.pdf)
  - **NeurIPS**
    - Auto-encoding Knowledge Graph for Unsupervised Medical Report Generation [[Paper]](https://proceedings.neurips.cc/paper/2021/file/876e1c59023b1a0e95808168e1a8ff89-Paper.pdf)
- <span id="year-2020">**Year 2020**</span>
  - **EMNLP**
    - Generating Radiology Reports via Memory-driven Transformer [[Paper]](https://aclanthology.org/2020.emnlp-main.112/) [[Code]](https://github.com/cuhksz-nlp/R2Gen)
    - Reinforcement Learning with Imbalanced Dataset for Data-to-Text Medical Report Generation [[Paper]](https://aclanthology.org/2020.findings-emnlp.202/)
  - **AAAI** 
    - When Radiology Report Generation Meets Knowledge Graph [[Paper]](https://arxiv.org/abs/2002.08277)
  - **ACCV**
    - Hierarchical X-Ray Report Generation via Pathology tags and Multi Head Attention [[Paper]](https://openaccess.thecvf.com/content/ACCV2020/papers/Srinivasan_Hierarchical_X-Ray_Report_Generation_via_Pathology_tags_and_Multi_Head_ACCV_2020_paper.pdf)
- <span id="year-2019">**Year 2019**</span>
  - **ACL**
    - Show, Describe and Conclude: On Exploiting the Structure Information of Chest X-Ray Reports [[Paper]](https://aclanthology.org/P19-1657/)
  - **MICCAI**
    - Automatic Radiology Report Generation based on Multi-view Image Fusion and Medical Concept Enrichment [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-32226-7_80)
  - **AAAI**
    - Knowledge-Driven Encode, Retrieve, Paraphrase for Medical Image Report Generation [[Paper]](https://ojs.aaai.org/index.php/AAAI/article/view/4637/4515)
  - **BMVC**
    - Addressing Data Bias Problems for Chest X-ray Image Report Generation [[Paper]](https://bmvc2019.org/wp-content/uploads/papers/1007-paper.pdf)
- <span id="year-2018">**Year 2018**</span>
  - **ACL**
    - On the Automatic Generation of Medical Imaging Reports [[Paper]](https://aclanthology.org/P18-1240/) [[Code]](https://github.com/ZexinYan/Medical-Report-Generation)
  - **MICCAI**
    - Multimodal Recurrent Model with Attention for Automated Radiology Report Generation [[Paper]](https://link.springer.com/chapter/10.1007/978-3-030-00928-1_52) [[Code]](https://github.com/tengfeixue-victor/Medical-Report-Generation)
  - **NeurIPS**
    - Hybrid Retrieval-Generation Reinforced Agent for Medical Image Report Generation [[Paper]](https://proceedings.neurips.cc/paper_files/paper/2018/file/e07413354875be01a996dc560274708e-Paper.pdf) 

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
# Datasets
[J. Am. Medical Informatics Assoc.] ***IU X-Ray:*** Preparing A Collection of Radiology Examinations for Distribution and Retrieval [[Paper]](https://pubmed.ncbi.nlm.nih.gov/26133894/) [[Dataset]](https://openi.nlm.nih.gov/faq)

[Scientific Data] ***MIMIC-CXR***, A De-identified Publicly Available Database of Chest Radiographs with Free-text Reports [[Paper]](https://www.nature.com/articles/s41597-019-0322-0) [[Dataset]](https://physionet.org/content/mimic-cxr/1.0.0/)

[arXiv] ***MIMIC-CXR-JPG***, A Large Publicly Available Database of Labeled Chest Radiographs [[Paper]](https://arxiv.org/abs/1901.07042) [[Dataset]](https://physionet.org/content/mimic-cxr/2.0.0/)

[NeurIPS 2021 Datasets & Benchmark] ***FFA-IR:*** Towards an Explainable and Reliable Medical Report Generation Benchmark [[Paper]](https://openreview.net/pdf?id=FgYTwJbjbf) [[Dataset]](https://physionet.org/content/ffa-ir-medical-report/1.0.0/) [[GitHub]](https://github.com/mlii0117/FFA-IR)

[NeurIPS 2021 Datasets & Benchmark] ***RadGraph:*** Extracting Clinical Entities and Relations from Radiology Reports [[Paper]](https://datasets-benchmarks-proceedings.neurips.cc/paper/2021/file/c8ffe9a587b126f152ed3d89a146b445-Paper-round1.pdf) [[Dataset]](https://physionet.org/content/radgraph/1.0.0/)

[<u><small><🎯Back to Top></small></u>](#contents)

<!-- omit in toc -->
# Q&A
- **Q: The conference sequence of this paper list?**
  - This paper list is organized according to the following sequence:
    - Conferences
      - ACL
      - EACL
      - NAACL
      - COLING
      - EMNLP
      - CVPR
      - ICCV
      - ECCV
      - MICCAI
      - AAAI
      - NeurIPS
      - ACCV
      - BMCV
      - ICASSP
      - ICIP
      - ICBB
      - WWW
    - Journals
      - AMI
      - MIA
      - TMM
      - TMI
    - arXiv

<!-- omit in toc -->
# References

The `reference.bib` file summarizes bibtex references of up-to-date image inpainting papers, widely used datasets, and toolkits.
Based on the original references, I have made the following modifications to make their results look nice in the `LaTeX` manuscripts:
- Refereces are normally constructed in the form of `author-etal-year-nickname`. Particularly, references of datasets and toolkits are directly constructed as `nickname`, e.g., `imagenet`.
- In each reference, all names of conferences/journals are converted into abbreviations, e.g., `Computer Vision and Pattern Recognition -> CVPR`.
- The `url`, `doi`, `publisher`, `organization`, `editor`, `series` in all references are removed.
- The `pages` of all references are added if they are missing.
- All paper names are in title case. Besides, I have added an additional `{}` to make sure that the title case would also work well in some particular templates. 

If you have other demands of reference formats, you may refer to the original references of papers by searching their names in [DBLP](https://dblp.org/) or [Google Scholar](https://scholar.google.com/).

[<u><small><🎯Back to Top></small></u>](#contents)