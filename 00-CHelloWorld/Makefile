#Variable para el compilador 
CC = gcc

#Banderas para cumplir el estandar C23 q pide la consigna
CFLAGS = -std=c23

#Objetivo principal: compilar el archivo hello.c y crear el ejecutabble (.exe) "hello"
all:
		$(CC) $(CFLAGS) hello.c -o hello

#Objetivo extra: compilar y ejecutar todo de una vez
run: all
		./hello
