---
layout: page
title: Master's Internship 2022
description: Machine-learning approaches to model interatomic interactions in materials
img: assets/img/fccBulk.png
importance: 3
category: academic
---

Master's internship project under the supervision of Dr. Julien Lam and Dr. Akshay Krishna. The report can be seen <a href="assets\pdf\SALAZAR-LETONA_Carlos-Rafael_M1.pdf">here</a>.

### Abstract
Machine learning (ML) methods have become more relevant in materials science over the last decade. They are now well recognized as effective methods for approximating extremely complex functions. Machine learning interaction potentials (MLIP) offer computation speeds close to empirical potentials, while having an accuracy close to the method used in training. In this project, the effects of the neural network (NN) architecture on its accuracy of prediction were studied. The machine learning framework n2p2 was used for the creation of potentials for gold systems from a Density-functional theory (DFT) database. The potential was then used together with Large-scale Atomic/Molecular Massively Parallel Simulator (LAMMPS) to calculate the surface energies and mechanical properties. These calculations were compared with values from DFT calculations as a measure of the agreement with DFT methods. Potentials were then trained using slightly different setup parameters in order to study their effect on the accuracy of the potential. The transferability of the potential was also investigated by training potentials with incomplete databases. It was found that the machine learning potential could be in good agreement with the DFT values, provided the setup parameters are properly chosen. Moreover, the potential showed good transferability, which is an important quality for the application of this potential in simulations. The results revealed that machine learning is not a one-size-fits-all solution, and that it still relies substantially on the setup parameters to properly minimize the errors with respect to the database.