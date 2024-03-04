---
title: "GazeTrak: Exploring Acoustic-based Eye Tracking on a Glass Frame"
collection: publications
permalink: /publication/2024-02-23-GazeTrak-Exploring-Acoustic-based-Eye-Tracking-on-a-Glass-Frame
excerpt: 'September 30-October 4, 2024, Washington, D.C., USA. Keyword: Eye Tracking, Acoustic Sensing, Smart Glasses, Low-power'
date: 2024-02-23
venue: 'The Annual International Conference on Mobile Computing and Networking (MobiCom)'
paperurl: 'http://arxiv.org/abs/2402.14634'
citation: '<u>Ke Li</u>, Ruidong Zhang, Boao Chen, Siyuan Chen, Sicheng Yin, Saif Mahmud, Qikang Liang, François Guimbretière, and Cheng Zhang. 2024. GazeTrak: Exploring Acoustic-based Eye Tracking on a Glass Frame. In <i>The Annual International Conference on Mobile Computing and Networking (MobiCom), September 30-October 4, 2024, Washington, D.C., USA</i>. ACM, New York, NY, USA.'
---
Selected Media Coverage: [New Scientist](https://www.newscientist.com/article/2418742-smart-glasses-use-sonar-to-work-out-where-youre-looking/)

September 30-October 4, 2024, Washington, D.C., USA<br>
Keyword: Eye Tracking, Acoustic Sensing, Smart Glasses, Low-power

<figure>
    <center><img src="https://keli97.github.io/files/gazetrak.png" alt="Trulli" style="width:100%" class="center"></center>
</figure>

In this paper, we present GazeTrak, the first acoustic-based eye tracking system on glasses. Our system only needs one speaker and four microphones attached to each side of the glasses. These acoustic sensors capture the formations of the eyeballs and the surrounding areas by emitting encoded inaudible sound towards eyeballs and receiving the reflected signals. These reflected signals are further processed to calculate the echo profiles, which are fed to a customized deep learning pipeline to continuously infer the gaze position. In a user study with 20 participants, GazeTrak achieves an accuracy of 3.6° within the same remounting session and 4.9° across different sessions with a refreshing rate of 83.3 Hz and a power signature of 287.9 mW. Furthermore, we report the performance of our gaze tracking system fully implemented on an MCU with a low-power CNN accelerator (MAX78002). In this configuration, the system runs at up to 83.3 Hz and has a total power signature of 95.4 mW with a 30 Hz FPS.

<iframe width="420" height="315"
src="https://www.youtube.com/embed/XvNLNkfQY7Q">
</iframe>
