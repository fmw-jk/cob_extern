project(libntcan)

catkin_project(${PROJECT_NAME}
  LIBRARIES ${PROJECT_NAME}
  INCLUDE_DIRS common/include)

include_directories(common/include)

# for compatibility with old build system
install(FILES manifest.xml
        DESTINATION share/${PROJECT_NAME})

