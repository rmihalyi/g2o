# Only build CSPARSE if we need to
IF(BUILD_CSPARSE)
  ADD_SUBDIRECTORY(csparse)
ENDIF(BUILD_CSPARSE)
