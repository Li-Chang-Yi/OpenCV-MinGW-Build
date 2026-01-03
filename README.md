# OpenCV-MinGW-Build
Which platform to used on： **Windows_x64**

Ref: https://github.com/huihut/OpenCV-MinGW-Build

MinGW 64bit version of OpenCV compiled on Windows.

## Releases

### [opencv-4.13.0-x64](https://github.com/Li-Chang-Yi/OpenCV-MinGW-Build/releases/tag/4.12.0-x64-with-contrib) | [zip](https://github.com/Li-Chang-Yi/OpenCV-MinGW-Build/releases/download/opencv-4.13.0-x64/opencv-4.13.0-x64.zip)

<details><summary>Configuration</summary> 

* Timestamp:                   2026-01-03T11:50:11Z
* Host:                        Windows 10.0.22621 AMD64
* CMake:                       3.31.9
* CMake generator:             MinGW Makefiles
* CMake build tool:            D:/Install/x86_64-15.2.0-release-posix-seh-ucrt-rt_v13-rev0/mingw64/bin/mingw32-make.exe
* Configuration:               Release

```
General configuration for OpenCV 4.13.0 =====================================
  Version control:               unknown

  Extra modules:
    Location (extra):            E:/Download/opencv4.13.0/opencv_contrib-4.13.0/modules
    Version control (extra):     unknown

  Platform:
    Timestamp:                   2026-01-03T11:50:11Z
    Host:                        Windows 10.0.22621 AMD64
    CMake:                       3.31.9
    CMake generator:             MinGW Makefiles
    CMake build tool:            D:/Install/x86_64-15.2.0-release-posix-seh-ucrt-rt_v13-rev0/mingw64/bin/mingw32-make.exe
    Configuration:               Release
    Algorithm Hint:              ALGO_HINT_ACCURATE

  CPU/HW features:
    Baseline:                    SSE SSE2 SSE3
      requested:                 SSE3
    Dispatched code generation:  SSE4_1 SSE4_2 AVX FP16 AVX2 AVX512_SKX
      SSE4_1 (17 files):         + SSSE3 SSE4_1
      SSE4_2 (1 files):          + SSSE3 SSE4_1 POPCNT SSE4_2
      AVX (9 files):             + SSSE3 SSE4_1 POPCNT SSE4_2 AVX
      FP16 (0 files):            + SSSE3 SSE4_1 POPCNT SSE4_2 AVX FP16
      AVX2 (37 files):           + SSSE3 SSE4_1 POPCNT SSE4_2 AVX FP16 AVX2 FMA3
      AVX512_SKX (7 files):      + SSSE3 SSE4_1 POPCNT SSE4_2 AVX FP16 AVX2 FMA3 AVX_512F AVX512_COMMON AVX512_SKX

  C/C++:
    Built as dynamic libs?:      YES
    C++ standard:                11
    C++ Compiler:                D:/Install/x86_64-15.2.0-release-posix-seh-ucrt-rt_v13-rev0/mingw64/bin/g++.exe  (ver 15.2.0)
    C++ flags (Release):         -fsigned-char -W -Wall -Wreturn-type -Wnon-virtual-dtor -Waddress -Wsequence-point -Wformat -Wformat-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Wsuggest-override -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -fvisibility=hidden -fvisibility-inlines-hidden -O3 -DNDEBUG  -DNDEBUG
    C++ flags (Debug):           -fsigned-char -W -Wall -Wreturn-type -Wnon-virtual-dtor -Waddress -Wsequence-point -Wformat -Wformat-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Wsuggest-override -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -fvisibility=hidden -fvisibility-inlines-hidden -g  -O0 -DDEBUG -D_DEBUG
    C Compiler:                  D:/Install/x86_64-15.2.0-release-posix-seh-ucrt-rt_v13-rev0/mingw64/bin/gcc.exe
    C flags (Release):           -fsigned-char -W -Wall -Wreturn-type -Waddress -Wsequence-point -Wformat -Wformat-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -fvisibility=hidden -O3 -DNDEBUG  -DNDEBUG
    C flags (Debug):             -fsigned-char -W -Wall -Wreturn-type -Waddress -Wsequence-point -Wformat -Wformat-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -fvisibility=hidden -g  -O0 -DDEBUG -D_DEBUG
    Linker flags (Release):      -Wl,--gc-sections  
    Linker flags (Debug):        -Wl,--gc-sections  
    ccache:                      NO
    Precompiled headers:         NO
    Extra dependencies:          pthread
    3rdparty dependencies:

  OpenCV modules:
    To be built:                 aruco bgsegm bioinspired calib3d ccalib core datasets dnn dnn_objdetect dnn_superres dpm face features2d flann fuzzy gapi hfs highgui img_hash imgcodecs imgproc intensity_transform line_descriptor mcc ml objdetect optflow phase_unwrapping photo plot quality rapid reg rgbd saliency shape signal stereo stitching structured_light superres surface_matching text tracking ts video videoio videostab wechat_qrcode world xfeatures2d ximgproc xobjdetect xphoto
    Disabled:                    java_bindings_generator python_bindings_generator python_tests
    Disabled by dependency:      -
    Unavailable:                 alphamat cannops cudaarithm cudabgsegm cudacodec cudafeatures2d cudafilters cudaimgproc cudalegacy cudaobjdetect cudaoptflow cudastereo cudawarping cudev cvv fastcv freetype hdf java julia matlab ovis python2 python3 sfm viz
    Applications:                apps
    Documentation:               NO
    Non-free algorithms:         NO

  Windows RT support:            NO

  GUI: 
    Win32 UI:                    YES
    VTK support:                 NO

  Media I/O: 
    ZLib:                        build (ver 1.3.1)
    JPEG:                        build-libjpeg-turbo (ver 3.1.2-70)
      SIMD Support Request:      YES
      SIMD Support:              NO
    WEBP:                        build (ver decoder: 0x0210, encoder: 0x0210, demux: 0x0107)
    AVIF:                        NO
    PNG:                         build (ver 1.6.53)
      SIMD Support Request:      YES
      SIMD Support:              YES (Intel SSE)
    TIFF:                        build (ver 42 - 4.7.1)
    JPEG 2000:                   build (ver 2.5.3)
    OpenEXR:                     build (ver 2.3.0)
    GIF:                         YES
    HDR:                         YES
    SUNRASTER:                   YES
    PXM:                         YES
    PFM:                         YES

  Video I/O:
    FFMPEG:                      YES (prebuilt binaries)
      avcodec:                   YES (58.134.100)
      avformat:                  YES (58.76.100)
      avutil:                    YES (56.70.100)
      swscale:                   YES (5.9.100)
      avdevice:                  NO
    GStreamer:                   NO
    DirectShow:                  YES
    Orbbec:                      NO

  Parallel framework:            pthreads

  Trace:                         YES (built-in)

  Other third-party libraries:
    Lapack:                      NO
    Eigen:                       NO
    Custom HAL:                  NO
    Protobuf:                    build (3.19.1)
    Flatbuffers:                 builtin/3rdparty (25.9.23)

  OpenCL:                        YES (NVD3D11)
    Include path:                E:/Download/opencv4.13.0/opencv-4.13.0/3rdparty/include/opencl/1.2
    Link libraries:              Dynamic load

  Python (for build):            D:/Install/miniforge3/python.exe

  Install to:                    E:/Download/opencv4.13.0/build/install
-----------------------------------------------------------------
```

