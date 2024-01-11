# Luke Lozenski

<img width="468" alt="round_headshots" src="https://user-images.githubusercontent.com/31415312/184555797-e85f70fd-3b75-47bc-91f9-a87d695f79b3.png">



I'm currently a fourth year Ph.D. candidate at Washington University in St. Louis. My thesis topic is about improving dynamic and multispectral photoacoustic and ultrasound computed tomography through the development of large-scale computational imaging methods. My research includes the development of scientific machine learning frameworks, such as neural fields and CNNs, for solving inverse problems. I also have a broader interest in infinite-dimensional/functional optmization, including those with PDE constraints, and am open to a very wide range of research topics.

[Link to my CV](https://github.com/ljlozenski/LozenskiResearch/Lozenski_CV.pdf)


## Biography

I was from Leavenworth, Kansas. In 2020, I graduated from Washington University in St. Louis where I majored in Systems Engineering, with a second major in applied mathematics and a minor in electrical engineering. Alongside my Bachelors degree, I also graduated with my Masters degree in Systems Engineering. 

In the fall of 2020, I began my Ph.D. program at Washington University, where I am studying under Dr. Umberto Villa (currently at the Oden Institute, University of Texas at Austin). I expect to complete my degree in May 2025. My resesearch focuses on developing solution methods for image reconstruction and inverse problems formulated in the infinite-dimensional domain. My work in this research area has included developing an ADMM solution method for inverse problems governed by multiple PDE forward models, Bayesian estimation of tumor growth, utilizing neural fields for high-resolution 5D image reconstruciton, and machine learning methods for accelerated reconstruction in ultrasound computed tomography.

In the summer of 2022 I received the Los Alamos Applied Machine Learning Summer Reserach Fellowship. During this Fellowship I worked under the mentorship of Youzuo Lin, Hanchen Wang, and Brendt Wohlberg at Los Alamos National Laboratory on developing convolutional neural networks for real-time USCT imaging using full waveform inversion.

I returned to Los Alamos the following summer in 2023 for a second internship, were I again worked with Youzuo Lin, Hanchen Wang, and Brendt Wohlberg. During this internship I worked on developing learned measurement correction methods to enable high resoltuion image reconstruction utilizing approximated physical models. 

## Repositories 
https://github.com/precise-lab/nf_crt_dynamic_imaging

## Publications
* L. Lozenski, R. Cam, M. Anastasio, U. Villa, “ProxNF: Neural Field Proximal Training for High-Resolution 4D Dynamic Image Reconstruction” (In preparation)
* L. Lozenski, H. Wang, F. Li, M. Anastasio, B. Wohlberg, Y.Lin, U. Villa “Learned Full Waveform Inversion Incorporating Task Information  for Ultrasound Computed Tomography” IEEE Transactions on Computational Imaging (2024)
* L. Lozenski, H. Wang, B. Wohlberg, U. Villa, Y. Lin,“Data-Driven Methods for Ultrasound Computed Tomography” Medical Imaging 2023: Physics of Medical Imaging. Vol 12463. SPIE, 2023.
* B. Liang, J. Tan, L. Lozenski, D. Hormuth, T. Yankeelov, U. Villa, D. Faghihi “Bayesian Inference of Tissue Heterogeneity for Prediction of Glioma Growth”  IEEE Transactions on Medical Imaging (2023)
* L. Lozenski, M. Anastasio, U. Villa, “A Memory-Efficient Self-Supervised Dynamic Image Reconstruction Method using Neural Fields” IEEE Transactions on Computational Imaging (2022)
* L. Lozenski, M. Anastasio, U.Villa, “Neural Fields for Dynamic Imaging” Medical Imaging 2022: Physics of Medical Imaging. Vol. 12031. SPIE, 2022.
* L. Lozenski, U. Villa, “Consensus ADMM for inverse problems governed by multiple PDE Models”, ArXiv Preprint arXiv:2104.13899 (2021) 
* M. Watanabe, and L. Lozenski, "Thermodynamics study of absorption of aromatic organic compounds to carbon nanotubes." Abstracts of Papers of the American Chemical Society. Vol. 251. 1155 


## Research Topics

* Learned Measurement Correction for Simplified Acoustic Forward Models in USCT 	    	      June 2023-
   * Work done during summer internship at Los Alamos National Laboratory under supervision of Youzuo Lin 
   * Development of convolutional neural network for model correction from accurate USCT data for inversion using a simplified physical model. 
   * Combines state of the art machine learning approaches with traditional model guided reconstruction methods
* Proximal Splitting Methods for Neural Field Based Dynamic-Image Reconstruction		 March 2022-
   * Development of scalable, memory-efficient dynamic image reconstruction algorithms using neural fields to represent 5D images
   * Application to photoacoustic dynamic imaging (circular Radon transform)
   * Implementation of algorithm in PyTorch and comparison with compressed sensing (low-rank based dynamic image reconstruction algorithms)
* Learned Full Waveform Inversion Incorporating Task Information  for USCT		June 2022-August 2023
   * Applied Machine Learning Fellowship at Los Alamos National Laboratory under supervision of Youzuo Lin
   * Development of convolutional neural network for data driven solutions to USCT inverse problems
   * Machine learning framework using PyTorch on GPU and HPC clusters
* Neural Field for Dynamic Imaging					 	     March 2021-September 2022
   * Development of scalable, memory-efficient dynamic image reconstruction algorithms using neural fields
   * Application to photoacoustic dynamic imaging (circular Radon transform)
   * Implementation of algorithm in PyTorch and comparison with compressed sensing (low-rank based dynamic image reconstruction algorithms)
* Inversion Algorithms for Photoacoustic Tomography Applications in Biological Tissue	June 2019-
   * Development of techniques for image reconstruction of biological tissue optical absorption properties
   * Python implementation utilizing Fenics and hiPPylib for solving inverse problems
   * Collaboration with Dr. Mark Anastasio at University of Illinois at Urbana-Champaign
* Consensus ADMM for Inverse Problems Governed by Multiple PDE Forward Models  May 2020-August 2021
   * Solution methods for inverse problems with multiple PDE forward models and nonsmooth regularization
   * Implemented the alternating direction method of multipliers (ADMM) with demonstrated scalability with respect to problem size and number of PDE forward models
* Bayesian Inference of Tissue Heterogeneity for  Glioma Growth			May 2020-April 2023 
   * Investigation on modeling tumor growth under the effects of radiotherapy as a time-dependent PDE 
   * Collaboration with Dr. Danial Faghihi at the University at Buffalo.  


### Additional Researh Topics

Exploring Deep Galerkin Methods: 						     August 2021-December 2021
* Group collaboration associated with graduate optimization course
* Implemented physics informed neural network to solve PDEs in high dimensions
* Compared scalability and accuracy to traditional Galerkin methods 

Scalable Transfer Operators							      August 2021-December 2021
* Independent study on the scalability of numerical approximation of transfer operators
* Developed a framework for propagating infinite dimensional probability distributions based on flow models

Signal Based Occupancy Detection with Application to Automobile Safety, 	      August 2019-May 2020
* Designed a system capable of detecting the entire range of breathing and small enough to be placed in a wide variety of settings, including inside of a car to detect if children were left inside
* Senior Capstone Group Project mentored Dr. Neal Patwari (ESE, WashU)



## Teaching Experience 
* Assistant Instructor– E35 ESE Optimization (Dr. Tunay) 	 	      	      	      August 2023-December 2024
* Assistant Instructor– E35 ESE Large-Scale Optimization (Dr. Kamilov) 	 	      	      August 2023-December 2024
* Assistant Instructor– E35 ESE 5931Mathematics of Imaging Science (Dr. Jha) 	 	      August 2022-December 2022
* Assistant Instructor– E35 ESE 524 Detection and Estimation Theory (Dr. Nehorai)		 	  January 2022-May 2022	
* Assistant Instructor– E35 ESE 520 Probability and Stochastic Processes (Dr. Kurenok) 		  January 2021-May 2021 
* Grader– L24 Math 5045 Algebraic Topology,  L24 Math 430 Abstract Algebra, E35 ESE 105 Introduction to Electrical and Systems Engineering, L24 Math 4111 Introduction to Analysis, E35 ESE 326 Probability and Statistics

## Proffesional Memberships
* IEEE. (since 2021)
* SIAM. (since 2021)
* SPIE.   (since 2021)

  
## References
* Dr. Umberto Villa, Research Scientist Oden Institute for Computational Engineering and Sciences, University of Texas at Austin uvilla@oden.utexas.edu Ph.D. advisor
* Dr. Youzuo Lin, Scientist, Team Leader Geophysics Group, Los Alamos National Laboratory ylin@lanl.gov Internship Advisor




 



