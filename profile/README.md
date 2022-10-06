<p align="center">
    <img width="400px" src="https://raw.githubusercontent.com/FluxML/Flux.jl/master/docs/src/assets/logo.png"/>
</p>

# The Elegant Machine Learning Stack

Flux is a 100% pure-Julia stack and provides lightweight abstractions on top of Julia's native GPU and AD support. It makes the easy things easy while remaining fully hackable.

## Features

Flux has features that sets it apart among ML systems

### Compiled Eager Code
Flux provides a single, intuitive way to define models, just like mathematical notation. Julia transparently [compiles your code](https://julialang.org/blog/2018/12/ml-language-compiler), optimising and fusing kernels for the GPU, for the best performance.

### Differentiable Programming
Existing Julia libraries are differentiable and can be incorporated directly into Flux models. Cutting edge models such as [Neural ODEs](https://julialang.org/blog/2019/01/fluxdiffeq) are first class, and [Zygote](https://github.com/FluxML/Zygote.jl) enables overhead-free gradients.

### First-class GPU support
GPU kernels can be written directly in Julia via [CUDA.jl](https://github.com/JuliaGPU/CUDA.jl). Flux is uniquely hackable and any part can be tweaked, from GPU code to custom gradients and layers.

### The Model Zoo
A [rich collection](https://github.com/FluxML/model-zoo) of Flux scripts to learn from, or tweak to your own data. Trained Flux models can be used from [TextAnalysis](https://github.com/JuliaText/TextAnalysis.jl) or [Metalhead](https://github.com/FluxML/Metalhead.jl).

### TPUs & Colab
Flux models can be [compiled to TPUs](https://github.com/JuliaTPU/XLA.jl) for cloud supercomputing, and run from Google Colab notebooks.

---

Check out [Flux's website](https://fluxml.ai) for more information on the FluxML stack!
