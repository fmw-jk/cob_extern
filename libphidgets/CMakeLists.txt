project(libphidgets)

catkin_project( ${PROJECT_NAME}
  LIBRARIES ${PROJECT_NAME} 
  INCLUDE_DIRS include )

include_directories( include )
include_directories( lib )


# for compatibility with old build system
install(FILES manifest.xml
        DESTINATION share/${PROJECT_NAME})

