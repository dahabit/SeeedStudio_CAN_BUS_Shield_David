################################################################################
# Automatically-generated file. Do not edit!
################################################################################

-include ../makefile.init

RM := del 

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir.mk
-include libraries\SPI\src/subdir.mk
-include libraries\CAN_BUS_Shield-master/subdir.mk
-include examples/subdir.mk
-include core\core/subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(INO_DEPS)),)
-include $(INO_DEPS)
endif
ifneq ($(strip $(PDE_DEPS)),)
-include $(PDE_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
AR += \
D:/Repositorio_de_Projetos/5-PESSOAL/SeeedStudio_CAN_BUS_Shield_David/Release/arduino.ar \

ELF += \
SeeedStudio_CAN_BUS_Shield_David.elf \

HEX += \
SeeedStudio_CAN_BUS_Shield_David.hex \


# All Target
all: SeeedStudio_CAN_BUS_Shield_David

# Tool invocations
SeeedStudio_CAN_BUS_Shield_David: $(HEX)
	@echo 'Building target: $@'
	@echo 'Printing size:'
	"C:\Users\DavidAlain\eclipse\cpp-neon2\eclipse\/arduinoPlugin/packages/arduino/tools/avr-gcc/4.9.2-atmel3.5.3-arduino2/bin/avr-size" -A "D:/Repositorio_de_Projetos/5-PESSOAL/SeeedStudio_CAN_BUS_Shield_David/Release/SeeedStudio_CAN_BUS_Shield_David.elf"
	@echo 'Finished building target: $@'
	@echo ' '

D:/Repositorio_de_Projetos/5-PESSOAL/SeeedStudio_CAN_BUS_Shield_David/Release/arduino.ar: $(AR_OBJ)
	@echo 'Starting archiver'
	"C:\Users\DavidAlain\eclipse\cpp-neon2\eclipse\/arduinoPlugin/packages/arduino/tools/avr-gcc/4.9.2-atmel3.5.3-arduino2/bin/avr-gcc-ar" rcs    D:/Repositorio_de_Projetos/5-PESSOAL/SeeedStudio_CAN_BUS_Shield_David/Release/arduino.ar $(AR_OBJ)
	@echo 'Finished building: $@'
	@echo ' '

SeeedStudio_CAN_BUS_Shield_David.elf: $(LINK_OBJ) $(AR)
	@echo 'Starting combiner'
	"C:\Users\DavidAlain\eclipse\cpp-neon2\eclipse\/arduinoPlugin/packages/arduino/tools/avr-gcc/4.9.2-atmel3.5.3-arduino2/bin/avr-gcc" -Wall -Wextra -Os -g -flto -fuse-linker-plugin -Wl,--gc-sections -mmcu=atmega328p -o "D:\Repositorio_de_Projetos\5-PESSOAL\SeeedStudio_CAN_BUS_Shield_David/Release/SeeedStudio_CAN_BUS_Shield_David.elf"   $(LINK_OBJ) $(AR)   D:/Repositorio_de_Projetos/5-PESSOAL/SeeedStudio_CAN_BUS_Shield_David/Release/arduino.ar  "-LD:\Repositorio_de_Projetos\5-PESSOAL\SeeedStudio_CAN_BUS_Shield_David/Release" -lm
	@echo 'Finished building: $@'
	@echo ' '

SeeedStudio_CAN_BUS_Shield_David.hex: $(ELF)
	@echo 'Do all objcopy commands'
	${A.RECIPE.OBJCOPY.EEP.PATTERN}
	${A.RECIPE.OBJCOPY.HEX.PATTERN}
	@echo 'Finished building: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(C_UPPER_DEPS)$(PDE_DEPS)$(C_DEPS)$(AR)$(CC_DEPS)$(AR_OBJ)$(C++_DEPS)$(LINK_OBJ)$(CXX_DEPS)$(ASM_DEPS)$(HEX)$(INO_DEPS)$(SIZEDUMMY)$(S_UPPER_DEPS)$(ELF)$(CPP_DEPS)
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets
