FROM fedora:36

WORKDIR /godot

# Base dependencies for Godot Linux compilation
RUN dnf install scons pkgconfig libX11-devel libXcursor-devel libXrandr-devel libXinerama-devel \
    libXi-devel mesa-libGL-devel mesa-libGLU-devel alsa-lib-devel pulseaudio-libs-devel \
    libudev-devel yasm gcc-c++ libstdc++-static libatomic-static

# Extra dependencies for Windows Godot cross-compilation from Linux
RUN dnf install mingw64-gcc-c++ mingw64-winpthreads-static \
    mingw32-gcc-c++ mingw32-winpthreads-static

CMD /bin/bash
