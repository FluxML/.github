<p align="center">
    <img width="400px" src="https://raw.githubusercontent.com/FluxML/Flux.jl/master/docs/src/assets/logo.png"/>
</p>

Flux is a library for machine learning geared towards high-performance production pipelines. It comes "batteries-included" with many useful tools built in, but also lets you use the full power of the Julia language where you need it. We follow a few key principles:

* **Doing the obvious thing**. Flux has relatively few explicit APIs for features like regularisation or embeddings. Instead, writing down the mathematical form will work – and be fast.
* **Extensible by default**. Flux is written to be highly extensible and flexible while being performant. Extending Flux is as simple as using your own code as part of the model you want - it is all [high-level Julia code](https://github.com/FluxML/Flux.jl/blob/ec16a2c77dbf6ab8b92b0eecd11661be7a62feef/src/layers/recurrent.jl#L131). When in doubt, it’s well worth looking at [the source](https://github.com/FluxML/Flux.jl/). If you need something different, you can easily roll your own.
* **Performance is key**. Flux integrates with high-performance AD tools such as [Zygote.jl](https://github.com/FluxML/Zygote.jl) for generating fast code. Flux optimizes both CPU and GPU performance. Scaling workloads easily to multiple GPUs can be done with the help of Julia's [GPU tooling](https://github.com/JuliaGPU/CUDA.jl) and projects like [DaggerFlux.jl](https://github.com/DhairyaLGandhi/DaggerFlux.jl).
* **Play nicely with others**. Flux works well with Julia libraries from [data frames](https://github.com/JuliaComputing/JuliaDB.jl) and [images](https://github.com/JuliaImages/Images.jl) to [differential equation solvers](https://github.com/JuliaDiffEq/DifferentialEquations.jl), so you can easily build complex data processing pipelines that integrate Flux models. Have a look at [Flux' ecosystem](https://fluxml.ai/Flux.jl/dev/ecosystem/) to learn more about how Flux integrates with other Julia packages.

Check out [Flux's website](https://fluxml.ai) for more information on the FluxML stack!