</details>

### [opencv-4.12.0-mingw810-x64-with-contrib](https://github.com/Li-Chang-Yi/OpenCV-MinGW-Build/releases/tag/4.12.0-x64-with-contrib) | [zip](https://github.com/Li-Chang-Yi/OpenCV-MinGW-Build/releases/download/4.12.0-x64-with-contrib/opencv-4.12.0-mingw810-x64-with-contrib.zip)

<details><summary>Configuration</summary> 


* mingw810_64
* Windows11_x64_23H2-22631.4460
* CMake-3.31.9

```
General configuration for OpenCV 4.12.0 =====================================
  Version control:               unknown

  Extra modules:
    Location (extra):            D:/Install/OpenCV/opencv_contrib-4.12.0/modules
    Version control (extra):     unknown

  Platform:
    Timestamp:                   2025-10-10T03:24:06Z
    Host:                        Windows 10.0.22631 AMD64
    CMake:                       3.31.9
    CMake generator:             MinGW Makefiles
    CMake build tool:            D:/Install/Qt5.15.2/Tools/mingw810_64/bin/mingw32-make.exe
    Configuration:               Release
    Algorithm Hint:              ALGO_HINT_ACCURATE

  CPU/HW features:
    Baseline:                    SSE SSE2 SSE3
      requested:                 SSE3
    Dispatched code generation:  SSE4_1 SSE4_2 AVX FP16 AVX2
      requested:                 SSE4_1 SSE4_2 AVX FP16 AVX2 AVX512_SKX
      SSE4_1 (17 files):         + SSSE3 SSE4_1
      SSE4_2 (1 files):          + SSSE3 SSE4_1 POPCNT SSE4_2
      AVX (9 files):             + SSSE3 SSE4_1 POPCNT SSE4_2 AVX
      FP16 (0 files):            + SSSE3 SSE4_1 POPCNT SSE4_2 AVX FP16
      AVX2 (37 files):           + SSSE3 SSE4_1 POPCNT SSE4_2 AVX FP16 AVX2 FMA3

  C/C++:
    Built as dynamic libs?:      YES
    C++ standard:                11
    C++ Compiler:                D:/Install/Qt5.15.2/Tools/mingw810_64/bin/g++.exe  (ver 8.1.0)
    C++ flags (Release):         -fsigned-char -W -Wall -Wreturn-type -Wnon-virtual-dtor -Waddress -Wsequence-point -Wformat -Wformat-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Wsuggest-override -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -fvisibility=hidden -fvisibility-inlines-hidden -O3 -DNDEBUG  -DNDEBUG
    C++ flags (Debug):           -fsigned-char -W -Wall -Wreturn-type -Wnon-virtual-dtor -Waddress -Wsequence-point -Wformat -Wformat-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Wsuggest-override -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -fvisibility=hidden -fvisibility-inlines-hidden -g  -O0 -DDEBUG -D_DEBUG
    C Compiler:                  D:/Install/Qt5.15.2/Tools/mingw810_64/bin/gcc.exe
    C flags (Release):           -fsigned-char -W -Wall -Wreturn-type -Waddress -Wsequence-point -Wformat -Wformat-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -fvisibility=hidden -O3 -DNDEBUG  -DNDEBUG
    C flags (Debug):             -fsigned-char -W -Wall -Wreturn-type -Waddress -Wsequence-point -Wformat -Wformat-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -fomit-frame-pointer -ffunction-sections -fdata-sections  -fvisibility=hidden -g  -O0 -DDEBUG -D_DEBUG
    Linker flags (Release):      -Wl,--gc-sections  
    Linker flags (Debug):        -Wl,--gc-sections  
    ccache:                      NO
    Precompiled headers:         NO
    Extra dependencies:          pthread
    3rdparty dependencies:

  OpenCV modules:
    To be built:                 aruco bgsegm bioinspired calib3d ccalib core datasets dnn dnn_objdetect dnn_superres dpm face features2d flann fuzzy gapi hfs highgui img_hash imgcodecs imgproc intensity_transform line_descriptor mcc ml objdetect optflow phase_unwrapping photo plot quality rapid reg rgbd saliency shape signal stereo stitching structured_light superres surface_matching text tracking ts video videoio videostab wechat_qrcode world xfeatures2d ximgproc xobjdetect xphoto
    Disabled:                    java_bindings_generator python_bindings_generator python_tests
    Disabled by dependency:      -
    Unavailable:                 alphamat cannops cudaarithm cudabgsegm cudacodec cudafeatures2d cudafilters cudaimgproc cudalegacy cudaobjdetect cudaoptflow cudastereo cudawarping cudev cvv fastcv freetype hdf java julia matlab ovis python2 python3 sfm viz
    Applications:                apps
    Documentation:               NO
    Non-free algorithms:         NO

  Windows RT support:            NO

  GUI: 
    Win32 UI:                    YES
    VTK support:                 NO

  Media I/O: 
    ZLib:                        build (ver 1.3.1)
    JPEG:                        build-libjpeg-turbo (ver 3.1.0-70)
      SIMD Support Request:      YES
      SIMD Support:              NO
    WEBP:                        build (ver decoder: 0x0209, encoder: 0x020f, demux: 0x0107)
    AVIF:                        NO
    PNG:                         build (ver 1.6.43)
      SIMD Support Request:      YES
      SIMD Support:              YES (Intel SSE)
    TIFF:                        build (ver 42 - 4.6.0)
    JPEG 2000:                   build (ver 2.5.3)
    OpenEXR:                     build (ver 2.3.0)
    GIF:                         YES
    HDR:                         YES
    SUNRASTER:                   YES
    PXM:                         YES
    PFM:                         YES

  Video I/O:
    FFMPEG:                      YES (prebuilt binaries)
      avcodec:                   YES (58.134.100)
      avformat:                  YES (58.76.100)
      avutil:                    YES (56.70.100)
      swscale:                   YES (5.9.100)
      avresample:                YES (4.0.0)
    GStreamer:                   NO
    DirectShow:                  YES

  Parallel framework:            pthreads

  Trace:                         YES (built-in)

  Other third-party libraries:
    Lapack:                      NO
    Eigen:                       NO
    Custom HAL:                  NO
    Protobuf:                    build (3.19.1)
    Flatbuffers:                 builtin/3rdparty (23.5.9)

  OpenCL:                        YES (NVD3D11)
    Include path:                D:/Install/OpenCV/opencv-4.12.0/3rdparty/include/opencl/1.2
    Link libraries:              Dynamic load

  Python (for build):            NO

  Install to:                    D:/Install/OpenCV/opencv-4.12.0-mingw810_64/install
-----------------------------------------------------------------
```

