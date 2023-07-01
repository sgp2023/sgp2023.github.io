---
title: "Program"
layout: "program"
type: "page"
menu: program


speakers: 
  - name: Theodore Kim
    url: https://seas.yale.edu/faculty-research/faculty-directory/theodore-kim
    affiliation: Yale University 
    title: The Character of Computer Animation Research
    abstract: Like all areas of research, physics-based simulation for computer animation encapsulates a core set of foundational problems. These include the simulation of smoke, water, and solids such as muscles and skin, efficient ways of controlling these simulations, and methods for dealing with their geometry. But where did these formulations come from, and how universal are they? In this talk, I will discuss their historical provenance. Far from being universal, they are highly tailored to analog-era industrial techniques from Walt Disney Animation Studios and Industrial Light and Magic. How does this then shape our perceptions, and what counts as valid research problems and solutions? I will not have many answers, but I hope to raise a few questions.
    portrait: /images/TKim.jpg
  - name: Alexander Bobenko
    url: https://page.math.tu-berlin.de/~bobenko/
    affiliation: Technical University Berlin
    title: "Structure preserving discretizations: Towards generalizations of conformal maps and circle patterns"
    abstract: "Structure-preserving discretization in the field of geometry is the paradigm of discrete differential geometry. Here, of course, deciding which of the structures are to be taken into account is a nontrivial problem. In some aspects, the discrete theory turns out to be even richer than its smooth counterpart. It focuses on developing constructive methods, which allow one to prove natural existence and uniqueness results, as well as the corresponding convergence statements. The well-established theory of discrete conformal maps and circle patterns has already found numerous applications in geometry processing. We present their generalizations beyond the conformal limit: decorated discrete conformal maps and ring patterns, which share the corresponding existence and uniqueness statements. The theory and construction methods are based on variational principles. We also briefly explain how structure preserving discretizations recently helped to answer the long-standing question whether a surface in three-space is uniquely determined by its metric and curvatures (Bonnet problem)."
    portrait: /images/ABobenko.png    

graduateSchoolCourses:
- title: Functional Correspondence from Discrete Geometry to Learning
  teaser: /images/school-discrete.png
  speakers:
    - name: Riccardo Marin 
      affiliation: University of Tuebingen
    - name: Emanuele Rodola
      affiliation: GLADIA
  abstract: |
     ***July 1st, 9:00 - 10:30***
     
     Geometry processing is a vital component for solving 3D shape-matching problems that have significant relevance in enabling various downstream tasks like artistic designs, CAD modeling, and medical analysis. With the advent of data-driven solutions, flexible alignment techniques have become essential tools to unleash the potential of deep learning methods. This tutorial introduces the Functional Maps paradigm, one of the main frameworks for the past decade. We will explain the main concepts of this elegant and flexible framework on graphs, and then develop the necessary tools for triangular mesh cases. We will review the crucial steps of this long-standing literature, from its inception to the advent of geometric deep learning. Additionally, we will highlight the latest and most promising research directions, giving participants a comprehensive understanding of the current state-of-the-art in this field.  
      
- title: Hands-On Introduction to FEM in Python
  teaser: /images/school-Python.png
  speakers:
    - name: Teseo Schneider
      affiliation: University of Victoria
  abstract: |
      ***July 1st, 10:45 - 12:15***
      
      The numerical solution of partial differential equations (PDEs) is ubiquitous in computer graphics and engineering applications, ranging from the computation of UV maps and skinning weights to the simulation of elastic deformations, fluids, and light scattering. The finite element method (FEM) is the most commonly used discretization of PDEs due to its generality and rich selection of off-the-shelf commercial implementations. In this course, we will implement a FE solver in 1D for the Laplace equation from scratch using only Numpy. We will briefly derive the necessary theory and quickly move into live coding the solver. At the end of the course, you will have a basic applied understanding of how the FEM works and how to extend the current code to higher dimensions and more complicated physics. 

- title: Computational Design of Deployable Structures
  teaser: /images/school-structures.png
  speakers:
    - name: Julian Panetta
      affiliation: UCDavis
  abstract: |
    ***July 1st, 13:15 - 14:45***
  
    Structures that transform from compact configurations (which are simpler to manufacture and transport) to 3D shapes with specific forms and functions have important advantages for applications like emergency shelters, temporary event spaces, medical devices, and satellite antennas. However, designing such structures is difficult, involving interesting technical challenges like controlling the highly nonlinear large-deformation behavior of elastic beam and membrane structures. This course presents computational techniques for tackling inverse design problems in this space. It will cover shape optimization using differentiable physics simulation and show various strategies for accelerating these optimization algorithms. It will also introduce two-scale design algorithms, where the low-level details of the physical system are abstracted using homogenization to obtain a coarsened design problem that can be solved robustly by traditional computer graphics techniques like surface parametrization algorithms. Then the coarsened solution is "de-homogenized" to a full-scale structure and fine-tuned with shape optimization.

- title: A quick journey into geometry processing
  teaser: /images/school-journey.png
  speakers:
    - name: Bruno Levy
      affiliation: Inria
  abstract: |
    ***July 1st, 15:00 - 16:30***
    
    This course is a gentle introduction to the set of notions useful in geometry processing that  I consider as the "minimal toolbox". I will illustrate the different notions with tips and tricks on how to efficiently implement them in a computer. Code and demos related to the notions that I'll present is available in Geogram (https://github.com/BrunoLevy/geogram) and Graphite (https://github.com/BrunoLevy/GraphiteThree)
    
- title: Connecting Language to 3D
  teaser: /images/school-language.png
  speakers:
    - name : Angel Chang
      affiliation: Simon Fraser University
  abstract: |
    ***July 1st, 16:45 - 18:15***
    
    In this tutorial, we will cover recent developments in connecting language to 3D. We will discuss components in multimodal models for language and 3D data. Then we will cover applications such as localizing and describing objects in 3D scenes, and text-to-3D shape and scene generation. We will conclude with open research challenges and opportunities in this emerging research direction.


- title: Hexmesh generation and processing
  teaser: /images/school-hexmeshing.png
  speakers:
    - name: Gianmarco Cherchi 
      affiliation: University of Cagliari
    - name: Marco Livesu
      affiliation: IMATI
  abstract: |
    ***July 2nd, 9:00 - 10:30***
    
    Hexahedral meshes are a prominent volumetric mesh representation. They are largely used as computational domains for the resolution of partial differential equations for physically based simulation, making them a core ingredient of many software tools used by the automobile, naval, aerospace, medical, and geological industries, as well as for many applications in Computer Graphics and Animation. In academic research and industry, the algorithmic generation and processing of hexahedral meshes have been studied for more than 30 years now. In this course, we will introduce the topic of hexahedral meshes and focus on the most relevant techniques for hexahedral mesh generation in Computer Graphics. For each technique, we will highlight capabilities and limitations, also pointing out the associated unsolved challenges. The required background, pertaining to geometrical as well as combinatorial aspects, will be introduced along the way.

- title: Dive into Neural Implicit-Explicit 3D Representations and their Applications
  teaser: /images/school-neural.png
  speakers: 
    - name: Songyou Peng
      affiliation:  ETH Zurich & MPI
  abstract: |
    ***July 2nd, 10:45 - 12:15***
    
    In this lecture talk, we will delve into the fascinating world of neural implicit-explicit 3D representations from a computer vision perspective. Beginning with the basics of explicit, implicit, and hybrid 3D scene representations, we will establish a foundation for understanding how these representations contribute to the field of 3D computer vision. We will then explore the recent evolution of hybrid implicit-explicit 3D representations in 3D reconstruction, neural rendering, and visual SLAM, discussing seminal works that have significantly advanced the state-of-the-art. In light of the recent hype surrounding ChatGPT, we will also briefly examine how large language models can be combined with implicit and explicit representations to enable new possibilities and innovative solutions in computer vision research
  
