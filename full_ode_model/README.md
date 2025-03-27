See https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0152337 for the details of the full ODE model of the alternative pathway.
The initial condition for the concentration of binding sites for the system of ODE is described in the method section and a sample calculation is provided below.

Na = 6.022e23 #Avagadro Number
conc_np = 2e12/Na/1e-3 #Concentration of Nanoparticles (M)
sites_per_np = 200 #Number of binding sites per nanoparticle
conc_c3b_sites = sites_per_np *conc_np
