# Analysis-of-Duffing-Oscillators


## Introduction

In this paper, we analyze an oscillating system subject to a nonlinear restoring force, as modeled by the Duffing Equation: $$\ddot{x} + \beta\dot{x} + \delta x + \alpha x^3 = \gamma\cos\omega t$$
This equation models a non-linear, damped, driven harmonic oscillator. The equation received the name of its main investigator, the German engineer Georg Duffing. The parameters $\beta$, $\alpha$, $\delta$, and $\gamma$ dictate the damping, the non-linearity of the restorative force, the linearity of the restorative force, and the amplitude of the driving force respectively. To analyze this system, we must also scrutinize the Duffing Potential, the potential function of the nonlinear restorative force
### Dependencies

### LaTeX Definitions and Commands

The code includes various LaTeX definitions and commands for convenience. These include custom math symbols, matrices, vectors, theorem styles, examples, and exercises.

## Algorithms

### Iterative Hard Thresholding (IHT)

IHT is an iterative algorithm used for compressed sensing. It aims to reconstruct sparse vectors from underdetermined measurements. The main function `IHT` takes an input matrix `A`, measurements `y`, sparsity level `k`, and an error tolerance `tol`. The output is a `k`-sparse approximation `x_hat` of the target signal `x`. The algorithm continues until the residual norm is less than the specified tolerance.

### Normalized Iterative Hard Thresholding (NIHT)

NIHT is an improved version of IHT. It also aims to reconstruct sparse vectors from underdetermined measurements. The main function `NIHT` takes similar inputs to IHT, but it employs normalized steps for better stability. The algorithm continues until the residual norm is less than the specified tolerance.

## Main Result

The main theorem proves the convergence of the NIHT algorithm. It states that under certain conditions on the asymmetric restricted isometry constants of the matrix `A`, the NIHT algorithm converges to the original sparse vector `x`. The theorem also provides an upper bound on the reconstruction error.

## License

This code is provided under the [MIT License](LICENSE). Feel free to use and modify it for your projects.

## Acknowledgments

Special thanks to the authors of the algorithms and the source papers for their contributions.

## Contact

For any questions or inquiries, please contact [tandetat@grinnell.edu](mailto:tandetat@grinnell.edu).
