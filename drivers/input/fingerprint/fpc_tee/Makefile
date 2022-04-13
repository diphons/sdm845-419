ccflags-y += -mllvm -inline-threshold=15000
ccflags-y += -mllvm -inlinehint-threshold=10000
ifndef CONFIG_ARCH_SDM845
ifeq ($(CONFIG_BOARD_ALIOTH), y)
obj-$(CONFIG_FINGERPRINT_FPC_TEE) += fpc1020_tee_alioth.o
else
obj-$(CONFIG_FINGERPRINT_FPC_TEE) += fpc1020_tee.o
endif
endif
