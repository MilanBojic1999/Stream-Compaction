# Stream-Compaction
Stream Compaction implemented with CUDA and Python

Based on paper: http://www.cse.chalmers.se/~uffe/streamcompaction.pdf

This shouldn't be finished project, there is a problem transfering between 2nd and 3th phase, because I couln't make all blocks synchronize on google machines. Will be looked in the future. 

Right now code removes all spaces from the text, if you want to change that you can in CUDA function good_char(char)

In the repository is also txt file with big text to test CUDA solution
