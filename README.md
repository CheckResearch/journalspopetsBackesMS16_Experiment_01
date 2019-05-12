# CheckResearch.org [Experiment](https://checkresearch.org/Experiment/View/27c8b4f2-d787-4d99-b483-0dea5e26fded)

 Publication ["Your Choice MATor(s)."](https://dblp.uni-trier.de/rec/html/journals/popets/BackesMS16) by "Michael Backes 0001, Sebastian Meiser 0001, Marcin Slowik"
 
 Reproduction of the preceding paper ["(Nothing else) MATor(s): Monitoring the Anonymity of Tor's Path Selection."](https://github.com/CheckResearch/confccsBackesKMM14_Experiment_01)

## Experiment Setup
1. Download *MATor2-new.zip* (located in `code` directory)
2. Follow instructions of the INSTALL file and/or commands of "Ubuntu-Install.sh" for installation.

The script *download-consensus.py* of the [preceding reproduction](https://github.com/CheckResearch/confccsBackesKMM14_Experiment_01) can be used to download Tor consensus data. With a little modification it can also be used to download Tor server descriptors.

### Experiment Content

I reproduced and extended the long time analysis shown in Figure 12 of the original paper. It was planned to conduct analysis with data from 2012 until end of 2018 but due to the higher runtime only a part of this time span was analysed.

### Hardware/Software

Computations were performed on a virtual machine with Ubuntu (16 GB RAM) and a 4 core CPU.   
Programming languages used:
* Python 3.7
* C++
* GO
## Experiment Assumptions

No additional assumptions.

## Preconditions
Following C++ libraries and Python modules have to be available:  

C++ libraries:  
* boost
* sqlite3


Python modules:  
* stem

## Experiment Steps

A short overview on the steps I took to reproduce the experiment. For a detailed description please have a look at Section 4.3.2 of my Bachelor thesis.

1. Get the source code.
2. Install dependencies, fix compiletime bugs.
3. Fix or inspect GO runtime bugs.
4. Fix C++ runtime bugs.
5. Alter "worklist-example-complex.py" to perform analysis with desired parameters.
6. Comparison of results
## Results

Reproduced and original values are similar, due to longer runtime of MATor2 only a part of the complete time span could be analysed. Again, for a detailed description of the results including graphs and a comparison with the original results, please have a look at Section 5.2 of my Bachelor thesis.