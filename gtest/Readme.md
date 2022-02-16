Gtest framework

sudo apt-get install libgtest-dev
sudo apt-get install cmake
cd /usr/src/gtest
sudo cmake CMakeLists.txt
sudo make
sudo cp *.a /usr/lib






touch sqrt.cpp
touch sqrt_test.cpp
touch CMakeLists.txt



cmake CMakeLists.txt
make
./executeTests