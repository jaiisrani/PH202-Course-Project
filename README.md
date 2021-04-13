# PH202-Course-Project
## Topic: Photonic Bound States in a Continuum
#### [Research Paper to be Implemented](https://www.nature.com/articles/s42005-020-0353-z)

### Abstract
We develop some theory and reproduce some of the calculations and graphs presented in the research paper using python code. First, we deal with an electron toy-model and look at the bound states in the continuum for a one-dimensional quantum potential well. We then exploit the one-to-one correspondence between electronic spin and polarisation states of light and develop the theory corresponding to bound states in the continuum for a one-dimensional photonic system, which consists of one-dimensional photonic crystal conjugated with a liquid-crystalline defect layer and covered by metal film. We perform numerical calculations and plot graphs of physical quantities of interest for both these systems.

### Team
- Nabeel Ahmed (19B030016) 
- Harshit Agarwal (190260022)
- Kasi Reddy Sreeman Reddy (190070029) 
- Jai Anil Israni (190010033) 

### About 
This project was undertaken by undergraduate sophomore students at the Physics Department at IIT Bombay as part of the course PH 202: Waves, Oscillations and Optics, instructed by Prof. Anshuman Kumar. The work presented in this paper is far from original and is merely a reproduction of the work done in the original paper. The calculation parameters have been explicity mentioned in the code blocks and the values have been taken from the original research paper. In cases where the values were not clear in these references, the values we have used have been explicitly declared as variables in the code blocks. The graphs we produced using python may not match the ones present in the original paper due to more than one of the following reasons: 
- Python(especially on Google Colab) has a limited processing capability as opposed to other numerical analysis tools (MATLAB was used by the authors). 
- The granularity of data points supported on python is limited. 
- Certain systems of non-linear equations may not converge on python due to limited solving capability of the mpmath/scipy solvers, so we used finite data points with a certain degree of error(the value of which can be displayed in each code block by adding a few extra commands). 

For continuous graphs such as the Q-factor graph, we found finite data points and used a cubic spline to interpolate the function, which have resulted in deviations
However, as far as the qualitative physics of the problems is concerned, all graphs convey the requisite information as is desired.

#### A [1-hour video](https://drive.google.com/file/d/1xelr_Dhui74bdr6y2ZumN_ljLaLfT-7y/view?usp=sharing)  made by us, demonstrating our project. 
#### Project report of other teams can be found [here](https://github.com/loqm/PH202_2020/tree/main/Projects).
