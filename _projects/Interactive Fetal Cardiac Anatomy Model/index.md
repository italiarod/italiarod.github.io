---
layout: post
title: Interactive Fetal Cardiac Anatomy Model
description: Developed an interactive 3D fetal cardiac anatomy model as part of my senior biomedical engineering design project focused on fetal echocardiography education. The project combined medical image segmentation, 3D mesh processing, anatomical modeling, and web-based visualization to create an accessible educational resource for exploring fetal heart anatomy and congenital heart defects.

skills:
  - Medical Image Segmentation
  - 3D Anatomical Modeling
  - 3D Slicer
  - Blender
  - Mesh Processing
  - Biomedical Visualization
  - Congenital Heart Defect Modeling
  - Human-Centered Design
  - Technical Communication
  - Web-Based 3D Visualization

main-image: /FetalHeartTitleCard.png
---

---

{% include image-gallery.html images="2026-04-02-Scene.png" height="400" %}


{% include image-gallery.html images="2026-04-04-Scene.png" height="400" %}


## Phase 1: Medical Image Segmentation

The project began with the development of a three-dimensional cardiac model from medical imaging data. Using 3D Slicer, cardiac structures were identified and segmented from volumetric imaging data to reconstruct the anatomy of a real human heart.

Individual anatomical regions were isolated from the surrounding tissue and converted into three-dimensional geometry. This process required balancing anatomical detail with the limitations of the source imaging data, particularly around smaller and more complex internal cardiac structures.

The resulting segmentation provided an anatomically grounded starting point for the educational model and allowed the team to move from medical imaging data into a format that could be further processed and modified using traditional 3D modeling software.


---

{% include image-gallery.html images="FetalAnatomyCompiled.png" height="400" %}


## Phase 2: Model Cleanup & Anatomical Refinement

After segmentation, the reconstructed geometry was imported into Blender for mesh cleanup and refinement. Medical image segmentation can produce irregular surfaces and unnecessary geometric complexity, so the raw model required additional processing before it could function effectively as an interactive educational resource.

The model was cleaned and refined to improve surface quality, remove segmentation artifacts, and create clearer representations of important cardiac structures. The geometry was also prepared with interactive visualization in mind, balancing anatomical detail with a model that could be efficiently displayed and manipulated digitally.

This stage transformed the raw medical-image reconstruction into a cleaner and more usable anatomical model suitable for further modification and integration into the educational platform.


---

{% include image-gallery.html images="FetalCHDsCompiled.png" height="400" %}


## Phase 3: Congenital Heart Defect Modeling

Once the baseline cardiac anatomy had been established, the model was modified to represent congenital heart defects (CHDs). These variations were created by altering relevant anatomical structures within the 3D model, allowing abnormal anatomy to be compared with the baseline heart.

Developing these variations required translating clinical descriptions of congenital heart defects into three-dimensional anatomical changes while maintaining the relationships between surrounding cardiac structures.

Including both baseline anatomy and CHD variations expanded the model beyond a general anatomy resource and supported its intended application in fetal echocardiography education, where understanding abnormal spatial relationships is particularly important.


---

{% include image-gallery.html images="FetalHeartWebsite.png height="400" %}


## Phase 4: Interactive Educational Platform

The cardiac models were compiled into a web-based educational platform designed to make three-dimensional fetal heart anatomy more accessible to people learning and working with fetal echocardiography.

Rather than requiring specialized 3D modeling or medical imaging software, the website was designed to allow users to access and interact with the model directly through a web browser. Users could manipulate the three-dimensional anatomy and explore cardiac structures from different orientations, providing a spatial reference for understanding anatomy encountered during fetal echocardiography.

The platform was designed around accessibility and education, with the goal of providing a freely available resource that could supplement traditional diagrams, ultrasound images, and existing anatomy models.


---

{% include image-gallery.html images="theheart2.png" height="400" %}


## Phase 5: Design Review & Final Presentation

Throughout the project, our team compiled the modeling process, technical decisions, educational objectives, and platform development into formal design documentation and presentations.

The completed project was presented to our faculty professor and project sponsor, demonstrating the progression from medical imaging and segmentation through mesh refinement, congenital heart defect modeling, and implementation of the interactive website.

The final presentation also communicated the design rationale behind the platform, limitations of the available anatomical data, and opportunities for continued development. By combining biomedical imaging, 3D modeling, and interactive visualization, the project demonstrated how engineering tools could be used to make complex fetal cardiac anatomy more accessible for fetal echocardiography education.
