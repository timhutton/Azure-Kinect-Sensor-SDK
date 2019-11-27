# Copyright (c) Microsoft Corporation. All rights reserved.
# Licensed under the MIT License.
add_executable(tango main.cpp)
target_include_directories( tango PRIVATE ${OpenCV_INCLUDE_DIRS} )
target_link_libraries(tango PRIVATE k4a::k4a ${OpenCV_LIBS})
