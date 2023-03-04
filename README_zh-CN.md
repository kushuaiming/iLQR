# iLQR
## 1. 在Linux如何环境下使用
### 1.1 安装 Eigen
从[Eigen offcial website](https://gitlab.com/libeigen/eigen/-/releases)下载源码 \
解压源码, 将其中的Eigen文件夹(其他文件夹不用管)放入以下路径:
```
/usr/local/include/
```
### 1.2 编译和运行
```
mkdir build
cd build
cmake ..
make
./run_iLQR
```
## 2. 参考文献
[1] W. Li and E. Todorov, "Iterative linear quadratic regulator design for nonlinear biological Movement systems." 2004.