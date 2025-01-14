
Note: Unfortunately, we have lost access to the previous GitHub Account/Repo. This is the new official github repo of Effective Video Mirror Detection with Inconsistent Motion Cues (CVPR2024) <br>
<i>The previous github repo: https://github.com/AlexAnthonyWarren/MG-VMD</i> <br> 

# Effective Video Mirror Detection with Inconsistent Motion Cues (CVPR2024)

[Alex Warren](https://alex-warren.co.uk), [Ke Xu](https://kkbless.github.io), [Jiaying Lin](https://jiaying.link), [Gary Tam](https://sites.google.com/site/csgarykl/home?authuser=0), [Rynson W.H. Lau](https://www.cs.cityu.edu.hk/~rynson/)
<br> Swansea University, City University of Hong Kong

[[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Warren_Effective_Video_Mirror_Detection_with_Inconsistent_Motion_Cues_CVPR_2024_paper.pdf)] [[Video](https://www.youtube.com/watch?v=q18VcqZz5y4)]

## Abstract 
Image-based mirror detection has recently undergone rapid research due to its significance in applications such as robotic navigation, semantic segmentation and scene reconstruction. Recently, VMD-Net was proposed as the first video mirror detection technique, by modeling dual correspondences between the inside and outside of the mirror both spatially and temporally. However, this approach is not reliable, as correspondences can occur completely inside or outside of the mirrors. In addition, the proposed dataset VMD-D contains many small mirrors, limiting its applicability to real-world scenarios. To address these problems, we developed a more challenging dataset that includes mirrors of various shapes and sizes at different locations of the frames, providing a better reflection of real-world scenarios. Next, we observed that the motions between the inside and outside of the mirror are often inconsistent. For instance, when moving in front of a mirror, the motion inside the mirror is often much smaller than the motion outside due to increased depth perception. With these observations, we propose modeling inconsistent motion cues to detect mirrors, and a new network with two novel modules. The Motion Attention Module (MAM) explicitly models inconsistent motions around mirrors via optical flow, and the Motion-Guided Edge Detection Module (MEDM) uses motions to guide mirror edge feature learning. Experimental results on our proposed dataset show that our method outperforms state-of-the-arts.

## Downloads
[🟢Online - Code & Weights](https://swanseauniversity-my.sharepoint.com/:u:/g/personal/851864_swansea_ac_uk/EZvJts8g1PtPmeKoBk_TyLEBYvm57sX8gKHYR_wfddGV5g?e=xr1894)
<br>
[🟢Online - MMD Dataset](https://swanseauniversity-my.sharepoint.com/:f:/g/personal/851864_swansea_ac_uk/EkTeIupBfSRDql5Vv4wg7aoBzy6vo6dM-NYJ-bApZVXFnw?e=N91Sru)

## Citation
```bibtex
@InProceedings{Warren_2024_CVPR,
    author    = {Warren, Alex and Xu, Ke and Lin, Jiaying and Tam, Gary K.L. and Lau, Rynson W.H.},
    title     = {Effective Video Mirror Detection with Inconsistent Motion Cues},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2024},
    pages     = {17244-17252}
}
```

