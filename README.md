# PL3
programs I implemented in PL3

*Please contribure and star my work if it was helpful*

INSTALLATION INSTRUCTIONS:

-------------------------------------------------------------

for BeagleBoneBlack assignments

*Connecting LED*
( i/p from GPIO ) OR ( i/p from GND ) --> LED
i.e. 
one input of OR gate is output from BBB GPIO pin
other input is from GND
output of OR gate to LED 

*Connecting SWITCH*
one end of switch to VCC
other end to BBB GPIO pin as input

dont forget connect VCC 3.3 and gnd of BBB
  
ssh 192.168.7.2
  
// if not connecting, remove everything from file using _gedit /.ssh/known_hosts_ 
 
-------------------------------------------------------------

installing lisp and sbcl

install clisp : https://sourceforge.net/projects/clisp/files/latest/download / yum install clisp / sudo apt-get install clisp
install sbcl : (tar.gz) https://sourceforge.net/projects/sbcl/files/latest/download
               (EXE) https://excellmedia.dl.sourceforge.net/project/sbcl/sbcl/1.3.15/sbcl-1.3.15-x86-64-windows-binary.msi 
               
-------------------------------------------------------------

installing LEX and YACC

you will need a c/c++ compiler, hence it is better to install it on linux
lex : yum install flex / apt-get install flex
yacc : yum install bison / apt-get install bison

-------------------------------------------------------------

installing  CUDA

install visual studio 2015 : http://download.cnet.com/Visual-Studio-Professional-2015/3001-2212_4-76440612.html?hasJs=n
and then install cuda 8.0.61 : https://developer.nvidia.com/cuda-downloads

-------------------------------------------------------------

installing OpenMP

you dont need to install openmp. It is a compiler feature. Just execute your openmp C code using 
_gcc -fopenmp filename.c_

-------------------------------------------------------------

installing opencl

We will modify visual studio for openCL
refer to this video tutorial : https://youtu.be/YkoLrqO2kng

executing OpenCL C code on Linux: 
gcc filename.c -l /usr/local/cuda/include -L /usr/local/cuda/lib64 -fOpenMP

















