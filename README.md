# PaperLists

## Physics
### [A Spacetime Perspective on Dynamical Computation in Neural Information Processing Systems](https://arxiv.org/pdf/2409.13669)
**Authors**: Keller, T Anderson and Muller, Lyle and Sejnowski, Terrence J and Welling, Max

*TL;DR*: It is shown that spatiotemporal dynamics may be a mechanism by which natural neural systems encode approximate visual, temporal, and abstract symmetries of the world as conserved quantities, thereby enabling improved generalization and long-term working memory. 
<details><summary>Abstract</summary>
  There is now substantial evidence for traveling waves and other structured spatiotemporal recurrent neural dynamics in cortical structures; but these observations have typically been difficult to reconcile with notions of topographically organized selectivity and feedforward receptive fields. We introduce a new 'spacetime' perspective on neural computation in which structured selectivity and dynamics are not contradictory but instead are complimentary. We show that spatiotemporal dynamics may be a mechanism by which natural neural systems encode approximate visual, temporal, and abstract symmetries of the world as conserved quantities, thereby enabling improved generalization and long-term working memory.
</details>

## Engineering
### [ReMEmbR: Building and Reasoning Over  Long-Horizon Spatio-Temporal Memory for Robot Navigation](https://arxiv.org/pdf/2409.13682)
**Authors**: Anwar, Abrar and Welsh, John and Biswas, Joydeep and Pouya, Soha and Chang, Yan

*TL;DR*: This work introduces a Retrieval-augmented Memory for Embodied Robots, or ReMEmbR, a system designed for long-horizon video question answering for robot navigation, and introduces the NaVQA dataset where it annotate spatial, temporal, and descriptive questions to long-horizon robot navigation videos.
<details><summary>Abstract</summary>
  Navigating and understanding complex environments over extended periods of time is a significant challenge for robots. People interacting with the robot may want to ask questions like where something happened, when it occurred, or how long ago it took place, which would require the robot to reason over a long history of their deployment. To address this problem, we introduce a Retrieval-augmented Memory for Embodied Robots, or ReMEmbR, a system designed for long-horizon video question answering for robot navigation. To evaluate ReMEmbR, we introduce the NaVQA dataset where we annotate spatial, temporal, and descriptive questions to long-horizon robot navigation videos. ReMEmbR employs a structured approach involving a memory building and a querying phase, leveraging temporal information, spatial information, and images to efficiently handle continuously growing robot histories. Our experiments demonstrate that ReMEmbR outperforms LLM and VLM baselines, allowing ReMEmbR to achieve effective long-horizon reasoning with low latency. Additionally, we deploy ReMEmbR on a robot and show that our approach can handle diverse queries. The dataset, code, videos, and other material can be found at the following link: https://nvidia-ai-iot.github.io/remembr
</details>

### Weakly Supervised Monocular 3D Object  Detection by Spatial-Temporal View Consistency
**Authors**: Han, Wencheng and Tao, Runzhou and Ling, Haibin and Shen, Jianbing

*TL;DR*: A weakly-supervised solution that trains monocular 3D object detectors solely using 2D labels, eliminating the requirement for 3D ground truths is presented, which achieves comparable performance to fully supervised methods.
<details><summary>Abstract</summary>
  Monocular 3D object detection plays a crucial role In the field of self-driving cars, estimating the size and location of objects solely based on input images. However, a notable disparity exists between the training and inference of 3D object detectors. This discrepancy arises because during inference, monocular 3D detectors depend solely on images captured by cameras; while during training, these methods require 3D ground truths labeled on point cloud data, which is obtained using specialized devices like LiDAR. This discrepancy creates a break in the data loop, preventing the feedback data from production cars from being utilized to enhance the robustness of the detectors. To address this issue and establish a connection in the data loop, we present a weakly-supervised solution that trains monocular 3D object detectors solely using 2D labels, eliminating the requirement for 3D ground truths. Our approach considers two view consistency: spatial and temporal view consistency, which play a crucial role in regulating the prediction of 3D bounding boxes. Spatial view consistency is achieved by employing projection and multi-view consistency techniques to guide the optimization of the target's location and size. We leverage temporal viewpoint consistency to provide temporal multi-view image pairs, and we further introduce temporal movement consistency to tackle the challenge of dynamic scenes. With only 2D ground truths, our method achieves comparable performance to fully supervised methods. Additionally, our method can be employed as a pre-training method and achieves significant improvement when fine-tuned with a small proportion of fully supervised labels.
</details>
