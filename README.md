## C++11 CMake Macros

The macros included in `CXX11.cmake` can be used for checking for and enabling C++11 support in a CMake project. These macros are still a work-in-progress.

### Documentation

The usage of the macros is described below:

* **check_for_cxx11_compiler(VAR)**  
   *determines whether the current compiler supports C++11*
 
   Parameters:
   - a variable that will be set to 1 if the compiler supports C++11

* **enable_cxx11()**  
   *sets the appropriate compiler flags to enable C++11*

