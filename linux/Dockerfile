FROM fedora:36

WORKDIR /godot

RUN dnf -y install git scons pkgconfig libX11-devel libXcursor-devel libXrandr-devel libXinerama-devel \
    libXi-devel mesa-libGL-devel mesa-libGLU-devel alsa-lib-devel pulseaudio-libs-devel \
    libudev-devel yasm gcc-c++ libstdc++-static libatomic-static

CMD /bin/bash