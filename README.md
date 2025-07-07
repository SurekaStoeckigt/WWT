# Kinetics Table
| **Reaction** | **Chemical Reaction** | **Rate Expression** | **Kinetics** | **Temperature Correlation** | **Reference** |
|---|---|---|---|---|---|
| Hydrolysis (Cellulose) | $C_6H_{10}O_5 + H_2O \rightarrow C_6H_{12}O_6$ | $r_{hyd} = k_{hyd} \cdot C_{cellulose}$| First-order |$k_{hyd,T} = k_{hyd,20} \cdot \theta_{hyd}^{(T - 20)}$| Batstone et al. (2002) |
| Hydrolysis (Protein) | $C_{5}H_{7}NO_{2} + H_2O \rightarrow amino\ acids$ | $r_{hyd} = k_{hyd} \cdot C_{protein}$| First-order |  $k_{hyd,T} = k_{hyd,20} \cdot \theta_{hyd}^{(T - 20)}$ | Angelidaki & Sanders (2004) |
| Hydrolysis (Lipids) |  $C_{57}H_{104}O_{6} + 3H_2O \rightarrow glycerol + fatty\ acids$ |  $r_{hyd} = k_{hyd} \cdot C_{lipid}$ | First-order |  $k_{hyd,T} = k_{hyd,20} \cdot \theta_{hyd}^{(T - 20)}$ | Batstone et al. (2002) |
| Carbon Oxidation | $C_6H_{12}O_6 + 6O_2 \rightarrow 6CO_2 + 6H_2O$ | $r_{ox} = \mu_H \cdot \frac{C_{BOD_s}}{K_S + C_{BOD_s}} \cdot \frac{C_{O_2}}{K_O + C_{O_2}} \cdot X_H$ | Monod | $\mu_{H,T} = \mu_{H,20} \cdot \theta_{H}^{(T-20)}$ | Henze et al. (2000) |
| Fermentation | $C_6H_{12}O_6 \rightarrow 2C_2H_5OH + 2CO_2$ | $r_{ferm} = $\`\mu_F \cdot \frac{C_{substrate}}{K_S + C_{substrate}} \cdot X_F`$ | Monod | $\mu_{F,T} = \mu_{F,20} \cdot \theta_{F}^{(T-20)}$ | Batstone et al. (2002) |
| Acidogenesis | $C_2H_5OH \rightarrow acetate + H_2$ | $r_{acid} = \mu_{acid} \cdot \frac{C_{ethanol}}{K_S + C_{ethanol}} \cdot X_{acid}$ | Monod | $\mu_{acid,T} = \mu_{acid,20} \cdot \theta_{acid}^{(T-20)}$ | Batstone et al. (2002) |
| Acetogenesis | $Propionate + H_2O \rightarrow acetate + H_2 + CO_2$ | $r_{acet} = \mu_{acet} \cdot \frac{C_{propionate}}{K_S + C_{propionate}} \cdot X_{acet} | Monod | \mu_{acet,T} = \mu_{acet,20} \cdot \theta_{acet}^{(T-20)}$ | Batstone et al. (2002) |
| Methanogenesis | $acetate + H_2 \rightarrow CH_4 + CO_2$ | $r_{meth} = \mu_{meth} \cdot \frac{C_{acetate}}{K_S + C_{acetate}} \cdot X_{meth}$ | Monod | $\mu_{meth,T} = \mu_{meth,20} \cdot \theta_{meth}^{(T-20)}$ | Batstone et al. (2002) |
| Nitrification (AOB) | $NH_4^+ + 1.5O_2 \rightarrow NO_2^- + H_2O + 2H^+ $| $r_{nit,AOB} = \mu_{AOB} \cdot \frac{C_{NH_4}}{K_{NH_4} + C_{NH_4}} \cdot \frac{C_{O_2}}{K_O + C_{O_2}} \cdot X_{AOB}$ | Monod | $\mu_{AOB,T} = \mu_{AOB,20} \cdot \theta_{AOB}^{(T-20)}$ | Henze et al. (2000) |
| Nitrification (NOB) | $NO_2^- + 0.5O_2 \rightarrow NO_3^-$ | $r_{nit,NOB} = \mu_{NOB} \cdot \frac{C_{NO_2}}{K_{NO_2} + C_{NO_2}} \cdot \frac{C_{O_2}}{K_O + C_{O_2}} \cdot X_{NOB}$ | Monod | \mu_{NOB,T} = \mu_{NOB,20} \cdot \theta_{NOB}^{(T-20)} | Henze et al. (2000) |
| Denitrification (NO_3-) | $NO_3^- \rightarrow N_2 + CO_2 + biomass$ | $r_{denit} = \mu_{denit} \cdot \frac{C_{NO_3}}{K_{NO_3} + C_{NO_3}} \cdot \frac{C_{BOD_s}}{K_S + C_{BOD_s}} \cdot X_{denit}$ | Monod | \mu_{denit,T} = \mu_{denit,20} \cdot \theta_{denit}^{(T-20)} | Henze et al. (2000) |
| PAC Adsorption | $C + PAC \leftrightarrow C_{adsorbed}$ | $r_{ads} = k_{ads} \cdot \frac{C \cdot PAC}{1 + K_{ads} \cdot C}$ | Langmuir | $k_{ads,T} = k_{ads,20} \cdot \theta_{ads}^{(T-20)}$ | Kuo et al. (2012) |

