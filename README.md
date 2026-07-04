# Dense and Convolutional Autoencoders for Real-Time Anomaly Detection and New Physics Searches at the LHC Level-1 Trigger

## Final project for the Statistics and Data Analysis course, Academic Year 2025–2026

### Giorgio Cividini, Università degli Studi di Milano-Bicocca

Real-time anomaly detection at the Large Hadron Collider Level-1 Trigger is crucial for identifying
new physics beyond the Standard Model. This report presents the results of a comparative study of
dense and convolutional Autoencoders for unsupervised anomaly detection using particle-level data
available at the 40 MHz collision rate. The project aims to explore the potential of model training
using a custom, physics-informed masked loss function that incorporates transverse momentum
p T , pseudorapidity η, and azimuthal angle ϕ measurements, with weights that tune the reciprocal
relevance of each observable. For every model, the performance is presented in terms of AUC and
TPR@FPR(10 −5 ) and compared with other studies used as benchmarks.

------------------------------------------------------------------




Download the data folder
[here](https://cernbox.cern.ch/s/9PCavcegMQaRs5m)

### Requirements:

python>=3.11

h5py

scikit-learn

numpy

matplotlib

seaborn

tensorflow

keras==3.14.1
