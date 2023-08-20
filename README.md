# PSCC2024_algo
Detailed algorithm Practical Optimal Placement of Measurement Devices in Electrical Distribution Systems with Active Network Management Considerations


**Common parameters for the different scenarios**

The initial candidate solution population consists of $|POP_{0}| =c_{d}=10$ solution candidates $\in \Omega$ which are $10$ possible emplacements for the measurement devices in the measurement set. 

Regarding the values of the random distortion vector $\Upsilon_t$, we use a normal distribution and, for the standard deviation $\sigma_k$, the business rules of ORES, the Walloon DSO. These are 1) for voltage angle $0.003°$ and 2) for voltage, active and reactive power measures $0.006$ kV, kW, and KVar respectively.

For the value of the random distortion vector $\tau_t$ used for the forecast, we use also a normal distribution with a standard deviation equal to $0.03$ as ORES,  observed that $95\%$ of its own forecast is in the range of $+/-10$%. The number of simulation runs of measurements $\zeta$ is fixed at $10$.

For the sake of simplicity without loss of generality, as the set of measurement devices is fixed, we consider that there is no difference in the cost for the placement of the measurement devices. Therefore, the vector $c$ in Eq.6  is put at zero and $f_b$ is equal to $1$ while the terms of Eq.[6] are:

    \item $\alpha$ = \EUR{500}
    \item $\beta$= \EUR{500}
    \item $\gamma$= \EUR{1000}
    \item $\eta$= 127.61\EUR{/MWh}

**Illustration of the load pattern for scenarios A and B**
The illustrated load curve show the exchange of power at the slackbus
![loadprofile(3)](https://github.com/VangulickD/PSCC2024_algo/assets/35199822/749fc807-ec05-484e-91a7-fc65a3c73dc0)

![loadprofile(3b)](https://github.com/VangulickD/PSCC2024_algo/assets/35199822/9c91be1c-2317-47ae-9767-8eeb0ac0d3ab)
