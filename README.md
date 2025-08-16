# PhysFMP  

This repository is dedicated to the development of a **physics-informed Flow-Matching policy**. Flow-Matching generative models are naturally compatible with physics-informed machine learning, as both are fundamentally connected to the formulation and solution of partial differential equations (PDEs).  

Recently, several works have highlighted the potential of integrating physical constraints into Flow-Matching models, such as:  

1)  [Physics-Constrained Flow Matching: Sampling Generative Models with Hard Constraints](https://arxiv.org/pdf/2506.04171v1)
2)  [Flow Matching Meets PDEs: A Unified Framework for Physics-Constrained Generation](https://arxiv.org/pdf/2506.08604v1)  

While these studies provide strong theoretical foundations, they have not yet extended their approaches to **robotics and policy learing**. This extension is crucial, since deploying imitation learning frameworks in real-world robotic systems requires explicit incorporation of physical constraints to ensure safe and reliable interaction.  

In robotics, safety is often enforced through mechanisms such as **tactile sensing** and **impedance control**, which prevent aggressive or unsafe robot responses when physical limits are exceeded.  

Building on this idea, our work proposes a framework that integrates **impedance control** directly into the Flow-Matching policy by leveraging physics-informed principles introduces by 1) and 2). This integration enables robots to perform sophisticated tasks such as sorting and pick-and-place of cluttered objects of varying shapes and materials while maintaining compliance and safety in human-centered environments.  

