# IT300-DAA-Project---Convex-Hull

To install opencv, please follow the following tutorial:
http://www.codebind.com/cpp-tutorial/install-opencv-ubuntu-cpp/

If the executable file is being used without compiling, it will need to be given execution access (Right click -> Properties -> Permissions).

---------------------------------------------------------------------------------

Object Outline (Sklansky): REQUIRES OPENCV
`
g++ main.cpp -o main \`pkg-config --cflags --libs opencv\`

./main test.jpeg
`

Divide and Conquer: REQUIRES C++ 11 AND ABOVE

g++ dac.cpp -o dac

./dac test.txt

Quickhull:

g++ quickhull.cpp -o quickhull

./quickhull test.txt

Graham Scan:

g++ graham_scan.cpp -o graham_scan

./graham_scan test.txt

Jarvis:

g++ jarvis.cpp -o jarvis

./jarvis test.txt
