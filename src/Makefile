#
# Mikael Elharrar
#	January 22, 2017
#
# Main makefile for apps. 
#
ifeq ($(RTE_SDK),)
$(error "Please define RTE_SDK environment variable")
endif

# Default target, can be overriden by command line or environment
RTE_TARGET ?= x86_64-native-linuxapp-gcc

include $(RTE_SDK)/mk/rte.vars.mk

DIRS-$(CONFIG_RTE_EXEC_ENV_LINUXAPP) += core

include $(RTE_SDK)/mk/rte.extsubdir.mk
