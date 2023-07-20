ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_SDM845) += \
		sdm845-mtp-overlay.dtbo \
		sdm845-v2-mtp-overlay.dtbo \
		sdm845-v2.1-mtp-overlay.dtbo \
		xiaomi/perseus/perseus-mp-v2.1-overlay.dtbo

sdm845-mtp-overlay.dtbo-base := sdm845.dtb
sdm845-v2-mtp-overlay.dtbo-base := sdm845-v2.dtb
sdm845-v2.1-mtp-overlay.dtbo-base := sdm845-v2.1.dtb
perseus-mp-v2.1-overlay.dtbo-base := sdm845-v2.1.dtb
else
dtb-$(CONFIG_ARCH_SDM845) += \
	sdm845-mtp.dtb \
	sdm845-v2-mtp.dtb \
	sdm845-v2.1-mtp.dtb \
	xiaomi/beryllium/beryllium-mp-v2.1.dtb \
	xiaomi/dipper/dipper-mp-v2.1.dtb \
	xiaomi/equuleus/equuleus-mp-v2.1.dtb \
	xiaomi/polaris/polaris-mp-v2.1.dtb \
	xiaomi/ursa/ursa-mp-v2.1.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
