# this is for emacs file handling -*- mode: cmake; indent-tabs-mode: nil -*-
ICMAKER_SET("test_icl_core_logging_performance" IDE_FOLDER ${ICL_CORE_IDE_FOLDER})

ICMAKER_ADD_SOURCES(test_icl_core_logging_performance.cpp )

ICMAKER_INTERNAL_DEPENDENCIES(
  icl_core
  icl_core_config
  icl_core_logging
  )

ICMAKER_BUILD_PROGRAM()
