# Courseware-on-MBSE

[![View Courseware on MBSE on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/181163-mbse-courseware) or [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=HaroldB-creator/courseware-on-MBSE)


**Curriculum Module**  
_Created with R2024b. Compatible with R2024b and later releases._  

## Description

This courseware on Model Based Systems Engineering (MBSE) addresses the various phases of moodel-based R&D projects and the specific tasks involved in each phase. During the course, we provide examples of how Mathworks' tools such as System Composer, Simulink Test, and State Flow support the MBSE process.\
\
Moreover, the interactive courseware uses extensively the [MATLAB&reg;](https://www.mathworks.com/products/matlab.html) Live Editor for the development and the presentation.\
\
Each chapter ends with a quiz to test your knowledge and understanding, many chapters provide exercises with the tools to improve your practical MBSE skills.\
\
This MBSE courseware was developed in close cooperation between Fontys University of Applied Sciences (department of Electrical Engineering) and The MathWoks.

## Owner/s
Harold Benten, MSc ([h.benten@fontys.nl](mailto:h.benten@fontys.nl))\
Tamir Azaouag, BSc ([tamir-azaouag@outlook.com](mailto:tamir-azaouag@outlook.com))


## Contents
The repository contains the following Live Scripts and folders:

- **``CoursewareonModelBasedSystemsEngineering.prj``**\
This is the MATLAB project file which sets up all necessary dependencies

- **``MBSE(1).mlx``**\
This is the main document that can be used to navigate to the rest of the Live Scripts in the repository

- **``Chapters/``**\
This folder contains the Live Scripts of the course chapters
  - **``Introduction(2).mlx``**\
  A real-world example is NASA's use of MBSE in developing spacecraft.
  
  - **``Advantages(3).mlx``**\
  Some important advantages of MBSE are shown in the figure below:
  <img src="https://github.com/MBSE-course/MBSE-courseware/blob/main/Chapters/figures/mbse_advantages.png" width="70%">
  
  - **``Requirements(4).mlx``**\
  Detailed and measurable requirements are the cornerstone of effective Requirements Engineering.
  <img src="https://github.com/MBSE-course/MBSE-courseware/blob/main/Chapters/figures/mbse_requirements.png" width="70%">
  
  - **``ImportingRequirements(5).mlx``**\
  MATLAB offers the convience of importing from various file formats like Word and Excel.

  - **``LinkingRequirements(6).mlx``**\
  It is crucial to requirements troughout the system desgin process.

  - **``System_Architecture(7).mlx``**\
  A high-level system architecture is a simplified overview of a system's structure. The picture above shows the high-level system architecture of a mini drone.
  <img src="https://github.com/MBSE-course/MBSE-courseware/blob/main/Chapters/figures/mbse_hlsa_mini_drone.png" width="80%">

  - **``LowLevel_Architecture(8).mlx``**\
  A well-crafted low-level design includes detailed diagrams, pseudocode and speciifications that guide developers through the systems process, ensuring that each module aligns with the system's overall objectives and integrates seamlessly with other components.

  - **``Stereotypes(9).mlx``**\
  Using stereotypes and profiles makes it easier to manage and understand your system because it standardizes how components are represented.
  
  - **``Architecture_Views(10).mlx``**\
 The structure of a complex system is usually different from its functional requirements. Architecture views help system designers focussing on a specifc part. 

  - **``Testing(11).mlx``**\
  The V-model (see figure below) is a key metyhod in MBSE that highlights testing at every stage, from initial requiremnts to final system deployment, pairing each desgin phase with a corresponding testing phase.
   <img src="https://github.com/MBSE-course/MBSE-courseware/blob/main/Chapters/figures/mbse_v-model.png" width="70%">

  - **``SimulinkTest(12).mlx``**\
  Simulink Test provides tools to create, manage, and run simulation-based tests for models, generated code, and both simulated and physical hardware.

  - **``Behavior_Models(13).mlx``**\
  Behavior models allow you to simulate real-life scenarios for your system, such as adding external factors or testing the system with different I/Os to evaulate its stability. MATLAB provides loads of subsystems, functions and models that help with creating the model behavior for your system.

  - **``Behavior_Models_Example(14).mlx``**\
  In this chapter, you will design your own behavior model using StateFlow.

  - **``Recap(15).mlx``**\
  This chapter summarizes the advantages, phases, tasks and tools that used in Model Based System Engineering.

## Concepts
Model Based Systems Engineering, requirements gathering, requirements analyzing, stereotypes, architecting, high-level design, low-level design, behavioral modelling, testing, implementation.

## Suggested Audience
All engineering disciplines, such as, electrical engineers, mechatronics engineers, mechanical engineers, etc.

## Workflow
Firstly, open the project file CoursewareonFiniteElementMethods.prj to have all the folder dependencies resolved. Then, open Live Script **MBSE(1).mlx** to start the course. Stay in the MBSE folder (so not in the chapters folder) for navigating through the course chapters.

## Release last tested
R2024b

## Revision History
Version 1.0 - inital version - May 20th 2025

