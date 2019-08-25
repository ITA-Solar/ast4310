# Exercises 3


## Astropy units


- Create a function to evaluate the Planck function for wavelength, $B_\lambda(T)$, using `astropy.constants`:

\begin{equation}
B_\lambda(T)= \frac{2hc^2}{\lambda^5}\frac{1}{\mathrm{e}^{hc/\lambda k_b T} - 1}
\end{equation}

- Make a plot of $B_\lambda$ for T=2000 K and wavelengths between $0 < \lambda < 1500$ nm. Evaluate the function for $\lambda = 1$ cm. Use $k_b$ in CGS and note any differences.

- Consider an atom with three levels. The level energies in wavenumber (in cm$^{-1}$) are: `[0.0, 82258.211, 97491.219]`. Calculate the wavelengths (in nm) of the transition from the ground state to the first excited state, and from the first to the second excited state. What are the level energies in eV and aJ?
    

