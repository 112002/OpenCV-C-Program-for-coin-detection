# OpenCV-C-Program-for-coin-detection
Things to know:  The code will only compile in Linux environment. To run in windows, please use the file: ‘coin.o’ and run it in cmd. However if it does not run(problem in system architecture) then compile it in windows by making suitable and obvious changes to the code like: Use in place of . Compile command: g++ -w coin.cpp -o coin.exe `pkg-config –libs opencv` Run command: ./coin The image containing coin/coins has to be in the same directory as the code. Before you run the code, please make sure that you have OpenCV installed on your // system.
#include "opencv2/highgui/highgui.hpp"
// highgui - an interface to video and image capturing.
