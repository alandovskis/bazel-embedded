##########################################################################################################################
# File automatically-generated by tool: [projectgenerator] version: [3.7.1] date: [Sun Mar 29 14:34:18 AWST 2020]
##########################################################################################################################

# ------------------------------------------------
# Generic Makefile (based on gcc)
#
# ChangeLog :
#	2017-02-10 - Several enhancements + project update mode
#   2015-07-22 - first version
# ------------------------------------------------

######################################
# target
######################################
TARGET = minimal_stm32l4_cubemx


######################################
# building variables
######################################
# debug build?
DEBUG = 1
# optimization
OPT = -Og


#######################################
# paths
#######################################
# Build path
BUILD_DIR = build

######################################
# source
######################################
# C sources
C_SOURCES =  \
Src/main.c \
Src/stm32l4xx_it.c \
Src/stm32l4xx_hal_msp.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_tim.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_tim_ex.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_i2c.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_i2c_ex.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_rcc.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_rcc_ex.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_flash.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_flash_ex.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_flash_ramfunc.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_gpio.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_dma.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_dma_ex.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_pwr.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_pwr_ex.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_cortex.c \
/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Src/stm32l4xx_hal_exti.c \
Src/system_stm32l4xx.c  

# ASM sources
ASM_SOURCES =  \
startup_stm32l432xx.s


#######################################
# binaries
#######################################
PREFIX = arm-none-eabi-
# The gcc compiler bin path can be either defined in make command via GCC_PATH variable (> make GCC_PATH=xxx)
# either it can be added to the PATH environment variable.
ifdef GCC_PATH
CC = $(GCC_PATH)/$(PREFIX)gcc
AS = $(GCC_PATH)/$(PREFIX)gcc -x assembler-with-cpp
CP = $(GCC_PATH)/$(PREFIX)objcopy
SZ = $(GCC_PATH)/$(PREFIX)size
else
CC = $(PREFIX)gcc
AS = $(PREFIX)gcc -x assembler-with-cpp
CP = $(PREFIX)objcopy
SZ = $(PREFIX)size
endif
HEX = $(CP) -O ihex
BIN = $(CP) -O binary -S
 
#######################################
# CFLAGS
#######################################
# cpu
CPU = -mcpu=cortex-m4

# fpu
FPU = -mfpu=fpv4-sp-d16

# float-abi
FLOAT-ABI = -mfloat-abi=hard

# mcu
MCU = $(CPU) -mthumb $(FPU) $(FLOAT-ABI)

# macros for gcc
# AS defines
AS_DEFS = 

# C defines
C_DEFS =  \
-DUSE_HAL_DRIVER \
-DSTM32L432xx


# AS includes
AS_INCLUDES = 

# C includes
C_INCLUDES =  \
-IInc \
-I/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Inc \
-I/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/STM32L4xx_HAL_Driver/Inc/Legacy \
-I/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/CMSIS/Device/ST/STM32L4xx/Include \
-I/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/CMSIS/Include \
-I/home/nathaniel/STM32Cube/Repository/STM32Cube_FW_L4_V1.15.1/Drivers/CMSIS/Include


# compile gcc flags
ASFLAGS = $(MCU) $(AS_DEFS) $(AS_INCLUDES) $(OPT) -Wall -fdata-sections -ffunction-sections

CFLAGS = $(MCU) $(C_DEFS) $(C_INCLUDES) $(OPT) -Wall -fdata-sections -ffunction-sections

ifeq ($(DEBUG), 1)
CFLAGS += -g -gdwarf-2
endif


# Generate dependency information
CFLAGS += -MMD -MP -MF"$(@:%.o=%.d)"


#######################################
# LDFLAGS
#######################################
# link script
LDSCRIPT = STM32L432KCUx_FLASH.ld

# libraries
LIBS = -lc -lm -lnosys 
LIBDIR = 
LDFLAGS = $(MCU) -specs=nano.specs -T$(LDSCRIPT) $(LIBDIR) $(LIBS) -Wl,-Map=$(BUILD_DIR)/$(TARGET).map,--cref -Wl,--gc-sections

# default action: build all
all: $(BUILD_DIR)/$(TARGET).elf $(BUILD_DIR)/$(TARGET).hex $(BUILD_DIR)/$(TARGET).bin


#######################################
# build the application
#######################################
# list of objects
OBJECTS = $(addprefix $(BUILD_DIR)/,$(notdir $(C_SOURCES:.c=.o)))
vpath %.c $(sort $(dir $(C_SOURCES)))
# list of ASM program objects
OBJECTS += $(addprefix $(BUILD_DIR)/,$(notdir $(ASM_SOURCES:.s=.o)))
vpath %.s $(sort $(dir $(ASM_SOURCES)))

$(BUILD_DIR)/%.o: %.c Makefile | $(BUILD_DIR) 
	$(CC) -c $(CFLAGS) -Wa,-a,-ad,-alms=$(BUILD_DIR)/$(notdir $(<:.c=.lst)) $< -o $@

$(BUILD_DIR)/%.o: %.s Makefile | $(BUILD_DIR)
	$(AS) -c $(CFLAGS) $< -o $@

$(BUILD_DIR)/$(TARGET).elf: $(OBJECTS) Makefile
	$(CC) $(OBJECTS) $(LDFLAGS) -o $@
	$(SZ) $@

$(BUILD_DIR)/%.hex: $(BUILD_DIR)/%.elf | $(BUILD_DIR)
	$(HEX) $< $@
	
$(BUILD_DIR)/%.bin: $(BUILD_DIR)/%.elf | $(BUILD_DIR)
	$(BIN) $< $@	
	
$(BUILD_DIR):
	mkdir $@		

#######################################
# clean up
#######################################
clean:
	-rm -fR $(BUILD_DIR)
  
#######################################
# dependencies
#######################################
-include $(wildcard $(BUILD_DIR)/*.d)

# *** EOF ***