#
# Makefile for misc devices that really don't fit anywhere else.
#
include $(srctree)/drivers/misc/mediatek/Makefile.custom

#obj-y += sensordriver/sensordrive_lens.o

ifeq ($(CONFIG_ARCH_MT6582),y)
obj-$(CONFIG_MTK_LENS_DUMMYLENS_SUPPORT) +=  mt6582/dummy_lens/
obj-$(CONFIG_MTK_LENS_DW9718AF_SUPPORT)  +=  mt6582/dw9718af/
obj-$(CONFIG_MTK_LENS_FM50AF_SUPPORT)    +=  mt6582/fm50af/
obj-$(CONFIG_MTK_LENS_GAF001AF_SUPPORT)  +=  mt6582/gaf001af/
obj-$(CONFIG_MTK_LENS_GAF002AF_SUPPORT)  +=  mt6582/gaf002af/
obj-$(CONFIG_MTK_LENS_GAF008AF_SUPPORT)  +=  mt6582/gaf008af/
obj-$(CONFIG_MTK_LENS_DW9714AF_SUPPORT)  +=  mt6582/dw9714af/
# LGE_CHANGE_S: [2014-11-28] yonghwan.lym@lge.com, OV8858 lens driver change.
obj-$(CONFIG_MTK_LENS_DW9714A_SUPPORT)  +=  mt6582/dw9714a/
# LGE_CHANGE_E: [2014-11-28] yonghwan.lym@lge.com, OV8858 lens driver change.
else 
        obj-$(CONFIG_MTK_LENS_DUMMYLENS_SUPPORT) += mt6752/dummy_lens/
        obj-$(CONFIG_MTK_LENS_AD5820AF_SUPPORT) += mt6752/ad5820af/
        obj-$(CONFIG_MTK_LENS_AD5823AF_SUPPORT) += mt6752/ad5823/
        obj-$(CONFIG_MTK_LENS_AD5823AF_SUPPORT) += mt6752/ad5823af/
        obj-$(CONFIG_MTK_LENS_BU6424AF_SUPPORT) += mt6752/bu6424af/
        obj-$(CONFIG_MTK_LENS_BU6429AF_SUPPORT) += mt6752/bu6429af/
        obj-$(CONFIG_MTK_LENS_BU64745GWZAF_SUPPORT) += mt6752/bu64745gwzaf/
        obj-$(CONFIG_MTK_LENS_DW9714AF_SUPPORT) += mt6752/dw9714af/
        obj-$(CONFIG_MTK_LENS_DW9718AF_SUPPORT) += mt6752/dw9718af/
        obj-$(CONFIG_MTK_LENS_FM50AF_SUPPORT) += mt6752/fm50af/
        obj-$(CONFIG_MTK_LENS_MT9P017AF_SUPPORT) += mt6752/mt9p017af/
        obj-$(CONFIG_MTK_LENS_OV8825AF_SUPPORT) += mt6752/ov8825af/
        obj-$(CONFIG_MTK_LENS_SENSORDRIVE_SUPPORT) += mt6752/sensordrive/
        obj-$(CONFIG_MTK_LENS_LC898122AF_SUPPORT) += mt6752/lc898122af/
        obj-$(CONFIG_MTK_LENS_LC898212AF_SUPPORT) += mt6752/lc898212af/
endif
