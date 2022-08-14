ifneq ($(filter y, $(CONFIG_MACH_XIAOMI_K11A) $(CONFIG_MACH_XIAOMI_L11R)),)
obj-$(CONFIG_FINGERPRINT_FPC_TEE) += fpc1020_tee_old.o
else
obj-$(CONFIG_FINGERPRINT_FPC_TEE) += fpc1020_tee.o
endif
