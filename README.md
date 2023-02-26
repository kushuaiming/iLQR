# iLQR
## 1. How to use in Linux System
### 1.1 Install Eigen
Download repository from [Eigen offcial website](https://gitlab.com/libeigen/eigen/-/releases) \
Unzip the source code, rename the folder to "Eigen", and put it in the following path.
```
/usr/local/include/
```
### 1.2 Build and run
```
mkdir build
cd build
cmake ..
make
./run_iLQR
```
## 2. Reference
[1] W. Li and E. Todorov, "Iterative linear quadratic regulator design for nonlinear biological Movement systems." 2004.