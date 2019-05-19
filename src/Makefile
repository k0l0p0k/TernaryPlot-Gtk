
CC = gcc

#CFLAGS = -Wall			 	\
#	-DG_DISABLE_DEPRECATED 	 	\
#	-DGDK_DISABLE_DEPRECATED 	\
#	-DGDK_PIXBUF_DISABLE_DEPRECATED \
#	-DGTK_DISABLE_DEPRECATED

CFLAGS = -lm 
	
ternaryplot: main.c ternaryplot.h ternaryplot.c 
	$(CC) main.c ternaryplot.c  -o ternaryplot $(CFLAGS) `pkg-config gtk+-2.0 --cflags --libs`	
	
clean: 
	rm -f *.o ternaryplot
