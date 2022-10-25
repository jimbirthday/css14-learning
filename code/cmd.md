g++ -o main main.cc
g++ -E test.cpp -o test.i  #预处理过程
g++ -S test.i -o test.s  #编译过程