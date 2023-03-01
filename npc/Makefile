all:
	verilator -Wall --cc --exe --build  ./csrc.main.cpp ./vsrc/example.v --trace 

sim:
	$(call git_commit, "sim RTL") # DO NOT REMOVE THIS LINE!!!
	

include ../Makefile
