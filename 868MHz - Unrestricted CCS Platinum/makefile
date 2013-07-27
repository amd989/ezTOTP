################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := C:/ti/ccsv5/tools/compiler/msp430_4.1.1

ORDERED_OBJS += \
$(GEN_CMDS__FLAG) \
"./driver/vti_ps.obj" \
"./driver/vti_as.obj" \
"./driver/timer.obj" \
"./driver/rf1a.obj" \
"./driver/radio.obj" \
"./driver/ports.obj" \
"./driver/pmm.obj" \
"./driver/display.obj" \
"./driver/buzzer.obj" \
"./driver/adc12.obj" \
"./logic/user.obj" \
"./logic/totp.obj" \
"./logic/test.obj" \
"./logic/temperature.obj" \
"./logic/stopwatch.obj" \
"./logic/sha1.obj" \
"./logic/rfsimpliciti.obj" \
"./logic/rfbsl.obj" \
"./logic/menu.obj" \
"./logic/hmac.obj" \
"./logic/date.obj" \
"./logic/clock.obj" \
"./logic/battery.obj" \
"./logic/base32.obj" \
"./logic/altitude.obj" \
"./logic/alarm.obj" \
"./logic/acceleration.obj" \
"./simpliciti/Applications/application/End Device/main_ED_BM.obj" \
"./simpliciti/Components/bsp/bsp.obj" \
"./simpliciti/Components/mrfi/mrfi.obj" \
"./simpliciti/Components/nwk/nwk_globals.obj" \
"./simpliciti/Components/nwk/nwk_frame.obj" \
"./simpliciti/Components/nwk/nwk_api.obj" \
"./simpliciti/Components/nwk/nwk_QMgmt.obj" \
"./simpliciti/Components/nwk/nwk.obj" \
"./simpliciti/Components/nwk_applications/nwk_security.obj" \
"./simpliciti/Components/nwk_applications/nwk_ping.obj" \
"./simpliciti/Components/nwk_applications/nwk_mgmt.obj" \
"./simpliciti/Components/nwk_applications/nwk_link.obj" \
"./simpliciti/Components/nwk_applications/nwk_join.obj" \
"./simpliciti/Components/nwk_applications/nwk_ioctl.obj" \
"./simpliciti/Components/nwk_applications/nwk_freq.obj" \
"./main.obj" \
-l"rts430x.lib" \
"../lnk_cc430f6137.cmd" \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include simpliciti/Components/nwk_applications/subdir_vars.mk
-include simpliciti/Components/nwk/subdir_vars.mk
-include simpliciti/Components/mrfi/subdir_vars.mk
-include simpliciti/Components/bsp/subdir_vars.mk
-include simpliciti/Applications/application/End\ Device/subdir_vars.mk
-include logic/subdir_vars.mk
-include driver/subdir_vars.mk
-include subdir_rules.mk
-include simpliciti/Components/nwk_applications/subdir_rules.mk
-include simpliciti/Components/nwk/subdir_rules.mk
-include simpliciti/Components/mrfi/subdir_rules.mk
-include simpliciti/Components/bsp/subdir_rules.mk
-include simpliciti/Applications/application/End\ Device/subdir_rules.mk
-include logic/subdir_rules.mk
-include driver/subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: ez430_chronos_868MHz.out

