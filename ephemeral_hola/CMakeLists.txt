# CMakeList.txt : CMake project for ephemeral_hola, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (ephemeral_hola "ephemeral_hola.cpp" "ephemeral_hola.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET ephemeral_hola PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.