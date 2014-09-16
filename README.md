# cmake-ffmpeg

CMake find module for FFmpeg based on COMPONENTS.

## Usage

````cmake
find_package(FFmpeg REQUIRED)
include_directories(${FFmpeg_INCLUDE_DIRS})

# Then link with ${FFmpeg_LIBRARIES}
````

## License

The cmake find module is licensed under the zlib license (see source file).
