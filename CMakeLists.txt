cmake_minimum_required( VERSION 2.6 )
project( EdmonsKarp-FlowOptimizer )

#add_executable(edmondskarp "edmondskarp.cpp")

file( GLOB APP_SOURCES edmondskarp.cpp )
SET( CMAKE_CXX_FLAGS  "${CMAKE_CXX_FLAGS} /FI\"alg_vs.h\"" ) 
message( ${CMAKE_CXX_FLAGS} )
