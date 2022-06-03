# Awesome NGP
Collect various implementation of NGP

## Content
- [Awesome NGP](#awesome-ngp)
  - [Content](#content)
    - [Instant-ngp (Original project)](#instant-ngp-original-project)
    - [JNeRF](#jnerf)
    - [torch-ngp](#torch-ngp)
    - [Different Project Compare](#different-project-compare)



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

### Different Project Compare

| Project            | PSNR  |
| ------------------ | ----- |
| Instant-ngp(paper) | 36.39 |
| JNeRF              | 36.41 |
| torch-ngp          | 35.52 |



