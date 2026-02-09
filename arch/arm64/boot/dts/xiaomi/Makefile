# SPDX-License-Identifier: GPL-2.0

ifeq ($(CONFIG_MACH_XIAOMI),y)
ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_MACH_XIAOMI_ANDROMEDA) += \
            andromeda-sm8150-overlay.dtbo \
            andromeda-sm8150-p1-overlay.dtbo \
            andromeda-sm8150-p1_1-overlay.dtbo \
            andromeda-sm8150-p2-overlay.dtbo \
            andromeda-sm8150-p2_1-overlay.dtbo \
            andromeda-sm8150-p2_2-overlay.dtbo \
            andromeda-sm8150-p2_21-overlay.dtbo \

	dtbo-$(CONFIG_MACH_XIAOMI_VAYU) += \
            vayu-sm8150-overlay.dtbo

	dtbo-$(CONFIG_MACH_XIAOMI_RAPHAEL) += \
            raphael-sm8150-overlay.dtbo

andromeda-sm8150-overlay.dtbo-base := sm8150-xiaomi.dtb sm8150-v2-xiaomi.dtb
andromeda-sm8150-p1-overlay.dtbo-base := sm8150-xiaomi.dtb sm8150-v2-xiaomi.dtb
andromeda-sm8150-p1_1-overlay.dtbo-base := sm8150-xiaomi.dtb sm8150-v2-xiaomi.dtb
andromeda-sm8150-p2-overlay.dtbo-base := sm8150-xiaomi.dtb sm8150-v2-xiaomi.dtb
andromeda-sm8150-p2_1-overlay.dtbo-base := sm8150-xiaomi.dtb sm8150-v2-xiaomi.dtb
andromeda-sm8150-p2_2-overlay.dtbo-base := sm8150-xiaomi.dtb sm8150-v2-xiaomi.dtb
andromeda-sm8150-p2_21-overlay.dtbo-base := sm8150-xiaomi.dtb sm8150-v2-xiaomi.dtb
vayu-sm8150-overlay.dtbo-base := sm8150-xiaomi.dtb sm8150-v2-xiaomi.dtb
raphael-sm8150-overlay.dtbo-base := sm8150-xiaomi.dtb sm8150-v2-xiaomi.dtb

endif
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
