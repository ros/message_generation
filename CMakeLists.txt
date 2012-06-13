cmake_minimum_required(VERSION 2.8)
project(langs-dev)
find_package(catkin REQUIRED)
catkin_stack()
catkin_project(${PROJECT_NAME}
  DEPENDS ${${PROJECT_NAME}_DEPENDS}
)
