# Embedded Systems Build System using GNU Make & GCC  

## *Author:*  
*Maddukuri Chaitanya Lokesh*  

## *Description*  
This project implements a build system using *GNU Make and GCC* for both a *host environment* and the *MSP432 embedded system*. The Makefile automates compilation, linking, and artifact generation while supporting platform-specific flags.  

## *Features*  
- Supports *native (Host) and cross-compilation (MSP432)*  
- Generates *object files, assembly files, dependency files, and executables*  
- Uses *GNU Make* for efficient build automation  
- Implements *platform-specific compiler flags and linker options*  
- Includes a *clean build system*  

## *Files*  
- Makefile - Main build script for compiling and linking  
- sources.mk - Contains source file definitions  
- src/ - Source files for both host and MSP432  
- include/ - Header files for common and platform-specific code  
- msp432p401r.lds - Linker script for MSP432  

## *Build Instructions*  

### *Build for Host System*  
```sh
make build PLATFORM=HOST
