#########################################################################
#                                                                       #
# Copyright 2014 Adobe Systems Incorporated.                       #
# All rights reserved.                                                  #
#                                                                       #
#########################################################################

# Configuration
CONFIG = release
CFLAGS = $(STD_OPTS)
# Library
ROOT_DIR = $(realpath ../../../../..)
SRC_DIR = $(ROOT_DIR)/source/t1write

LIB_SRCS = $(SRC_DIR)/t1write.c
LIB_OBJS = t1write.o
LIB_TARGET = $(LIB_DIR)/t1write.a

# Build targets
TARGETS = $(LIB_TARGET)

# Standard definitions
include $(realpath ../../../../../config/linux/gcc/gcc_tx.mak)

# Object rules
t1write.o:
	$(CC) $(CFLAGS) -c $(SRC_DIR)/t1write.c -o $@
