FROM godot:latest

WORKDIR /godot

RUN dnf install scons pkgconfig libX11-devel libXcursor-devel libXrandr-devel libXinerama-devel \
    libXi-devel mesa-libGL-devel mesa-libGLU-devel alsa-lib-devel pulseaudio-libs-devel \
    libudev-devel yasm gcc-c++ libstdc++-static libatomic-static


CMD /bin/bash