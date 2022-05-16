FROM diplodocusdb/gcc-diplodocusdb:0.16.0

ENV NEMU_CPP=/nemu/cpp

WORKDIR /nemu/cpp

RUN git clone https://github.com/nemu-cpp/core.git
RUN cd core/build/gnumake && make

RUN git clone https://github.com/nemu-cpp/web-framework.git
RUN cd web-framework/build/gnumake && make

RUN git clone https://github.com/nemu-cpp/mustache-template-engine.git
RUN cd mustache-template-engine/build/gnumake && make

RUN git clone https://github.com/nemu-cpp/nemu.git

WORKDIR /
