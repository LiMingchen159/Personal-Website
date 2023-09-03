---
title: Modelling Variable Refrigerant Flow System for Control Purpose
publication_types:
  - "2"
authors:
  - D Wang
  - Mingchen Li
  - M Guo
  - Q Shi
  - C Zheng
  - D Li
  - S Li
  - Z Wang
author_notes:
  - Co-first author
  - Co-first author
doi: https://doi.org/10.1016/j.enbuild.2023.113163
publication: Energy and Buildings
abstract: Variable Refrigerant Flow (VRF) systems are gradually gaining
  popularity in small and medium-sized commercial and residential buildings
  owing to their high part-load performance, flexible control, and ease of
  installation and maintenance. Developing models of VRF systems to predict
  their performance are important for model-based control, fault diagnostic and
  detection. There are VRF models published in existing literatures, however
  those models were developed and validated in different datasets. As a result,
  the model accuracy cannot be directly compared. To fill this gap, this paper
  presents a comprehensive review of the existing VRF models, and summarizes the
  input/output parameters and mathematical formulas of 16 VRF models from
  literature (referred to as physics-based model). Next, we validate and compare
  the model accuracy of existing models using the same dataset. Additionally, we
  develop data-driven models using the state-of-art machine learning algorithms,
  and compare the model accuracy between existing physics-based models with
  data-driven models. We find the model proposed by Hu et al. in 2019, which
  regresses the VRF cooling capacity and COP as a linear combination of indoor
  and outdoor temperatures times a cubed polynomial function of compressor
  frequency, is the most accurate physics-based model, with a prediction error
  of 22.19% in the training dataset and 22.44% in the validation dataset.
  XGBoost is the most accurate data-driven model, with a prediction error of
  19.29% in the training dataset and 22.02% in the validation dataset. The
  data-driven model is more accurate while the physics-based model is more
  generalizable. The findings of this study can help researchers to select the
  proper VRF model for building energy prediction, model-based optimization, and
  fault diagnostic and detection.
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
date: 2023-09-03T14:15:28.407Z
---
