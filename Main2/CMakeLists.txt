
set(ProjectName Main2)


add_executable (${ProjectName} "main.cpp" "main.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET ${ProjectName} PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
