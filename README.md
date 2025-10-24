# The chemodynamical memory of a major merger in a NIHAO-UHD Milky Way analogue II: Were Splash stars heated or already born hot?

## Authors

Sven Buder (ANU Canberra, sven.buder@anu.edu.au), Tobias Buck (IWR Heidelberg), Ása Skúladóttir (University Florence), Melissa Ness (ANU Canberra), Madeleine McKenzie (Carnegie Observatories Pasadena), and Stephanie Monty (IoA Cambridge)

## Abstract

One of the most debated consequences of the Milky Way's last major merger is the so-called \textit{Splash}: stars with disc-like chemistry but halo-like kinematics, often interpreted as evidence for the violent heating of an early protodisc. Using the same high-resolution NIHAO-UHD cosmological simulation analysed in Buder et al. (2025b, hereafter Paper I), we test whether, and if so how, a Splash-like population arises in the Milky Way analogue. By tracing stellar birth positions, ages, and present-day orbits, we find that protodisc stars were already born on dynamically hot orbits, with no evidence for significant additional dynamical \textit{splashing} of these particular in-situ stars despite a 1:5 stellar mass merger. The observed Splash may therefore reflect the already turbulent early disc, subsequently intermixed with accreted stars and those formed from merger-driven gas inflows, rather than a distinct merger-heated population. When selecting stars with similar chemistry and age as the Splash-like ones, we find their azimuthal velocity distribution to be broad and positively skewed, with $V_\varphi = 73_{-59}^{+74}\,\mathrm{km\,s^{-1}}$. The transition to a rotation-supported disc with large azimuthal velocities occurs only during or after the merger. Our results suggest an alternative to the proposed splashing scenario and highlight the need to disentangle the relative contributions of merger-induced heating and intrinsically hot disc formation to clarify the nature of Splash-like stars and their role in shaping the early Milky Way.

## Main Figures

<p align=center>
    <img src="https://github.com/svenbuder/golden_thread_II/blob/main/figures/splash_feh_vphi.png" alt="Iron abundance [Fe/H] vs. azimuthal velocity $V_\varphi$ for stars within $R_\mathrm{3D} < 50\mathrm{kpc}$ (left panels) and the Solar-like locus (right panels)" width="50%"/>
</p>

Figure: Iron abundance [Fe/H] vs. azimuthal velocity $V_\varphi$ for stars within $R_\mathrm{3D} < 50\,\mathrm{kpc}$ (left panels) and the Solar-like locus (right panels). Panels a) and b) show the density distribution, when normalising the density across each row, as done by Belokurov et al. (2020, see their Fig~1). Panels c) and d) show the logarithmic density distribution of all stars. Panels e) and f) show in-situ stars, while panels g) and h) show accreted stars. Dashed black rectangles with letters A-F at their lower left corner annotate the selection of different subsamples of the Solar neighbourhood.

<p align=center>
    <img src="https://github.com/svenbuder/golden_thread_II/blob/main/figures/splash_age.png" alt="Age distribution of different samples of stars in the Solar neighbourhood as selected in the $\mathrm{[Fe/H]}$ vs. $V_\varphi$ plane." width="49%"/>  
    <img src="https://github.com/svenbuder/golden_thread_II/blob/main/figures/splash_alfe_mgmn_extended.png" alt="Abundance distribution in [Al/Fe] vs. [Mg/Mn] of different samples of stars in the Solar neighbourhood as selected in the $\mathrm{[Fe/H]}$ vs. $V_\varphi$ plane." width="49%"/>
</p>

Figure left: Age distribution of different samples of stars in the Solar neighbourhood as selected in the $\mathrm{[Fe/H]}$ vs. $V_\varphi$ plane. A grey bar indicates the time of the major merger around $8.6\,\mathrm{Gyr}$.
Figure right: Abundance distribution in [Al/Fe] vs. [Mg/Mn] of different samples of stars in the Solar neighbourhood as selected in the $\mathrm{[Fe/H]}$ vs. $V_\varphi$ plane. Contours correspond to the 68\,\% highest-density interval. An inset figure is showing the distribution of samples C and D with ages of $9-11\,\mathrm{Gyr}$, with contours showing the 40, 60, and 80\,\% highest-density intervals

