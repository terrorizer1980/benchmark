FROM ubuntu:xenial-20210114

ENV DEBIAN_FRONTEND noninteractive

ADD ./install_dependencies.sh install_dependencies.sh
RUN bash ./install_dependencies.sh && rm ./install_dependencies.sh

USER root
CMD ["bash"]
