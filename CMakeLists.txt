<<<<<<< HEAD
cmake_minimum_required(VERSION 3.10)

project(yaml)

file(GLOB_RECURSE src CONFIGURE_DEPENDS src/*.cpp src/*.h)

add_library(yaml STATIC ${src})
target_include_directories(yaml PUBLIC include)
target_compile_definitions(yaml PUBLIC YAML_CPP_STATIC_DEFINE)

=======
cmake_minimum_required(VERSION 3.10)

project(yaml)

file(GLOB_RECURSE src CONFIGURE_DEPENDS src/*.cpp src/*.h)

add_library(yaml STATIC ${src})
target_include_directories(yaml PUBLIC include)
target_compile_definitions(yaml PUBLIC YAML_CPP_STATIC_DEFINE)

>>>>>>> e3c70a9566816c86bf426dd6f4f1812feb43eded
