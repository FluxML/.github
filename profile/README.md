<p align="center">
    <img width="400px" src="https://raw.githubusercontent.com/FluxML/Flux.jl/master/docs/src/assets/logo.png"/>
</p>

# The Elegant Machine Learning Stack

Flux is a 100% pure-Julia stack and provides lightweight abstractions on top of Julia's native GPU and AD support. It makes the easy things easy while remaining fully hackable.

## Features

Flux has features that sets it apart among ML systems.

### Compiled Eager Code
Flux provides a single, intuitive way to define models, just like mathematical notation. Julia transparently [compiles your code](https://julialang.org/blog/2018/12/ml-language-compiler), optimizing kernels for the GPU, for the best performance.

### Differentiable Programming
Existing Julia libraries are differentiable and can be incorporated directly into Flux models. Cutting edge models such as [Universal Neural Differential Equations](https://github.com/SciML/DiffEqFlux.jl) are first class, and [Zygote](https://github.com/FluxML/Zygote.jl) enables overhead-free gradients.

### First-class GPU support
GPU kernels can be written directly in Julia via [CUDA.jl](https://github.com/JuliaGPU/CUDA.jl). Flux is uniquely hackable and any part can be tweaked, from GPU code to custom gradients and layers.

### Model Ecosystem
[Model-zoo](https://github.com/FluxML/model-zoo) is a collection of demonstrations of the Flux machine learning library. Any of these may freely be used as a starting point for your own models. [Metalhead](https://github.com/FluxML/Metalhead.jl) and [Flux3D](https://github.com/FluxML/Flux3D.jl) provide trained vision-based and 3D vision-based Flux models, respectively. Furthermore, [Transformers](https://github.com/chengchingwen/Transformers.jl) provides transformer-based Flux models written in 100% Julia!

---

Check out [Flux's website](https://fluxml.ai) for more information on the FluxML stack!
