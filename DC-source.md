# PPT 第 4 页论文排序：Open-Surface Mesh / Dual Contouring 相关性

Generated: 2026-06-22

来源：当前 `2026.6-3D-Rep&Gen-v7-WendaShi.pptx` 第 4 页仍可见的 53 篇论文；已排除之前从 PPT 中删除的 E50/E51/E52/E55/E56 Gaussian Splatting 条目，并补入本地 CVPR 2026 Oral 核心 open-surface 论文 L02/L03。

说明：以下“摘要中文译述”基于官方会议页的 abstract 或 SIGGRAPH 官方 description 改写，避免逐字长段转载。排序优先考虑：
- `OpenSurfaceMesh`：是否直接输出/保持/学习开放表面、非水密表面、garment panels/seams、显式 mesh 或 surface reconstruction。
- `DualContouring`：是否直接使用 Dual Contouring，或与 UDF/SDF/voxel/implicit surface extraction 有机制关联。
- 综合排序：先看 open-surface/simulation-ready garment 和 UDF/open reconstruction，再看 mesh-native generation/reconstruction，最后是 CAD、texture、face/body、strand 等弱相关条目。

## 快速排序表

| Rank | ID | Paper | Venue | OpenSurfaceMesh | DualContouring | Primary link |
| --- | --- | --- | --- | ---: | ---: | --- |
| 1 | E11 | Dual Contouring over Expanded Cubes (DCx) for Zero-Level Set Extraction from Neural Unsigned Distance Functions | SIGGRAPH 2026 | 5/5 | 5/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_1461&sess=sess146) |
| 2 | L03 | TRELLIS.2: Native and Compact Structured Latents for 3D Generation | CVPR 2026 Oral | 5/5 | 4/5 | [Project Page](https://microsoft.github.io/TRELLIS.2/) |
| 3 | L02 | Faithful Contouring: Near-Lossless 3D Voxel Representation Free from Iso-surface | CVPR 2026 Oral | 5/5 | 3/5 | [arXiv](https://arxiv.org/abs/2511.04029) |
| 4 | E08 | Distilling Unsigned Distance Function for Surface Reconstruction from 3D Gaussian Splatting | CVPR 2026 | 5/5 | 3/5 | [CVPR OpenAccess](https://openaccess.thecvf.com/content/CVPR2026/html/Li_Distilling_Unsigned_Distance_Function_for_Surface_Reconstruction_from_3D_Gaussian_CVPR_2026_paper.html) |
| 5 | E24 | Garment Particles: A 2D–3D Symmetric Garment Representation for Generation and Editing | SIGGRAPH 2026 | 5/5 | 1/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_584&sess=sess117) |
| 6 | E26 | PatternGSL: A Structured Specification Language for Template-Free and Simulation-Ready 3D Garments | SIGGRAPH 2026 | 5/5 | 1/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_185&sess=sess117) |
| 7 | E04 | ReWeaver: Towards Simulation-Ready and Topology-Accurate Garment Reconstruction | CVPR 2026 | 5/5 | 1/5 | [CVPR OpenAccess](https://openaccess.thecvf.com/content/CVPR2026/html/Li_ReWeaver_Towards_Simulation-Ready_and_Topology-Accurate_Garment_Reconstruction_CVPR_2026_paper.html) |
| 8 | E25 | Learning Sewing Patterns via Latent Flow Matching of Implicit Fields | SIGGRAPH 2026 | 5/5 | 1/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_292&sess=sess117) |
| 9 | E05 | SwiftTailor: Efficient 3D Garment Generation with Geometry Image Representation | CVPR 2026 | 5/5 | 0/5 | [Project Page](https://qualcomm-ai-research.github.io/SwiftTailor) |
| 10 | E47 | GarmentGPT: Compositional Garment Pattern Generation via Discrete Latent Tokenization | ICLR 2026 | 5/5 | 0/5 | [OpenReview](https://openreview.net/forum?id=XzXKnazRBF) |
| 11 | E27 | LoBoFit: Flexible Garment Refitting via Local Bone Mapping Blending | SIGGRAPH 2026 | 4/5 | 0/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_718&sess=sess117) |
| 12 | E28 | Surface Reconstruction from Unoriented Points via Green’s 3rd Identity | SIGGRAPH 2026 | 4/5 | 2/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_889&sess=sess153) |
| 13 | E48 | Mesh Splatting for End-to-end Multiview Surface Reconstruction | ICLR 2026 | 4/5 | 1/5 | [OpenReview](https://openreview.net/forum?id=PSgps4JXTb) |
| 14 | E34 | FastSESR: Fast Scene-level Explicit Surface Reconstruction | ICML 2026 | 4/5 | 1/5 | [Official page](https://icml.cc/virtual/2026/poster/64625) |
| 15 | E03 | PixARMesh: Autoregressive Mesh-Native Single-View Scene Reconstruction | CVPR 2026 | 4/5 | 0/5 | [Project Page](https://mlpc-ucsd.github.io/PixARMesh/) |
| 16 | E02 | MeshWeaver: Sparse-Voxel-Guided Surface Weaving for Autoregressive Mesh Generation | CVPR 2026 | 4/5 | 0/5 | [CVPR OpenAccess](https://openaccess.thecvf.com/content/CVPR2026/html/Xu_MeshWeaver_Sparse-Voxel-Guided_Surface_Weaving_for_Autoregressive_Mesh_Generation_CVPR_2026_paper.html) |
| 17 | E01 | FACE: A Face-based Autoregressive Representation for High-Fidelity and Efficient Mesh Generation | CVPR 2026 Highlight | 4/5 | 0/5 | [CVPR OpenAccess](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_FACE_A_Face-based_Autoregressive_Representation_for_High-Fidelity_and_Efficient_Mesh_CVPR_2026_paper.html) |
| 18 | E17 | Nexus: Native Mesh Generation with Diffusion | SIGGRAPH 2026 | 4/5 | 0/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_808&sess=sess121) |
| 19 | E18 | MeshFlow: Mesh Generation with Equivariant Flow Matching | SIGGRAPH 2026 | 4/5 | 0/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_1165&sess=sess121) |
| 20 | E29 | LATO: 3D Mesh Flow Matching with Structured TOpology Preserving LAtents | ICML 2026 | 4/5 | 0/5 | [Official page](https://icml.cc/virtual/2026/poster/61796) |
| 21 | E41 | QuadGPT: Native Quadrilateral Mesh Generation with Autoregressive Models | ICLR 2026 | 4/5 | 0/5 | [Project Page](https://hitcslj.github.io/QuadGPT/) |
| 22 | E42 | Topology-Preserved Auto-regressive Mesh Generation in the Manner of Weaving Silk | ICLR 2026 | 4/5 | 0/5 | [Project Page](https://gaochao-s.github.io/pages/MeshSilksong/) |
| 23 | E19 | Strips as Tokens: Artist Mesh Generation with Native UV Segmentation | SIGGRAPH 2026 | 3/5 | 0/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_164&sess=sess121) |
| 24 | E43 | Unsupervised Representation Learning for 3D Mesh Parameterization with Semantic and Visibility Objectives | ICLR 2026 | 3/5 | 0/5 | [Project Page](https://ahhhz975.github.io/Automatic3DMeshParameterization/) |
| 25 | E14 | Differentiable Voxelization of Surface Representations | SIGGRAPH 2026 | 3/5 | 1/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_1260&sess=sess149) |
| 26 | E32 | Focusing: View-Consistent Sparse Voxels for Efficient 3D VAE | ICML 2026 | 3/5 | 1/5 | [Official page](https://icml.cc/virtual/2026/poster/63722) |
| 27 | E44 | Neural Compression of 3D Meshes using Sparse Implicit Representation | ICLR 2026 | 3/5 | 1/5 | [Project Page](https://github.com/yydlmzyz1/SIR-SNC) |
| 28 | E12 | SuperSDF:Sparse SDF Super-Resolution for Surface Extraction | SIGGRAPH 2026 | 2/5 | 2/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_1060&sess=sess146) |
| 29 | E35 | NoiseSDF2NoiseSDF: Learning Clean Neural Fields from Noisy Supervision | ICML 2026 | 2/5 | 2/5 | [Official page](https://icml.cc/virtual/2026/poster/63881) |
| 30 | E13 | SAND: Spatially Adaptive Network Depth for Fast Sampling of Neural Implicit Surfaces | SIGGRAPH 2026 | 2/5 | 1/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_770&sess=sess146) |
| 31 | E33 | $\texttt{PRISM}$:A 3D Probabilistic Neural Representation for Interpretable Shape Modeling | ICML 2026 | 2/5 | 0/5 | [Official page](https://icml.cc/virtual/2026/poster/63964) |
| 32 | E45 | DiMeR: Disentangled Mesh Reconstruction Model with Normal-only Geometry Training | ICLR 2026 | 3/5 | 0/5 | [Project Page](https://lutao2021.github.io/DiMeR_page/) |
| 33 | E31 | XSpecMesh: Quality-Preserving Auto-Regressive Mesh Generation Acceleration via Multi-Head Speculative Decoding | ICML 2026 | 3/5 | 0/5 | [Official page](https://icml.cc/virtual/2026/poster/66559) |
| 34 | E30 | TextMesh4D: Zero-shot Text-to-4D Mesh Generation | ICML 2026 | 3/5 | 0/5 | [Official page](https://icml.cc/virtual/2026/poster/64889) |
| 35 | E49 | Guaranteed Simply Connected Mesh Reconstruction from an Unorganized Point Cloud | ICLR 2026 | 2/5 | 1/5 | [OpenReview](https://openreview.net/forum?id=jjEnTBsffi) |
| 36 | E15 | DualBrep: A Dual-Field Continuous Representation for B-rep Modelling | SIGGRAPH 2026 | 2/5 | 1/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_295&sess=sess142) |
| 37 | E16 | Autoregressive B-Rep Shape Generation with Parametric Surfaces | SIGGRAPH 2026 | 2/5 | 0/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_165&sess=sess142) |
| 38 | E38 | Brep2Shape: Boundary and Shape Representation Alignment via Self-supervised Transformers | ICML 2026 | 2/5 | 0/5 | [Official page](https://icml.cc/virtual/2026/poster/62274) |
| 39 | E39 | CADFit: Precise Mesh-to-CAD Program Generation with Hybrid Optimization | ICML 2026 | 2/5 | 0/5 | [Project Page](https://ghadinehme.github.io/cadfit.github.io/) |
| 40 | E40 | Bridging Tokens and Geometry: Token-wise 3D Supervision for CAD Generation | ICML 2026 | 2/5 | 0/5 | [Official page](https://icml.cc/virtual/2026/poster/65302) |
| 41 | E09 | FILTR: Extracting Topological Features from Pretrained 3D Models | CVPR 2026 Oral | 1/5 | 0/5 | [Project Page](https://filtr-topology.github.io/) |
| 42 | E54 | LiTo: Surface Light Field Tokenization | ICLR 2026 | 1/5 | 0/5 | [Project Page](https://apple.github.io/ml-lito/) |
| 43 | E37 | GHOST: Geometry-Guided Hallucination of Opaque Surface Textures | ICML 2026 | 1/5 | 0/5 | [Official page](https://icml.cc/virtual/2026/poster/65389) |
| 44 | E07 | Representing 3D Faces with Learnable B-Spline Volumes | CVPR 2026 Highlight | 1/5 | 0/5 | [CVPR OpenAccess](https://openaccess.thecvf.com/content/CVPR2026/html/Chandran_Representing_3D_Faces_with_Learnable_B-Spline_Volumes_CVPR_2026_paper.html) |
| 45 | E46 | Pixel3DMM: Versatile Screen-Space Priors for Single-Image 3D Face Reconstruction | ICLR 2026 | 1/5 | 0/5 | [Project Page](https://simongiebenhain.github.io/pixel3dmm/) |
| 46 | E53 | UniF$^2$ace: A $\underline{Uni}$fied $\underline{F}$ine-grained $\underline{Face}$ Understanding and Generation Model | ICLR 2026 | 0/5 | 0/5 | [OpenReview](https://openreview.net/forum?id=LV01JdxARe) |
| 47 | E10 | SAM 3D Body: Robust Full-Body Human Mesh Recovery | CVPR 2026 Oral | 1/5 | 0/5 | [CVPR OpenAccess](https://openaccess.thecvf.com/content/CVPR2026/html/Yang_SAM_3D_Body_Robust_Full-Body_Human_Mesh_Recovery_CVPR_2026_paper.html) |
| 48 | E36 | SAMT: Generating Structured Avatar Meshes and Textures from a Single Image | ICML 2026 | 1/5 | 0/5 | [Official page](https://icml.cc/virtual/2026/poster/61104) |
| 49 | E06 | EfficientMonoHair: Fast Strand-Level Reconstruction from Monocular Video via Multi-View Direction Fusion | CVPR 2026 | 0/5 | 0/5 | [CVPR OpenAccess](https://openaccess.thecvf.com/content/CVPR2026/html/Li_EfficientMonoHair_Fast_Strand-Level_Reconstruction_from_Monocular_Video_via_Multi-View_Direction_CVPR_2026_paper.html) |
| 50 | E20 | HairLRM: Strand-based Hair Modeling via Large Reconstruction Models | SIGGRAPH 2026 | 0/5 | 0/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_371&sess=sess119) |
| 51 | E21 | HairGPT: A Unified Autoregressive Framework for 3D Realistic Hairstyle Synthesis | SIGGRAPH 2026 | 0/5 | 0/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_869&sess=sess119) |
| 52 | E22 | HairPort: In-context 3D-aware Hair Import and Transfer for Images | SIGGRAPH 2026 | 0/5 | 0/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_204&sess=sess119) |
| 53 | E23 | Curvature Space Editing of Highly-Coiled Hair | SIGGRAPH 2026 | 0/5 | 0/5 | [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_651&sess=sess119) |

## 详细条目

### 01. E11 — Dual Contouring over Expanded Cubes (DCx) for Zero-Level Set Extraction from Neural Unsigned Distance Functions

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=5/5`, `DualContouring=5/5`
- 排序理由: 直接把 Dual Contouring 从 SDF 扩展到 neural UDF，并显式面向 non-manifold / complex topology；这是当前页里与 open surface mesh 和 DC 都最直接相关的论文。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_1461&sess=sess146)
- 摘要中文译述: DCx 将传统 Dual Contouring 从有符号距离场扩展到无符号距离场，用 expanded 2x2x2 cube 查表来抽取零水平集，从而支持更复杂、尤其是非流形结构的表面提取。

### 02. L03 — TRELLIS.2: Native and Compact Structured Latents for 3D Generation

- Venue: CVPR 2026 Oral
- Scores: `OpenSurfaceMesh=5/5`, `DualContouring=4/5`
- 排序理由: O-Voxel 明确支持 open、non-manifold 和 enclosed surfaces；同时它的 Flexible Dual Grid 是 field-free 的 DC-like 路线：直接用 mesh surface 与 voxel / dual-grid edges 求交得到 edge intersection flags 和 Hermite data，再做 QEF vertex placement。它很接近 Dual Contouring 的几何机制，但不是 SDF-sampled Dual Contouring。
- Link: [Project Page](https://microsoft.github.io/TRELLIS.2/); [arXiv](https://arxiv.org/abs/2512.14692); [Code](https://github.com/microsoft/TRELLIS); local PDF: [CVPR26oral_Trellis-2.pdf](CVPR26oral_Trellis-2.pdf)
- 摘要中文译述: TRELLIS.2 提出面向大规模 3D 生成的 native structured latent O-Voxel，把开放表面、非流形结构和封闭表面统一到紧凑稀疏体素/dual-grid 表示中；再通过 Sparse Compression VAE 和 flow matching 生成高质量 3D assets，同时保持比传统稠密场或单纯 mesh token 更强的结构性与可扩展性。

### 03. L02 — Faithful Contouring: Near-Lossless 3D Voxel Representation Free from Iso-surface

- Venue: CVPR 2026 Oral
- Scores: `OpenSurfaceMesh=5/5`, `DualContouring=3/5`
- 排序理由: 这是 field-free sparse voxel mesh representation，直接面向 arbitrary real-world meshes，包括 non-watertight 和 non-manifold；它避开 SDF/iso-surface 转换造成的闭合化和细节损失。和 Dual Contouring 的关联在 voxel/contouring/mesh extraction 层面，但它不是经典 SDF Dual Contouring。
- Link: [arXiv](https://arxiv.org/abs/2511.04029); local PDF: [CVPR26oral_Faithful_contouring.pdf](CVPR26oral_Faithful_contouring.pdf)
- 摘要中文译述: Faithful Contouring 提出一种近乎无损的稀疏体素化 mesh 表示，既不把任意 mesh 转成连续 field function，也不依赖 iso-surface remeshing；它能保留开放边界、非流形结构、尖锐特征和内部结构，并配合 dual-mode autoencoder 在复杂真实 mesh 上实现高质量重建与紧凑编码。

### 04. E08 — Distilling Unsigned Distance Function for Surface Reconstruction from 3D Gaussian Splatting

- Venue: CVPR 2026
- Scores: `OpenSurfaceMesh=5/5`, `DualContouring=3/5`
- 排序理由: UDF 明确适合 open surface；虽然不是 dual contouring 方法，但它把 3DGS 几何蒸馏成 UDF，是后续 open-surface meshing 的关键桥梁。
- Link: [CVPR OpenAccess](https://openaccess.thecvf.com/content/CVPR2026/html/Li_Distilling_Unsigned_Distance_Function_for_Surface_Reconstruction_from_3D_Gaussian_CVPR_2026_paper.html); official: [official page](https://cvpr.thecvf.com/virtual/2026/poster/38929)
- 摘要中文译述: 论文指出 UDF 适合开放表面，但多视图图像监督下难学；方法把 patch-based UDF 先验蒸馏进 Gaussian 优化过程，用近表面可靠监督和可见性/几何置信权重稳定训练并保留细节。

### 05. E24 — Garment Particles: A 2D–3D Symmetric Garment Representation for Generation and Editing

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=5/5`, `DualContouring=1/5`
- 排序理由: Garment particles 同时编码 2D sewing pattern 和 3D garment geometry，天然是 open cloth surface 任务；与 DC 只在“表面重建输出”层面弱相关。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_584&sess=sess117)
- 摘要中文译述: Garment Particles 用 5D point-cloud 同时表示二维纸样和三维服装几何，并基于 rectified flow 支持文本/图像到 simulation-ready sewing pattern 的生成，以及 2D/3D 联动编辑。

### 06. E26 — PatternGSL: A Structured Specification Language for Template-Free and Simulation-Ready 3D Garments

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=5/5`, `DualContouring=1/5`
- 排序理由: 明确目标是 simulation-ready garment，并有 panel/edge/stitch topology；这是 Garment4Robo 方向很靠前的 open-surface 表示。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_185&sess=sess117)
- 摘要中文译述: PatternGSL 提出结构化、template-free 的服装规格语言；从单张服装图像预测可编辑纸样，并显式表示 panel、edge 和 stitch 拓扑，用于重建、布料仿真和设计流程。

### 07. E04 — ReWeaver: Towards Simulation-Ready and Topology-Accurate Garment Reconstruction

- Venue: CVPR 2026
- Scores: `OpenSurfaceMesh=5/5`, `DualContouring=1/5`
- 排序理由: 重建 garment topology、seams、panels 和 sewing structure，直接服务 simulation-ready open cloth mesh。
- Link: [CVPR OpenAccess](https://openaccess.thecvf.com/content/CVPR2026/html/Li_ReWeaver_Towards_Simulation-Ready_and_Topology-Accurate_Garment_Reconstruction_CVPR_2026_paper.html); official: [official page](https://cvpr.thecvf.com/virtual/2026/poster/38489)
- 摘要中文译述: ReWeaver 从稀疏多视图 RGB 图像重建拓扑准确的三维服装和缝纫纸样，预测 2D/3D 中的 seams、panels 及连接关系，使结果可转成仿真可用的高保真服装。

### 08. E25 — Learning Sewing Patterns via Latent Flow Matching of Implicit Fields

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=5/5`, `DualContouring=1/5`
- 排序理由: sewing pattern implicit fields 面向 panel geometry 与 stitching；open garment topology 明确，但不是 mesh extraction / DC。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_292&sess=sess117)
- 摘要中文译述: 该工作用距离场隐式表示缝纫纸样，再结合 latent flow matching 学习 panel 几何和缝合关系分布，支持生成、图像估计和优化，并可处理灵活拓扑。

### 09. E05 — SwiftTailor: Efficient 3D Garment Generation with Geometry Image Representation

- Venue: CVPR 2026
- Scores: `OpenSurfaceMesh=5/5`, `DualContouring=0/5`
- 排序理由: geometry image 表示 garment panels 并输出 3D mesh；open cloth 相关性强，但与 dual contouring 基本无关。
- Link: [Project Page](https://qualcomm-ai-research.github.io/SwiftTailor); official: [official page](https://cvpr.thecvf.com/virtual/2026/poster/36938)
- 摘要中文译述: SwiftTailor 先用轻量视觉语言模块预测 sewing pattern，再用 dense prediction transformer 生成 Garment Geometry Image，在统一 UV 空间编码服装表面，并通过反向映射、重网格化和动态缝合得到 3D mesh。

### 10. E47 — GarmentGPT: Compositional Garment Pattern Generation via Discrete Latent Tokenization

- Venue: ICLR 2026
- Scores: `OpenSurfaceMesh=5/5`, `DualContouring=0/5`
- 排序理由: 离散 latent token 生成 garment pattern，强相关于 open garment surface 的上游纸样表示；不是网格抽取算法。
- Link: [OpenReview](https://openreview.net/forum?id=XzXKnazRBF); official: [official page](https://iclr.cc/virtual/2026/poster/10008926)
- 摘要中文译述: GarmentGPT 用 RVQ-VAE 将连续纸样边界曲线 token 化，再由微调的视觉语言模型自回归生成离散 token 序列，使服装生成从低层坐标回归转向可组合的纸样结构推理。

### 11. E27 — LoBoFit: Flexible Garment Refitting via Local Bone Mapping Blending

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=4/5`, `DualContouring=0/5`
- 排序理由: garment refitting 保留衣物细节和 fit style，面向开放衣物表面，但不是核心表示/抽面方法。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_718&sess=sess117)
- 摘要中文译述: LoBoFit 通过 blended local bone coordinates 对服装进行优化式 refitting，在大体型变化、任意姿态和多层衣物下保留原始设计特征、皱褶和穿着风格。

### 12. E28 — Surface Reconstruction from Unoriented Points via Green’s 3rd Identity

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=4/5`, `DualContouring=2/5`
- 排序理由: 从 unoriented points 做 surface reconstruction，与 open/partial scan 很相关；不是 DC，但属于 surface extraction 栈。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_889&sess=sess153)
- 摘要中文译述: G3R 用 Green 第三恒等式从无朝向点云恢复全局一致法线，并通过条件良好的线性系统减少 winding-number 类方法的切向零空间问题，从而提升表面重建质量。

### 13. E48 — Mesh Splatting for End-to-end Multiview Surface Reconstruction

- Venue: ICLR 2026
- Scores: `OpenSurfaceMesh=4/5`, `DualContouring=1/5`
- 排序理由: 直接以 mesh/surface 为核心，通过 splatting 让 mesh 可端到端多视图优化；不是 open-boundary 专门方法，但 mesh reconstruction 相关性高。
- Link: [OpenReview](https://openreview.net/forum?id=PSgps4JXTb); official: [official page](https://iclr.cc/virtual/2026/poster/10009671)
- 摘要中文译述: Mesh Splatting 将 mesh 软化为多层半透明结构，使其可通过 volumetric rendering 端到端优化；结合 splatting renderer 和拓扑控制，在较短时间内得到更高质量的表面重建 mesh。

### 14. E34 — FastSESR: Fast Scene-level Explicit Surface Reconstruction

- Venue: ICML 2026
- Scores: `OpenSurfaceMesh=4/5`, `DualContouring=1/5`
- 排序理由: scene-level explicit surface reconstruction，输出三角面片；对 open scene surfaces 有用，但没有 DC/UDF 机制。
- Link: [Official page](https://icml.cc/virtual/2026/poster/64625)
- 摘要中文译述: FastSESR 用两阶段框架快速从点云恢复显式场景表面：先用 triangular candidate network 捕捉局部连接，再用 offset optimization network 细化几何，大幅加速场景级重建。

### 15. E03 — PixARMesh: Autoregressive Mesh-Native Single-View Scene Reconstruction

- Venue: CVPR 2026
- Scores: `OpenSurfaceMesh=4/5`, `DualContouring=0/5`
- 排序理由: mesh-native scene reconstruction，避免 SDF 后处理；open-boundary 不是核心主张，但对显式 mesh pipeline 很有用。
- Link: [Project Page](https://mlpc-ucsd.github.io/PixARMesh/); official: [official page](https://cvpr.thecvf.com/virtual/2026/poster/40089)
- 摘要中文译述: PixARMesh 从单张 RGB 图像自回归重建完整室内场景 mesh，同时预测物体布局和几何，用 pixel-aligned 图像特征与场景上下文生成紧凑、高质量的 artist-ready mesh。

### 16. E02 — MeshWeaver: Sparse-Voxel-Guided Surface Weaving for Autoregressive Mesh Generation

- Venue: CVPR 2026
- Scores: `OpenSurfaceMesh=4/5`, `DualContouring=0/5`
- 排序理由: native mesh generation + sparse voxel scaffold；对 mesh 表示强相关，但 open-surface/边界保持未作为核心保证。
- Link: [CVPR OpenAccess](https://openaccess.thecvf.com/content/CVPR2026/html/Xu_MeshWeaver_Sparse-Voxel-Guided_Surface_Weaving_for_Autoregressive_Mesh_Generation_CVPR_2026_paper.html); official: [official page](https://cvpr.thecvf.com/virtual/2026/poster/38494)
- 摘要中文译述: MeshWeaver 将 mesh 生成视为 surface weaving，不再独立预测坐标，而是逐顶点生成；多层 sparse-voxel encoder 提供局部几何上下文和结构约束，提高高面数 mesh 的保真度。

### 17. E01 — FACE: A Face-based Autoregressive Representation for High-Fidelity and Efficient Mesh Generation

- Venue: CVPR 2026 Highlight
- Scores: `OpenSurfaceMesh=4/5`, `DualContouring=0/5`
- 排序理由: face-level mesh tokens 是显式 mesh 生成方向的强基线；但没有针对 open boundaries 或 DC。
- Link: [CVPR OpenAccess](https://openaccess.thecvf.com/content/CVPR2026/html/Wang_FACE_A_Face-based_Autoregressive_Representation_for_High-Fidelity_and_Efficient_Mesh_CVPR_2026_paper.html); official: [official page](https://cvpr.thecvf.com/virtual/2026/poster/39237)
- 摘要中文译述: FACE 把三角面片作为基本 token，避免把 mesh 拉平成过长的顶点坐标序列；这种 one-face-one-token 策略显著压缩序列长度，并结合 VecSet encoder 和 latent diffusion 实现高质量 image-to-mesh。

### 18. E17 — Nexus: Native Mesh Generation with Diffusion

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=4/5`, `DualContouring=0/5`
- 排序理由: native polygon mesh diffusion，且描述中提到 complex/non-manifold geometry；open-surface 需全文确认，DC 无关。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_808&sess=sess121)
- 摘要中文译述: Nexus 用两阶段 diffusion 直接生成高保真 polygon meshes，通过几何结构和拓扑 diffusion 替代慢速序列建模，以更快、更可控的方式处理复杂 mesh。

### 19. E18 — MeshFlow: Mesh Generation with Equivariant Flow Matching

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=4/5`, `DualContouring=0/5`
- 排序理由: 直接生成 triangle mesh，属于 mesh-native 方向；open surface 与 DC 都不是核心。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_1165&sess=sess121)
- 摘要中文译述: MeshFlow 用 equivariant flow matching / diffusion 框架，把随机 triangle soups 转换成高质量 mesh，强调快速生成和几何一致性。

### 20. E29 — LATO: 3D Mesh Flow Matching with Structured TOpology Preserving LAtents

- Venue: ICML 2026
- Scores: `OpenSurfaceMesh=4/5`, `DualContouring=0/5`
- 排序理由: 显式 mesh latent，恢复 topology 不依赖 isosurface extraction；与 open boundary 未直接绑定，但比 SDF 后处理更接近 mesh-native。
- Link: [Official page](https://icml.cc/virtual/2026/poster/61796)
- 摘要中文译述: LATO 用 anchored-on-surface 的 Vertex Displacement Field 表示 mesh，并用 sparse voxel VAE 压缩成结构化 topology-aware latent；解码时逐步细分/剪枝体素并预测顶点连接。

### 21. E41 — QuadGPT: Native Quadrilateral Mesh Generation with Autoregressive Models

- Venue: ICLR 2026
- Scores: `OpenSurfaceMesh=4/5`, `DualContouring=0/5`
- 排序理由: native quad mesh generation，拓扑质量重要；但 abstract 更偏 quad topology/watertight asset，不是 open surface。
- Link: [Project Page](https://hitcslj.github.io/QuadGPT/); official: [official page](https://iclr.cc/virtual/2026/poster/10007410)
- 摘要中文译述: QuadGPT 端到端生成以四边形为主的 mesh，提出统一 tokenization 处理三角/四边混合拓扑，并用强化学习式微调提升生成质量和拓扑指标。

### 22. E42 — Topology-Preserved Auto-regressive Mesh Generation in the Manner of Weaving Silk

- Venue: ICLR 2026
- Scores: `OpenSurfaceMesh=4/5`, `DualContouring=0/5`
- 排序理由: 拓扑保持 mesh tokenization 很相关，但其目标包含 manifoldness/watertightness，和 open-surface preservation 有张力。
- Link: [Project Page](https://gaochao-s.github.io/pages/MeshSilksong/); official: [official page](https://iclr.cc/virtual/2026/poster/10007983)
- 摘要中文译述: 该方法通过 vertex layering 和 ordering 建立 canonical topological framework，让自回归 mesh 生成更好保持流形性、法线一致性、part awareness 和整体拓扑结构。

### 23. E19 — Strips as Tokens: Artist Mesh Generation with Native UV Segmentation

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=3/5`, `DualContouring=0/5`
- 排序理由: artist mesh / UV boundary / edge flow 与开放边界和纹理生产相关，但不是重建或 DC。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_164&sess=sess121)
- 摘要中文译述: SATO 用类似 triangle strips 的 token ordering，把面序列组织成连接链并显式编码 UV boundaries，从而更好保留 artist-created mesh 的 edge flow 和语义布局。

### 24. E43 — Unsupervised Representation Learning for 3D Mesh Parameterization with Semantic and Visibility Objectives

- Venue: ICLR 2026
- Scores: `OpenSurfaceMesh=3/5`, `DualContouring=0/5`
- 排序理由: mesh parameterization 会处理 seams/cuts，和 open boundary/UV seams 有间接关系；不是几何重建。
- Link: [Project Page](https://ahhhz975.github.io/Automatic3DMeshParameterization/); official: [official page](https://iclr.cc/virtual/2026/poster/10011122)
- 摘要中文译述: 该工作提出无监督 mesh UV 参数化框架，在几何保持之外加入语义一致和可见性目标，让 UV charts 更对齐语义部件，并把切缝引导到较不显眼区域。

### 25. E14 — Differentiable Voxelization of Surface Representations

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=3/5`, `DualContouring=1/5`
- 排序理由: 把 surface representation 可微 voxelize，可作为 mesh/voxel/implicit pipeline 的桥；但不是抽面算法。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_1260&sess=sess149)
- 摘要中文译述: 论文给出一种让 voxel values 对生成该 voxel grid 的 surface positions 可微的方法，从而让三角网格等表面表示也能利用规则体素网格上容易求解的任务。

### 26. E32 — Focusing: View-Consistent Sparse Voxels for Efficient 3D VAE

- Venue: ICML 2026
- Scores: `OpenSurfaceMesh=3/5`, `DualContouring=1/5`
- 排序理由: sparse voxel VAE 关注高分辨率几何重建，和表面表示相关；但 open surface 与 DC 都不是核心。
- Link: [Official page](https://icml.cc/virtual/2026/poster/63722)
- 摘要中文译述: Focusing 通过 view-consistent sparse voxels 和 depth-driven voxel carving，只激活当前视角相关体素，降低解码/注意力成本，并用 depth、normal、mask 与感知损失训练高效 3D VAE。

### 27. E44 — Neural Compression of 3D Meshes using Sparse Implicit Representation

- Venue: ICLR 2026
- Scores: `OpenSurfaceMesh=3/5`, `DualContouring=1/5`
- 排序理由: Sparse Implicit Representation 用近表面 SDF 支持 surface recovery；但 SDF 倾向闭合，不是 open surface。
- Link: [Project Page](https://github.com/yydlmzyz1/SIR-SNC); official: [official page](https://iclr.cc/virtual/2026/poster/10010986)
- 摘要中文译述: 该工作用 Sparse Implicit Representation 只在表面附近规则网格记录 SDF 值，再用轻量压缩网络编码成 bitstream，以更低内存实现高质量 mesh/point cloud 压缩和表面恢复。

### 28. E12 — SuperSDF:Sparse SDF Super-Resolution for Surface Extraction

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=2/5`, `DualContouring=2/5`
- 排序理由: SDF super-resolution 和 surface extraction 相关，也接近 marching/contouring 家族；但 SDF 通常偏闭合流形，不适合 open surface preservation。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_1060&sess=sess146)
- 摘要中文译述: SuperSDF 学习从粗 SDF 直接超分辨出高保真 SDF，并在表面附近用 sparse voxel network 提升质量、效率和可扩展性，最终重建高质量 mesh。

### 29. E35 — NoiseSDF2NoiseSDF: Learning Clean Neural Fields from Noisy Supervision

- Venue: ICML 2026
- Scores: `OpenSurfaceMesh=2/5`, `DualContouring=2/5`
- 排序理由: neural SDF clean-up 对隐式表面重建有用；但 SDF 不是 open-surface 友好表示，DC 也只是下游可能性。
- Link: [Official page](https://icml.cc/virtual/2026/poster/63881)
- 摘要中文译述: NoiseSDF2NoiseSDF 将 Noise2Noise 思路扩展到 3D neural fields，从 noisy point clouds 的 noisy SDF supervision 中学习干净 SDF，提升低质量扫描点云的隐式表面重建。

### 30. E13 — SAND: Spatially Adaptive Network Depth for Fast Sampling of Neural Implicit Surfaces

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=2/5`, `DualContouring=1/5`
- 排序理由: neural implicit surface 加速采样，属于 field 表示基础设施；但不解决 open boundary 或 contouring 本身。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_770&sess=sess146)
- 摘要中文译述: SAND 根据空间重要性和局部几何复杂度自适应网络深度，用 volumetric depth map 和 tailed MLP 减少查询成本，同时保持隐式表面重建质量和 neural LoD。

### 31. E33 — $\texttt{PRISM}$:A 3D Probabilistic Neural Representation for Interpretable Shape Modeling

- Venue: ICML 2026
- Scores: `OpenSurfaceMesh=2/5`, `DualContouring=0/5`
- 排序理由: probabilistic neural shape representation 和连续隐式形状有关，但目标是可解释统计形状建模，不是 mesh extraction/open boundary。
- Link: [Official page](https://icml.cc/virtual/2026/poster/63964)
- 摘要中文译述: PRISM 将隐式神经表示和带不确定性的统计形状分析结合，建模给定协变量下的形状分布，并在任意空间位置估计群体均值和局部不确定性。

### 32. E45 — DiMeR: Disentangled Mesh Reconstruction Model with Normal-only Geometry Training

- Venue: ICLR 2026
- Scores: `OpenSurfaceMesh=3/5`, `DualContouring=0/5`
- 排序理由: mesh reconstruction 输出 mesh，但面向 sparse-view object reconstruction，open surface 不是核心。
- Link: [Project Page](https://lutao2021.github.io/DiMeR_page/); official: [official page](https://iclr.cc/virtual/2026/poster/10008246)
- 摘要中文译述: DiMeR 将几何与纹理解耦，用 normal maps 作为几何预测的核心输入，并重新设计 mesh extraction 与 3D-supervised regularization，以减少纹理掩盖几何错误的问题。

### 33. E31 — XSpecMesh: Quality-Preserving Auto-Regressive Mesh Generation Acceleration via Multi-Head Speculative Decoding

- Venue: ICML 2026
- Scores: `OpenSurfaceMesh=3/5`, `DualContouring=0/5`
- 排序理由: 服务 AR mesh generation 的推理加速；不是新表面表示，但对 mesh-token pipeline 有辅助价值。
- Link: [Official page](https://icml.cc/virtual/2026/poster/66559)
- 摘要中文译述: XSpecMesh 用轻量 multi-head speculative decoding 并行预测多个 token，再由 backbone 验证/重采样，在基本不损失质量的前提下加速自回归 mesh 生成。

### 34. E30 — TextMesh4D: Zero-shot Text-to-4D Mesh Generation

- Venue: ICML 2026
- Scores: `OpenSurfaceMesh=3/5`, `DualContouring=0/5`
- 排序理由: 直接生成 dynamic meshes，比 NeRF/3DGS 更 surface-controllable；但不是 open surface 或 DC 专门工作。
- Link: [Official page](https://icml.cc/virtual/2026/poster/64889)
- 摘要中文译述: TextMesh4D 面向 zero-shot text-to-4D mesh generation，用 face-level Jacobian Deformation Field 建模动态形变，并用局部-全局语义正则保持时间一致的结构与身份。

### 35. E49 — Guaranteed Simply Connected Mesh Reconstruction from an Unorganized Point Cloud

- Venue: ICLR 2026
- Scores: `OpenSurfaceMesh=2/5`, `DualContouring=1/5`
- 排序理由: point-cloud-to-mesh 重建相关，但 simply connected / sphere-like guarantee 与任意 open surface 相反。
- Link: [OpenReview](https://openreview.net/forum?id=jjEnTBsffi); official: [official page](https://iclr.cc/virtual/2026/poster/10007858)
- 摘要中文译述: 该方法从 noisy point cloud 重建闭合表面 mesh，并保证拓扑 simply connected；它通过 Delaunay triangulation、三角面朝向估计和体网格边界恢复交替优化重建。

### 36. E15 — DualBrep: A Dual-Field Continuous Representation for B-rep Modelling

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=2/5`, `DualContouring=1/5`
- 排序理由: B-rep/UDF topology 对边界表示有启发，但面向 CAD reverse engineering/generation，通常不是 open cloth mesh。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_295&sess=sess142)
- 摘要中文译述: DualBrep 用两个连续标量场表示 CAD：SDF 表示几何，UDF 表示拓扑；二者压缩到统一 latent 中，以支持更稳健的 reverse engineering 和 generative modeling。

### 37. E16 — Autoregressive B-Rep Shape Generation with Parametric Surfaces

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=2/5`, `DualContouring=0/5`
- 排序理由: native parametric surfaces 对 CAD 表示有价值；但不是 mesh extraction，也不强调 open surface。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_165&sess=sess142)
- 摘要中文译述: ParaCAD 是点云条件的自回归 B-Rep 生成框架，直接预测原生 parametric surface 类型和连续参数，以保留 CAD 语义和后续可编辑性。

### 38. E38 — Brep2Shape: Boundary and Shape Representation Alignment via Self-supervised Transformers

- Venue: ICML 2026
- Scores: `OpenSurfaceMesh=2/5`, `DualContouring=0/5`
- 排序理由: B-rep surface/curve tokens 和 topology attention 有关系，但主要是 CAD 表征对齐，不是 open mesh。
- Link: [Official page](https://icml.cc/virtual/2026/poster/62274)
- 摘要中文译述: Brep2Shape 通过 self-supervised pretraining 对齐抽象 B-rep 与直观 shape 表示，使用 surface/curve 双流 transformer 和 topology attention 来学习曲面、曲线及其拓扑关系。

### 39. E39 — CADFit: Precise Mesh-to-CAD Program Generation with Hybrid Optimization

- Venue: ICML 2026
- Scores: `OpenSurfaceMesh=2/5`, `DualContouring=0/5`
- 排序理由: mesh-to-CAD 逆向工程与可编辑几何相关；但输出 CAD program，不是 open surface mesh。
- Link: [Project Page](https://ghadinehme.github.io/cadfit.github.io/); official: [official page](https://icml.cc/virtual/2026/poster/61824)
- 摘要中文译述: CADFit 从 mesh 或点云恢复复杂可编辑 CAD construction sequences，用 IoU-driven optimization 逐步拟合并验证 extrusion、revolution、fillet、chamfer 等参数化操作。

### 40. E40 — Bridging Tokens and Geometry: Token-wise 3D Supervision for CAD Generation

- Venue: ICML 2026
- Scores: `OpenSurfaceMesh=2/5`, `DualContouring=0/5`
- 排序理由: CAD token 的几何监督对程序化形状生成有用；但与 open surface/DC 很远。
- Link: [Official page](https://icml.cc/virtual/2026/poster/65302)
- 摘要中文译述: 该工作提出 Argument-induced 3D Point Loss，将 CAD argument tokens 映射到对应 3D points，并用 Grammar-constrained Operator 约束序列生成，从而提升 CAD 生成的几何准确性和有效性。

### 41. E09 — FILTR: Extracting Topological Features from Pretrained 3D Models

- Venue: CVPR 2026 Oral
- Scores: `OpenSurfaceMesh=1/5`, `DualContouring=0/5`
- 排序理由: 拓扑特征提取可用于评估/诊断 mesh，但不生成或抽取 surface。
- Link: [Project Page](https://filtr-topology.github.io/); official: [official page](https://cvpr.thecvf.com/virtual/2026/oral/40323)
- 摘要中文译述: FILTR 研究预训练 3D encoder 是否保留拓扑信息，提出 DONUT benchmark 和 Filtration Transformer，从 frozen encoder 特征中预测 persistence diagrams。

### 42. E54 — LiTo: Surface Light Field Tokenization

- Venue: ICLR 2026
- Scores: `OpenSurfaceMesh=1/5`, `DualContouring=0/5`
- 排序理由: surface light field tokenization 涉及 surface samples，但核心是视角相关外观，不是 mesh/open boundary。
- Link: [Project Page](https://apple.github.io/ml-lito/); official: [official page](https://iclr.cc/virtual/2026/poster/10009308)
- 摘要中文译述: LiTo 将 RGB-D 视作 surface light field samples，并编码成紧凑 latent，以联合表示几何和视角相关外观；再用 latent flow matching 进行单图条件 3D 物体生成。

### 43. E37 — GHOST: Geometry-Guided Hallucination of Opaque Surface Textures

- Venue: ICML 2026
- Scores: `OpenSurfaceMesh=1/5`, `DualContouring=0/5`
- 排序理由: geometry-guided texture preprocessing 间接帮助 depth/reconstruction；但不是 3D representation 或 mesh extraction。
- Link: [Official page](https://icml.cc/virtual/2026/poster/65389)
- 摘要中文译述: GHOST 用视觉基础模型把透明区域转成结构一致的 opaque 表示，并结合 mask、透明物理属性、surface normal priors 合成保留几何结构的 RGB 图像，帮助下游深度和重建。

### 44. E07 — Representing 3D Faces with Learnable B-Spline Volumes

- Venue: CVPR 2026 Highlight
- Scores: `OpenSurfaceMesh=1/5`, `DualContouring=0/5`
- 排序理由: B-spline volume 是连续 face-specific 表示，可编辑但不面向 open surface mesh。
- Link: [CVPR OpenAccess](https://openaccess.thecvf.com/content/CVPR2026/html/Chandran_Representing_3D_Faces_with_Learnable_B-Spline_Volumes_CVPR_2026_paper.html); official: [official page](https://cvpr.thecvf.com/virtual/2026/poster/36519)
- 摘要中文译述: CUBE 用带高维 control features 的 B-spline volume 表示数字人脸，通过局部支撑和小 MLP 生成 refined surface points，并服务于 scan registration 和单目 3D face reconstruction。

### 45. E46 — Pixel3DMM: Versatile Screen-Space Priors for Single-Image 3D Face Reconstruction

- Venue: ICLR 2026
- Scores: `OpenSurfaceMesh=1/5`, `DualContouring=0/5`
- 排序理由: FLAME/3DMM face reconstruction 是模板化闭合面部模型，和 open surface 很弱。
- Link: [Project Page](https://simongiebenhain.github.io/pixel3dmm/); official: [official page](https://iclr.cc/virtual/2026/poster/10009198)
- 摘要中文译述: Pixel3DMM 用视觉 transformer 预测每像素 normal 和 UV 坐标等几何线索，再拟合 FLAME 3DMM 参数，从单张 RGB 图像重建高精度人脸几何。

### 46. E53 — UniF$^2$ace: A $\underline{Uni}$fied $\underline{F}$ine-grained $\underline{Face}$ Understanding and Generation Model

- Venue: ICLR 2026
- Scores: `OpenSurfaceMesh=0/5`, `DualContouring=0/5`
- 排序理由: 主要是 face understanding/generation 的统一多模态模型，不是 surface mesh 表示。
- Link: [OpenReview](https://openreview.net/forum?id=LV01JdxARe); official: [official page](https://iclr.cc/virtual/2026/poster/10010032)
- 摘要中文译述: UniF2ace 面向细粒度人脸理解与生成，提出 Dual Discrete Diffusion loss 和 grouped Mixture-of-Experts，并构建大规模人脸图文/VQA 数据集提升属性理解和生成质量。

### 47. E10 — SAM 3D Body: Robust Full-Body Human Mesh Recovery

- Venue: CVPR 2026 Oral
- Scores: `OpenSurfaceMesh=1/5`, `DualContouring=0/5`
- 排序理由: human body mesh 是显式 mesh，但参数化人体通常闭合且类别特化；与 open garment surface 关系弱。
- Link: [CVPR OpenAccess](https://openaccess.thecvf.com/content/CVPR2026/html/Yang_SAM_3D_Body_Robust_Full-Body_Human_Mesh_Recovery_CVPR_2026_paper.html); official: [official page](https://cvpr.thecvf.com/virtual/2026/oral/40311)
- 摘要中文译述: SAM 3D Body 是可 prompt 的单图全身 3D human mesh recovery 模型，使用新的 Momentum Human Rig 解耦骨架姿态和体型，并支持关键点/掩码等辅助提示。

### 48. E36 — SAMT: Generating Structured Avatar Meshes and Textures from a Single Image

- Venue: ICML 2026
- Scores: `OpenSurfaceMesh=1/5`, `DualContouring=0/5`
- 排序理由: avatar face mesh/texture 生成是类别特化闭合资产；和 open-surface/DC 很弱。
- Link: [Official page](https://icml.cc/virtual/2026/poster/61104)
- 摘要中文译述: SAMT 用两阶段框架从单图生成结构化 3D avatar mesh 和多视图一致纹理：先训练 facial mesh latent diffusion，再用 mesh geometry 引导 texturing diffusion。

### 49. E06 — EfficientMonoHair: Fast Strand-Level Reconstruction from Monocular Video via Multi-View Direction Fusion

- Venue: CVPR 2026
- Scores: `OpenSurfaceMesh=0/5`, `DualContouring=0/5`
- 排序理由: hair strands 是开放曲线而不是 surface mesh；如果研究 strand representation 才值得靠前。
- Link: [CVPR OpenAccess](https://openaccess.thecvf.com/content/CVPR2026/html/Li_EfficientMonoHair_Fast_Strand-Level_Reconstruction_from_Monocular_Video_via_Multi-View_Direction_CVPR_2026_paper.html); official: [official page](https://cvpr.thecvf.com/virtual/2026/poster/38881)
- 摘要中文译述: EfficientMonoHair 将隐式网络与多视图几何融合结合，从单目视频快速重建 strand-level hair，并用 fusion-patch optimization 和并行 hair-growing 提升速度与稳定性。

### 50. E20 — HairLRM: Strand-based Hair Modeling via Large Reconstruction Models

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=0/5`, `DualContouring=0/5`
- 排序理由: strand-based hair 与 open curve 有关，但不是 open surface mesh。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_371&sess=sess119)
- 摘要中文译述: HairLRM 将 Large Reconstruction Model 的几何先验引入发丝生成，借助 LRM mesh anchor 和 Dual Orientation AutoEncoder，把粗几何转换成高保真发丝。

### 51. E21 — HairGPT: A Unified Autoregressive Framework for 3D Realistic Hairstyle Synthesis

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=0/5`, `DualContouring=0/5`
- 排序理由: strand-as-language 很有意思，但目标是发型曲线生成，不是 mesh/DC。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_869&sess=sess119)
- 摘要中文译述: HairGPT 把真实感 3D hair generation 表述为 dual-decoupled autoregressive process，把发丝作为基本生成单元来建模复杂发型。

### 52. E22 — HairPort: In-context 3D-aware Hair Import and Transfer for Images

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=0/5`, `DualContouring=0/5`
- 排序理由: 3D-aware hair transfer 是图像/发型迁移应用，非 surface mesh 表示。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_204&sess=sess119)
- 摘要中文译述: HairPort 把参考发型迁移到源人脸图像上，通过分离 hair removal 与 synthesis，并用 3D reconstruction 约束几何一致性来保留身份和姿态尺度差异。

### 53. E23 — Curvature Space Editing of Highly-Coiled Hair

- Venue: SIGGRAPH 2026
- Scores: `OpenSurfaceMesh=0/5`, `DualContouring=0/5`
- 排序理由: curvature-space hair editing 是曲线编辑，不属于 mesh/open surface。
- Link: [SIGGRAPH official page](https://s2026.conference-schedule.org/presentation/?id=papers_651&sess=sess119)
- 摘要中文译述: 该工作用 super-helix model 的 material curvatures 分析和编辑高卷曲发丝，并提出 ruffling、handedness flip tracking 和控制骨架等曲率空间编辑操作。
