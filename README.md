# BGVSR
Bayesian Grouped Variable Selection Regression
Algorithm: EM, Variational EM 

### Prerequisites
The following packages are required on a linux machine to compile and use the software package. 
```
g++
cmake
make
boost
```
### Installing
Installing BGVSR is fairly simple. Follow the following steps:
```
git clone https://github.com/usr0001/BGVSR.git
cd BGVSR
mkdir build
cd build
cmake ..
make
```
### Usage
```
./bgvsr -g ../data/10k_5k -p ../data/pheno.plink -nfm 
```

