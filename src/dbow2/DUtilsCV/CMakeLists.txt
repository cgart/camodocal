camodocal_library(camodocal_DUtilsCV SHARED
  Drawing.cpp
  Geometry.cpp
  GUI.cpp
  IO.cpp
  Mat.cpp
  Transformations.cpp
  Types.cpp
)

camodocal_link_libraries(camodocal_DUtilsCV
  ${OPENCV_CALIB3D_LIBRARY}
  ${OPENCV_CORE_LIBRARY}
  ${OPENCV_FEATURES2D_LIBRARY}
  ${OPENCV_HIGHGUI_LIBRARY}
  ${OPENCV_IMGPROC_LIBRARY}
)
