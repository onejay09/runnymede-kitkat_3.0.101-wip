ccflags-y := -O3 -ffast-math -fgcse-lm -fgcse-sm -fsched-spec-load -fforce-addr -fsingle-precision-constant -mtune=cortex-a8 -marm -march=armv7-a -mfpu=neon -ftree-vectorize -mvectorize-with-neon-double -Wframe-larger-than=2048
obj-y += afe.o audio_interct.o mi2s.o audio_dev_ctl.o voice.o snddev_data.o
obj-$(CONFIG_MARIMBA_CODEC) += snddev_icodec.o lpa.o
obj-$(CONFIG_TIMPANI_CODEC) += snddev_icodec.o lpa.o
#obj-y += audio_pcm.o audio_wma.o audio_aac.o audio_amrnb.o
#obj-y += audio_amrwb.o audio_wmapro.o audio_adpcm.o audio_evrc.o audio_qcelp.o
obj-y += aux_pcm.o snddev_ecodec.o audio_out.o audpp.o snddev_mi2s.o
obj-y += audio_mp3.o audio_lpa.o mp3_funcs.o pcm_funcs.o
obj-y += audpreproc.o audio_pcm_in.o
#obj-y += audio_evrc_in.o audio_qcelp_in.o audio_aac_in.o audio_amrnb_in.o
obj-y += adsp.o adsp_driver.o adsp_info.o
obj-y += audio_acdb.o audio_aac.o audio_amrnb_in.o audio_evrc_in.o audio_qcelp_in.o
obj-y += audio_mvs.o

#obj-$(CONFIG_MARIMBA_CODEC) += snddev_data_marimba.o
#obj-$(CONFIG_TIMPANI_CODEC) += snddev_data_timpani.o
#obj-y += snddev_virtual.o
CFLAGS_audio_lpa.o := -DDEBUG
