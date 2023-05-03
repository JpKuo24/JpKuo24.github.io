---
layout: single
title: "Project"
permalink: Proect
author_profile: true
redirect_from: 
  - /project/
  - /project.html
---

My research aims to build an efficient mobile vision system with edge-assisted live video analytics.
I am interested in exploiting and developing a multi-disciplinary solution that incorporates computer vision, edge computing multimedia and machine leanring to to enhance the system's effectiveness and efficiency. 

Currently, I am particular interested in the following problems:
* Making mobile vision more efficient with more video compression
* Enhance DNN deployment efficiency in diverse use sceaniro


Compress Video without Compromising Analytical Accuracy
----
Given the fast development in computer vision, we orthogonally enforces more efficient compression for the specific vision inference tasks.It adapts to input contexts and significantly reduces the volume of video data without sacrificing visual inference accuracy (negligible
impacts).

<div style="display: flex">
    <video width="320" height="240" controls style="float: left; margin-right: 10px;">
        <source src="../images/dcc.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <p>DCC utilizes the drone-specific context and intermediate information obtained from object detection to
jointly adjust the resolution, QP, and frame rate during run-time. We use vehicle detection from the drone as a showcase to show its effectiveness.</p>
</div>


<div style="display: flex">
    <video width="320" height="240" controls style="float: left; margin-right: 10px;">
        <source src="../images/vpplus.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>
    <p>VPPlus takes a further step by expanding the configuration space that can be tuned
during on-device processing for general object detection task. It generates proper feedback automatically to guide the joint
tuning over more than 8 parameters.</p>
</div>





Customize DNN Deployment in Diverse Use Scenario
----
When presented with diverse mobile devices performing distinct application tasks that facilitate varying scenarios, we tailor DNN to enhance performance for each scenario with Once-For-All DNN training: Train one super network and search different sub-networks (subnet) to fit use scenario.

<div style="display: flex">
    <img src="../images/ofa_flow.png" alt="Your Image" width="300" style="float: left; margin-right: 10px;">
    <p>Instead of training a specialized DNN for each deployment scenario, we have developed a
novel approach of using the shallow subnet to test the water. The effectiveness of using a
shallow subnet to accelerate the search of a deep subnet has been validated effective in image
classification, one showcase application.</p>
</div>