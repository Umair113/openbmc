# Copyright 2015-present Facebook. All Rights Reserved.
all: fpc-util

fpc-util: fpc-util.c 
	$(CC) -lpal -std=c99 -o $@ $^ $(LDFLAGS)

.PHONY: clean

clean:
	rm -rf *.o fpc-util
