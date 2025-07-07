# Kinetics Summary
-------------------------------------------------------------------------------------------------------------------
| No. | Reaction Name              | Chemical Reaction                           | Rate Expression                        |
|-----|----------------------------|---------------------------------------------|-----------------------------------------|
| 1   | Hydrolysis                 | C_6H_{10}O_5 + H_2O -> C_6H_{12}O_6          | r_{hyd} = k_{hyd} \cdot C_{BOD_p}       |
|     |                            |                                             | Kinetics: First-order                   |
|     |                            |                                             | Temp Correction: k_{hyd,T} = k_{hyd,20} \cdot \theta_{hyd}^{(T - 20)} |
|     |                            |                                             | Reference: Batstone et al., 2002        |
-------------------------------------------------------------------------------------------------------------------
| 2   | Carbon Oxidation           | C_6H_{12}O_6 + O_2 -> CO_2 + Biomass        | r_{ox} = \mu_H \cdot \dfrac{C_S}{K_S + C_S} \cdot \dfrac{C_O}{K_O + C_O} \cdot X_H |
|     |                            |                                             | Kinetics: Monod dual limitation         |
|     |                            |                                             | Temp Correction: \mu_{H,T} = \mu_{H,20} \cdot \theta_H^{(T - 20)} |
|     |                            |                                             | Reference: Henze et al., 2000           |
-------------------------------------------------------------------------------------------------------------------
| 3   | Nitrification – NH4 Oxid.  | NH_4^+ + 1.5 O_2 -> NO_2^- + 2H^+ + H_2O     | r_{nit1} = \mu_{AOB} \cdot \dfrac{C_{NH4}}{K_{NH4} + C_{NH4}} \cdot \dfrac{C_O}{K_O + C_O} \cdot X_{AOB} |
|     |                            |                                             | Kinetics: Monod dual limitation         |
|     |                            |                                             | Temp Correction: \mu_{AOB,T} = \mu_{AOB,20} \cdot \theta_{AOB}^{(T - 20)} |
|     |                            |                                             | Reference: Henze et al., 2000           |
-------------------------------------------------------------------------------------------------------------------
| 4   | Nitrification – NO2 Oxid.  | NO_2^- + 0.5 O_2 -> NO_3^-                  | r_{nit2} = \mu_{NOB} \cdot \dfrac{C_{NO2}}{K_{NO2} + C_{NO2}} \cdot \dfrac{C_O}{K_O + C_O} \cdot X_{NOB} |
|     |                            |                                             | Kinetics: Monod dual limitation         |
|     |                            |                                             | Temp Correction: \mu_{NOB,T} = \mu_{NOB,20} \cdot \theta_{NOB}^{(T - 20)} |
|     |                            |                                             | Reference: Henze et al., 2000           |
-------------------------------------------------------------------------------------------------------------------
| 5   | Denitrification – NO3 Red. | NO_3^- -> NO_2^- + Biomass                 | r_{denit1} = \mu_{denit} \cdot \dfrac{C_{NO3}}{K_{NO3} + C_{NO3}} \cdot \dfrac{C_S}{K_S + C_S} \cdot X_{denit} |
|     |                            |                                             | Kinetics: Monod                         |
|     |                            |                                             | Temp Correction: \mu_{denit,T} = \mu_{denit,20} \cdot \theta_{denit}^{(T - 20)} |
|     |                            |                                             | Reference: Henze et al., 2000           |
-------------------------------------------------------------------------------------------------------------------
| 6   | Denitrification – NO2 Red. | NO_2^- -> N_2                               | r_{denit2} = \mu_{denit2} \cdot \dfrac{C_{NO2}}{K_{NO2} + C_{NO2}} \cdot \dfrac{C_S}{K_S + C_S} \cdot X_{denit} |
|     |                            |                                             | Kinetics: Monod                         |
|     |                            |                                             | Temp Correction: \mu_{denit2,T} = \mu_{denit2,20} \cdot \theta_{denit2}^{(T - 20)} |
|     |                            |                                             | Reference: Henze et al., 2000           |
-------------------------------------------------------------------------------------------------------------------
| 7   | Fermentation               | C_6H_{12}O_6 -> VFA + CO_2 + H_2            | r_{ferm} = \mu_{ferm} \cdot \dfrac{C_S}{K_S + C_S} \cdot X_{ferm} |
|     |                            |                                             | Kinetics: Monod                         |
|     |                            |                                             | Temp Correction: \mu_{ferm,T} = \mu_{ferm,20} \cdot \theta_{ferm}^{(T - 20)} |
|     |                            |                                             | Reference: Batstone et al., 2002        |
-------------------------------------------------------------------------------------------------------------------
| 8   | Acidogenesis               | VFA -> Acetate + CO_2 + H_2                 | r_{acid} = \mu_{acid} \cdot \dfrac{C_{VFA}}{K_{VFA} + C_{VFA}} \cdot X_{acid} |
|     |                            |                                             | Kinetics: Monod                         |
|     |                            |                                             | Temp Correction: \mu_{acid,T} = \mu_{acid,20} \cdot \theta_{acid}^{(T - 20)} |
|     |                            |                                             | Reference: Batstone et al., 2002        |
-------------------------------------------------------------------------------------------------------------------
| 9   | Acetogenesis               | Acetate -> CH_4 + CO_2                      | r_{acet} = \mu_{acet} \cdot \dfrac{C_{acetate}}{K_{acetate} + C_{acetate}} \cdot X_{acet} |
|     |                            |                                             | Kinetics: Monod                         |
|     |                            |                                             | Temp Correction: \mu_{acet,T} = \mu_{acet,20} \cdot \theta_{acet}^{(T - 20)} |
|     |                            |                                             | Reference: Batstone et al., 2002        |
-------------------------------------------------------------------------------------------------------------------
|10   | Methanogenesis             | Acetate + H_2 -> CH_4 + CO_2                | r_{meth} = \mu_{meth} \cdot \dfrac{C_{acetate}}{K_{acetate} + C_{acetate}} \cdot X_{meth} |
|     |                            |                                             | Kinetics: Monod                         |
|     |                            |                                             | Temp Correction: \mu_{meth,T} = \mu_{meth,20} \cdot \theta_{meth}^{(T - 20)} |
|     |                            |                                             | Reference: Batstone et al., 2002        |
-------------------------------------------------------------------------------------------------------------------
|11   | PAC Adsorption             | Contaminant + PAC <-> Surface Complex      | r_{ads} = k_{ads} \cdot C_{contaminant} \cdot \dfrac{C_{PAC}}{1 + K_{ads} \cdot C_{contaminant}} |
|     |                            |                                             | Kinetics: Langmuir                      |
|     |                            |                                             | Temp Correction: k_{ads,T} = k_{ads,20} \cdot \theta_{ads}^{(T - 20)} |
|     |                            |                                             | Reference: Kuo et al., 2012             |
-------------------------------------------------------------------------------------------------------------------
