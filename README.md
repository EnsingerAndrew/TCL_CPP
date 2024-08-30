# TCL_CPP
Tensor Contraction Layer backpropagation implementation in C++.

Dependencies: 
- g++ 

Steps to Train Parameters: 
1. extract contents from zip file `eigen-3.4.0.zip` and save to folder titled `eigen-3.4.0`
2. run ` g++ main.cpp -O3 functions.cpp "-Ieigen-3.4.0"` in command prompt
3. run `./a.exe`
4. observe changes in average accuracy and average error
    1. Note 1: the save_frequency variable is set to 100 so the first 100 results will be deflated because values initialized to 0
    2. Note 2: the weights have already been trained so accuracy should be relatively stable at approx 85-90%

Weights can be set to random initial values by running the script `parameter_randomizer.py`
