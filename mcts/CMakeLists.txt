cmake_minimum_required(VERSION 3.10)
project(mcts)
add_executable(mcts mcts.c)
find_package (ZLIB)
if (ZLIB_FOUND)
  include_directories(${ZLIB_INCLUDE_DIRS})
  target_link_libraries (mcts ${ZLIB_LIBRARIES})
  target_compile_options(mcts PUBLIC -DHAVE_ZLIB)
endif (ZLIB_FOUND)
