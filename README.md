# ECG-Analysis-and-Vectorcardiography-

Used Python to complete this project (Pandas, NumPy, matplotlib, scipy, and wfdb)

VCG captures the "equivalent heart dipole" which provides quantitative data often missed by standard flat ECGs.
That's why VCG is important in even more accurate clinical diagonsis of heart issues.

Before Constructing the VCG visualizations I've had some time exploring the dataset provided by PTB-XL on physionet. I've Applied my data analysis skills and data wrangling  techniques to understand the data and trying to create visulas that help in displaying the distribution of the data.

I've created a function that preprocesses each input ECG signal:

1. filtering it to get rid of all forms of noise:
   1. low frequency noise such as the baseline wander caused by patient movement
   2.  high frequency noise such as power line interference & Electromygraphic noise which caused by the muscle activity
  
2. Calculating some important metrics like the signal R-peaks, and the R-R interval to then compute the Heart Rate of the pateint.

3. And after that I've applied the formulas of the X, Y, and Z arrays from the standard leads after the filteration process to visualize the VCG and look at the heart's signal flow from different ways. 
