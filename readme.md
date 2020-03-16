# Manifests for ford and austin

### Fix build errors 

  1)  ``` /bin/sh: 1: arm-eabi-gcc: not found ```
  
      It cant find the toolchain to fix this run: 'export PATH=$PATH:~/[builddir]/prebuilts/gcc/linux-x86/arm/arm-eabi-4.8/bin'
      change builddir with whatever you named the build directory 
      
  2) ``` COMMON_GLOBAL_C(PP)FLAGS changed ```
     if you have this error follow this: https://forum.xda-developers.com/showpost.php?p=69892170&postcount=3
