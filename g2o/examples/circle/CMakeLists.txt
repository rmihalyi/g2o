ADD_EXECUTABLE(circle_fit
  circle_fit.cpp
)

INCLUDE_DIRECTORIES(${CSPARSE_INCLUDE_DIR})

SET_TARGET_PROPERTIES(circle_fit PROPERTIES OUTPUT_NAME circle_fit${EXE_POSTFIX})
TARGET_LINK_LIBRARIES(circle_fit core solver_csparse)
