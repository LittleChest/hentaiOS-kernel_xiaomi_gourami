# SPDX-License-Identifier: GPL-2.0
# UFSHCD makefile
obj-$(CONFIG_SCSI_UFS_DWC_TC_PCI) += tc-dwc-g210-pci.o ufshcd-dwc.o tc-dwc-g210.o
obj-$(CONFIG_SCSI_UFS_DWC_TC_PLATFORM) += tc-dwc-g210-pltfrm.o ufshcd-dwc.o tc-dwc-g210.o
obj-$(CONFIG_SCSI_UFS_QCOM) += ufs_qcom.o
ufs_qcom-y += ufs-qcom.o
ufs_qcom-$(CONFIG_SCSI_UFS_CRYPTO) += ufs-qcom-ice.o
obj-$(CONFIG_SCSI_UFSHCD) += ufshcd-core.o
ufshcd-core-objs := ufshcd.o ufs-sysfs.o
obj-$(CONFIG_UFSFEATURE) += ufsfeature.o
obj-$(CONFIG_UFSHPB) += ufshpb.o
obj-$(CONFIG_UFSTW) += ufstw.o
obj-$(CONFIG_UFSFEATURE_31) += ufsfeature31.o
obj-$(CONFIG_UFSHPB_31) += ufshpb31.o
obj-$(CONFIG_UFSTW_31) += ufstw31.o
obj-$(CONFIG_UFSHID) += ufshid.o
obj-$(CONFIG_UFSRINGBUF) += ufsringbuf.o
obj-$(CONFIG_SCSI_UFSHCD_PCI) += ufshcd-pci.o
obj-$(CONFIG_SCSI_UFSHCD_PLATFORM) += ufshcd-pltfrm.o
obj-$(CONFIG_SCSI_UFS_TEST) += ufs_test.o
ufshcd-core-$(CONFIG_DEBUG_FS) += ufs-debugfs.o
ufs_qcom-${CONFIG_DEBUG_FS} += ufs-qcom-debugfs.o
obj-$(CONFIG_SCSI_UFS_HISI) += ufs-hisi.o
ufshcd-core-$(CONFIG_SCSI_UFS_CRYPTO) += ufshcd-crypto.o
