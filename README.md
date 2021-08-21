# NeuralOperators

## Source code status

| **Documentation** | **Build Status** |
|:-----------------:|:----------------:|
| [![doc dev badge]][doc dev link] | [![ci badge]][ci link] [![codecov badge]][codecov link] |

[doc dev badge]: https://img.shields.io/badge/docs-dev-blue.svg
[doc dev link]: https://foldfelis.github.io/NeuralOperators.jl//dev

[ci badge]: https://github.com/foldfelis/NeuralOperators.jl/actions/workflows/CI.yml/badge.svg
[ci link]: https://github.com/foldfelis/NeuralOperators.jl/actions/workflows/CI.yml
[codecov badge]: https://codecov.io/gh/foldfelis/NeuralOperators.jl/branch/master/graph/badge.svg?token=JQH3MP1Y9R
[codecov link]: https://codecov.io/gh/foldfelis/NeuralOperators.jl

[Neural Operator](https://github.com/zongyi-li/graph-pde) is a novel deep learning method to learned the mapping
between infinite-dimensional spaces of functions introduced by [Zongyi Li](https://github.com/zongyi-li) et al.

In this project I temporarily provide the SpectralConv layer and the
[Fourier Neural Operator](https://github.com/zongyi-li/fourier_neural_operator).
For more information, please take a look at the
[Fourier Neural Operator model](src/model.jl) and the [example](example/burgers.jl) of solving
[Burgers' equation](https://www.wikiwand.com/en/Burgers%27_equation)