- title: Topology-Aware Reconstruction
  teaser: /images/school-topology.png
  speakers:
    - name: Tao Ju
      affiliation: Washington University in St. Louis
  abstract: |
    ***July 2nd, 13:15 - 14:45***
    
    Surface reconstruction from raw and imperfect inputs often results in shapes containing unwanted topological features, such as islands, handles, and voids. These errors are detrimental to downstream geometric processing tasks such as simplification, parameterization, and simulation. Topological errors can either be removed after the shape has been reconstructed (known as topological repair) or prevented during reconstruction by imposing topological constraints. This course will introduce fundamental concepts of topology that are relevant to surface reconstruction, review existing methods for topology repair and topology-constrained reconstruction, and describe several selected methods in detail. The course will end with a discussion of open problems in this area that await future research.
                
- title: Geometry Processing with Implicit Surfaces
  teaser: /images/school-implicit.png
  speakers:
    - name: David R. Palmer
      affiliation: MIT
  abstract: |
    ***July 2nd, 15:00-16:30***
    
    The recent popularity of neural implicit surfaces has renewed interest in implicit representations of geometry. In this session, we will dive into the world of implicit surfaces, both classical and neural. First, we will look at the use of implicit surfaces in surface reconstruction from point clouds. We will explore how a classical method, Poisson surface reconstruction, has recently been reinterpreted in a Gaussian process framework. Then we will take a look at recent neural implicit methods for surface reconstruction and the architecture and regularization choices they make. We will take a brief detour to look at NeRF and its descendants and their relationship to neural implicit models. The success of neural implicit representations has driven an interest in building a complete geometry processing pipeline around these representations. We will look at some attempts in this direction and conclude with some reflections about the future of the field.    
    
- title: Machine Learning for Structural Biology
  teaser: /images/covid_spike.png
  speakers:
    - name: Ellen Zhong
      affiliation: Princeton University
  abstract: |
    ***July 2nd, 16:45-18:15***
  
    Over the past few years, structural biology, the study of the 3D structure or shape of proteins and other biomolecules, has been transformed by breakthroughs from machine learning algorithms. The goal of this course will be to highlight some of these recent advances and to make connections between their underlying algorithms to related methods in geometry processing. After a brief primer on proteins and the significance of their 3D structures (assuming no prior knowledge of biology), I will overview two complementary research thrusts:
    
    1) &bull; protein structure prediction (e.g. AlphaFold) and 
    2) &bull; protein structure determination via 3D reconstruction of cryo-electron microscopy images. 
    
    Topics will include structured transformers for 3D data and implicit neural representations, respectively. A desired outcome will be to convey the unique, multimodal challenges in this highly interdisciplinary area.
                
paperSessions: 
- name: Meshing (Monday 10:45-12:45)
  papers:
      - title: "HalfedgeCNN for Native and Flexible Deep Learning on Triangle Meshes"
        authors:
          - name: Daniel Tyson
          - name: Ingmar Ludwig        
          - name: Marcel Campen
      - title: "HexBox: Interactive Box Modeling of Hexahedral Meshes"
        authors:
          - name: Francesco Zoccheddu          
          - name: Enrico Gobbetti
          - name: Marco Livesu
          - name: Nico Pietroni
          - name: Gianmarco Cherchi                    
      - title: "Quadratic-Attraction Subdivision"
        authors:
          - name: Kestutis Karciauskas
          - name: Jorg Peters          
      - title: "PowerRTF: Power Diagram based Restricted Tangent Face for Surface Remeshing"  
        authors:
          - name: Yuyou Yao
          - name: Jingjing Liu
          - name: Yue Fei
          - name: Wenming Wu
          - name: Gaofeng Zhang
          - name: Dongming Yan          
          - name: Liping Zheng

