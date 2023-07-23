# Analysis-of-Duffing-Oscillators


## Introduction

In this paper, we analyze an oscillating system subject to a nonlinear restoring force, as modeled by the Duffing Equation: $$\ddot{x} + \beta\dot{x} + \delta x + \alpha x^3 = \gamma\cos\omega t$$
This equation models a non-linear, damped, driven harmonic oscillator. The equation received the name of its main investigator, the German engineer Georg Duffing. The parameters $\beta$, $\alpha$, $\delta$, and $\gamma$ dictate the damping, the non-linearity of the restorative force, the linearity of the restorative force, and the amplitude of the driving force respectively. To analyze this system, we must also scrutinize the Duffing Potential, the potential function of the nonlinear restorative force
### Dependencies
- `scipy.integrate.odeint`
- `scipy.interpolate.UnivariateSpline`
- `pyplot`


See Jupyter Notebook for numerical solver, time series, Poincaré sections, and phase spaces graphs. See PDF for summary of findings.

## License

This code is provided under the [MIT License](LICENSE). Feel free to use and modify it for your projects.

## Acknowledgments

Special thanks to the authors of the algorithms and the source papers for their contributions.

## Contact

For any questions or inquiries, please contact [tandetat@grinnell.edu](mailto:tandetat@grinnell.edu).
