################################################
#
# CMA_plant_module
#
################################################
PK_CMA_PLANT_MOD_NAME        := CMA_plant_module
PK_CMA_PLANT_MOD_VERSION     := $(CONFIG_PK_CMA_PLANT_MOD_VERSION)
PK_CMA_PLANT_MOD_SITE        := $(CONFIG_PK_CMA_PLANT_MOD_URL)
PK_CMA_PLANT_MOD_GITHUB      := $(CONFIG_PK_CMA_PLANT_MOD_GITHUB)
PK_CMA_PLANT_MOD_SUBNAME     :=
PK_CMA_PLANT_MOD_BUILDARCH   := $(CONFIG_PK_CMA_PLANT_MOD_BUILDARCH)
PK_CMA_PLANT_MOD_DIR         := $(srctree)/package/CMA/CMA_plant_module
PK_CMA_PLANT_MOD_PATCH       := $(PK_CMA_PLANT_MOD_DIR)/patch
PK_CMA_PLANT_MOD_BSBIT       := CMA_plant_module-$(PK_CMA_PLANT_MOD_VERSION).bsbit
PK_CMA_PLANT_MOD_OUT         :=
PK_CMA_PLANT_MOD_SCRIPTS     := $(srctree)/scripts/package/package-module.sh
PK_CMA_PLANT_MOD_TAR         := $(CONFIG_PK_CMA_PLANT_MOD_TAR)
PK_CMA_PLANT_MOD_PACKAGE     :=
PK_CMA_PLANT_MOD_CONFIG      := $(CONFIG_PK_CMA_PLANT_MOD_CONFIG)
SUB_TARGET                  += $(PK_CMA_PLANT_MOD_DIR)/build

PK_CMA_PLANT_MOD_sh = $(CONFIG_SHELL) $(PK_CMA_PLANT_MOD_SCRIPTS) \
                 $1X \
                 $(PK_CMA_PLANT_MOD_NAME)X \
                 $(PK_CMA_PLANT_MOD_VERSION)X \
                 $(PK_CMA_PLANT_MOD_SITE)X \
                 $(PK_CMA_PLANT_MOD_GITHUB)X \
                 $(PK_CMA_PLANT_MOD_PATCH)X \
                 $(CONFIG_LINUX_KERNEL_VERSION)X \
	         $(CONFIG_MAIN_PROJ_NAME)X \
                 $(PK_CMA_PLANT_MOD_TAR)X \
                 $(CONFIG_LINUX_KERNEL_CROSS_COMPILE)X \
                 $(PK_CMA_PLANT_MOD_SUBNAME)X \
                 $(CONFIG_PK_CMA_PLANT_MOD_CONFIG)X \
                 $(CONFIG_PK_CMA_PLANT_MOD_LIBPATH)X \
                 $(CONFIG_PK_CMA_PLANT_MOD_CPPFLAGS)X \
                 $(CONFIG_PK_CMA_PLANT_MOD_DPKCONFIG)X \
                 $(CONFIG_PK_CMA_PLANT_MOD_CFLAGS)X \
                 $(CONFIG_PK_CMA_PLANT_MOD_LDFLAGS)X \
                 $(CONFIG_PK_CMA_PLANT_MOD_CXXFLAGS)X \
                 $(CONFIG_PK_CMA_PLANT_MOD_ASFLAGS)X \
                 $(PK_CMA_PLANT_MOD_BSBIT)X \
                 $(PK_CMA_PLANT_MOD_BUILDARCH)X \
		 $(PK_CMA_PLANT_MOD_CSRCFILE)X \
                 $(CONFIG_PK_CMA_PLANT_MOD_SRCFILE)X \
                 $(CONFIG_PK_CMA_PLANT_MOD_CSRCFILE)

$(PK_CMA_PLANT_MOD_DIR)/build: FORCE
	$(Q)$(call PK_CMA_PLANT_MOD_sh,$(srctree))
