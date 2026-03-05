# Makefile

main_temp_1: main.o temp.o 
	clang main.o temp.o  -o main_temp_1 -l m

main.o: main.c 
	clang -c main.c

temp.o: temp.c
	clang -c temp.c

clean :
	rm *.o main_temp_1

