ifneq ($(strip $(TARGET_BUILD_VARIANT)),eng)
ccflags-y += -DDISABLE_FACTORY_MODE
endif
obj-$(CONFIG_MTK_BOOT) += BOOT_COMMON.o
BOOT_COMMON-$(CONFIG_MTK_BOOT) := mt_boot_common.o mt_boot.o
