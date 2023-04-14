project(image_read)

cmake_minimum_required(VERSION 2.8)

# find_package(OpenCV REQUIRED)
# message(STATUS "OpenCV library status:")
# message(STATUS "    version: ${OpenCV_VERSION}")
# message(STATUS "    libraries: ${OpenCV_LIBS}")
# message(STATUS "    include path: ${OpenCV_INCLUDE_DIRS}")

# add_library(decoder decoder.h decoder.cpp)
# add_executable(readimg readimg.cpp)
add_executable(cpu_memo cpu_memo.cpp)
# Link your application with OpenCV libraries
# target_link_libraries(readimg ${OpenCV_LIBS})
# target_link_libraries(cpu_memo)