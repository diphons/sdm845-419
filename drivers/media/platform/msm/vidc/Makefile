ccflags-y += -I$(srctree)/drivers/media/platform/msm/vidc/

msm-vidc-objs := msm_v4l2_vidc.o \
                                msm_v4l2_private.o \
				msm_vidc_platform.o \
                                msm_vidc_common.o \
                                msm_vidc.o \
                                msm_vdec.o \
                                msm_venc.o \
                                msm_cvp.o \
                                msm_smem.o \
                                msm_vidc_debug.o \
                                msm_vidc_ar50_dyn_gov.o \
                                msm_vidc_dyn_gov.o \
                                msm_vidc_res_parse.o \
                                venus_hfi.o \
                                hfi_response_handler.o \
                                hfi_packetization.o \
                                vidc_hfi.o \
                                msm_vidc_clocks.o

obj-$(CONFIG_MSM_VIDC_LEGACY_V4L2) := msm-vidc.o