# Tool invocations
ez430_chronos_868MHz.out: $(OBJS) $(CMD_SRCS) $(LIB_SRCS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: MSP430 Linker'
	"C:/ti/ccsv5/tools/compiler/msp430_4.1.1/bin/cl430" --cmd_file="C:\Users\Alejandro\Dropbox\Projects\GitHub\ezTOPT\simpliciti\Applications\configuration\smpl_nwk_config.dat" --cmd_file="C:\Users\Alejandro\Dropbox\Projects\GitHub\ezTOPT\simpliciti\Applications\configuration\End Device\smpl_config.dat"  -vmspx -g -O4 --opt_for_speed=0 --define=__CCE__ --define=ISM_EU --define=__CC430F6137__ --define=MRFI_CC430 --diag_warning=225 --call_assumptions=0 --auto_inline=0 --gen_opt_info=2 --printf_support=minimal -z -m"ez430_chronos_868MHz.map" --stack_size=80 --heap_size=80 --use_hw_mpy=F5 --warn_sections -i"C:/ti/ccsv5/ccs_base/msp430/include" -i"C:/ti/ccsv5/tools/compiler/msp430_4.1.1/lib" -i"C:/ti/ccsv5/tools/compiler/msp430_4.1.1/include" -i"C:/ti/ccsv5/msp430/include" --reread_libs --rom_model -o "ez430_chronos_868MHz.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '
	$(MAKE) --no-print-directory post-build

# Other Targets
clean:
	-$(RM) $(MSP430_EXECUTABLE_OUTPUTS__QUOTED) "ez430_chronos_868MHz.out"
	-$(RM) "main.pp" "simpliciti\Components\nwk_applications\nwk_freq.pp" "simpliciti\Components\nwk_applications\nwk_ioctl.pp" "simpliciti\Components\nwk_applications\nwk_join.pp" "simpliciti\Components\nwk_applications\nwk_link.pp" "simpliciti\Components\nwk_applications\nwk_mgmt.pp" "simpliciti\Components\nwk_applications\nwk_ping.pp" "simpliciti\Components\nwk_applications\nwk_security.pp" "simpliciti\Components\nwk\nwk.pp" "simpliciti\Components\nwk\nwk_QMgmt.pp" "simpliciti\Components\nwk\nwk_api.pp" "simpliciti\Components\nwk\nwk_frame.pp" "simpliciti\Components\nwk\nwk_globals.pp" "simpliciti\Components\mrfi\mrfi.pp" "simpliciti\Components\bsp\bsp.pp" "simpliciti\Applications\application\End Device\main_ED_BM.pp" "logic\acceleration.pp" "logic\alarm.pp" "logic\altitude.pp" "logic\base32.pp" "logic\battery.pp" "logic\clock.pp" "logic\date.pp" "logic\hmac.pp" "logic\menu.pp" "logic\rfbsl.pp" "logic\rfsimpliciti.pp" "logic\sha1.pp" "logic\stopwatch.pp" "logic\temperature.pp" "logic\test.pp" "logic\totp.pp" 
	-$(RM) "logic\user.pp" "driver\adc12.pp" "driver\buzzer.pp" "driver\display.pp" "driver\pmm.pp" "driver\ports.pp" "driver\radio.pp" "driver\rf1a.pp" "driver\timer.pp" "driver\vti_as.pp" "driver\vti_ps.pp" 
	-$(RM) "main.obj" "simpliciti\Components\nwk_applications\nwk_freq.obj" "simpliciti\Components\nwk_applications\nwk_ioctl.obj" "simpliciti\Components\nwk_applications\nwk_join.obj" "simpliciti\Components\nwk_applications\nwk_link.obj" "simpliciti\Components\nwk_applications\nwk_mgmt.obj" "simpliciti\Components\nwk_applications\nwk_ping.obj" "simpliciti\Components\nwk_applications\nwk_security.obj" "simpliciti\Components\nwk\nwk.obj" "simpliciti\Components\nwk\nwk_QMgmt.obj" "simpliciti\Components\nwk\nwk_api.obj" "simpliciti\Components\nwk\nwk_frame.obj" "simpliciti\Components\nwk\nwk_globals.obj" "simpliciti\Components\mrfi\mrfi.obj" "simpliciti\Components\bsp\bsp.obj" "simpliciti\Applications\application\End Device\main_ED_BM.obj" "logic\acceleration.obj" "logic\alarm.obj" "logic\altitude.obj" "logic\base32.obj" "logic\battery.obj" "logic\clock.obj" "logic\date.obj" "logic\hmac.obj" "logic\menu.obj" "logic\rfbsl.obj" "logic\rfsimpliciti.obj" "logic\sha1.obj" "logic\stopwatch.obj" "logic\temperature.obj" 
	-$(RM) "logic\test.obj" "logic\totp.obj" "logic\user.obj" "driver\adc12.obj" "driver\buzzer.obj" "driver\display.obj" "driver\pmm.obj" "driver\ports.obj" "driver\radio.obj" "driver\rf1a.obj" "driver\timer.obj" "driver\vti_as.obj" "driver\vti_ps.obj" 
	-@echo 'Finished clean'
	-@echo ' '

post-build:
	-@echo 'Create flash image: TI-TXT'
	-"C:/ti/ccsv5/tools/compiler/msp430_4.1.1/bin/hex430.exe" --ti_txt "ez430_chronos_868MHz.out" -o "ez430_chronos_868MHz.txt" -order MS -romwidth 16
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY: post-build

-include ../makefile.targets
