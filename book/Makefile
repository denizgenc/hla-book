all: build clean
	make build
	make clean

build:
	hla page002_helloWorld.hla
	mv page002_helloWorld bin # Note missing `.hla` - this is the binary
	hla page016_DemoMOVaddSUB.hla
	mv page016_DemoMOVaddSUB bin


clean:
	rm *.o
