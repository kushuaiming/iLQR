cmake_minimum_required(VERSION 3.5)
project(iLQR)

add_executable(run_iLQR main.cc)
target_include_directories(run_iLQR PRIVATE
  ${PROJECT_SOURCE_DIR}/src,
)