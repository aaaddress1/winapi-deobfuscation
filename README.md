# Towards Generic Deobfuscation of Windows API Calls

## Paper 

### Paper

The official version of the paper can be found [here](https://www.ndss-symposium.org/wp-content/uploads/2018/07/bar2018_11_Kotov_paper.pdf). 

### Citation 
Kotov, V., & Wojnowicz, M. (2018). Towards generic deobfuscation of Windows API calls. In _2018 Symposium on Network and Distributed System Security (NDSS), Workshop on Binary Analysis Research (BAR)._

## Code 

We provide source code to replicate the data collection process and experimental results.


### data_collection
This folder contains the simplified symbolic execution engine and scripts to extract API call information from 32-bit Windows executables; as well as prepare the data to be fed into our HMM-based classifier.

### experiments
This folder has all the code required to replicate both experiments described in the paper. It takes in the data prepared using the scripts from data_collection folder.


