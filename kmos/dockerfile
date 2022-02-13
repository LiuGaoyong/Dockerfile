FROM  ubuntu:14.04

LABEL maintainer="LiuGaoyong <liugaoyong_88@163.com>"

RUN 	apt-get update &&\
	apt-get install -y software-properties-common \
			python-software-properties gfortran\
			python-dev python-lxml python-numpy python-ase python-matplotlib &&\ 
	add-apt-repository ppa:campos-dev/campos && apt-get update &&\
	apt-get install -y gazpacho gfortran python-dev \
                     python-glade2 python-kiwi python-lxml \
                     python-matplotlib python-numpy python-ase \
                     python-pygoocanvas git 
    #git clone http://www.github.com/mhoffman/kmos kmos
