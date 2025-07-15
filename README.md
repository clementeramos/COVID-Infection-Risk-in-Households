# COVID-Infection-Risk-in-Households
<h1>Estimating the Probability of Infection For COVID-19 in Symptomatic and Non-symptomatic Individuals</h1>

<h2>Description</h2>
In this lab, I quantified the secondary attack rate (SAR) by enforcing a prior and likelihood distribution across data from k epidemiological studies.
Then, I constructed a posterior distribution using Markov Chain Monte Carlo (MCMC) sampling to quantify infection risk. 
Ultimately, the goal is to identify the regions with lower SAR to investigate what contributed to their relative success, and those with a higher SAR to know which areas are in urgent need of intervention to slow the spread.  

<h2>Environments Used </h2>

- <b>Jupyter Notebook</b> 

<h2>Walk-through:</h2>

<p align="center">
Create a Bayesian hierarchical model: <br/>
<img src="https://i.imgur.com/b0sXwLW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Compute a trivial estimate of the true posterior probability:  <br/>
<img src="https://i.imgur.com/4DAAu7S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Approximate the empirical distribution of SAR given the observed data: <br/>
<img src="https://i.imgur.com/NG3kfLt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/lTYhGRG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/PlauRyq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Compare the theoretical and empirical distribution w/ a weak prior:  <br/>
<img src="https://i.imgur.com/TcDHUoa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Compare the distributions using a strong prior:  <br/>
<img src="https://i.imgur.com/MPAWBN4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Hierarchical Model Accounting For Asymptomatic Individuals:  <br/>
<img src="https://i.imgur.com/TD06DeK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The asymptomatic rate for COVID-19 falls between 0.18 and 0.35; it is unlikely that the posterior distribution of infection has a large fraction of asymptomatic cases:  <br/>
<img src="https://i.imgur.com/T1EZVnY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/NpQPtDu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
