# Federated-Deep-Unrolling-Lidar-Super-resolution-SLAM
In this paper, we propose a novel adaptive federated optimization approach to enhance automotive Lidar super-resolution for improving the efficiency of simultaneous localization and mapping (SLAM) applications, addressing the significant cost associated with high-resolution Lidar sensors. In further detail, our method can be adopted by a number of vehicles coordinated with a central server towards learning a regularizer - essentially a neural network - for capturing the intricate features and attributes of the Lidar data.
To tackle this adaptive federated optimization problem effectively, we initially propose  a deep unrolling framework, converting our solution into a well-justified deep learning architecture. The learnable parameters of this architecture are directly derived from the solution of the proposed optimization problem. Further, we extend the capabilities of our deep unrolling technique by incorporating a federated learning strategy. Our federated deep unrolling  model employs an innovative Adapt-then-Combine strategy

## Dependencies

The following Python libraries are required to run this project:
- numpy
- pytorch
- sklearn
- tenseal
