# Awesome-Infrared-Simulation
Welcome to the Infrared Simulator Repository! This repository aims to collect various infrared simulators to promote the development and usage of infrared technology. Whether you are an engineer, researcher, or enthusiast, this repository will provide you with a wide range of infrared simulators to explore and utilize.

## Table of Contents
- [Introduction](#getting-started)
- [How to Contribute](#How-to-Contribute)
- [Infrared Simulators](#Infrared-Simulators)

## Introduction
Infrared simulators play a crucial role in understanding and optimizing the performance of infrared systems. They allow us to predict and evaluate the behavior of infrared imaging devices, atmospheric conditions, and image processing algorithms. By simulating infrared scenarios, we can minimize risks, optimize system designs, and ensure that the proposed systems meet specific requirements.

This repository will include a diverse collection of infrared simulators, covering various aspects of infrared technology. The simulators may focus on:
- Simulator for infrared cameras
- Dataset for infrared sythesis
- Simulation method for infrared 


## How to Contribute
We encourage contributions from the community to enrich the repository with new infrared simulators. If you have developed or come across an infrared simulator that is not yet included in this repository, please follow these steps to contribute:

- Fork this repository.
- Create a new branch with a descriptive name for your simulator.
- Add your simulator to the repository, including any necessary documentation or instructions.
- Commit your changes and create a pull request.


Our team will review your contribution, provide feedback if needed, and merge it into the main repository upon approval.
By contributing to this repository, you will help create a comprehensive resource for the infrared community and promote the advancement of infrared technology.

## Infrared Simulators
### [AirSim ](https://microsoft.github.io/AirSim/)
You can find it in their [Official Link](https://microsoft.github.io/AirSim/). And get some help in [simulated thermal infrared (IR) ](https://microsoft.github.io/AirSim/InfraredCamera/). But they are basicly using a LUT method in their segmentation map. So the simulation is not good enough even for Deep Learning models. The models can learn nothing but seg ability.

![infrared image sample from airsim](https://github.com/LT1st/Awesome-Infrared-Simulation/assets/39019137/90f0162b-8804-419b-ae64-6b79b4b05a38)

### [JRM EO/IR Sensor Plug-In & SDK](http://jrmtech.com/unreal/)
This looks great, but may cost a lot.

The JRM EO/IR Sensor Plug-in is JRM’s physics-based, real-time spectral EO/IR sensor scene simulator, utilizing the popular UNREAL ENGINE toolkit to load materially-encoded targets and terrain. JRM EO/IR Sensor Plug-in integrates JRM’s SigSim and SenSim run-time libraries to predict correlated, radiometrically-correct 2D sensor imagery for arbitrary sensor bands, under arbitrary weather conditions and spatio-temporal viewing locations.

```
Physics-based, dynamic environmental spectral irradiances & atmospherics
Spectral reflectance/specularity support
Physics-based volumetric and combustion effects (dust clouds, fires, smokes, flares, plumes)
Physics-based spectral man-made and natural light sources
On-the-fly transient thermal solutions
Dynamic heating/cooling of vehicles
Full spatial correlation among wavebands
Design Blur, Diffraction MTFs, user defined MTFs, motion blur, detector blur, and 3rd order aberrations (FOV dependent) blur
Aero-optical effects
Scanning effects
(1/f)n, Poisson, thermal, & fixed-pattern noise
Detector non-uniformity, dead pixels, fill-factor
Pre/Post amplification control, AGC
Physically-correct NVG light point haloing and low light CCD streaking Photon transfer computing to produce detector counts output
```
### [VIRSuite](https://www.dst.defence.gov.au/sites/default/files/publications/documents/DSC%201756%20Avalon%20Air%20Show%20VIR%20Suite.pdf)
VIRSuite is a software application for the generation of
visible and infrared scenes in real-time. This software
was developed by the Defence Science and Technology
(DST) Group for the simulation, analysis, development
and evaluation of electro-optical systems in a range of
complex scenarios and environments. 



## Infrared Simulation Methods
### Papers
#### [Simulation of near Infrared Sensor in Unity for Plant-weed Segmentation Classification](https://www.scitepress.org/Papers/2020/98279/98279.pdf)
Weed spotting through image classification is one of the methods applied in precision agriculture to increase
efficiency in crop damage reduction. These classifications are nowadays typically based on deep machine
learning with convolutional neural networks (CNN), where a main difficulty is gathering large amounts of
labeled data required for the training of these networks. Thus, synthetic dataset sources have been developed
including simulations based on graphic engines; however, some data inputs that can improve the performance
of CNNs like the near infrared (NIR) have not been considered in these simulations. This paper presents a
simulation in the Unity game engine that builds fields of sugar beets with weeds. Images are generated to
create datasets that are ready to train CNNs for semantic segmentation. The dataset is tested by comparing
classification results from the bonnet CNN network trained with synthetic images and trained with real images,
both with RGB and RGBN (RGB+near infrared) as inputs. The preliminary results suggest that the addition
of the NIR channel to the simulation for plant-weed segmentation can be effectively exploited. These show a
difference of 5.75% for the global mean IoU over 820 classified images by including the NIR data in the unity
generated dataset.

#### [Tensorial properties via the neuroevolution potential framework: Fast simulation of infrared and Raman spectra](https://arxiv.org/abs/2312.05233)
Infrared and Raman spectroscopy are widely used for the characterization of gases, liquids, and solids, as the spectra contain a wealth of information concerning in particular the dynamics of these systems. Atomic scale simulations can be used to predict such spectra but are often severely limited due to high computational cost or the need for strong approximations that limit application range and reliability. Here, we introduce a machine learning (ML) accelerated approach that addresses these shortcomings and provides a significant performance boost in terms of data and computational efficiency compared to earlier ML schemes. To this end, we generalize the neuroevolution potential approach to enable the prediction of rank one and two tensors to obtain the tensorial neuroevolution potential (TNEP) scheme. We apply the resulting framework to construct models for the dipole moment, polarizability, and susceptibility of molecules, liquids, and solids, and show that our approach compares favorably with several ML models from the literature with respect to accuracy and computational efficiency. Finally, we demonstrate the application of the TNEP approach to the prediction of infrared and Raman spectra of liquid water, a molecule (PTAF-), and a prototypical perovskite with strong anharmonicity (BaZrO3). The TNEP approach is implemented in the free and open source software package GPUMD, which makes this methodology readily available to the scientific community.

#### [Dynamic Infrared Simulation: A Feasibility Study of a Physically Based Infrared Simulation Model](http://www.diva-portal.org/smash/get/diva2:22896/FULLTEXT01.pdf)
The increased usage of infrared sensors by pilots has created a growing demand
for simulated environments based on infrared radiation. This has led to an
increased need for Saab to refine their existing model for simulating real-time
infrared imagery, resulting in the carrying through of this thesis. Saab develops
the Gripen aircraft, and they provide training simulators where pilots can train
in a realistic environment. The new model is required to be based on the realworld behavior of infrared radiation, and furthermore, unlike Saab’s existing
model, have dynamically changeable attributes.
This thesis seeks to develop a simulation model compliant with the
requirements presented by Saab, and to develop the implementation of a test
environment demonstrating the features and capabilities of the proposed model.
All through the development of the model, the pilot training value has been kept
in mind.

The first part of the thesis consists of a literature study to build a theoretical
base for the rest of the work. This is followed by the development of the
simulation model itself and a subsequent implementation thereof. The
simulation model and the test implementation are evaluated as the final step
conducted within the framework of this thesis.
The main conclusions of this thesis first of all includes that the proposed
simulation model does in fact have its foundation in physics. It is further
concluded that certain attributes of the model, such as time of day, are
dynamically changeable as requested. Furthermore, the test implementation is
considered to have been feasibly integrated with the current simulation
environment.

A plan concluding how to proceed has also been developed. The plan suggests
future work with the proposed simulation model, since the evaluation shows that
it performs well in comparison to the existing model as well as other products
on the market.





















### Disscussions
[About AimSim's poor performance on infrared simulation](https://stackoverflow.com/questions/76872875/how-to-simulate-ir-vision-in-unreal-engine)

The [Stefan–Boltzmann law](https://en.wikipedia.org/wiki/Stefan%E2%80%93Boltzmann_law), also known as Stefan's law, describes the intensity of the thermal radiation emitted by matter in terms of that matter's temperature. It is named for Josef Stefan, who empirically derived the relationship, and Ludwig Boltzmann who derived the law theoretically.

![image](https://github.com/LT1st/Awesome-Infrared-Simulation/assets/39019137/5d37cacd-0294-43cc-aabd-ee7e9d35092a)

## Sources
1. [GitHub - othneildrew/Best-README-Template](https://github.com/othneildrew/Best-README-Template)
2. [A simple README.md template · GitHub](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
