MUSIC (GCMC code) GPL
======

	gfortran version
	Ubuntu 18.04 LTS (64 bit)

## Unpack


*	tar zxvf music-4.0-gnu.tar.gz


*	tar zxvf music-4.0-gnu-O2.tar.gz


*	tar zxvf music-4.0-gnu-debug.tar.gz


## Compiling


*	cd music-4.0/src


*	cp ../drivers/music_gcmc.F90 music.F90


*	make clean


*	./makemake *.F90 *.F


*	make FC="gfortran" CMD="music_gcmc"


*	change "gcmc" to other calculation. e.g., mapmaker, post, md, etc


## Test


*	cd ~/music-4.0/tests

*	./testall


## Usage (examples)


*	~/music-4.0/music_gcmc ctr.file

