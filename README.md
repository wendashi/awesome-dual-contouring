# Awesome Dual Contouring

Learn Dual Contouring. Build it. Go beyond it.

<p align="center">
  <img src="figs/awesome-DC-0.png" alt="Implicit 3D representations and surface extraction overview" width="100%">
</p>

## Dual Contouring Related Research Map

<p align="center">
  <img src="figs/awesome-DC-1.png" alt="Dual Contouring related research map" width="100%">
</p>

This repo tracks Dual Contouring and nearby surface-extraction methods for SDF, UDF, occupancy fields, sparse voxel representations, and field-free mesh/dual-grid pipelines.

## Contents

- [Research & Academic Projects](#-research--academic-projects)
- [Classical Foundations](#classical-foundations)
- [DC: Single-Dual-Vertex Methods](#dc-single-dual-vertex-methods)
- [DC: Multi-Dual-Vertex Methods](#dc-multi-dual-vertex-methods)
- [MC / DMC / Differentiable Isosurfacing](#mc--dmc--differentiable-isosurfacing)
- [Field-Free and DC-Like Structured Representations](#field-free-and-dc-like-structured-representations)
- [Open-Surface UDF Reconstruction](#open-surface-udf-reconstruction)
- [Contributing](#contributing)

## 🔬 Research & Academic Projects

### Classical Foundations

1. [Marching Cubes: A High Resolution 3D Surface Construction Algorithm](https://doi.org/10.1145/37402.37422) - **SIGGRAPH 1987** | input = discrete SDF / scalar field | [YouTube tutorial](https://www.youtube.com/watch?v=M3iI2l0ltbE&t=143s)

2. [Dual Contouring of Hermite Data](https://doi.org/10.1145/566570.566586) - **SIGGRAPH 2002** | input = Hermite data from SDF / scalar field | [YouTube tutorial](https://www.youtube.com/watch?v=B_5VBtpVuLQ)

3. [Dual Marching Cubes: Primal Contouring of Dual Grids](https://doi.org/10.1111/j.1467-8659.2005.00843.x) - **VIS 2004 / Computer Graphics Forum** | input = discrete SDF / scalar field on dual grids

4. [Manifold Dual Contouring](https://doi.org/10.1109/TVCG.2007.1012) - **TVCG 2007** | input = SDF / implicit field + Hermite data

### DC: Single-Dual-Vertex Methods

1. [Neural Dual Contouring](https://arxiv.org/abs/2202.01999) - **SIGGRAPH / TOG 2022** | input = SDF / UDF / occupancy grid / point cloud | [Code](https://github.com/czq142857/NDC)
   <a href="https://github.com/czq142857/NDC" title="GitHub Repo">
     <img src="https://img.shields.io/github/stars/czq142857/NDC.svg?style=social" alt="Stars">
   </a>

2. [Surface Extraction from Neural Unsigned Distance Fields](https://arxiv.org/abs/2309.08878) - **ICCV 2023** | input = continuous neural UDF | [Code](https://github.com/cong-yi/DualMesh-UDF)
   <a href="https://github.com/cong-yi/DualMesh-UDF" title="GitHub Repo">
     <img src="https://img.shields.io/github/stars/cong-yi/DualMesh-UDF.svg?style=social" alt="Stars">
   </a>

3. [Robust Zero Level-Set Extraction from Unsigned Distance Fields Based on Double Covering](https://arxiv.org/abs/2310.03431) - **SIGGRAPH Asia / TOG 2023** | input = continuous UDF | [Code](https://github.com/jjjkkyz/DCUDF)
   <a href="https://github.com/jjjkkyz/DCUDF" title="GitHub Repo">
     <img src="https://img.shields.io/github/stars/jjjkkyz/DCUDF.svg?style=social" alt="Stars">
   </a>

4. [Dual Contouring of Signed Distance Data](https://arxiv.org/abs/2604.00157) - **SIGGRAPH 2026** | input = discrete SDF

5. [Dual Contouring over Expanded Cubes (DCx) for Zero-Level Set Extraction from Neural Unsigned Distance Functions](https://s2026.conference-schedule.org/presentation/?id=papers_1461&sess=sess146) - **SIGGRAPH 2026** | input = continuous neural UDF | [Code](https://github.com/jjjkkyz/DCx)
   <a href="https://github.com/jjjkkyz/DCx" title="GitHub Repo">
     <img src="https://img.shields.io/github/stars/jjjkkyz/DCx.svg?style=social" alt="Stars">
   </a>

### DC: Multi-Dual-Vertex Methods

1. [Occupancy-Based Dual Contouring](https://arxiv.org/abs/2409.13418) - **SIGGRAPH Asia 2024** | input = continuous occupancy field | [Code](https://github.com/KAIST-Visual-AI-Group/ODC)
   <a href="https://github.com/KAIST-Visual-AI-Group/ODC" title="GitHub Repo">
     <img src="https://img.shields.io/github/stars/KAIST-Visual-AI-Group/ODC.svg?style=social" alt="Stars">
   </a>

### MC / DMC / Differentiable Isosurfacing

1. [MeshUDF: Fast and Differentiable Meshing of Unsigned Distance Field Networks](https://arxiv.org/abs/2111.14549) - **ECCV 2022** | input = continuous neural UDF | [Code](https://github.com/cvlab-epfl/MeshUDF)
   <a href="https://github.com/cvlab-epfl/MeshUDF" title="GitHub Repo">
     <img src="https://img.shields.io/github/stars/cvlab-epfl/MeshUDF.svg?style=social" alt="Stars">
   </a>

2. [Flexible Isosurface Extraction for Gradient-Based Mesh Optimization](https://arxiv.org/abs/2308.05371) - **SIGGRAPH / TOG 2023** | input = optimizable SDF / scalar field + FlexiCubes parameters | [Code](https://github.com/nv-tlabs/FlexiCubes)
   <a href="https://github.com/nv-tlabs/FlexiCubes" title="GitHub Repo">
     <img src="https://img.shields.io/github/stars/nv-tlabs/FlexiCubes.svg?style=social" alt="Stars">
   </a>

3. [SparseFlex: High-Resolution and Arbitrary-Topology 3D Shape Modeling](https://arxiv.org/abs/2503.21732) - **ICCV 2025 Oral** | input = sparse voxelized SDF / scalar field + SparseFlex parameters | [Project](https://xianglonghe.github.io/TripoSF) | [Code](https://github.com/VAST-AI-Research/TripoSF)
   <a href="https://github.com/VAST-AI-Research/TripoSF" title="GitHub Repo">
     <img src="https://img.shields.io/github/stars/VAST-AI-Research/TripoSF.svg?style=social" alt="Stars">
   </a>

### Field-Free and DC-Like Structured Representations

1. [TRELLIS.2: Native and Compact Structured Latents for 3D Generation](https://microsoft.github.io/TRELLIS.2/) - **CVPR 2026 Oral** | input = field-free mesh surface x voxel / dual-grid intersections | [Paper](https://arxiv.org/abs/2512.14692) | [Code](https://github.com/microsoft/TRELLIS)
   <a href="https://github.com/microsoft/TRELLIS" title="GitHub Repo">
     <img src="https://img.shields.io/github/stars/microsoft/TRELLIS.svg?style=social" alt="Stars">
   </a>

2. [Faithful Contouring: Near-Lossless 3D Voxel Representation Free from Iso-surface](https://arxiv.org/abs/2511.04029) - **CVPR 2026 Oral** | input = field-free sparse voxel mesh representation | [Code](https://github.com/Luo-Yihao/FaithC)
   <a href="https://github.com/Luo-Yihao/FaithC" title="GitHub Repo">
     <img src="https://img.shields.io/github/stars/Luo-Yihao/FaithC.svg?style=social" alt="Stars">
   </a>

### Open-Surface UDF Reconstruction

1. [Distilling Unsigned Distance Function for Surface Reconstruction from 3D Gaussian Splatting](https://openaccess.thecvf.com/content/CVPR2026/html/Li_Distilling_Unsigned_Distance_Function_for_Surface_Reconstruction_from_3D_Gaussian_CVPR_2026_paper.html) - **CVPR 2026** | input = 3D Gaussian Splatting -> continuous UDF

2. [SpUDD: Superpower Contouring of Unsigned Distance Data](https://arxiv.org/abs/2604.19568) - **arXiv 2026** | input = discrete UDF

3. [VoroUDF: Meshing Unsigned Distance Fields with Voronoi Optimization](https://arxiv.org/abs/2602.02907) - **arXiv 2026** | input = continuous UDF

## Contributing

Pull requests are welcome. Good entries should include:

- paper / project link
- venue and year
- code link, if official code exists
- input type, such as `continuous UDF`, `discrete UDF`, `SDF`, `occupancy field`, `point cloud`, or `field-free mesh/dual-grid`

Please prefer official project pages, arXiv / DOI pages, conference pages, and official code repositories.
