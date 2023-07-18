ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
    dtbo-$(CONFIG_ARCH_SM8150) += \
		hotdogg-sdx55m-overlay-t0.dtbo \
		hotdogg-sdx55m-overlay-evt1.dtbo \
		hotdogg-sdx55m-overlay-evt2.dtbo \
		hotdogg-sdx55m-overlay-dvt.dtbo \
		hotdogg-sdx55m-overlay-pvt.dtbo


    hotdogg-sdx55m-overlay-t0.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
    hotdogg-sdx55m-overlay-evt1.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
    hotdogg-sdx55m-overlay-evt2.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
    hotdogg-sdx55m-overlay-dvt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
    hotdogg-sdx55m-overlay-pvt.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb

else
dtb-$(CONFIG_ARCH_SM8150) += 	sm8150-v2-mtp.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
