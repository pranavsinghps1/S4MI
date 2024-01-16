# S4MI (Self-Supervision and Semi-Supervision for Medical Imaging)

Official PyTorch implementation of the following paper: [ Shifting to Machine Supervision: Annotation-Efficient Semi and Self-Supervised Learning for Automatic Medical Image Segmentation and Classification](https://arxiv.org/abs/2311.10319). arXiv 2023.

The S4MI (Self-Supervision and Semi-Supervision for Medical Imaging) pipeline aims at overcoming the limitations of traditional supervised learning. By utilizing self-supervised and semi-supervised learning techniques, S4MI significantly reduces the need for extensive annotated data, a process that is both costly and time-consuming. This innovative pipeline involves auxiliary tasks that don't require labeling, streamlining machine supervision and scaling more effectively than fully-supervised methods.

Our extensive research, benchmarking these techniques across three medical imaging datasets, highlights their impressive effectiveness in classification and segmentation tasks. Notably, self-supervised learning with just 10% of the annotation outperformed full annotation in most datasets' classification tasks. Similarly, we observed that semi-supervised approach excelled in segmentation, achieving better results than fully-supervised methods with half the labels across all datasets.

In our commitment to fostering scientific advancement, we are releasing the S4MI code to the public. This will facilitate broader application and continuous development of these cutting-edge methods in medical imaging. 

**For ease of use and replication, the code for reproducing classification tasks is organized in the 'classification' folder, while the code pertinent to segmentation is conveniently located in the 'segmentation' folder.**

Pranav Singh, Raviteja Chukkapalli, Shravan Chaudhari, Luoyao Chen, Mei Chen, Jinqian Pan, Craig Smuda and Jacopo Cirrone \
 New York University.
