## Critical Equations & Formulas for Noise Types in a Dilution Refrigerator

| **Noise Type**              | **Equation**                                                                                   | **Description**                                                                 |
|-----------------------------|-----------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|
| **Thermal Noise**           | \(P_{\text{thermal}} = k_B T\)                                                                | Thermal energy per mode due to temperature.                                     |
|                             | \(k_B T \ll \hbar \omega\)                                                                    | Mitigation condition: Thermal noise is negligible below the energy splitting.   |
| **Phonon Noise**            | \(n_{\text{phonon}} = \frac{1}{e^{\hbar \omega / k_B T} - 1}\)                                | Average number of thermal phonons.                                             |
|                             | \(n_{\text{phonon}} \to 0\) at low \(T\)                                                     | Mitigation condition: Phonon noise is suppressed as temperature decreases.      |
| **Resistive Noise**         | \(S_V = 4 k_B T R\)                                                                           | Voltage noise power spectral density due to resistance.                        |
|                             | \(R = 0\) (superconductors) \(\Rightarrow S_V = 0\)                                           | Mitigation condition: Resistive noise is eliminated in superconducting states.  |
| **Blackbody Radiation**     | \(I(\nu, T) = \frac{2 h \nu^3}{c^2} \frac{1}{e^{h \nu / k_B T} - 1}\)                         | Spectral radiance of blackbody radiation.                                       |
|                             | \(I(\nu, T) \to 0\) at low \(T\)                                                             | Mitigation condition: Blackbody radiation intensity is suppressed at low \(T\). |
| **Magnetic Noise**          | \(M_T \propto \sqrt{k_B T}\)                                                                 | Thermal magnetization fluctuation.                                             |
|                             | \(M_T \to 0\) at low \(T\)                                                                   | Mitigation condition: Magnetic noise is minimized by reducing temperature.      |
| **Quasiparticle Noise**     | \(n_{\text{qp}} \propto e^{-\Delta / k_B T}\)                                                | Quasiparticle density decreases exponentially with lower temperature.           |
|                             | \(n_{\text{qp}} \to 0\) at low \(T\)                                                         | Mitigation condition: Quasiparticles are suppressed at ultra-low temperatures.  |
| **Vibration-Induced Noise** | \(F = m a\)                                                                                  | Force due to mechanical vibrations.                                            |
|                             | Vibration isolation minimizes \(a\)                                                         | Mitigation strategy: Reduces mechanical noise effects.                          |
| **Residual Gas Noise**      | \(\lambda = \frac{k_B T}{\sqrt{2} \pi d^2 P}\)                                               | Mean free path of gas molecules.                                               |
|                             | \(P \to 0\) at low \(T\)                                                                     | Mitigation condition: Residual gas noise is eliminated as pressure drops.       |
