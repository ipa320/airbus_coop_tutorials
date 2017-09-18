cmake_minimum_required(VERSION 2.8.3)
project(airbus_templates)

find_package(catkin REQUIRED COMPONENTS
  airbus_cobot_gui
)

catkin_package()

install(DIRECTORY launch config
  DESTINATION ${CATKIN_PACKAGE_SHARE_DESTINATION}
)
