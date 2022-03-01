FROM diplodocusdb/gcc-diplodocusdb:0.5.0

ENV NEMU_CPP=/nemu/cpp

WORKDIR /nemu/cpp

RUN git clone https://github.com/nemu-cpp/core.git
RUN cd core/build/gnumake && make

RUN git clone https://github.com/nemu-cpp/nemu.git

WORKDIR /
