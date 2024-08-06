vendor := $(srctree)/$(src)

#ifneq "$(wildcard $(vendor)/qcom)" ""
#	subdir-y += qcom
#endif

ifeq "$(wildcard $(vendor)/oplus)" ""
	$(error !!!not find oplus directory!!!)
endif
subdir-y += oplus

