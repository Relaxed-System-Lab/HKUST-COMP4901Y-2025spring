<div style="text-align:center">
<a href="https://hkust.edu.hk/"><img src="https://hkust.edu.hk/sites/default/files/images/UST_L3.svg" height="45"></a>


# COMP4901Y 2025 Spring

</div>

<h2 style="text-align: center;"> Large-Scale Machine Learning for Foundation Models </h2>

**Lecturer**: [Binhang Yuan](https://binhangyuan.github.io/site/). 

**Teaching Assistant**: You Peng, Yukun Zhou, Yuxuan Li.


## Overview

In recent years, foundation models have fundamentally revolutionized the state-of-the-art of artificial intelligence. Thus, the computation in the training or inference of the foundation model could be one of the most important workflows running on top of modern computer systems. This course unravels the secrets of the efficient deployment of such workflows from the system perspective. Specifically, we will i) explain how a modern machine learning system (i.e., PyTorch) works; ii) understand the performance bottleneck of machine learning computation over modern hardware (e.g., Nvidia GPUs); iii) discuss four main parallel strategies in foundation model training (data-, pipeline-, tensor model-, optimizer- parallelism); and iv) real-world deployment of foundation model including efficient inference and fine-tuning. 




## Syllabus 

| Date | Topic |
|-----|------|
|W1-02/04,02/06 | - Introduction and Logistics [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%201%20-%20Introduction%20and%20Logistics.pdf) <br> - ML Preliminary [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%202%20-%20Machine%20Learning%20Preliminary.pdf) [[Notebook]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/lecture-notebook/Lecture-2.ipynb) |
|W2-02/11,02/13 | - Stochastic Gradient Descent [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%203%20-%20Stochastic%20Gradient%20Descent.pdf) [[Notebook]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/lecture-notebook/Lecture-3.ipynb) <br> - Automatic Differentiation [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%204%20-%20Automatic%20Differentiation.pdf) [[Notebook]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/lecture-notebook/Lecture-4.ipynb) |
|W3-02/18,02/20 | - Language Model Architecture [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%205%20-%20Language%20Model%20Architecture.pdf) <br> - Large Scale Pretrain Overview [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%206%20-%20LLM%20Pretraining.pdf) |
|W4-02/25,02/27 | - Nvidia GPU Performance [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%207%20-%20Nvidia%20GPU%20Performance.pdf)  <br> - Collective Communication Library [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%208%20-%20Nvidia%20Collective%20Communication%20Library.pdf)  |
|W5-03/04,03/06 | - Data-, Pipeline- Parallel Training [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%209%20-%20Data%20and%20Pipeline%20Parallel%20Training.pdf) <br> - Tensor Model-, Optimizer- Parallel Training [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%2010%20-%20Tensor%20Model%20and%20Optimizer%20Parallel%20Training.pdf) |
|W6-03/11,03/13 | - Sequence-, MoE- parallelism [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%2011%20-%20MoE%20and%20Sequence%20Parallelism.pdf) <br> - Mid-Term Review [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%2012%20-%20Midterm%20Review.pdf) |
|W7-03/18,03/20 | - Mid-Term Exam :heavy_check_mark: <br> - Generative Inference [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%2013%20-%20Generative%20Inference%20Overview.pdf)  [[Notebook]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/lecture-notebook/Lecture-13.ipynb)  |
|W8–03/25,03/27 | - Inference Alogirhtm Optimizations [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%2014%20-%20Generative%20Inference%20Algorithm%20Optimization.pdf) <br> - Inference System Optimizations [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%2015%20-%20Generative%20Inference%20System%20Optimization.pdf) |
|W9-04/01,04/03 | - Spring Break |
|W10-04/08,04/10 | - Prompt Engineering [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%2016%20-%20Prompt%20Engineering.pdf) <br> - Inference Scaling [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%2017%20-%20%20Inference%20Time%20Scaling.pdf) |
|W11-04/15,04/17 | - Retrieval Augmented Generation [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%2018%20-%20Retrieval%20Augmented%20Generation.pdf)  <br>  - LLM Agent [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%2019%20-%20LLM%20Agent.pdf)  |
|W12-04/22,04/24 | - Parameter Efficient Fine-Tuning [[Slides]](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/blob/main/Lecture%2020%20-%20Parameter%20Efficient%20Finetuning.pdf) <br> - RL Alignment |
|W13-04/29       | - LLM Evaluation  |
|W14-05/06,05/08 | - Guest Speech <br> - Final Review|


## Grading Policy
- 4 Homework (4 $\times$ 5% $=$ 20%);
- Mid-term exam (30%);
- Final exam (50%).

## Homework 
| Topic | Release |   Due   |
|-------|---------|---------|
| [Homework1](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/tree/main/homework1) |2025/02/13 :heavy_check_mark: | 2025/02/22 :heavy_check_mark:|
| [Homework2](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/tree/main/homework2) |2025/03/04 :heavy_check_mark: | 2025/03/12 :heavy_check_mark: |
| [Homework3](https://github.com/Relaxed-System-Lab/HKUST-COMP4901Y-2025spring/tree/main/homework3) |2025/03/25 :heavy_check_mark: | 2025/04/10 :heavy_check_mark:|
| Homework4 |2025/04/22 | 2025/05/06 |




