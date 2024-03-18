# Ecg_assignment
Ecg_assignment for Programming III

# ECG study case
This repository contains the analysis of the ECG study case.
Purpose: to investigate the streaming ECG data.  

# Methodology
1. Develop a client app
2. Fetches the data in streaming modules and updates the plot simultaneously
3. Apply neurokit2 to find the features of the ECG data. [1]
4. Statistical analysis:
5. Visualization: line chatrs, interactive bokeh plots

## Verion
Python 3.11.5
Bokeh 3.2.1
Jupyter Notebook 6.5.4

# Data
The streaming data file is accessed at the WebSocket server URL, ws://assemblix:8282
Description of the data: messages contain
 1. Deltatime since start of measurement
 2. ECG signal raw
 3. ECG signal filtered [2]
     
# Conclusion
1. 
2. 
3. 

# Files
1. ecg_assignment.ipynb
    Jupyter notebook, to perform the complete analysis of the data
    
2. config.yaml
    The configuration file contains data path.

# Author
Mary(Pei-Shan) Wu  
p.wu.2@st.hanze.nl  

# References
[1] Nemirko A.P., Lugovaya T.S. Biometric human identification based on electrocardiogram. Proc. XII-th Russian Conference on Mathematical Methods of Pattern Recognition, Moscow, MAKS Press, 2005, pp. 387-390. ISBN 5-317-01445-X.  
[2] Makowski, D., Pham, T., Lau, Z. J., Brammer, J. C., Lespinasse, F., Pham, H., Schölzel, C., & Chen, S. A. (2021). NeuroKit2: A Python toolbox for neurophysiological signal processing. Behavior Research Methods, 53(4), 1689-1696. https://doi.org/10.3758/s13428-020-01516-y.  
[3] 

