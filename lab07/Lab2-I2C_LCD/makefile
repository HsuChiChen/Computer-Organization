# Application name
APPL ?= IIC_LCD

BOARD=iotdk
TOOLCHAIN=gnu

#
# root dir of embARC
#
EMBARC_ROOT = ../

MID_SEL = common

# application source dirs
APPL_CSRC_DIR = .
APPL_ASMSRC_DIR = .

# application include dirs
APPL_INC_DIR = .
OLEVEL=Og

# include current project makefile
COMMON_COMPILE_PREREQUISITES += makefile

### Options above must be added before include options.mk ###
# include key embARC build system makefile
include $(EMBARC_ROOT)/options/options.mk