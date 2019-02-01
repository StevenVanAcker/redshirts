FROM ubuntu:latest

USER root
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
	libx32gcc-4.8-dev \
	libc6-dev-i386 \
	libffi-dev \
	build-essential \
	ipython \
	ipython3

RUN pip install pwn

