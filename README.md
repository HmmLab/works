Hmm Works: The Whole Works in Human Motion Modeling Laboratory
============
This project is created to display the works of the Human Motion Modeling Lab at Institute of Computing Technology, Chinese Academy of Sciences. The Lab is hosted by Prof. <a href="https://people.ucas.ac.cn/~xiashihong?language=en">Shihong Xia</a>. This project includes published works in the lab, including 3D human motion modeling, face modeling, and their applications. 

------------
**TVCG 2023**<br />
**Pose-aware Attention Network for Flexible Motion Retargeting by Body Part**<br >
<sub>
<a href="https://hlcdyy.github.io/">Lei Hu</a>, 
<a href="http://zihaozhang.tech/">Zihao Zhang</a>, 
<a Chongyang Zhong</a>,
<a Boyuan Jiang</a>,
<a href="https://people.ucas.ac.cn/~xiashihong?language=en">Shihong Xia</a>, 
IEEE Transactions on Visualization and Computer Graphics, DOI: 10.1109/TVCG.2023.3277918
<sub>
------------
<img src ="Media/TVCG_2023_PAN/Teaser.png" width="100%">

<p align="center">
Motion retargeting is a fundamental problem in computer graphics and computer vision. Existing approaches usually have many strict requirements, such as the source-target skeletons needing to have the same number of joints or share the same topology. To tackle this problem, we note that skeletons with different structure may have some common body parts despite the differences in joint numbers. Following this observation, we propose a novel, flexible motion retargeting framework. The key idea of our method is to regard the body part as the basic retargeting unit rather than directly retargeting the whole body motion. To enhance the spatial modeling capability of the motion encoder, we introduce a pose-aware attention network (PAN) in the motion encoding phase. The PAN is pose-aware since it can dynamically predict the joint weights within each body part based on the input pose, and then construct a shared latent space for each body part by feature pooling. Extensive experiments show that our approach can generate better motion retargeting results both qualitatively and quantitatively than state-of-the-art methods. Moreover, we also show that our framework can generate reasonable results even for a more challenging retargeting scenario, like retargeting between bipedal and quadrupedal skeletons because of the body part retargeting strategy and PAN.
</p>

<p align="center">
-
<a href="https://www.youtube.com/watch?v=oTAcxTtPXUg&t=95s&ab_channel=HMM_LAB">Video</a>
-
<a href="https://ieeexplore.ieee.org/document/10129844">Paper</a>    # you can put a pdf file or paper websites
-
<a href="https://github.com/hlcdyy/pan-motion-retargeting">Code & Demo</a>
-
</p>

<p align="center">
<a href="https://www.youtube.com/watch?v=oTAcxTtPXUg&t=95s&ab_channel=HMM_LAB">
<img width="60%" src="Media/TVCG_2023_PAN/h2d.png">
</a>
</p>

------------

