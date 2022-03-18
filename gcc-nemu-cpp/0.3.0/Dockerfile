FROM diplodocusdb/gcc-diplodocusdb:0.7.0

ENV NEMU_CPP=/nemu/cpp

WORKDIR /nemu/cpp

RUN git clone https://github.com/nemu-cpp/core.git
RUN cd core/build/gnumake && make

RUN git clone https://github.com/nemu-cpp/ishiko-connection-engine.git
RUN cd ishiko-connection-engine/build/gnumake && make

RUN git clone https://github.com/nemu-cpp/mustache-templating-engine.git
RUN cd mustache-templating-engine/build/gnumake && make

RUN git clone https://github.com/nemu-cpp/nemu.git

WORKDIR /
