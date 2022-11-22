The <BHAR> & <BHAR>/<SFR> vs. logM_star for Figs.9 & 13 in
  Yang et al. (2018), MNRAS, 475(2), 1887 
  Version 1.0, 02/19/2018
  Any questions should be sent to Guang Yang, gyang206265@gmail.com 

Data explanation:
  File names: z#.txt
    #, redshift
  In each z#.txt file:
    logM_star, total stellar mass (units: M_sun) in logarithm 
    logBHAR, ensemble-averaged black hole accretion rate (units: M_sun/yr) in logarithm
    logBHAR_lolim & logBHAR_uplim, lower & upper limits of logBHAR
    log(BHAR/SFR), ensemble-averaged black hole accretion rate divided by star formation rate (units: none) in logarithm.
		   The SFR values are from Behroozi et al. (2013) model.
		   At large logM_star, SFR might be not available. In that case, log(BHAR/SFR) is set to nan