- name: 2D Geometry (Monday 15:00-16:00)  
  papers:
      - title: "Singularity-Free Frame Fields for Line Drawing Vectorization"      
        authors:
          - name: Olga Guțan        
          - name: Shreya Hegde         
          - name: Erick Jimenez Berumen          
          - name: Mikhail Bessmeltsev
          - name: Edward Chien
      - title: "Variational Pruning of Medial Axes of Planar Shapes"   
        authors:
          - name: Peter Rong           
          - name: Tao Ju

- name: Details on surfaces (Monday 16:30-18:00)
  papers:
      - title: "Deep Deformation Detail Synthesis for Thin Shell Models"  
        authors:
          - name: Lan Chen     
          - name: Lin Gao   
          - name: Jie Yang
          - name: Shibiao Xu
          - name: Juntao Ye
          - name: Xiaopeng Zhang          
          - name: Yu-Kun Lai 
                                                                                                                                                                           
      - title: "Graph-Based Synthesis for Skin Micro Wrinkles"  
        authors:
          - name: Sebastian Weiss
          - name: Jonathan Moulin
          - name: Prashanth Chandran    
          - name: Gaspard Zoss    
          - name: Paulo Gotardo          
          - name: Derek Bradley

      - title: "A Shape Modulus for Fractal Geometry Generation"  
        authors:
          - name: Alexa Schor        
          - name: Theodore Kim
 
                                         
- name: Surface Reconstruction (Tuesday 10:45-12:45)   
  papers:
      - title: "Feature-Preserving Offset Mesh Generation from Topology-Adapted Octrees"    
        authors:
          - name: Daniel Zint
          - name: Nissim Maruani         
          - name: Mael Rouxel-Labbe
          - name: Pierre Alliez          
      - title: "Poisson Manifold Reconstruction - Beyond Co-dimension One"  
        authors:
          - name: Maximilian Kohlbrenner
          - name: Singchun Lee
          - name: Marc Alexa
          - name: Misha Kazhdan
      - title: "ANISE: Assembly-based Neural Implicit Surface reconstruction"  
        authors:      
          - name: Dmitry Petrov
          - name: Matheus Gadelha
          - name: Radomír Měch
          - name: Evangelos Kalogerakis

- name: Deformation (Tuesday 15:00-16:00)  
  papers:
      - title: "ARAP Revisited: Discretizing the Elastic Energy using Intrinsic Voronoi Cells" 
        authors:      
          - name: Ugo Finnendahl
          - name: Matthias Schwartz
          - name: Marc Alexa
      - title: "Maximum Likelihood Coordinates"  
        authors:      
          - name: Qingjun Chang   
          - name: Chongyang Deng          
          - name: Kai Hormann
      
- name: Point clouds and Scenes (Tuesday 16:30-18:00)
  papers:
      - title: "Cross-Shape Attention for Part Segmentation of 3D Point Clouds" 
        authors:    
          - name: Marios Loizou        
          - name: Siddhant Garg   
          - name: Dmitrii Petrov          
          - name: Melinos Averkiou
          - name: Evangelos Kalogerakis
      - title: "Lightweight Curvature Estimations on Point Clouds with Randomized Corrected Curvature Measures"  
        authors:      
          - name: Jacques-Olivier Lachaud       
          - name: David Coeurjolly  
          - name: Céline Labart   
          - name: Pascal Romon          
          - name: Boris Thibert
      - title: "Factored Neural Representation for Scene Understanding" 
        authors:     
          - name: Yu-Shiang Wong        
          - name: Niloy Mitra
      
- name: Shape Correspondence (Wednesday 10:45-12:45)  
  papers:
      - title: "Attention And Positional Encoding Are (Almost) All You Need For Shape Matching" 
        authors:     
          - name: Alessandro Raganato      
          - name: Gabriella Pasi       
          - name: Simone Melzi

      - title: "Partial Matching of Non rigid Shapes by Learning Piecewise Smooth Functions"  
        authors:   
          - name: David Bensaid   
          - name: Noam Rotstein       
          - name: Nelson Goldenstein          
          - name: Ron Kimmel
      - title: "BPM: Blended Piecewise Mobius Maps"  
        authors:     
          - name: Shir Rorberg    
          - name: Amir Vaxman          
          - name: Mirela Ben-Chen
      - title: "VOLMAP: a Large Scale Benchmark for Volume Mappings to Simple Base Domains"        
        authors:      
          - name: Gianmarco Cherchi        
          - name: Marco Livesu
 
          
