FROM ubuntu:19.04

USER root
ENV DEBIAN_FRONTEND=noninteractive


RUN apt-get update && apt-get -y upgrade
RUN apt-get install -y ltrace \
	strace \
	vim \
	gdb \
	man \
	tcpdump \
	libc6-i386 \
	pngcheck \
	pngmeta \
	libc6-dev-i386 \
	libffi-dev \
	build-essential \
	libx32gcc-*-dev \
	ipython \
	ipython3 \
	python3-pip \
	python-pip  \
	git \
	wget \
	unzip \
	openjdk-11-jdk \
	tcptrace \
	netcat \
	libssl-dev \
	vim-python-jedi \
	clang \
	curl \
	sudo \
	fcrackzip \
	volatility \
	volatility-tools

RUN vim-addons install python-jedi

RUN pip install pwn
RUN cd /opt && git clone https://github.com/ALSchwalm/foresight.git && cd foresight && python3 setup.py install
RUN cd /opt && git clone https://github.com/Gallopsled/pwntools.git && cd pwntools && pip3 install .
RUN cd /opt && git clone https://gitlab.com/akihe/radamsa.git && cd radamsa && make && sudo make install
RUN cd /opt && git clone https://github.com/radare/radare2.git && cd /opt/radare2 && ./sys/install.sh
RUN cd /opt && git clone https://github.com/bwall/HashPump.git && cd /opt/HashPump && make && make install && pip install hashpumpy

RUN wget http://www.caesum.com/handbook/Stegsolve.jar -O /opt/stegsolve.jar

RUN pip3 install argon2-cffi websocket_client angr
