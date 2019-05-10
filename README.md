# Enabling Large Intelligent Surfaces with Compressive Sensing and Deep Learning
Simulation code for "Enabling Large Intelligent Surfaces with Compressive Sensing and Deep Learning" by Abdelrahman Taha, Muhammad Alrabeiah, Ahmed Alkhateeb, arXiv e-prints, p. arXiv:1904.10136, Apr 2019.
# Abstract of the Article
Employing large intelligent surfaces (LISs) is a promising solution for improving the coverage and rate of future wireless systems. These surfaces comprise a massive number of nearly-passive elements that interact with the incident signals, for example by reflecting them, in a smart way that improves the wireless system performance. Prior work focused on the design of the LIS reflection matrices assuming full knowledge of the channels. Estimating these channels at the LIS, however, is a key challenging problem, and is associated with large training overhead given the massive number of LIS elements. This paper proposes efficient solutions for these problems by leveraging tools from compressive sensing and deep learning. First, a novel LIS architecture based on sparse channel sensors is proposed. In this architecture, all the LIS elements are passive except for a few elements that are active (connected to the baseband of the LIS controller). We then develop two solutions that design the LIS reflection matrices with negligible training overhead. In the first approach, we leverage compressive sensing tools to construct the channels at all the LIS elements from the channels seen only at the active elements. These full channels can then be used to design the LIS reflection matrices with no training overhead. In the second approach, we develop a deep learning based solution where the LIS learns how to optimally interact with the incident signal given the channels at the active elements, which represent the current state of the environment and transmitter/receiver locations. We show that the achievable rates of the proposed compressive sensing and deep learning solutions approach the upper bound, that assumes perfect channel knowledge, with negligible training overhead and with less than 1% of the elements being active.
# Code Package Content
This code package reproduces the results in the original article: Abdelrahman Taha, Muhammad Alrabeiah, and Ahmed Alkhateeb, “Enabling Large Intelligent Surfaces with Compressive Sensing and Deep Learning,” arXiv e-prints, p. arXiv:1904.10136, Apr 2019. [Online]. Available: https://arxiv.org/abs/1904.10136
# License and Referencing
This code package is licensed under the GPLv3 license. If you in any way use this code for research that results in publications, please cite our original article listed below.

@ARTICLE{2019arXiv190410136T,
       author = {{Taha}, Abdelrahman and {Alrabeiah}, Muhammad and {Alkhateeb}, Ahmed},
        title = "{Enabling Large Intelligent Surfaces with Compressive Sensing and Deep Learning}",
      journal = {arXiv e-prints},
     keywords = {Computer Science - Information Theory, Electrical Engineering and Systems Science - Signal Processing},
         year = "2019",
        month = "Apr",
          eid = {arXiv:1904.10136},
        pages = {arXiv:1904.10136},
archivePrefix = {arXiv},
       eprint = {1904.10136},
 primaryClass = {cs.IT},
       adsurl = {https://ui.adsabs.harvard.edu/abs/2019arXiv190410136T},
      adsnote = {Provided by the SAO/NASA Astrophysics Data System}
}