<p align=center>
    <img src="https://github.com/svenbuder/golden_thread_II/blob/main/figures/splash_rbirth_zbirth.png" alt="Density distribution of birth positions in galactocentric cylindrical coordinates $R_\mathrm{birth, 2D}$ and $Z_\mathrm{birth}$ for star particles of samples A-F (corresponding to panels a-f) that are currently in the Solar neighbourhood (black circles) of $2\mathrm{kpc}$ around $R_\mathrm{2D} = 8.2\mathrm{kpc}$." width="80%"/>
</p>

Figure: Density distribution of birth positions in galactocentric cylindrical coordinates $R_\mathrm{birth, 2D}$ and $Z_\mathrm{birth}$ for star particles of samples A-F (corresponding to panels a-f) that are currently in the Solar neighbourhood (black circles) of $2\mathrm{kpc}$ around $R_\mathrm{2D} = 8.2\mathrm{kpc}$. In panels e) and f) we note the imprint of our selection of in-situ vs. accreted stars via $\vert Z_\mathrm{birth} \vert > 5\mathrm{kpc}$.

<p align=center>
    <img src="https://github.com/svenbuder/golden_thread_II/blob/main/figures/trace_star_formation_xy_xz_feh_selection.png" alt="Distributions of iron abundances [Fe/H] for the face-on ($X_\mathrm{birth}$ vs. $Y_\mathrm{birth}$, odd rows) and edge-on ($X_\mathrm{birth}$ vs. $Z_\mathrm{birth}$, even rows) views in ten selected birth epochs within $0.5\mathrm{Gyr}$." width="80%"/>
</p>

Figure: Distributions of iron abundances [Fe/H] for the face-on ($X_\mathrm{birth}$ vs. $Y_\mathrm{birth}$, odd rows) and edge-on ($X_\mathrm{birth}$ vs. $Z_\mathrm{birth}$, even rows) views in ten selected birth epochs within $0.5\mathrm{Gyr}$, starting from $12.5-13.0\mathrm{Gyr}$ in the top-left panel to $0.0-0.5\mathrm{Gyr}$ in the bottom-right panel. Dashed black arrows indicate the path of the last major merger.

## In this repository

The code to reproduce the analysis and figures of this repository can be found in the repository's Jupyter notebook [golden_thread_II.ipynb](https://github.com/svenbuder/golden_thread_II/blob/main/golden_thread_II.ipynb).
The used simulation snapshot can be publicly accessed as FITS file via https://github.com/svenbuder/preparing_NIHAO. Original data, more snapshots and other galaxies can be found at https://tobias-buck.de/#sim_data. We encourage interested readers to get in contact with the authors for full data access and advice for use and cite [Buck et al. (2020)](https://ui.adsabs.harvard.edu/abs/2020MNRAS.491.3461B) as well as [Buck et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021MNRAS.508.3365B).

## How to Cite

Please cite this work as follows:

```bibtex
@article{Buder2025,
    author = {{Buder}, Sven and {Buck}, Tobias and {Sk\'ulad\'ottir}, \'Asa and {Ness}, Melissa and {McKenzie}, Madeleine and {Monty}, Stephanie},
    title = {The chemodynamical memory of a major merger in a NIHAO-UHD Milky Way analogue II: A golden thread through time and space},
    journal = {arXiv e-prints},
    year = 2025,
    month = oct,
    pages = {arXiv:2510.20233},
    archivePrefix = {arXiv},
    eprint = {2510.20233},
    keywords = {Galaxy: evolution -- Galaxy: formation -- Galaxy: structure -- Galaxy: abundances -- Galaxy: kinematics and dynamics},
    doi = {10.48550/arXiv.2510.20233},
    primaryClass = {astro-ph.GA},
    adsurl = {https://ui.adsabs.harvard.edu/abs/2510arXiv251020233B}
}
```
