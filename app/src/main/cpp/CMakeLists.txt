cmake_minimum_required(VERSION 3.4.1)

add_library(raw SHARED
        Native.cc)

# Include libraries needed for hello-jni lib
target_link_libraries(raw
                      android
                      log)
