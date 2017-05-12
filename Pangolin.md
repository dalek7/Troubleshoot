# Installation
```
git clone https://github.com/stevenlovegrove/Pangolin.git
cd Pangolin
mkdir build
cd build
cmake ..
make -j

```

# Troubleshoot
## CMAKE
```
sudo apt-get install mesa-common-dev
sudo apt-get install freeglut3-dev
sudo apt-get install libglew-dev
```


```
Pangolin/build$ cmake ..
Build type not set (defaults to release)
-DCMAKE_BUILD_TYPE=Debug for debug
CMake Error at CMakeModules/FindGLEW.cmake:51 (MESSAGE):
  Could not find GLEW
Call Stack (most recent call first):
  src/CMakeLists.txt:162 (find_package)

-- Configuring incomplete, errors occurred!
See also "/home/seung/FL/toolkits/Pangolin/build/CMakeFiles/CMakeOutput.log".
```


```
 $ sudo apt-get install libglew-dev
```
See https://groups.google.com/forum/#!topic/autoware/45R9cjCFKVo



```
Build type not set (defaults to release)
-DCMAKE_BUILD_TYPE=Debug for debug
CMake Error at /usr/share/cmake-2.8/Modules/FindPackageHandleStandardArgs.cmake:108 (message):
  Could NOT find OpenGL (missing: OPENGL_gl_LIBRARY OPENGL_INCLUDE_DIR)
Call Stack (most recent call first):

```
-->
```
sudo apt-get install mesa-common-dev
sudo apt-get install freeglut3-dev
```
	


