# Components from Association between age of cannabis initiation and gray matter covariance networks in recent onset psychosis

In this repository you can find the components that were derived in our PRONIA-CIP-publication: "Association between age of cannabis initiation and gray matter
covariance networks in recent onset psychosis" (Penzel et al., Neuropsychopharmacology, in press).
In our study, we employed group information guided independent component analysis (GIG-ICA) (Luo et al., 2012; Lin et al., 2010) using the GIFT-toolbox (http://mialab.mrn.org/software/gift/). This approach at the same time maximizes independence between the components and minimizes the distance to reference components (components of interest). As we aimed to investigate the effects of the age of cannabis use initiation on brain structures that are reliably associated with schizophrenia we used the 4 out of 9 components from Gupta et al. (2015) that were both, significantly different between schizophrenia and healthy controls and robust against site effects. Before employing GIG-ICA, the reference components were thresholded with the so-called "g-mask" to reduce the impact of study-specific scanner differences (Koutsouleris et al., 2018).  
Our main finding was that the age of cannabis initiation was negatively associated with gray matter volume in the COI9_cerebellum in patients with recent onset psychosis, thus greater gray matter volume in the cerebellum (COI9_cerebellum) was associated with an earlier cannabis consume. 

In case of any questions feel free to contact me (nora.penzel@gmail.com). 

### Acknowledgements
We want to thank Prof. Vince Calhoun, and Dr. Navin Gupta for sharing their component results with us. 

### References
- Penzel N, Antonucci LA, Betz LT, Sanfelici R, Weiske J, Pogarell O, Cumming P, Quednow BB, Howes O, Falkai P, Upthegrove R, Bertolino A, Borgwardt S, Brambilla P, Lencer R, Meisenzahl E, Rosen M, Haidl T, Kambeitz-Ilankovic L, Ruhrmann S, Salokangas RRK, Pantelis C, Wood SJ, Koutsouleris N, Kambeitz J and the PRONIA Consortium. Association between Age of Cannabis Initiation and Gray Matter Covariance Networks in Recent Onset Psychosis. Neuropsychopharmacology, in press. 
- Luo L, Xu L, Jung R, Pearlson G, Adali T, Calhoun VD. Constrained source-based morphometry identifies structural networks associated with default mode network. Brain Connect 2012;2:33–43. DOI: 10.1089/brain.2011.0026
- Lin Q-H, Liu J, Zheng Y-R, Liang H, Calhoun VD. Semiblind spatial ICA of fMRI using spatial constraints. Hum Brain Mapp 2010;31:1076–88. DOI: 10.1002/hbm.20919
- Gupta CN, Calhoun VD, Rachakonda S, Chen J, Patel V, Liu J, Segall J, Franke B., Zwiers MP, Arias-Vasquez A, Buitelaar J, Fisher SE, Fernandez G, Erp vTGM, Potkin S, Ford J, Mathalon D, McEwen S, Lee HJ, Mueller BA, Greve DN, Andreassen O, Agartz I, Gollub RL, Sponheim SR, Ehrlich S, Wang L, Pearlson G, Glahn DC, Sprooten E, Mayer AR, Stephen J, Jung RE, Canive J, Bustillo J, Turner JA. Patterns of Gray Matter Abnormalities in Schizophrenia Based on an International Mega-analysis. Schizophr Bull 2015;41:1133–42. https://doi.org/10.1093/schbul/sbu177
- Koutsouleris N, Kambeitz-Ilankovic L, Ruhrmann S, Rosen M, Ruef A, Dwyer DB, et al. Prediction Models of Functional Outcomes for Individuals in the Clinical High-Risk State for Psychosis or With Recent-Onset Depression: A Multimodal, Multisite Machine Learning Analysis. JAMA Psychiatry 2018;75:1156–72. doi:10.1001/jamapsychiatry.2018.2165
