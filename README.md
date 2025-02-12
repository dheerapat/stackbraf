# StackBRAF: a large-scale stacking ensemble learning for BRAF affinity prediction
#### This software can be used for BRAF V600E protein affinity prediction
#### You can use this model in [Web Application](https://qsarlabs.com/#stackbraf)
* Author: Nur Fadhilah Syahid, Natthida Weerapreeyakul, and Tarapong Srisongkram*
* Corresponding author: Tarapong Srisongkram (tarasri@kku.ac.th)
* Division of Pharmaceutical Chemistry, Faculty of Pharmaceutical Sciences, Khon Kaen University, Khon Kaen, 40002, Thailand
### If you think this code or model useful, please cite us at 
### Syahid, N. F., Weerapreeyakul, N., & Srisongkram, T. (2023). StackBRAF: A Large-Scale Stacking Ensemble Learning for BRAF Affinity Prediction. ACS Omega. https://doi.org/10.1021/acsomega.3c01641
# How to Run a Program as a Container
```bash
# download and setup
git clone <THIS REPO> stackbraf
cd stackbraf
unzip models/models-fp/SVR_reg_KlekotaRoth.zip

# running docker
docker build -t stackbraf .
docker run stackbraf
```
