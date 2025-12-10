<a href='https://honglab.ai'><p style="text-align:center;"><img src='https://lh3.googleusercontent.com/lY3ySXooSmwsq5r-mRi7uiypbo0Vez6pmNoQxMFhl9fmZJkRHu5lO2vo7se_0YOzgmDyJif9fi4_z0o3ZFdwd8NVSWG6Ea80uWaf3pOHpR4GHGDV7kaFeuHR3yAjIJjDgfXMxsvw=w2400'  class="center" width="100%" height="100%"/></p></a>

<center><em>Content Copyright by HongLab, Inc.</em></center>

# 3D 가우시안 스플래팅의 진화

참고자료: [TUM AI Lecture Series - The 3D Gaussian Splatting Adventure: Past, Present, Future (George Drettakis)](https://www.youtube.com/live/DjOqkVIlEGY?si=t7QlBlTCwzZey9o-)

용어 몇 가지: 렌더링, 새로운 시점 합성(novel view synthesis)

## 1. 초기 이미지 기반 렌더링 (1990년대)

[View Interpolation for Image Synthesis](https://cseweb.ucsd.edu/~ravir%20/6998/papers/p279-chen.pdf) (SIGGRAPH 1993)

[Modeling and Rendering Architecture from Photographs (Facade)](https://www.pauldebevec.com/Research/) (SIGGRAPH 1996)

[The Lumigraph](https://cseweb.ucsd.edu/~ravir/6160/papers/p43-gortler.pdf) (SIGGRAPH 1996)

[Light Field Rendering](https://graphics.stanford.edu/papers/light/) (SIGGRAPH 1996)

# 2. 고전적 3D 복원 (1999-2010)

[Multiple View Geometry in Computer Vision](https://www.robots.ox.ac.uk/~vgg/hzbook/) (2004)

[Distinctive Image Features from Scale-Invariant Keypoints](https://www.cs.ubc.ca/~lowe/papers/ijcv04.pdf) (IJCV 2004)

[Photo Tourism: Exploring Photo Collections in 3D](http://phototour.cs.washington.edu/) (SIGGRAPH 2006)

[Building Rome in a Day](https://grail.cs.washington.edu/rome/) (ICCV 2009)

[Accurate, Dense, and Robust Multiview Stereopsis](https://3d.bk.tudelft.nl/courses/backup/geo1016/2023/handouts/05_MVS-papers.pdf) (IEEE TPAMI 2010)

## 3. 포인트 기반 그래픽스 시대 (2000-2004)

[QSplat: A Multiresolution Point Rendering System for Large Meshes](https://www.cs.princeton.edu/~smr/papers/qsplat/qsplat_paper.pdf) (SIGGRAPH 2000)

[Surfels: Surface Elements as Rendering Primitives](https://www.cs.umd.edu/~zwicker/publications/Surfels-SIG00.pdf) (SIGGRAPH 2000)

[EWA Volume Splatting](https://www.cs.umd.edu/~zwicker/publications/EWAVolumeSplatting-VIS01.pdf) (2001)

[Surface Splatting](https://www.cs.umd.edu/~zwicker/publications/SurfaceSplatting-SIG01.pdf) (SIGGRAPH 2001)

[Pointshop 3D: An Interactive System for Point-Based Surface Editing](https://cgl.ethz.ch/Downloads/Publications/Papers/2002/p_Zwi02.pdf) (SIGGRAPH 2002)

[Interactive Point-based Modeling of Complex Objects from Images](https://www-sop.inria.fr/reves/Basilic/2003/PSDFD03/Poulin-2003-IPM.pdf) (Graphics Interface 2003)

## 4. 현대 SfM/MVS 및 뷰별 기법 (2013-2016)

[Depth Synthesis and Local Warps for Plausible Image-based Navigation](https://www-sop.inria.fr/reves/Basilic/2013/CDSD13/) (ACM TOG 2013)

[Pixelwise View Selection for Unstructured Multi-View Stereo](https://demuc.de/papers/schoenberger2016mvs.pdf) (ECCV 2016)

[COLMAP: Structure-from-Motion Revisited](https://demuc.de/papers/schoenberger2016sfm.pdf) (CVPR 2016)

## 5. 초기 미분 가능 렌더링 (2014-2018)

[OpenDR: An Approximate Differentiable Renderer](https://files.is.tue.mpg.de/black/papers/OpenDR.pdf) (ECCV 2014)

[Neural 3D Mesh Renderer](https://arxiv.org/abs/1711.07566) (CVPR 2018)

[MVSNet: Depth Inference for Unstructured Multi-view Stereo](https://arxiv.org/abs/1804.02505) (ECCV 2018)

## 6. 미분 가능 래스터화 및 신경망 텍스처 (2019-2020)

[Deferred Neural Rendering: Image Synthesis using Neural Textures](https://arxiv.org/pdf/1904.12356) (SIGGRAPH 2019)

[Differentiable Surface Splatting](https://arxiv.org/abs/1906.04173) (SIGGRAPH Asia 2019)

[Free-viewpoint Indoor Neural Relighting from Multi-view Stereo](https://repo-sam.inria.fr/fungraph/deep-indoor-relight/) (SIGGRAPH Asia 2019)

[SynSin: End-to-end View Synthesis from a Single Image](https://github.com/facebookresearch/synsin) (CVPR 2020)

## 7. NeRF 혁명 (2021-2022)

[NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://www.matthewtancik.com/nerf) (ECCV 2020)

[PlenOctrees](https://alexyu.net/plenoctrees/) (ICCV 2021)

[KiloNeRF](https://github.com/creiser/kilonerf) (ICCV 2021)

[Pulsar: Efficient Sphere-Based Neural Rendering](https://arxiv.org/pdf/2004.07484) (CVPR 2021)

[Instant NGP](https://github.com/NVlabs/instant-ngp) (SIGGRAPH 2022)

[Plenoxels: Radiance Fields without Neural Networks](https://alexyu.net/plenoxels/) (CVPR 2022)

## 8. 3D 가우시안 스플래팅 - 통합 (2023)

[3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) (SIGGRAPH 2023)

## 9. 정적 장면을 넘어서 – 미래 방향 (2023– )

[4D Gaussian Splatting for Real-Time Dynamic Scene Rendering](https://guanjunwu.github.io/4dgs/) (SIGGRAPH Asia 2023)

[CityGaussian: Real-Time High-Quality Large-Scale Scene Rendering with Gaussian Splatting](https://arxiv.org/abs/2404.01133) (arXiv 2023)

[GaussianAvatar: Towards Realistic Human Avatars based on 3D Gaussian Splatting](https://arxiv.org/abs/2312.02069) (arXiv 2023)

[A Hierarchical 3D Gaussian Representation for Real-Time Rendering of Very Large Datasets](https://arxiv.org/abs/2406.12080) (arXiv 2024)

[Analytic-Splatting: Anti-Aliased 3D Gaussian Splatting via Analytic Integration](https://arxiv.org/abs/2403.11056) (arXiv 2024)

[Triangle Splatting 2: Real-Time Differentiable Rendering with Triangle Primitives](https://trianglesplatting2.github.io/trianglesplatting2/) (Project page)

[DreamGaussian: Generative Gaussian Splatting for Efficient 3D Content Creation](https://github.com/dreamgaussian/dreamgaussian) (arXiv 2023)

[GaussianDreamer: Fast Generation from Text-to-3D Gaussian Splatting](https://github.com/hustvl/GaussianDreamer) (arXiv 2023)

[SplaTAM: Splat-based Dense Visual SLAM](https://arxiv.org/abs/2312.02126) (arXiv 2023)

[WorldGen: From Text to Traversable and Interactive 3D Worlds](https://www.meta.com/blog/worldgen-3d-world-generation-reality-labs-generative-ai-research/) (Project page)

[Optimizing 3D Gaussian Splattering for Mobile GPUs](https://arxiv.org/pdf/2511.16298)

[FastGS: Training 3D Gaussian Splatting in 100 Seconds](https://fastgs.github.io/)

[YoNoSplat: You Only Need One Model for Feedforward 3D Gaussian Splatting](https://botaoye.github.io/yonosplat/)

[PhysGaussian: Physics-Integrated 3D Gaussians for Generative Dynamics](https://xpandora.github.io/PhysGaussian/)

[pixelSplat: 3D Gaussian Splats from Image Pairs for Scalable Generalizable 3D Reconstruction](https://github.com/dcharatan/pixelsplat)

## 10. 추가

[A2O MAY 공연 영상](https://youtu.be/jdm_uPQtzs0?si=1Z2NLvTf2V94bR0S)에 4DGS가 사용되었다고 합니다.

[4D Gaussian Videos with Motion Layering](https://turandai.github.io/projects/4d_gaussian_video/)