# Federated-Deep-Unrolling-Lidar-Super-resolution-SLAM
In this paper, we propose a novel  federated deep unrolling method for increasing the accuracy of the Lidar Super resolution. The proposed framework not only offers notable improvements in Lidar-based SLAM methodologies but also  provides a solution to the  significant cost associated with high-resolution Lidar sensors. Particularly, our method can be adopted by a number of vehicles coordinated with a server towards learning a regularizer - a neural network - for capturing the dependencies of the Lidar data.
To tackle this adaptive federated optimization problem effectively, we initially propose  a deep unrolling framework, converting our solution into a well-justified deep learning architecture. The learnable parameters of this architecture are directly derived from the solution of the proposed optimization problem, thus resulting in an explainable architecture. Further, we extend the capabilities of our deep unrolling technique by incorporating a federated learning strategy. Our federated deep unrolling  model employs an innovative Adapt-then-Combine strategy, where each vehicle optimizes its model and, subsequently, their learnable regularizers are combined to formulate a robust global regularizer, equipped to handle diverse environmental conditions.
Through extensive numerical evaluations on real-world Lidar based SLAM applications, our proposed model demonstrates superior performance along with a significant reduction in trainable parameters, with $99.75\%$ fewer parameters compared to state of the art lidar super-resolution deep neural networks. Essentially, this study is the first initiative to combine deep unrolling with federated learning, showcasing an efficient, and data-secure approach to automotive Lidar super-resolution SLAM applications.

## Dependencies

The following Python libraries are required to run this project:
- numpy
- pytorch
- sklearn
- tenseal


## Data

The data used in this work is derived from the [Lidar Super Resolution](https://github.com/RobustFieldAutonomyLab/lidar_super_resolution/tree/master) repository on GitHub.

To download the training and testing datasets used in this work, please visit the following link: [Data Folder](https://drive.google.com/drive/folders/1pxaBZxTdlMhJV8-4xROnjeldxzYjO4Gz?usp=drive_link)
