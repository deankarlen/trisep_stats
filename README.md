# TRISEP 2025 Statistics Sessions
Dean Karlen, University of Victoria and TRIUMF

### [Reference notes and apps](https://karlen.web.cern.ch/trisep/)

## Tutorial notebooks

["Scratch" notebook for rough calculations](notebooks/scratch.ipynb)

### 0. Simple Discrete Measurement Example

![image](notebooks/img/Wood_Block_Balance_3.jpg)

- A: [Model 1](notebooks/discrete_A.ipynb)
  - a reproducible measurement
  - confidence and credible intervals
    - [posterior probability](notebooks/posterior_probability.ipynb)
    - [intervals](notebooks/intervals.ipynb)
- B: [Model 2](notebooks/discrete_B.ipynb)
  - a measurement with variability but no prior
  - confidence and credible intervals
- C: [Model 3](notebooks/discrete_C.ipynb)
  - a measurement with variability and a prior
  - confidence and credible intervals

### 1. Radioactivity Analyses

![image](notebooks/img/radioactive_source.jpg)

 - A: [Basic analysis](notebooks/radioactivity_A.ipynb)
   - descriptive statistics
   - approximate interval
 - B: [Model the experiment](notebooks/radioactivity_B.ipynb)
   - maximum likelihood
   - approaximate interval
 - C: [Frequentist analysis with 1 parameter](notebooks/radioactivity_C.ipynb)
   - Rigorous definition of confidence interval
 - D: [Bayesian analysis with 1 parameter](notebooks/radioactivity_D.ipynb)
   - making a credible interval
 - E: [Including background in the model](notebooks/radioactivity_E.ipynb)
   - likelihood function with 2 parameters
   - difficulty with frequentist approach
 - F: [Bayesian analysis of experiment with background](notebooks/radioactivity_F.ipynb)
   - Markov Chain Monte Carlo
 - G: [Including inefficiency and background in the model](notebooks/radioactivity_G.ipynb)
   - MCMC
   - Numerical optimization with MINUIT
   
 ### 2. Lifetime Analyses
 
 - A: [Basic analysis](notebooks/lifetime_A.ipynb)
   - descriptive statistics
 - B: [Model the lifetime experiment (perfect setup)](notebooks/radioactivity_B.ipynb)
   - rigorous confidence interval
 - C: [Include more complexity to the model](notebooks/radioactivity_C.ipynb)
   - includes: background process, time offset, and time resolution
   
 ### 3. T2K $\nu_e$ appearance analysis
 
 - A: [Simplified analysis](notebooks/nueT2K.ipynb)
   - MCMC treatment
   - Effect of changing prior for physics parameter
