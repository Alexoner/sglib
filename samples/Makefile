runall: arraysort arraysort1 arraybinsearch listsort \
        listinsertsort listinsertsort1 rbtree dllist \
        hash \
        selftest clean

CFLAGS=-g -Wall -I../src


arraysort: arraysort.c ../src/sglib.h
	$(CC) -o $@ $^ $(CFLAGS)
	./$@ 6 7 3 4 1 4 1 3 5

arraysort1: arraysort1.c ../src/sglib.h
	$(CC) -o $@ $^ $(CFLAGS)
	./$@ 6 7 3 4 1 4 1 3 5

arraybinsearch: arraybinsearch.c ../src/sglib.h
	$(CC) -o $@ $^ $(CFLAGS)
	./$@ 6 7 3 4 1 4 1 3 5

listsort: listsort.c ../src/sglib.h
	$(CC) -o $@ $^ $(CFLAGS)
	./$@ 6 7 3 4 1 4 1 3 5

dllist: dllist.c ../src/sglib.h
	$(CC) -o $@ $^ $(CFLAGS)
	./$@ 6 7 3 4 1 4 1 3 5

hash: hash.c ../src/sglib.h
	$(CC) -o $@ $^ $(CFLAGS)
	./$@  1 3 1 5 2 3 1 7 11 33 11

listinsertsort: listinsertsort.c ../src/sglib.h
	$(CC) -o $@ $^ $(CFLAGS)
	./$@ 6 7 3 4 1 4 1 3 5

listinsertsort1: listinsertsort1.c ../src/sglib.h
	$(CC) -o $@ $^ $(CFLAGS)
	./$@ 6 7 3 4 1 4 1 3 5

rbtree: rbtree.c ../src/sglib.h
	$(CC) -o $@ $^ $(CFLAGS)
	./$@ 6 7 3 4 1 4 1 3 5


selftest: selftest.c ../src/sglib.h
	$(CC) -o $@ $^ $(CFLAGS)
	./$@
	echo Done.

clean:;
	rm -f ./$@

