# 2021_eLife
The code was used in the following publication:

Calcium dependence of neurotransmitter release at a high fidelity synapse.  
Eshra A, Schmidt H, Eilers J, Hallermann S.  
eLife 2021  


The Mathematica code calculates the uncaging-evoked calcium transients and the resulting calcium-driven cumulative release of models 1, 2, and 3. Analysis of the cumulative release is performed by sampling, adding realistic noise, and fitting with mono- and bi-exponential functions.

The code was run on Mac OSX 11.5.3 with Mathematica 12.1.1. To run the code, the text-files in the "data to fit"-folder should be available at "../data to fit/". The Mathematica file including the output cells is also provided as a PDF (e.g. "model1.pdf"). If exportYes is set to 1, a large number of text files containing various simulation results will be exported in the current folder. To reproduce the complete simulations of the manuscript, increase the variables noiseRepeats, aNumberDMN05, aNumberDMN2, and aNumberDMN10 as indicated in the comments, which will increase the calculation time up to hours depending on the computer speed. The resulting Mathematica files are provided as PDFs (e.g. "model1 complete.pdf"). To illustrate the function of the code, some parameters were reduced in the provided code, which results in an execution time of less than a minute. The resulting Mathematica files are also provided as PDFs (e.g. "model1.pdf"). To generate the data provided in the figure 6E, further data processing is required as explained in the folder "data processing".

For more information contact hallermann@medizin.uni-leipzig.de
