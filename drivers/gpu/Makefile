obj-y			+= drm/ vga/ ion/ sprd_iommu/
obj-$(CONFIG_TEGRA_HOST1X)	+= host1x/

ifeq ($(CONFIG_MALI400),y)
ifeq ($(CONFIG_MALI_VER_R4P0),y)
obj-y           += mali400/r4p0/
endif
endif
