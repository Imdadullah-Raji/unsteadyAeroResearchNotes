## Abstract
- Scope of study:
	- Reynolds number Range : $500<Re<5000$ 
	- AoA range: $0\leq\alpha\leq20$
- Method: Water-channel experiments, numerical simulations(**SEM** ), [[Floquet Stability Analysis]]

## Literature Review of the Paper

- Huang and Lin(1995 JFM) smoke-wire visualization at $Re=3195$ and
- Huang(2001 JFM) PIV with qualitative flow regimes classification: 
	1. Attached flow
	2. TEV
	3. Seperation vortex
	4. LEV
	5. bluff-body effect
- *Alam* MM, Zhou Y, 2010; $Re=5300$ LIF study.
- [[Kurtulus 2016 IJMAV  NACA0012 Modes]], 5 qualitative modes were described for 2D numerical study based on wake vorticity pattern.
### 1.2 Prediction of onset of three dimensionality in Wakes
- Studies on stationary cylinder wake are present in the late 80s, early 90s 
	1. [[Barkley and Henderson 1996 JFM  cylinder 3D instability]], floquet stability analysis of 3D flow past a cylinder: prediction of the cirtical Re and wavelength $\lambda$ of the instability.
	2. Stability analysis study on different shapes following the lead of Barkley and Henderson papers: elliptic, rotating cylnder, rounder square cylinder. 
### 1.3 Focus of this work
- Developed a relationship between $\text{Re}$ and critical angle of attack $\alpha_{3D} \textasciitilde \text{Re}^{-0.5}$ .  Also a relationship between Re and supercritical Hopf bifurcation that results in periodic vortex shedding

## 2.1 Methodology

They used a method called nodal spectral-element method. A book by Karniadakis is mentioned.

## Key Results 


![[regime_mapReAOA_Gupta2023JFM.png]]
>At Re = 1000 3D instability starts at 13 degrees. Which calls into question the validity of period double 2D simulations in case of real flows.

My thought experiment verbatim:
>This is the thought exp: I take a 2D base flow and copy it along z-axis. Small numerical instabilities make it go unstable. I take the a line along the z axis and do FFT and record the time series of the amplitudes. The elementwise ratio in this time series is the floquet mutiplier at that wavelength.

They classified the spanwise 3D instabilities following the lead of CHK Williamsons 3D cylinder instability works. See [[Williamson ARFM 1996 Cylinder Wake Vortex Dynamics ]]


