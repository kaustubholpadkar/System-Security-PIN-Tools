##############################################################
#
#                   DO NOT EDIT THIS FILE!
#
##############################################################


# export PIN_ROOT=/home/sekar/Downloads/pin-3.13-98189-g60a6ef199-gcc-linux
# export INTEL_JIT_PROFILER32=/home/sekar/Downloads/pin-3.13-98189-g60a6ef199-gcc-linux/ia32/lib/libpinjitprofiling.so
# export TOOLS_ROOT=/home/sekar/Downloads/pin-3.13-98189-g60a6ef199-gcc-linux/source/tools

# If the tool is built out of the kit, PIN_ROOT must be specified in the make invocation and point to the kit root.
ifdef PIN_ROOT
CONFIG_ROOT := $(PIN_ROOT)/source/tools/Config
else
CONFIG_ROOT := ../Config
endif
include $(CONFIG_ROOT)/makefile.config
include makefile.rules
include $(TOOLS_ROOT)/Config/makefile.default.rules

##############################################################
#
#                   DO NOT EDIT THIS FILE!
#
##############################################################
