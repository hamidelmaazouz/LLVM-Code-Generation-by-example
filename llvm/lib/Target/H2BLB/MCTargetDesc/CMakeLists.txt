add_llvm_component_library(LLVMH2BLBDesc
  H2BLBAsmBackend.cpp
  H2BLBMachObjectWriter.cpp
  H2BLBMCAsmInfo.cpp
  H2BLBMCCodeEmitter.cpp
  H2BLBMCTargetDesc.cpp
  H2BLBInstPrinter.cpp

  LINK_COMPONENTS
  BinaryFormat
  Support
  H2BLBInfo
  MC

  ADD_TO_COMPONENT
  H2BLB
  )
