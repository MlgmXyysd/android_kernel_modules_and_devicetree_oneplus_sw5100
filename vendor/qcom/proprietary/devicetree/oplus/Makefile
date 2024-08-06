
ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_MONACO) += \
	monaco-oplus-x24909-overlay.dtbo \
	monaco-oplus-x23912-overlay.dtbo \
	monaco-oplus-x22907-overlay.dtbo


monaco-oplus-x24909-overlay.dtbo-base := monaco-oplus-base.dtb
monaco-oplus-x23912-overlay.dtbo-base := monaco-oplus-base.dtb
monaco-oplus-x22907-overlay.dtbo-base := monaco-oplus-base.dtb

else
dtb-$(CONFIG_ARCH_MONACO) += \
	monaco-oplus-x24909.dtbo \
	monaco-oplus-x23912.dtbo \
	monaco-oplus-x22907.dtbo
endif


always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