- name: Representation and Learning (Wednesday 16:30-18:00)  
  papers:
      - title: "Neural Representation of Open Surfaces" 
        authors:      
          - name: Thor Christiansen        
          - name: Jakob Andreas Bærentzen
          - name: Rasmus Paulsen          
          - name: Morten Rieger Hannemose

      - title: "3D Keypoint Estimation using Implicit Representation Learning"  
        authors:   
          - name: Xiangyu Zhu       
          - name: Dong Du  
          - name: Haibin Huang          
          - name: Chongyang Ma
          - name: Xiaoguang Han
      - title: "3D Generative Model Latent Disentanglement via Local Eigenprojection"      
        authors:      
          - name: Simone Foti
          - name: Bongjin Koo
          - name: Danail Stoyanov
          - name: Matthew J. Clarkson

---  


<!-- 

Toponet?


paper1055	Partial Matching of Nonrigid Shapes by Learning Piecewise Smooth Functions		Ron Kimmel                             David Bensaid                             Noam Rotstein                             Nelson Goldenstein


          

The complete program schedule can be downloaded [here.](/images/SGP_2022_Program.pdf) (The file with timestamp 2022-06-20 09:00:00 is the current one)

paperUSB: https://cloud.fraunhofer.at/s/sY2mezd4NgRRoPM/download/USB-SGP2021.zip
paperURL: https://diglib.eg.org/handle/10.2312/2633079     

        affiliation: Università degli Studi di Cagliari   
      - name: Marco Livesu
        affiliation: IMATI
        

    teaser: /images/default_thumbnail.jpg

    abstract: Hexahedral meshes are a prominent volumetric mesh representation. They are largely used as computational domains for the resolution of partial differential equations for physically based simulation, making them a core ingredient of many software tools used by the automobile, naval, aerospace, medical, and geological industries, as well as for many applications in Computer Graphics and Animation. In academic research and industry, the algorithmic generation and processing of hexahedral meshes have been studied for more than 30 years now. In this course, we will introduce the topic of hexahedral meshes and focus on the most relevant techniques for hexahedral mesh generation in Computer Graphics. For each technique, we will highlight capabilities and limitations, also pointing out the associated unsolved challenges. The required background, pertaining to geometrical as well as combinatorial aspects, will be introduced along the way.
    
    
    
    
