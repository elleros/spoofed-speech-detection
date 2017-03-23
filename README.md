# Synthetic Speech Detection with the Bob.Bio SPEAR Python Library

This notebook implements a Gaussian mixture model maximum likelihood (GMM-ML) classifier for synthetic (spoofed) speech detection. This approach uses regular mel frequency cepstral coefficients (MFCC) features and gives the best performance on the [ASVspoof 2015 dataset](https://www.idiap.ch/dataset/avspoof) among the standard classifiers (GMM-SV, GMM-UBM, ...). For more background information see: *Hanilçi, Cemal, Tomi Kinnunen, Md Sahidullah, and Aleksandr Sizov. \"Classifiers for synthetic speech detection: a comparison.\" In INTERSPEECH 2015*. The scripts use the Python package [Bob.Bio.SPEAR 2.04](https://pypi.python.org/pypi/bob.bio.spear/2.0.4) for speaker recogntion.

This work is part of the [\"DDoS Resilient Emergency Dispatch Center\"](https://www.dhs.gov/science-and-technology/news/2015/09/04/dhs-st-awards-university-houston-26m-cyber-security-research) project at the University of Houston, funded by the Department of Homeland Security (DHS).

April 19, 2015
 
Lorenzo Rossi

lorenzo **[dot]** rossi **[at]** gmail **[dot]** com
