FROM diplodocusdb/gcc-diplodocusdb:0.4.0

WORKDIR /nemu/cpp

RUN git clone https://github.com/nemu-cpp/core.git
RUN cd core/build/gnumake && make

WORKDIR /
