include $(srctree)/drivers/misc/mediatek/Makefile.custom

ifeq ($(CONFIG_MTK_GF318),y)
obj-y	+= GF318/
endif
ifeq ($(CONFIG_MTK_GF516),y)
obj-y   += gf516m/
endif
ifeq ($(CONFIG_FINGERPRINT_GOODIX_GF_TEE),y)
obj-y	+=  gf/
endif
ifeq ($(CONFIG_FINGERPRINT_FPC1020),y)
obj-y	+=  fpc1020/
endif
ifeq ($(CONFIG_FINGERPRINT_FPC1020_TEE),y)
obj-y	+=  fpc1020_tee/
endif
ifeq ($(CONFIG_FINGERPRINT_FPC_TEE),y)
obj-y	+=  fpc_tee/
endif
ifeq ($(CONFIG_FINGERPRINT_FPC_FULL_FUNCTION),y)
obj-y	+=  fpc_full/
endif
