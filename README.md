# Awesome NGP
Collect various implementation of NGP




| Project            | PSNR  | Train Speed |
| ------------------ | ----- | ----------- |
| [Instant-ngp(paper)](#instant-ngp-original-project) | 36.39 (5 min) | -           |
| [JNeRF](#jnerf)             | 36.41 (5 min) | 133 iters/s |
| [torch-ngp](#torch-ngp)          | 35.52 | 50 iters/s  |
| [HashNeRF-pytorch](#hashnerf-pytorch) | - | - |



------




### Instant-ngp (Original project)

An implementation of four **neural graphics primitives**, being neural radiance fields (NeRF), signed distance functions (SDFs), neural images, and neural volumes. 

 [Instant Neural Graphics Primitives with a Multiresolution Hash Encoding](https://nvlabs.github.io/instant-ngp/assets/mueller2022instant.pdf), Thomas Müller , Alex Evans , Christoph Schied , Alexander Keller , **SIGGRAPH 2022**

[Project github](https://github.com/NVlabs/instant-ngp/)



------




### JNeRF

JNeRF is a NeRF benchmark based on Jittor. JNeRF supports Instant-NGP capable of training NeRF in 5 seconds and achieves similar performance and speed to the paper.

[Project github](https://github.com/Jittor/JNeRF)



------


### torch-ngp

A pytorch implementation of [instant-ngp](https://github.com/NVlabs/instant-ngp), as described in [*Instant Neural Graphics Primitives with a Multiresolution Hash Encoding*](https://nvlabs.github.io/instant-ngp/assets/mueller2022instant.pdf).

[Project github](https://github.com/ashawkey/torch-ngp)



------



### HashNeRF-pytorch

HashNeRF-pytorch is a **pure PyTorch** implementation of [Instant-NGP](https://github.com/NVlabs/instant-ngp).

[Project github](https://github.com/johnny-walker/HashNeRF)



------