include_directories(common)
include_directories(geometry)
if (USE_CUDA)
    include_directories(CUDA)
endif ()