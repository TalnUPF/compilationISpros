# Thematicity-Prosody Experiments
This repository contains data and code as well as instructions to reproduce our experiments in [1].

###################
## Software requirements
###################

In order to reproduce the experiments described in [1] you need to firstly download and install the following software:
	- Weka Data Mining software [2] from the following link http://www.cs.waikato.ac.nz/ml/weka/downloading.html
	- Praat for feature annotation [3] from our repository https://github.com/monikaUPF/featureAnnotationforPraat
	NB: The extension of Praat for feature annotation currently works under Lynux

###################
## Speech Data
###################

The following data are made available from our corpus on read speech:
	- Binary files: intensity and pitch objects created using Praat from raw speech files.
	- TextGrids: segmentation into words and thematicity spans.
	- Arff files: the sentence span database (SSD) and the thematicity span database (TSD).
	
###################
## Praat Scripts
###################

Praat scripts for extraction of acoustic parameters, feature annotation and exporting to txt format consist on 5 modules.
These modules require the extension of Praat for feature annotation [2] to run. They do not run on standard Praat. These modules include the improved intensity detection module presented in [3]. The modules are to be executed in order (from 1 to 5).

###################
## Reproducibility instructions
###################

In order to reproduce our experiments from the beginning you need to follow these steps: 
	1. download  and install the required software;
	2. download speech data and praat scripts;
	3. run the 5 modules on the data;
	4. create the arff files or use the ones we provide;
	5. perform the classification experiments on Weka explained in the publication [1]
	
