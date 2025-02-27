<h2 align="center">Focusing on Projection-Stable Patch: Cross-View Localization with Geometric-Semantic Alignment</h2>
<p align="center">
<a >Riyu Qin</a><sup></sup>, 
<a >Zhengyu Liu</a><sup></sup>,
<a >Kaiyang Wang</a><sup></sup>,
<a >Xia Yuan</a><sup>*</sup>,
<br>
</p>

## Partial Content

<p align="center"><img  src="./Figures/overview.jpg" alt="description" width="40%"></p>
Fig.1 :overview of the proposed method.The method mitigates occlusion effects through a perspective-driven attention fusion module (a)-(b) that projects ground view feature map to satellite view representations. A projection-stable patch optimizer (d) then refines camera pose estimation by minimizing discrepancies between transformed ground features and satellite-view features (c), achieving high-precision rotation estimation.

<p align="center"><img align="center" src="./Figures/cross_view_0226.jpg" alt="description" width="80%"> </p>
Fig.2 :Framework of the proposed method. (1) PDAF: perspective-driven attention fusion module. (2) HFAM: hierarchical feature aggregation module (3) PSPG:projection-stable patch-guided pose optimizer.The initial orientation (Ori) and translation (T) serve as initial inputs to the geometry projection. During each subsequent iteration, the updated orientation parameters and translation values are fed back into the geometric projection process. Through two complete iteration cycles, PSPG produces the final orientation estimation (Ori_pred), which subsequently guides the location branch to generate the translation estimation (T_pred). <br> 
<br>

## Datasets
- KITTI dataset: please refer to https://github.com/shiyujiao/HighlyAccurate to download the dataset.
- Ford multi-AV: please refer to https://github.com/shiyujiao/HighlyAccurate to download the dataset.

## Codes
will be release soon！
