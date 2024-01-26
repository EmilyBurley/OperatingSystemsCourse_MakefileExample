# Operating Systems Course  
## Makefile Example  

### Explanation given by the professor:  

Instead of running  

> gcc –Wall –c main.c  
> > gcc -Wall -c f1.c  
> > > gcc -Wall -o test main.o f1.o  

you could run  

> make  

to compile and link in generating the executable file "test".  