paperSessions: 
 - name: MODELING & MAPPING
    chair: ...
    teaser: /images/default_thumbnail.jpg
    papers:
      - title: "Harmonic Shape Interpolation on Multiply-connected Domains"
        authors:
          - name: Dongbo Shi
          - name: Renjie Chen
      - title: "Localized Shape Modelling with Global Coherence: An Inverse Spectral Approach"
        authors: 
          - name: Marco Pegoraro
          - name: Simone Melzi
          - name: Umberto Castellani, Riccardo Marin, Emanuele Rodola
          - name: Umberto Castellani
          - name: Riccardo Marin
          - name: Emanuele Rodola
      - title: "Non-Isometric Shape Matching via Functional Maps on Landmark-Adapted Bases (CGF)"
        authors: 
          - name: Mikhail Panine
          - name: Maxime Kirgo
          - name: Maks Ovsjanikov
          
  - name: CURVES & FEATURES
    chair: ...
    teaser: /images/default_thumbnail.jpg
    papers:
      - title: "Smooth Interpolating Curves with Local Control and Monotone Alternating Curvature"
        authors:
          - name: Alexandre Binninger
          - name: Olga Sorkine-Hornung
      - title: "b/Surf: Interactive Bézier Splines on Surface Meshes (TVCG)"
        authors:
          - name: Claudio Mancinelli
          - name: Giacomo Nazzaro   
          - name: Fabio Pellacini    
          - name: Enrico Puppo     
      - title: "SGLBP: Subgraph-based Local Binary Patterns for Feature Extraction on Point Clouds (CGF)"
        authors:
          - name: Bao Guo
          - name: Yuhe Zhang     
          - name: Jian Gao,  
          - name: Chunhui Li
          - name: Yao Hu   
 
  - name: LEARNING & CREATING
    chair: ...
    teaser: /images/default_thumbnail.jpg
    papers:
      - title: "PriFit: Learning to Fit Primitives Improves Few Shot Point Cloud Segmentation"
        authors:
          - name: Gopal Sharma
          - name: Bidya Dash
          - name: Aruni RoyChowdhury
          - name: Matheus Gadelha
          - name: Marios Loizou
          - name: Liangliang Cao
          - name: Rui Wang
          - name: Erik G. Learned-Miller
          - name: Subhransu Maji
          - name: Evangelos Kalogerakis
      - title: "SDF-StyleGAN: Implicit SDF-Based StyleGAN for 3D Shape Generation"
        authors:
          - name: Xinyang Zheng
          - name: Yang Liu
          - name: Pengshuai Wang
          - name: Tong Xin
      - title: "MendNet: Restoration of Fractured Shapes Using Learned Occupancy Functions"
        authors:
          - name: Nikolas Lamb
          - name: Sean Banerjee
          - name: Natasha Banerjee

  - name: MESHES & PARTITIONS
    chair: ...
    teaser: /images/default_thumbnail.jpg
    papers:
      - title: "Precise High-order Meshing of 2D Domains with Rational Bézier Curves"
        authors:
          - name: Jinlin Yang
          - name: Shibo Liu
          - name: Shuangming Chai
          - name: Ligang Liu
          - name: Xiao-Ming Fu
      - title: "Rational Bézier Guarding"
        authors:
          - name: Payam Khanteimouri
          - name: Manish Mandad
          - name: Marcel Campen
      - title: "Simplification of 2D Polygonal Partitions via Point-line Projective Duality, and Application to Urban Reconstruction (CGF)"
        authors:
          - name: Julien Vuillamy
          - name: Andre Lieutier    
          - name: Florent Lafarge   
          - name: Pierre Alliez
         
  - name: TOOLS & DATA
    chair: ...
    teaser: /images/default_thumbnail.jpg
    papers:
      - title: "Deterministic Linear Time for Maximal Poisson-Disk Sampling using Chocks without Rejection or Approximation"
        authors:
          - name: Scott Mitchell 
      - title: "TinyAD: Automatic Differentiation in Geometry Processing Made Simple"
        authors:
          - name: Patrick Schmidt
          - name: Janis Born
          - name: David Bommes 
          - name: Marcel Campen  
          - name: Leif Kobbelt
      - title: "Hex Me If You Can"
        authors:
          - name: Pierre-Alexandre Beaufort
          - name: Maxence Reberol
          - name: Denis Kalmykov
          - name: Heng Liu
          - name: Franck Ledoux
          - name: David Bommes 

  - name: TILING & NESTING
    chair: ...
    teaser: /images/default_thumbnail.jpg
    papers:
      - title: "Constructing L∞ Voronoi Diagrams in 2D and 3D"
        authors:
          - name: Dennis Bukenberger
          - name: Kevin Buchin
          - name: Mario Botsch
      - title: "Fabricable Multi-Scale Wang Tiles"
        authors:
          - name: Xiaokang Liu
          - name: Chenran Li
          - name: Lin Lu
          - name: Oliver Deussen
          - name: Changhe Tu 
      - title: "Topological Simplification of Nested Shapes"
        authors:
          - name: Dan Zeng
          - name: Erin Chambers 
          - name: David Letscher
          - name: Tao Ju
          
          
-->