</details>

### [opencv-4.10.0-mingw730-x64-with-contrib](https://github.com/Li-Chang-Yi/OpenCV-MinGW-Build/releases/tag/4.10.0-x64-with-contrib) | [zip](https://github.com/Li-Chang-Yi/OpenCV-MinGW-Build/releases/download/4.12.0-x64-with-contrib/opencv-4.12.0-mingw810-x64-with-contrib.zip)

<details><summary>Configuration</summary> 

* mingw730_64
* Windows-11-64bit-22000.2538
* CMake-3.31.3

```
General configuration for OpenCV 4.10.0 =====================================
  Version control:               unknown

  Extra modules:
    Location (extra):            D:/OpenCV/opencv_contrib-4.10.0/modules
    Version control (extra):     unknown

  Platform:
    Timestamp:                   2025-01-04T07:40:07Z
    Host:                        Windows 10.0.22000 AMD64
    CMake:                       3.31.3
    CMake generator:             MinGW Makefiles
    CMake build tool:            D:/Qt/Qt5.12.12/Tools/mingw730_64/bin/mingw32-make.exe
    Configuration:               Release

  CPU/HW features:
    Baseline:                    SSE SSE2 SSE3
      requested:                 SSE3
    Dispatched code generation:  SSE4_1 SSE4_2 FP16 AVX AVX2
      requested:                 SSE4_1 SSE4_2 AVX FP16 AVX2 AVX512_SKX
      SSE4_1 (16 files):         + SSSE3 SSE4_1
      SSE4_2 (1 files):          + SSSE3 SSE4_1 POPCNT SSE4_2
      FP16 (0 files):            + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 AVX
      AVX (8 files):             + SSSE3 SSE4_1 POPCNT SSE4_2 AVX
      AVX2 (36 files):           + SSSE3 SSE4_1 POPCNT SSE4_2 FP16 FMA3 AVX AVX2

  C/C++:
    Built as dynamic libs?:      YES
    C++ standard:                11
    C++ Compiler:                D:/Qt/Qt5.12.12/Tools/mingw730_64/bin/g++.exe  (ver 7.3.0)
    C++ flags (Release):         -fsigned-char -W -Wall -Wreturn-type -Wnon-virtual-dtor -Waddress -Wsequence-point -Wformat -Wformat-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Wsuggest-override -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -fopenmp -O3 -DNDEBUG  -DNDEBUG
    C++ flags (Debug):           -fsigned-char -W -Wall -Wreturn-type -Wnon-virtual-dtor -Waddress -Wsequence-point -Wformat -Wformat-security -Wmissing-declarations -Wundef -Winit-self -Wpointer-arith -Wshadow -Wsign-promo -Wuninitialized -Wsuggest-override -Wno-delete-non-virtual-dtor -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fvisibility-inlines-hidden -fopenmp -g  -O0 -DDEBUG -D_DEBUG
    C Compiler:                  D:/Qt/Qt5.12.12/Tools/mingw730_64/bin/gcc.exe
    C flags (Release):           -fsigned-char -W -Wall -Wreturn-type -Waddress -Wsequence-point -Wformat -Wformat-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fopenmp -O3 -DNDEBUG  -DNDEBUG
    C flags (Debug):             -fsigned-char -W -Wall -Wreturn-type -Waddress -Wsequence-point -Wformat -Wformat-security -Wmissing-declarations -Wmissing-prototypes -Wstrict-prototypes -Wundef -Winit-self -Wpointer-arith -Wshadow -Wuninitialized -Wno-comment -Wimplicit-fallthrough=3 -Wno-strict-overflow -fdiagnostics-show-option -Wno-long-long -fomit-frame-pointer -ffunction-sections -fdata-sections  -msse -msse2 -msse3 -fvisibility=hidden -fopenmp -g  -O0 -DDEBUG -D_DEBUG
    Linker flags (Release):      -Wl,--gc-sections  
    Linker flags (Debug):        -Wl,--gc-sections  
    ccache:                      NO
    Precompiled headers:         NO
    Extra dependencies:          pthread
    3rdparty dependencies:

  OpenCV modules:
    To be built:                 aruco bgsegm bioinspired calib3d ccalib core cvv datasets dnn dnn_objdetect dnn_superres dpm face features2d flann fuzzy gapi hfs highgui img_hash imgcodecs imgproc intensity_transform line_descriptor mcc ml objdetect optflow phase_unwrapping photo plot python3 quality rapid reg rgbd saliency shape signal stereo stitching structured_light superres surface_matching text tracking ts video videoio videostab wechat_qrcode xfeatures2d ximgproc xobjdetect xphoto
    Disabled:                    java_bindings_generator python_tests world
    Disabled by dependency:      -
    Unavailable:                 alphamat cannops cudaarithm cudabgsegm cudacodec cudafeatures2d cudafilters cudaimgproc cudalegacy cudaobjdetect cudaoptflow cudastereo cudawarping cudev freetype hdf java julia matlab ovis python2 sfm viz
    Applications:                apps
    Documentation:               NO
    Non-free algorithms:         YES

  Windows RT support:            NO

  GUI:                           QT5
    QT:                          YES (ver 5.12.12 )
      QT OpenGL support:         YES (Qt5::OpenGL 5.12.12)
    Win32 UI:                    YES
    OpenGL support:              YES (opengl32 glu32)
    VTK support:                 NO

  Media I/O: 
    ZLib:                        build (ver 1.3.1)
    JPEG:                        build-libjpeg-turbo (ver 3.0.3-70)
      SIMD Support Request:      YES
      SIMD Support:              NO
    WEBP:                        build (ver encoder: 0x020f)
    PNG:                         build (ver 1.6.43)
      SIMD Support Request:      YES
      SIMD Support:              YES (Intel SSE)
    TIFF:                        build (ver 42 - 4.6.0)
    JPEG 2000:                   build (ver 2.5.0)
    OpenEXR:                     build (ver 2.3.0)
    HDR:                         YES
    SUNRASTER:                   YES
    PXM:                         YES
    PFM:                         YES

  Video I/O:
    DC1394:                      NO
    FFMPEG:                      YES (prebuilt binaries)
      avcodec:                   YES (58.134.100)
      avformat:                  YES (58.76.100)
      avutil:                    YES (56.70.100)
      swscale:                   YES (5.9.100)
      avresample:                YES (4.0.0)
    GStreamer:                   NO
    DirectShow:                  YES

  Parallel framework:            OpenMP

  Trace:                         YES (built-in)

  Other third-party libraries:
    Lapack:                      NO
    Eigen:                       NO
    Custom HAL:                  NO
    Protobuf:                    build (3.19.1)
    Flatbuffers:                 builtin/3rdparty (23.5.9)

  OpenCL:                        YES (NVD3D11)
    Include path:                D:/OpenCV/opencv-4.10.0/3rdparty/include/opencl/1.2
    Link libraries:              Dynamic load

  Python 3:
    Interpreter:                 D:/Anaconda3/python.exe (ver 3.8.8)
    Libraries:                   D:/Anaconda3/libs/python38.lib (ver 3.8.8)
    Limited API:                 NO
    numpy:                       D:/Anaconda3/lib/site-packages/numpy/core/include (ver 1.20.1)
    install path:                D:/Anaconda3/Lib/site-packages/cv2/python-3.8

  Python (for build):            D:/Anaconda3/python.exe

  Install to:                    D:/OpenCV/opencv-4.10.0/build-opencv4.10.0-mingw730-windows-x64/install
-----------------------------------------------------------------
```

</details>
