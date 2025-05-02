# 🔍 SOT_Deepfake_Detection_Mechanisms

A curated collection of GitHub repositories and papers covering state-of-the-art Deepfake Detection techniques, as categorized in our systematic review:

📄 **Paper**: _Unmasking Synthetic Realities in the GAI Era: A Systematic Review of Uni-Modal and Multi-Modal Deepfake Detection for Enhanced Adversarial Robustness_  
🔗 [Link to paper (coming soon)]  
🔗 [GitHub Repository for Paper](https://github.com/Magnet200/SOT_Deepfake_Detection_Mechanisms)

---

## Threats posed by Generative Artificial Intelligence (GAI)
The most pressing challenges associated with GAI is the proliferation of synthetic media, commonly known as DeepFakes. DeepFakes leverage generative models to manipulate visual, auditory, and textual content, posing substantial threats to digital security, democratic stability, and public trust.
### ! (figs/Multi_modal_Image_edit.png)

## Broad taxonomy of Deepfake generation and detection strategies
This systematic review provides a comprehensive synthesis of deepfake detection methodologies, encompassing all primary modalities—image, video, audio, text, and multi-modal systems. It bridges critical gaps in the literature by integrating uni-modal and multi-modal approaches while offering a structured evaluation of their resilience to adversarial threats and their adaptability across diverse synthetic media contexts.

### ! (figs/Deepfake_taxonomy_scr_shot.png)

## 📚 Repository Structure
### 1. 🧠 Uni-modal Deepfake Detection

Detection methods that use **a single modality** such as image, video, audio, o
#### 📷 Image-Based Detection
- **LGrad**: [GitHub](https://github.com/chuangchuangtan/LGrad)
- **Deepfake Detection without Deepfakes **: [GitHub](https://github.com/davide-coccomini/Deepfake-Detection-without-Deepfakes-Generalization-via-Synthetic-Frequency-Patterns-Injection.git)
- **FREQUENCY MASKING FOR UNIVERSAL DEEPFAKE DETECTION**: [GitHub](https://github.com/chandlerbing65nm/FakeImageDetection.git)
- **ON THE EXPLOITATION OF DCT-TRACES IN THE GENERATIVE-AI DOMAIN**: [GitHub](https://github.com/opontorno/dcts_analysis_deepfakes.git)
- **FreqNet-DeepfakeDetection (AAAI 2024)**: [GitHub](https://github.com/chuangchuangtan/FreqNet-DeepfakeDetection.git)
- **Wavelet-CLIP (2025)**: [GitHub](https://github.com/lalithbharadwajbaru/Wavelet-CLIP.git)
- **FatFormer (CVPR 2024)**: [GitHub](https://github.com/Michel-liu/FatFormer.git)
- **UniversalFakeDetect (CVPR 2023)**: [GitHub](https://github.com/WisconsinAIVision/UniversalFakeDetect.git)
- **Faster Than Lies (CVPR Workshop 2024)**: [GitHub](https://github.com/fedeloper/binary_deepfake_detection.git)
- **DistilDIRE (ICML 2024)**: [GitHub](https://github.com/miraflow/DistilDIRE.git)
- **AI-assisted Deepfake Detection Using Adaptive Blind Image Watermarking (Jvcir 2024)** : [GitHub](https://github.com/lyhsu01/AwDD.git)
- **PTW: Pivotal Tuning Watermarking for Pre-Trained Image Generators (USENIX 2023)** : [GitHub](https://github.com/nilslukas/gan-watermark.git)
- **LampMark: Proactive Deepfake Detection via Training-Free Landmark Perceptual Watermarks (MM 2024)**: [GitHub](https://github.com/wangty1/LampMark.git)
- **SepMark (ACM International Conference on Multimedia 2023)**: [GitHub](https://github.com/sh1newu/SepMark.git)
- **Interpretable-through-prototypes deepfake detection for diffusion models (ICCV workshop 2023)**: [GitHub](https://github.com/lira-centre/DeepfakeDetection.git)
- **DeepFeatureX Net: (International Conference on Pattern Recognition 2025)**: [GitHub](https://github.com/opontorno/block-based_deepfake-detection.git)
- **Data-Independent Operator: (arXiv 2024)**: [GitHub](https://github.com/chuangchuangtan/Data-Independent-Operator.git)
- **Rethinking the Up-Sampling Operations in CNN-based Generative Network for Generalizable Deepfake Detection: (CVPR 2024)**: [GitHub](https://github.com/chuangchuangtan/NPR-DeepfakeDetection.git)
- **DIRE for Diffusion-Generated Image Detection (ICCV 2023)**: [GitHub](https://github.com/ZhendongWang6/DIRE.git)
- **Adaptive Meta-Learning for Robust Deepfake Detection:(arXive 2024)**: [GitHub](https://github.com/dineshsrivasthav/adaptive_meta_learning_with_multi_agent_framework.git)
- **An Analysis of Recent Advances in Deepfake Image Detection in an Evolving Threat Landscape (IEEE S\&P 2024)**: [GitHub](https://github.com/secml-lab-vt/EvolvingThreat-DeepfakeImageDetect.git)
- **Optimized Frequency Collaborative Strategy Drives AI Image Detection (IEEE Internet of Things Journal 2025)**: [GitHub](https://github.com/JackPotProject/Frequency-Collaborative.git)




#### 🎞️ Video-Based Detection
- **Deepfake detection using Enhanced Self Blended Images using DWT features (Image and Vision Computing 2025)**: [GitHub](https://github.com/gufranSabri/FSBI.git)
- **SeqDeepFake: Detecting and Recovering Sequential DeepFake Manipulation (ECCV 2022)**: [GitHub](https://github.com/rshaojimmy/SeqDeepFake.git)
- **Exposing Lip-syncing Deepfakes from Mouth Inconsistencies (ICME 2024)**: [GitHub](https://github.com/skrantidatta/LIPINC.git)
- **Learning Spatiotemporal Inconsistency via Thumbnail Layout for Face Deepfake Detection (IJCV 2024)**: [GitHub](https://github.com/rainy-xu/TALL4Deepfake.git)
- **GrDT: Towards Robust Deepfake Detection using Geometric Representation Distribution and Texture (WACV workshop 2025)**: [GitHub](https://github.com/SIPLab24/GrDT.git)
- **Masked Relation Learning for DeepFake Detection (TIFS 2023)**: [GitHub](https://github.com/zimyang/MaskRelation.git)
- **MARLIN: Masked Autoencoder for facial video Representation LearnINg (CVPR 2023)**: [GitHub](https://github.com/ControlNet/MARLIN.git)
- **SeeABLE: Soft Discrepancies and Bounded Contrastive Learning for Exposing Deepfakes (arXiv 2022)**: [GitHub](https://github.com/anonymous-author-sub/seeable.git)
- **Contrastive Pseudo Learning for Open-World DeepFake Attribution (ICCV 2023)**: [GitHub](https://github.com/TencentYoutuResearch/OpenWorld-DeepFakeAttribution.git)
- **Open-Set Deepfake Detection: A Parameter-Efficient Adaptation Method with Forgery Style Mixture (arXiv 2024)**: [GitHub](https://github.com/ChenqiKONG/OSDFD.git)
- **DeepFake-Adapter: Dual-Level Adapter for DeepFake Detection (IJCV 2025)**: [GitHub](https://github.com/rshaojimmy/DeepFake-Adapter.git)
- **C2P-CLIP: Injecting Category Common Prompt in CLIP to Enhance Generalization in Deepfake Detection (AAAI 2025)**: [GitHub](https://github.com/chuangchuangtan/C2P-CLIP-DeepfakeDetection.git)
- **Robust face forgery detection integrating local texture and global texture information (Journal of Information Security 2025)**: [GitHub](https://github.com/hryyyy/MST.git)
- **Deepfake Detection Using Spatiotemporal Transformer (ACM Trans. Multimedia Comput. Commun. Appl. 2024)**: [GitHub](https://github.com/KADDAR-Bachir/HCiT.git)
- **Improved Deepfake Video Detection Using Convolutional Vision Transformer (GEM 2024)**: [GitHub](https://github.com/erprogs/CViT.git)
- **Unmasking Deepfake Faces from Videos An Explainable Cost-Sensitive Deep Learning Approach (ICCIT 2023)**: [GitHub](https://github.com/Faysal-MD/Unmasking-Deepfake-Faces-from-Videos-An-Explainable-Cost-Sensitive-Deep-Learning-Approach-IEEE2023.git)
- **Improving the Perturbation-Based Explanation of Deepfake Detectors Through the Use of Adversarially-Generated Samples (WACVW 2025)**: [GitHub](https://github.com/IDT-ITI/Adv-XAI-Deepfakes.git)
- **Preserving Fairness Generalization in Deepfake Detection (CVPR 2024)**: [GitHub](https://github.com/Purdue-M2/Fairness-Generalization.git)
- **Face Forgery Detection by 3D Decomposition and Composition Search (IEEE Transactions on Pattern Analysis and Machine Intelligence 2023)**: [GitHub](https://github.com/ZhangTSia/FD2ClueSearching.git)
- **DeepFidelity: Perceptual Forgery Fidelity Assessment for Deepfake Detection (arXiv 2023)**: [GitHub](https://github.com/shimmer-ghq/DeepFidelity.git)
- **Exposing the Deception: Uncovering More Forgery Clues for Deepfake Detection (AAAI 2024)**: [GitHub](https://github.com/QingyuLiu/Exposing-the-Deception.git)
- **Implicit Identity Leakage: The Stumbling Block to Improving Deepfake Detection Generalization (CVPR 2023)**: [GitHub](https://github.com/megvii-research/CADDM.git)
- **LAA-Net: Localized Artifact Attention Network for Quality-Agnostic and Generalizable Deepfake Detection (CVPR 2024)**: [GitHub](https://github.com/10Ring/LAA-Net.git)
- 




- 
- 

#### 🔊 Audio-Based Detection
- **Region-Based Optimization in Continual Learning for Audio Deepfake Detection (AAAI 2025**: [GitHub](https://github.com/cyjie429/RegO.git)
- **BTS-E: Audio Deepfake Detection Using Breathing-Talking-Silence Encoder (ICASSP 2023)**: [GitHub](https://github.com/josebeo2016/BTS-Encoder-ASVspoof.git)
- **What to remember: Self-adaptive continual learning for audio deepfake detection (AAAI 2024)**: [GitHub](https://github.com/Cecile-hi/Radian-Weight-Modification.git)
- **RawBMamba: End-to-End Bidirectional State Space Model for Audio Deepfake Detection (arXiv 2024)**: [GitHub](https://github.com/cyjie429/RawBMamba.git)
- **SONICS: Synthetic Or Not - Identifying Counterfeit Songs (ICLR 2025)**: [GitHub](https://github.com/awsaf49/sonics.git)
- **A Conformer-based audio deepfake detection system with hierarchical pooling and multi-level classification token aggregation methods (arXiv 2023)**: [GitHub](https://github.com/talkingnow/HM-Conformer.git)
- **Prompt Tuning for Audio Deepfake Detection: (INTERSPEECH 2024)**: [GitHub](https://github.com/Yuto-Matsunaga/Prompt_Tuning_for_Audio_Deepfake_Detection.git)
- **A ROBUST AUDIO DEEPFAKE DETECTION SYSTEM VIA MULTI-VIEW FEATURE (ACASSP 2024)**: [GitHub](https://gitee.com/mindspore/models)
- **Audio Deepfake Detection with XLS-R and SLS classfier (ACM International Conference on Multimedia 2024)**: [GitHub](https://github.com/QiShanZhang/SLSforASVspoof-2021-DF.git)
- **Dual-Channel-Audio-Deepfake-Detection (IEEE Access 2025)**: [GitHub](https://github.com/gunwoo5034/Dual-Channel-Audio-Deepfake-Detection.git)
- **SafeEar: Content Privacy-Preserving Audio Deepfake Detection (ACM CCS 2024)**: [GitHub](https://github.com/LetterLiGo/SafeEar.git)
- **Cross-Domain-Audio-Deepfake-Detection-Dataset-and-Analysis (Conference on Empirical Methods in Natural Language Processing 2024)**: [GitHub](https://github.com/leolya/CD-ADD.git)
- **CLAD: Robust Audio Deepfake Detection Against Manipulation Attacks with Contrastive Learning (arXiv 2024)**: [GitHub](https://github.com/CLAD23/CLAD.git)
  


#### 📝 Text-Based Detection
- **TopFormer: Topology-Aware Authorship Attribution of Deepfake Texts with Diverse Writing Styles(ECAI 2024)**: [GitHub](https://github.com/AdaUchendu/topformer.git)
- **MAGE: Machine-generated Text Detection in the Wild (Association for Computational Linguistics 2024)**: [GitHub](https://github.com/yafuly/MAGE.git)
- **Deepfake Text Detection: Limitations and Opportunities (IEEE S\&P 2023)**: [GitHub](https://github.com/jmpu/DeepfakeTextDetection.git)


---

### 2. 🔀 Multi-modal Deepfake Detection

Combining two or more modalities (audio-video, image-text, etc.) for improved detection.

- **AntifakePrompt: Prompt-Tuned Vision-Language Models are Fake Image Detectors (arXive 2024)**: [GitHub](https://github.com/nctu-eva-lab/AntifakePrompt.git)
- **Raising the Bar of AI-generated Image Detection with CLIP (arXiv 2024)**: [GitHub](https://github.com/grip-unina/ClipBased-SyntheticImageDetection.git)
- **Can ChatGPT Detect DeepFakes? A Study of Using Multimodal Large Language Models for Media Forensics (arXiv 2024)**: [GitHub](https://github.com/shanface33/GPT4MF_UB.git)
- **Harnessing the Power of Large Vision Language Models for Synthetic Image Detection (arXiv 2024)**: [GitHub](https://github.com/Mamadou-Keita/VLM-DETECT.git)
- **GM-DF: Generalized Multi-Scenario Deepfake Detection (arXiv 2024)**: [GitHub](https://github.com/laiyingxin2/GM-DF.git)
- **Conditioned Prompt-Optimization for Continual Deepfake Detection (arXiv 2024)**: [GitHub](https://github.com/laitifranz/Prompt2Guard.git)
- **Robust Diffusion Model-Generated Image Detection with CLIP (arXiv 2024)**: [GitHub](https://github.com/Purdue-M2/Robust_DM_Generated_Image_Detection.git)
- DE-FAKE: Detection and Attribution of Fake Images Generated by Text-to-Image Generation Models (CCS 2023)**: [GitHub](https://github.com/zeyangsha/De-Fake.git)
- **Detecting and Grounding Multi-Modal Media Manipulation (CVPR 2023)**: [GitHub](https://github.com/rshaojimmy/MultiModal-DeepFake.git)
- **On Learning Multi-Modal Forgery Representation for Diffusion Generated Video Detection (NeurIPS 2024)**: [GitHub](https://github.com/SparkleXFantasy/MM-Det.git)
- **Common Sense Reasoning for Deepfake Detection (arXiv 2024)**: [GitHub](https://github.com/Reality-Defender/Research-DD-VQA.git)
- **Audio-Visual Person-of-Interest DeepFake Detection (CVPR 2023)**: [GitHub](https://github.com/grip-unina/poi-forensics.git)
- **Self-Supervised Video Forensics by Audio-Visual Anomaly Detection (CVPR 2023)**: [GitHub](https://github.com/cfeng16/audio-visual-forensics.git)
- **SpeechForensics: Audio-Visual Speech Representation Learning for Face Forgery Detection (NeurIPS 2024)**: [GitHub](https://github.com/Eleven4AI/SpeechForensics.git)
- **Lips Are Lying: Spotting the Temporal Inconsistency between Audio and Visual in Lip-syncing DeepFakes (NeruIPS 2024)**: [GitHub](https://github.com/AaronComo/LipFD.git)
- **Cross-Modality and Within-Modality Regularization for Audio-Visual DeepFake Detection (arXiv 2024)**: [GitHub](https://github.com/Vincent-ZHQ/MRDF.git)
- **A Multi-Stream Fusion Approach with One-Class Learning for Audio-Visual Deepfake Detection (arXiv 2024)**: [GitHub](https://github.com/bok-bok/MSOC.git)
- **AVFF: Audio-Visual Feature Fusion for Video Deepfake Detection (CVPR 2024)**: [GitHub](https://github.com/JoeLeelyf/OpenAVFF.git)
- **AVT2-DWF: Improving Deepfake Detection with Audio-Visual Fusion and Dynamic Weighting Strategies (arXiv 2024)**: [GitHub](https://github.com/raining-dev/AVT2-DWF.git)
- **Audio Multi-View Spoofing Detection Framework Based on Audio-Text-Emotion Correlations (IEEE 2024)**: [GitHub](https://github.com/ItzJuny/AMSDF.git)
- **AVoiD-DF: Audio-Visual Joint Learning for Detecting Deepfake (IEEE 2023)**: [GitHub](https://github.com/SYSU-DISG/AVoiD-DF.git)
- **A Hitchhikers Guide to Fine-Grained Face Forgery Detection Using Common Sense Reasoning (NeurIPS 2024)**: [GitHub](https://github.com/NickyFot/HitchhikersGuide.git)
- **Detecting Deepfakes Without Seeing Any (arXiv 2023)**: [GitHub](https://github.com/talreiss/FACTOR.git)
- **Vulnerability-Aware Spatio-Temporal Learning for Generalizable and Interpretable Deepfake Video Detection ()**: [GitHub](https://github.com/10Ring/FakeSTormer)
- **Where Deepfakes Gaze at? Spatial-Temporal Gaze Inconsistency Analysis for Video Face Forgery Detection (IEEE 2024)**: [GitHub](https://github.com/ziminMIAO/DFGaze.git)
- **GrDT: Towards Robust Deepfake Detection using Geometric Representation Distribution and Texture (WACV 2025)**: [GitHub](https://github.com/SIPLab24/GrDT.git)
- **FakeBench: Probing Explainable Fake Image Detection via Large Multimodal Models (arXiv 2024)**: [GitHub](https://github.com/Yixuan423/FakeBench.git)
- **AltFreezing for More General Video Face Forgery Detection (CVPR 2023)**: [GitHub](https://github.com/ZhendongWang6/AltFreezing.git)
  


---

### 3. ✨ Subtle Edits Detection & Localization

Focused on detecting and **localizing fine-grained manipulations** (e.g., minor face edits, inpainting, diffusion edits).
- **Is JPEG AI going to change image forensics? (arXiv 2025)**: [GitHub](https://github.com/polimi-ispl/jpeg-ai-antifor.git)
- **TruFor: Leveraging all-round clues for trustworthy image forgery detection and localization (CVPR 2023)**: [GitHub](https://github.com/grip-unina/TruFor.git)
- **A Lightweight and Effective Image Tampering Localization Network with Vision Mamba (arXiv 2025)**: [GitHub](https://github.com/multimediaFor/ForMa.git)
- **Hierarchical Fine-Grained Image Forgery Detection and Localization (CVPR 2023)**: [GitHub](https://github.com/CHELSEA234/HiFi_IFDL.git)
- **Exploring Multi-Modal Fusion for Image Manipulation Detection and Localization (MMM 2024)**: [GitHub](https://github.com/IDT-ITI/MMFusion-IML.git)
- **Localization of Diffusion Model-Based Inpainting through Inter-Intra Similarity of Frequency Features (Elsevier 2024)**: [GitHub](https://github.com/tmdrn9/Localization-of-Diffusion-Model-Based-Inpainting.git)
- **Exploring Multi-View Pixel Contrast for General and Robust Image Forgery Localization (IEEE 2025)**: [GitHub](https://github.com/multimediaFor/MPC.git)
- **IML-ViT: Benchmarking Image Manipulation Localization by Vision Transformer (arXiv 2023)**: [GitHub](https://github.com/SunnyHaze/IML-ViT.git)
- **DeCLIP: Decoding CLIP representations for deepfake localization (WACV 2025)**: [GitHub](https://github.com/bit-ml/DeCLIP.git)
- **Can We Get Rid of Handcrafted Feature Extractors? SparseViT: Nonsemantics-Centered, Parameter-Efficient Image Manipulation Localization through Spare-Coding Transformer (AAAI 2025)**: [GitHub](https://github.com/scu-zjz/SparseViT.git)
- **Weakly-supervised deepfake localization in diffusion-generated images (WACV 2024)**: [GitHub](https://github.com/bit-ml/dolos.git)
- **Dense Feature Interaction Network for Image Inpainting Localization (IEEE 2025)**: [GitHub](https://github.com/Boombb/DeFI-Net_Inpainting.git)
- **SAMIF: Adapting Segment Anything Model for Image Inpainting Forensics (ACCV 2024)**: [GitHub](https://github.com/xin-liao/xin-liao.github.io/blob/main/resource/SAMIF%20Adapting%20Segment%20Anything%20Model%20for%20Image%20Inpainting%20Forensics.pdf)
- **Pre-training-free Image Manipulation Localization through Non-Mutually Exclusive Contrastive Learning (ICCV 2023)**: [GitHub](https://github.com/Knightzjz/NCL-IML.git)
- **EditGuard: Versatile Image Watermarking for Tamper Localization and Copyright Protection (CVPR 2024)**: [GitHub](https://github.com/xuanyuzhang21/EditGuard.git)
- **OmniGuard: Hybrid Manipulation Localization via Augmented Versatile Deep Image Watermarking  (arXiv 2024)**: [GitHub](https://github.com/xuanyuzhang21/OmniGuard.git)
- **PIM-Net: Progressive Inconsistency Mining Network for Image Manipulation Localization (Pattern Recognition 2024)**: [GitHub](https://github.com/ningnbai/PIM-Net.git)
- **HDF-Net: Capturing Homogeny Difference Features to Localize the Tampered Image (IEEE 2024)**: [GitHub](https://github.com/ruidonghan/HDF-Net.git)
- **FFAA: Face Forgery Analysis Assistant (arXiv 2024)**: [GitHub](https://github.com/thu-huangzc/FFAA.git)
- **Toward real text manipulation detection: New dataset and new solution (Pattern Recogntion, 2024)**: [GitHub](https://github.com/DrLuo/RTM.git)
- **Towards Modern Image Manipulation Localization: A Large-Scale Dataset and Novel Methods(CVPR 2024)**: [GitHub](https://github.com/qcf-568/MIML.git)
- **ObjectFormer for Image Manipulation Detection and Localization (CVPR 2024)**: [GitHub](https://github.com/wdrink/Objectformer.git)
- **FakeShield: Explainable Image Forgery Detection and Localization via Multi-modal Large Language Models (ICLR 2025)**: [GitHub](https://github.com/zhipeixu/FakeShield.git)
- **Mesoscopic Insights: Orchestrating Multi-scale & Hybrid Architecture for Image Manipulation Localization (AAAI 2025)**: [GitHub](https://github.com/scu-zjz/Mesorch.git)
- **Detect Any Deepfakes: Segment Anything Meets Face Forgery Detection and Localization (CCBR 2023)**: [GitHub](https://github.com/laiyingxin2/DADF.git)
- **Spatio-Temporal Co-Attention Fusion Network for Video Splicing Localization (JEI 2024)**: [GitHub](https://github.com/multimediaFor/SCFNet.git)
- **Undercover Deepfakes: Detecting Fake Segments in Videos (ICCV 2023)**: [GitHub](https://github.com/rgb91/temporal-deepfake-segmentation.git)
- **Locate and Verify: A Two-Stream Network for Improved Deepfake Detection (ACM MM'23)**: [GitHub](https://github.com/sccsok/Locate-and-Verify.git)
- **Localization and detection of deepfake videos based on self-blending method (nature 2025)**: [GitHub](https://pan.baidu.com/share/init?surl=nHD5QUYF_2MLlGbhGZv52w&pwd=1234)
- **Interpretable Spatial-Temporal Video Transformer for Deepfake Detection (IEEE 2023)**: [GitHub](https://github.com/Vill-Lab/2023-TIFS-ISTVT.git)
- **VANE-Bench: Video Anomaly Evaluation Benchmark for Conversational LMMs (NAACL 2025)**: [GitHub](https://github.com/rohit901/VANE-Bench.git)
- **1M-Deepfakes Detection Challenge (MM 2024)**: [GitHub](https://github.com/ControlNet/AV-Deepfake1M.git)
- **Glitch in the Matrix: A Large Scale Benchmark for Content Driven Audio-Visual Forgery Detection and Localization (CVIU 2023)**: [GitHub](https://github.com/ControlNet/LAV-DF.git)
- **WWW: Where, Which and Whatever Enhancing Interpretability in Multimodal Deepfake Detection (arXiv 2024)**: [GitHub](https://github.com/lsy0882/FakeMix.git)
- **Contextual Cross-Modal Attention for Audio-Visual Deepfake Detection and Localization (IEEE 2024)**: [GitHub](https://github.com/vcbsl/audio-visual-deepfake.git)
- **AVT2-DWF: Improving Deepfake Detection with Audio-Visual Fusion and Dynamic Weighting Strategies (arXiv 2024)**: [GitHub](https://github.com/raining-dev/AVT2-DWF.git)
- **UMMAFormer: A Universal Multimodal-adaptive Transformer Framework For Temporal Forgery Localization (ACM MM'23)**: [GitHub](https://github.com/ymhzyj/UMMAFormer.git)
- **LlamaPartialSpoof: An LLM-Driven Fake Speech Dataset Simulating Disinformation Generation (IEEE 2025)**: [GitHub](https://github.com/hieuthi/LlamaPartialSpoof.git)
- **AudioSeal: Proactive Detection of Voice Cloning with Localized Watermarking (ICML 2024)**: [GitHub](https://github.com/facebookresearch/audioseal.git)
- **Coarse-to-Fine Proposal Refinement Framework for Audio Temporal Forgery Detection and Localization (ACM MM'24)**: [GitHub](https://github.com/ItzJuny/CFPRF.git)
- **Adversarial Training and Gradient Optimization for Partially Deepfake Audio Localization (ICASSP 2025)**: [GitHub](https://github.com/Little-dingding/ATGO.git)
- **HFMF: Hierarchical Fusion Meets Multi-Stream Models for Deepfake Detection (WACV 2025)**: [GitHub](https://github.com/taco-group/HFMF.git)
- **Multi-spectral Class Center Network for Face Manipulation Detection and Localization (arXiv 2024)**: [GitHub](https://github.com/miaoct/MSCCNet.git)


---

### 4. 🧪 Adversarial attacks Methods on Deepfake detection models

These papers address the critical issue of **robustness against adversarial attacks**, a gap identified in most detection systems.

### Image and Video Attacks
- **Evading DeepFake Detectors via Adversarial Statistical Consistency (CVPR 2023)**: [GitHub](https://github.com/tobuta/evadingfakedetector.git)
- **Imperceptible Adversarial Attack via Invertible Neural Networks (AAAI 2023)**: [GitHub](https://github.com/jjhuangcs/AdvINN.git)
- **Towards Quantitative Evaluation of Explainable AI Methods for Deepfake Detection (ICASSP 2024)**: [GitHub](https://github.com/IDT-ITI/XAI-Deepfakes.git)
- **ROBUSTNESS OF AI-IMAGE DETECTORS: FUNDAMENTAL LIMITS AND PRACTICAL ATTACKS (ICLR 2024)**: [GitHub](https://github.com/mehrdadsaberi/watermark_robustness.git)
- **2D-Malafide: Adversarial Attacks Against Face Deepfake Detection Systems (BIOSIG 2024)**: [GitHub](https://github.com/eurecom-fscv/2D-Malafide.git)
- **AVA: Inconspicuous Attribute Variation-based Adversarial Attack bypassing DeepFake Detection (arXiv 2023)**: [GitHub](https://github.com/AnonymousUserA/AVA.git)
- **StealthDiffusion: Towards Evading Diffusion Forensic Detection through Diffusion Model (ACM MM'24)**: [GitHub](https://github.com/wyczzy/StealthDiffusion.git)
- **DiffAM: Diffusion-based Adversarial Makeup Transfer for Facial Privacy Protection (CVPR 2024)**: [GitHub](https://github.com/HansSunY/DiffAM.git)
- **Efficient Generation of Targeted and Transferable Adversarial Examples for Vision-Language Models Via Diffusion Models (IEEE 2025)**: [GitHub](https://github.com/gq-max/AdvDiffVLM.git)
- **Unlocking The Potential of Adaptive Attacks on Diffusion-Based Purification (arXiv 2025)**: [GitHub](https://github.com/andrekassis/DiffBreak.git)
- **DiffProtect: Generate Adversarial Examples with Diffusion Models for Facial Privacy Protection (arXiv 2023)**: [GitHub](https://github.com/joellliu/DiffProtect.git)


---

### 5 🧪 Adversarial Robustness-Focused Methods
- **Defense against Adversarial Attacks on Audio DeepFake Detection (Proc. INTERSPEECH 2023)**: [GitHub](https://github.com/piotrkawa/audio-deepfake-adversarial-attacks.git)
- **XAI-Based Detection of Adversarial Attacks on Deepfake Detectors (TMLR 2024)**: [GitHub](https://github.com/razla/XAI-Based-Detection-of-Adversarial-Attacks-on-Deepfake-Detectors.git)
- **CapsFake: A Multimodal Capsule Network for Detecting Instruction-Guided Deepfakes (arXiv 2025)**: [GitHub](https://github.com/tuanrpt/CapsFake.git)



### 6. 🚀 Datasets & Benchmarks

A list of datasets used or referenced in the reviewed papers.

- **AV-Deepfake1M: A large-scale LLM-driven audio-visual deepfake dataset (MM 2024)**: [GitHub](https://github.com/ControlNet/AV-Deepfake1M.git)

| Modality        | Dataset Examples                                    |
|------------------|----------------------------------------------------|
| Image            | FFHQ, ProGAN, COCO, ForenSynths                    |
| Video            | FaceForensics++, DFDC, Celeb-DF                    |
| Audio            | ASVspoof, FakeAVCeleb                              |
| Text             | OpenLLMText, TweepFake, RealNews                   |
| Multi-modal      | FakeAVCeleb, AV-Deepfake1M, AVSecure               |

---

## 🤝 Contributing

We welcome contributions from the community to keep this repository up-to-date with new methods, datasets, and benchmarks. Please open an issue or a pull request if you'd like to contribute.

---

## 📫 Contact

For questions or collaborations, reach out to:  
📧 **Naseem Khan** — nakh12498@hbku.edu.qa  
🏛️ Hamad Bin Khalifa University, Qatar

---

© 2025 | For academic and non-commercial use only.
