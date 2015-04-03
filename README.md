
# LoFASM Tools Python Package
---

Tools for working on filterbank data from the Low Frequency All Sky Monitor (LoFASM).
LoFASM is a phased dipole antenna array designed to monitor the skies for radio 
transients. LoFASM's band of interest is 5-88MHz. LoFASM was built and designed by 
a group of students and professor at the University of Texas at Brownsville.

## Installation

### Mac OSX and Linux
To install run the setup.py script with root permissions

	sudo python setup.py install
 
### Windows
This software has not been tested on Windows. If you get it working
please let me know!

## Dependencies
* numpy
* scipy
* astropy
* matplotlib

## Getting up and running
Once the LoFASM Tools have been installed you can check that they were installed 
correctly by plotting up a small test data set from LoFASM I in 
Port Mansfield, Texas. 

The test data set is located at `/path/to/lofasm/testdata/20150323_033624.lofasm`, 
where `path/to/lofasm` is the path to the cloned repo directory.


To plot the data open a terminal window and navigate to the clone directory. 
Once there execute

	lofasm_plot.py -f testdata/20150323_033624.lofasm

to plot the test data. If you see an animated plot then the tools have been installed 
correctly. :)


__Refer to the _docs_ directory for more information.__


## Contributing
Pushing directly to this repository is discouraged. Please 
fork this repo and push your changes to your own working copy. 
Once your code is ready to be added to the repo create a pull
request so that I can merge it.




