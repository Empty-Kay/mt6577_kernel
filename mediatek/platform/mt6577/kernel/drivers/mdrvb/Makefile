#######################################
# Sepcify source files
#######################################
include $(MTK_PATH_BUILD)/Makefile

lib_obj := src/mtk_drvb_mod.o
#lib_obj += $(call my-dir)/prebuilt/sec_drvb.o
obj-m += mtk_drvb.o

# HEADER FILES
EXTRA_CFLAGS += -I$(src) -I$(src)/inc
EXTRA_CFLAGS += -fno-pic

# INCLUDE DRVB LIBRARY	
mtk_drvb-y += $(lib_obj)
