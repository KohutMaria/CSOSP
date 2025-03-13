# Computer Simulation of Stochastic Processes

This repository contains programming assignments and projects from the **Computer Simulation of Stochastic Processes** course, which is part of my Master's studies at **Wrocław University of Science and Technology**. The tasks are implemented using **Jupyter Notebooks**, and explore various methods for simulating different types of stochastic processes.

## Structure

The repository is divided into two parts:

### Part 1: Individual Assignments

These tasks were completed during laboratory classes and focus on the simulation and analysis of different stochastic processes.

- **CSOSP_1**: Implemented inverse transform sampling for the **exponential** and **Pareto** distributions and compared the results with inbuilt Python simulation methods.
  
- **CSOSP_2**: Simulated **symmetric** and **non-symmetric stable random variables** for \( \alpha = 1 \) and \( \alpha \neq 1 \). Plotted the results and compared the **Cumulative Distribution Function (CDF)**.

- **CSOSP_3**: Extended **CSOSP_2** by creating a generalized method for generating all cases. Plotted the empirical CDF and characteristic function (CF).

- **CSOSP_5**: Simulated an **α-stable vector** using **spectral measures** and **masses**. Estimated the spectral measure and simulated a **sub-Gaussian vector**.

- **CSOSP_6**: Developed a method for calculating **codifference** and applied it to α-stable vectors with independent symmetric marginals and symmetric spectral measures.

- **CSOSP_7**: Created a method to simulate **α-stable processes** using increments. Simulated both **Brownian motion** and **α-stable motions**.

- **CSOSP_8**: Implemented methods for calculating **Ensemble-Averaged MSD (EA-MSD)**, **Time-Averaged MSD (TA-MSD)**, and **EA-TA-MSD**. Simulated and plotted the results for **Brownian** and **α-stable motions**.

- **CSOSP_9**: Implemented a method to simulate **fractional Brownian motion (fBM)** using **Cholesky decomposition**. Generated multiple trajectories for fBM with various **Hurst parameters (H)**.

- **CSOSP_10**: Created a method for the **Lamperti transformation** to generate the **Ornstein-Uhlenbeck process** using Brownian motion. Simulated and plotted results for the Ornstein-Uhlenbeck process.

- **CSOSP_11**: Implemented a method to simulate **fractional Lévy stable motion (FLSM)** via its **integral representation**. Generated and plotted trajectories and their increments.

### Part 2: Group Project (Pair Work)

The second part of the course involved group projects, completed in pairs. The reports and implementations were based on more advanced simulations and analyses.

- **Report 1**: Implemented a generator for **α-stable distributions** and estimators for the **α parameter**. Plotted **Empirical CDF (ECDF)** and **Characteristic Function (CF)** with fitted lines. Analyzed the distribution of estimated \( \hat{\alpha} \)'s using **Monte Carlo simulations**. Calculated **Mean Squared Errors (MSE)** and **Mean Absolute Errors (MAE)** for the estimators and presented a **2D contour plot** for MSE and MAE.

- **Report 2**: Implemented a generator for **multivariable stable distributions** with **discrete spectral measures** and masses, covering three main cases: symmetric stable vectors, stable vectors with independent components, and stable vectors that are neither symmetric nor independent. Additionally, a generator for **sub-Gaussian vectors** with a **uniform spectral measure** was developed. The **α parameter** was estimated for all these cases using the **empirical characteristic function** and **spectral measure** based on the **Rachev-Xin-Chen method**. The characteristic function of the multivariate stable distributions was estimated for each case. An implementation for calculating the **codifference** was also provided and applied to a separate example.

- **Report 3**: Implemented functions to plot **quantile lines** and calculate **EAMSD**, **TAMSD**, and **EATAMSD**. Simulated **fractional Brownian motion** using **Cholesky decomposition**, applied **Lamperti transformation** to generate **fractional Ornstein-Uhlenbeck processes**, and used **integral and series representations** for generating **fractional Lévy stable motion**. Simulated and analyzed all three processes, calculating their increments and plotting trajectories, quantile lines, variance over time, mean square displacements, and histograms. Assessed whether the processes were stationary or normally distributed. In addition, we applied the same analyses to the increments of these processes. Finally, simulated a **SαS Lévy process** until it exited a specified interval and calculated the **exit time**.
