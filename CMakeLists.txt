cmake_minimum_required(VERSION 2.8.3)
project(langs-dev)

find_package(catkin REQUIRED)

catkin_package(CATKIN_DEPENDS gencpp genlisp genpy)
