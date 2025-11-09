# patch-fpcupdeluxe-Raspberry-pico
This patch solve the problem of sysutils when fpc is installed with fpcupdeluxe.  
To apply this patch:  
copy the files embedded_sysutils.path and compilertl.sh in folder path_to_fpcupdeluxe/fpcupdeluxe/fpcsrc/rtl/embedded  
then to apply the patch and recompile the rtl for arm-embedded:  
cd path_to_fpcupdeluxe/fpcupdeluxe/fpcsrc/rtl/embedded  
chmod +x compilertl.sh  
./compilertl.sh path_to_fpcupdeluxe/ 
  
The whole rtl is compiled with the sysutils file patched and everything is restored.
