
fronton0 : fronton0.c winsuport.o winsuport.h
	gcc -Wall fronton0.c winsuport.o -o fronton0 -lcurses

fronton1 : fronton1.c winsuport.o winsuport.h
	gcc -Wall fronton1.c winsuport.o -o fronton1 -lcurses -lpthread

fronton2 : fronton2.c winsuport.o winsuport.h
	gcc fronton2.c winsuport.o -o fronto2 -lcurses -lpthread

winsuport.o : winsuport.c winsuport.h
	gcc -c winsuport.c -o winsuport.o
