# Semantic Segmentation with Domain Adaptation
Course project for CS236 at Stanford: Deep Generative Models. Accomplished by Zhanghao Sun, Qiwen Wang and Mi Yu.

In this project, we explore the domain adaptation problem in semantic segmentation. Semantic segmen- tation aims to assign each pixel a semantic label. Re- cently, CNN based models have achieved significant progress on this task. However, there’s a large domain gap between synthetic and real-world data. This im- pairs the practical application of models trained on large and cheap synthetic datasets.
We set up adversarial models for this task. Our contributions are in three folds:
+ Implemented several multi-layer fusion discriminator architectures.
+ Proposed and implemented a category-level discriminator. Explored its potential advantage in category clustering.
+ Implemented an ensemble model to achieve state-of-the-art performance on GTA5-Cityscape dataset adaptation.

For more details, please refer to the poster and the project report. Here is a qualitative comparison on several models:
![image]("result.png")
