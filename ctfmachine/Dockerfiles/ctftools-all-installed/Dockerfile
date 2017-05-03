FROM ctftools-orig

RUN bash -ic "manage-tools -s install afl"
RUN bash -ic "manage-tools -s install android-sdk"
### RUN bash -ic "manage-tools -s install angr" # ???? FIXME
RUN bash -ic "manage-tools -s install apktool"
RUN bash -ic "manage-tools -s install barf"
### RUN bash -ic "manage-tools -s install beef" ### Need to get ruby with RVM... Unsupported for now
### RUN bash -ic "manage-tools -s install bin"
RUN bash -ic "manage-tools -s install bindead"
RUN bash -ic "manage-tools -s install binwalk"
RUN bash -ic "manage-tools -s install burpsuite"
RUN bash -ic "manage-tools -s install capstone"
RUN bash -ic "manage-tools -s install checksec"
RUN bash -ic "manage-tools -s install codereason" ### >>>>>> FIXME
RUN bash -ic "manage-tools -s install commix"
RUN bash -ic "manage-tools -s install cribdrag"
### RUN bash -ic "manage-tools -s install cross2"
### RUN bash -ic "manage-tools -s install crosstool"
RUN bash -ic "manage-tools -s install df"
RUN bash -ic "manage-tools -s install dirb"
RUN bash -ic "manage-tools -s install dirsearch"
RUN bash -ic "manage-tools -s install dislocker"
RUN bash -ic "manage-tools -s install elfkickers"
RUN bash -ic "manage-tools -s install elfparser"
RUN bash -ic "manage-tools -s install evilize"
RUN bash -ic "manage-tools -s install exetractor"
RUN bash -ic "manage-tools -s install featherduster"
RUN bash -ic "manage-tools -s install firmware-mod-kit"
RUN bash -ic "manage-tools -s install foresight"
RUN bash -ic "manage-tools -s install gdb"
RUN bash -ic "manage-tools -s install gdb-heap"
RUN bash -ic "manage-tools -s install gef"
RUN bash -ic "manage-tools -s install hash-identifier"
RUN bash -ic "manage-tools -s install hashkill"
RUN bash -ic "manage-tools -s install hashpump"
RUN bash -ic "manage-tools -s install hashpump-partialhash"
RUN bash -ic "manage-tools -s install honggfuzz"
RUN bash -ic "manage-tools -s install jdgui"
RUN bash -ic "manage-tools -s install keystone"
RUN bash -ic "manage-tools -s install libheap"
RUN bash -ic "manage-tools -s install littleblackbox"
RUN bash -ic "manage-tools -s install mitmproxy"
RUN bash -ic "manage-tools -s install msieve"
### RUN bash -ic "manage-tools -s install panda"  ### compilation errors
### RUN bash -ic "manage-tools -s install pathgrind" ### only for kernels 2.4 and 2.6
RUN bash -ic "manage-tools -s install pdf-parser"
RUN bash -ic "manage-tools -s install peda"
RUN bash -ic "manage-tools -s install peepdf"
RUN bash -ic "manage-tools -s install pemcrack"
RUN bash -ic "manage-tools -s install pkcrack"
RUN bash -ic "manage-tools -s install preeny"
RUN bash -ic "manage-tools -s install pwndbg"
RUN bash -ic "manage-tools -s install pwntools"
RUN bash -ic "manage-tools -s install python-paddingoracle"
RUN bash -ic "manage-tools -s install python-pin"
RUN bash -ic "manage-tools -s install pyvmmonitor"
RUN bash -ic "manage-tools -s install qemu"
RUN bash -ic "manage-tools -s install qira"
RUN bash -ic "manage-tools -s install radare2"
RUN bash -ic "manage-tools -s install reveng"
RUN bash -ic "manage-tools -s install ropper"
RUN bash -ic "manage-tools -s install rp++"
RUN bash -ic "manage-tools -s install scrdec18"
RUN bash -ic "manage-tools -s install shellnoob"
RUN bash -ic "manage-tools -s install shellsploit"
RUN bash -ic "manage-tools -s install snowman"
### RUN bash -ic "manage-tools -s install sonic-visualizer" ### build errors
RUN bash -ic "manage-tools -s install sqlmap"
RUN bash -ic "manage-tools -s install ssh_decoder"
RUN bash -ic "manage-tools -s install sslsplit"
RUN bash -ic "manage-tools -s install steganabara"
RUN bash -ic "manage-tools -s install stegdetect"
RUN bash -ic "manage-tools -s install stegsolve"
RUN bash -ic "manage-tools -s install subbrute"
### RUN bash -ic "manage-tools -s install taintgrind" ### missing Iop_* declarations
RUN bash -ic "manage-tools -s install testdisk"
RUN bash -ic "manage-tools -s install tor-browser"
RUN bash -ic "manage-tools -s install uncompyle2"
RUN bash -ic "manage-tools -s install uncompyle6"
RUN bash -ic "manage-tools -s install unicorn"
### RUN bash -ic "manage-tools -s install veles" ### Cmake is too old
RUN bash -ic "manage-tools -s install villoc"
RUN bash -ic "manage-tools -s install virtualsocket"
### RUN bash -ic "manage-tools -s install wcc" ### depends on xenial
RUN bash -ic "manage-tools -s install xortool"
RUN bash -ic "manage-tools -s install xrop"
RUN bash -ic "manage-tools -s install xspy"
RUN bash -ic "manage-tools -s install yafu"
RUN bash -ic "manage-tools -s install z3"
RUN bash -ic "manage-tools -s install zsteg"



RUN sudo apt-get update && sudo apt-get install -y ltrace \
	strace \
	vim \
	gdb \
	man \
	openjdk-7-jre \
	tcpdump \
	tshark \
	libc6-i386 \
	pngcheck \
	pngmeta \
	libx32gcc-4.8-dev \
	libc6-dev-i386 \
	ipython \
	ipython3
