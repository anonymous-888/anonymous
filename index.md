---
layout: project_page
permalink: /

title: Textured 3D Regenerative Morphing with 3D Diffusion Prior
authors: Paper 5140

---

<!-- Using HTML to center the abstract -->
<div class="columns is-centered has-text-centered">
    <div class="column is-four-fifths">
        <h2>Abstract</h2>
        <div class="content has-text-justified">
Textured 3D morphing creates **smooth** and **plausible** interpolation sequences between two 3D objects, focusing on transitions in both **shape** and **texture**. This is important for creative applications like visual effects in filmmaking. Previous methods rely on establishing point-to-point correspondences and determining smooth deformation trajectories, which inherently restrict them to shape-only morphing on untextured, topologically aligned datasets. This restriction leads to labor-intensive preprocessing and poor generalization. To overcome these challenges, we propose a method for 3D regenerative morphing using a 3D diffusion prior. Unlike previous methods that depend on explicit correspondences and deformations, our method eliminates the additional need for obtaining correspondence and uses the 3D diffusion prior to generate morphing. Specifically, we first introduce a 3D diffusion model and interpolate the source and target information at three levels: initial noise, model parameters, and condition features. We then explore an Attention Fusion strategy to generate more smooth morphing sequences. To further improve the plausibility of semantic interpolation and the generated 3D surfaces, we propose two strategies: (a) Token Reordering, where we match approximate tokens based on semantic analysis to guide implicit correspondences in the denoising process of the diffusion model, and (b) Low-Frequency Enhancement, where we enhance low-frequency signals in the tokens to improve the quality of generated surfaces. Experimental results show that our method achieves superior smoothness and plausibility in 3D morphing across diverse cross-category object pairs, offering a novel regenerative method for 3D morphing with textured representations.
        </div>
    </div>
</div>
---
# More Qualitative Experimental Results
# 3D Generation Model: Gaussian Anything
# How to Align/Prepare the Input 3D and Images with GaussianAnything?
# How to Choose Appropriate 3D Diffusion Models for 3D Morphing?
# Semantics of the Same Position in Different Blocks
# Baseline Methods and Implementation Details
# Related Works That You Might Confuse: Comparisons with Shape Morphing Methods and Out-of-Setting Clarification
# Exploratory Experiments with Explicit Correspondence
# Testing Protocol and Cases
# Raw Statistics of User Study
# Failure Cases and Analysis
---

## More Cases (Ours)

![](/static/image/video_ours_1.gif) ![](/static/image/video_ours_2.gif)
![](/static/image/video_ours_3.gif) ![](/static/image/video_ours_4.gif)
![](/static/image/video_ours_5.gif) ![](/static/image/video_ours_6.gif)
![](/static/image/video_ours_7.gif) ![](/static/image/video_ours_8.gif)
![](/static/image/video_ours_9.gif) ![](/static/image/video_ours_10.gif)
![](/static/image/video_ours_11.gif) ![](/static/image/video_ours_12.gif)
![](/static/image/video_ours_13.gif) ![](/static/image/video_ours_14.gif)
![](/static/image/video_ours_15.gif) 

## Baseline Comparison \# 1/10

![](/static/image/case_1_diffmorpher.gif) ![](/static/image/case_1_aid.gif)
![](/static/image/case_1_mvadapter.gif) ![](/static/image/case_1_luma.gif)
![](/static/image/case_1_morphflow.gif) ![](/static/image/case_1_ours.gif)

## Baseline Comparison \# 2/10

![](/static/image/case_2_diffmorpher.gif) ![](/static/image/case_2_aid.gif)
![](/static/image/case_2_mvadapter.gif) ![](/static/image/case_2_luma.gif)
![](/static/image/case_2_morphflow.gif) ![](/static/image/case_2_ours.gif)

## Baseline Comparison \# 3/10

![](/static/image/case_3_diffmorpher.gif) ![](/static/image/case_3_aid.gif)
![](/static/image/case_3_mvadapter.gif) ![](/static/image/case_3_luma.gif)
![](/static/image/case_3_morphflow.gif) ![](/static/image/case_3_ours.gif)

## Baseline Comparison \# 4/10

![](/static/image/case_4_diffmorpher.gif) ![](/static/image/case_4_aid.gif)
![](/static/image/case_4_mvadapter.gif) ![](/static/image/case_4_luma.gif)
![](/static/image/case_4_morphflow.gif) ![](/static/image/case_4_ours.gif)

## Baseline Comparison \# 5/10

![](/static/image/case_5_diffmorpher.gif) ![](/static/image/case_5_aid.gif)
![](/static/image/case_5_mvadapter.gif) ![](/static/image/case_5_luma.gif)
![](/static/image/case_5_morphflow.gif) ![](/static/image/case_5_ours.gif)

## Baseline Comparison \# 6/10

![](/static/image/case_6_diffmorpher.gif) ![](/static/image/case_6_aid.gif)
![](/static/image/case_6_mvadapter.gif) ![](/static/image/case_6_luma.gif)
![](/static/image/case_6_morphflow.gif) ![](/static/image/case_6_ours.gif)

## Baseline Comparison \# 7/10

![](/static/image/case_7_diffmorpher.gif) ![](/static/image/case_7_aid.gif)
![](/static/image/case_7_mvadapter.gif) ![](/static/image/case_7_luma.gif)
![](/static/image/case_7_morphflow.gif) ![](/static/image/case_7_ours.gif)

## Baseline Comparison \# 8/10

![](/static/image/case_8_diffmorpher.gif) ![](/static/image/case_8_aid.gif)
![](/static/image/case_8_mvadapter.gif) ![](/static/image/case_8_luma.gif)
![](/static/image/case_8_morphflow.gif) ![](/static/image/case_8_ours.gif)

## Baseline Comparison \# 9/10

![](/static/image/case_9_diffmorpher.gif) ![](/static/image/case_9_aid.gif)
![](/static/image/case_9_mvadapter.gif) ![](/static/image/case_9_luma.gif)
![](/static/image/case_9_morphflow.gif) ![](/static/image/case_9_ours.gif)

## Baseline Comparison \# 10/10

![](/static/image/case_10_diffmorpher.gif) ![](/static/image/case_10_aid.gif)
![](/static/image/case_10_mvadapter.gif) ![](/static/image/case_10_luma.gif)
![](/static/image/case_10_morphflow.gif) ![](/static/image/case_10_ours.gif)

## Ablation Study

![](/static/image/ablation_1.gif) ![](/static/image/ablation_2.gif)
![](/static/image/ablation_3.gif) ![](/static/image/ablation_4.gif)
![](/static/image/ablation_5.gif) ![](/static/image/ablation_6.gif)

