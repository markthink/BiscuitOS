################################################
#
# PERCPU linux 2.6.12.4
#
################################################
PK_PERCPU_2_6_12_4_NAME        := BiscuitOS_PERCPU
PK_PERCPU_2_6_12_4_VERSION     := $(CONFIG_PK_PERCPU_2_6_12_4_VERSION)
PK_PERCPU_2_6_12_4_SITE        := $(CONFIG_PK_PERCPU_2_6_12_4_URL)
PK_PERCPU_2_6_12_4_GITHUB      := $(CONFIG_PK_PERCPU_2_6_12_4_GITHUB)
PK_PERCPU_2_6_12_4_SUBNAME     :=
PK_PERCPU_2_6_12_4_BUILDARCH   := $(CONFIG_PK_PERCPU_2_6_12_4_BUILDARCH)
PK_PERCPU_2_6_12_4_DIR         := $(srctree)/package/memory_history/PERCPU/linux-2.6.12.4
PK_PERCPU_2_6_12_4_PATCH       := $(PK_PERCPU_2_6_12_4_DIR)/patch
PK_PERCPU_2_6_12_4_BSBIT       := BiscuitOS_PERCPU-$(PK_PERCPU_2_6_12_4_VERSION).bsbit
PK_PERCPU_2_6_12_4_OUT         :=
PK_PERCPU_2_6_12_4_SCRIPTS     := $(srctree)/scripts/package/package-memory.sh
PK_PERCPU_2_6_12_4_TAR         := $(CONFIG_PK_PERCPU_2_6_12_4_TAR)
PK_PERCPU_2_6_12_4_PACKAGE     :=
PK_PERCPU_2_6_12_4_CONFIG      := $(CONFIG_PK_PERCPU_2_6_12_4_CONFIG)
SUB_TARGET                  += $(PK_PERCPU_2_6_12_4_DIR)/build

PK_PERCPU_2_6_12_4_sh = $(CONFIG_SHELL) $(PK_PERCPU_2_6_12_4_SCRIPTS) \
                 $1X \
                 $(PK_PERCPU_2_6_12_4_NAME)X \
                 $(PK_PERCPU_2_6_12_4_VERSION)X \
                 $(PK_PERCPU_2_6_12_4_SITE)X \
                 $(PK_PERCPU_2_6_12_4_GITHUB)X \
                 $(PK_PERCPU_2_6_12_4_PATCH)X \
                 $(CONFIG_LINUX_KERNEL_VERSION)X \
	         $(CONFIG_MAIN_PROJ_NAME)X \
                 $(PK_PERCPU_2_6_12_4_TAR)X \
                 $(CONFIG_LINUX_KERNEL_CROSS_COMPILE)X \
                 $(PK_PERCPU_2_6_12_4_SUBNAME)X \
                 $(CONFIG_PK_PERCPU_2_6_12_4_CONFIG)X \
                 $(CONFIG_PK_PERCPU_2_6_12_4_LIBPATH)X \
                 $(CONFIG_PK_PERCPU_2_6_12_4_CPPFLAGS)X \
                 $(CONFIG_PK_PERCPU_2_6_12_4_DPKCONFIG)X \
                 $(CONFIG_PK_PERCPU_2_6_12_4_CFLAGS)X \
                 $(CONFIG_PK_PERCPU_2_6_12_4_LDFLAGS)X \
                 $(CONFIG_PK_PERCPU_2_6_12_4_CXXFLAGS)X \
                 $(CONFIG_PK_PERCPU_2_6_12_4_ASFLAGS)X \
                 $(PK_PERCPU_2_6_12_4_BSBIT)X \
                 $(PK_PERCPU_2_6_12_4_BUILDARCH)X \
		 $(PK_PERCPU_2_6_12_4_CSRCFILE)X \
                 $(CONFIG_PK_PERCPU_2_6_12_4_SRCFILE)X \
                 $(CONFIG_PK_PERCPU_2_6_12_4_CSRCFILE)

$(PK_PERCPU_2_6_12_4_DIR)/build: FORCE
	$(Q)$(call PK_PERCPU_2_6_12_4_sh,$(srctree))
