add_executable(ctests src/ctests.c)
add_executable(cpptests src/cpptests.cpp)

# include header files
target_include_directories(ctests PRIVATE ../include)
target_include_directories(cpptests PRIVATE ../include)

# set debug mode for -g
set(CMAKE_BUILD_TYPE Debug)
