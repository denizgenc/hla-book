all: build clean
	make build
	make clean

build:
	hla section_1.9.2_if_statement.hla
	mv section_1.9.2_if_statement bin # Note missing `.hla` - this is the binary
	hla section_1.9.3_boolean_operators.hla
	mv section_1.9.3_boolean_operators bin


clean:
	rm *.o
