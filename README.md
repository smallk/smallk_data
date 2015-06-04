# smallk_data
his repository holds the data sets for testing
the smallk library. 

The smallk source code can be cloned from:

https://github.com/smallk/smallk

In the Makefile for the smallk source is a switch for
specifying the data directory. That relevant portion of the Makefile
for the DARPA XDATA project is included here for convenience:

# The 'make check' and 'make distcheck' targets require the location of the 
# xdata_data project.  Users can supply the path to this project on the make 
# command line by defining the DATA_DIR variable.  If users did not specify 
# the path, assume the following location:
DATA_DIR ?= ../xdata_data
export DATA_DIR

Thus, for running 'make check' with smallk, include the switch using a command line
like:

$make check DATA_DIR=../smallk_data

or to the path where the smallk_data repository has been cloned.

    Status API Training Shop Blog About 

