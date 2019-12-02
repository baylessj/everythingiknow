# macOS VM

VBoxManage modifyvm Sierra --cpuidset 00000001 000306a9 00020800 80000201 178bfbff VBoxManage setextradata "Sierra" "VBoxInternal/Devices/efi/0/Config/DmiSystemProduct" "iMac11,3" VBoxManage setextradata "Sierra" "VBoxInternal/Devices/efi/0/Config/DmiSystemVersion" "1.0" VBoxManage setextradata "Sierra" "VBoxInternal/Devices/efi/0/Config/DmiBoardProduct" "Iloveapple" VBoxManage setextradata "Sierra" "VBoxInternal/Devices/smc/0/Config/DeviceKey" "ourhardworkbythesewordsguardedpleasedontsteal\(c\)AppleComputerInc" VBoxManage setextradata "Sierra" "VBoxInternal/Devices/smc/0/Config/GetKeyFromRealSMC" 1

