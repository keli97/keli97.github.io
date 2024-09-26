---
title: "PoseSonic: 3D Upper Body Pose Estimation Through Egocentric Acoustic Sensing on Smartglasses"
collection: publications
permalink: /publication/2023-09-27-PoseSonic-3D-Upper-Body-Pose-Estimation-Through-Egocentric-Acoustic-Sensing-on-Smartglasses
excerpt: 'October 8-12, 2023, Cancún, Mexico. Keyword: Human Pose Estimation, Acoustic Sensing, Smart/AR Glasses, Deep Learning, Cross-Modal Supervision'
date: 2023-09-27
venue: 'The Proceedings of the Association for Computing Machinery on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT)/UbiComp'
paperurl: 'https://dl.acm.org/doi/10.1145/3610895'
citation: 'Saif Mahmud, <u>Ke Li</u>, Guilin Hu, Hao Chen, Richard Jin, Ruidong Zhang, François Guimbretière, and Cheng Zhang. 2023. PoseSonic: 3D Upper Body Pose Estimation Through Egocentric Acoustic Sensing on Smartglasses. <i>The Proceedings of the Association for Computing Machinery on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT)/UbiComp</i>, Volume 7, Issue 3, Article 111 (September 2023), 28 pages.'
---
Selected Media Coverage: [Cornell Chronicle](https://news.cornell.edu/stories/2023/11/glasses-use-sonar-ai-interpret-upper-body-poses-3d)

October 8-12, 2023, Cancún, Mexico<br>
Keyword: Human Pose Estimation, Acoustic Sensing, Smart/AR Glasses, Deep Learning, Cross-Modal

<figure>
    <center><img src="https://keli97.github.io/files/posesonic.png" alt="Trulli" style="width:100%" class="center"></center>
</figure>

In this paper, we introduce PoseSonic, an intelligent acoustic sensing solution for smartglasses that estimates upper body poses. Our system only requires two pairs of microphones and speakers on the hinges of the eyeglasses to emit FMCW-encoded inaudible acoustic signals and receive reflected signals for body pose estimation. Using a customized deep learning model, PoseSonic estimates the 3D positions of 9 body joints including the shoulders, elbows, wrists, hips, and nose. We adopt a cross-modal supervision strategy to train our model using synchronized RGB video frames as ground truth. We conducted in-lab and semi-in-the-wild user studies with 22 participants to evaluate PoseSonic, and our user-independent model achieved a mean per joint position error of 6.17 cm in the lab setting and 14.12 cm in semi-in-the-wild setting when predicting the 9 body joint positions in 3D. Our further studies show that the performance was not significantly impacted by different surroundings or when the devices were remounted or by real-world environmental noise. Finally, we discuss the opportunities, challenges, and limitations of deploying PoseSonic in real-world applications.

<iframe width="420" height="315"
src="https://www.youtube.com/embed/Q8KV1XfeBCE">
</iframe>
