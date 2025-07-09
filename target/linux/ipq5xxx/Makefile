include $(TOPDIR)/rules.mk

ARCH:=arm
BOARD:=ipq5xxx
BOARDNAME:=Qualcomm IPQ5XXX
FEATURES:=squashfs ext4 pci usb pcie
CPU_TYPE:=cortex-a53
CPU_SUBTYPE:=generic
KERNEL_PATCHVER:=5.15

KERNEL_DEVICE_LINK:=ipq5018-be6500

include $(INCLUDE_DIR)/target.mk

define Target/Description
    Build firmware images for Qualcomm IPQ5XXX based boards.
endef

$(eval $(call BuildTarget))
