ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_SDM670) += \
		sdm670-mtp-overlay.dtbo \
		sdm710-mtp-overlay.dtbo

sdm670-mtp-overlay.dtbo-base := sdm670.dtb
sdm710-mtp-overlay.dtbo-base := sdm710.dtb
else
dtb-$(CONFIG_ARCH_SDM670) += \
	sdm670-mtp.dtb \
	sdm710-mtp.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
