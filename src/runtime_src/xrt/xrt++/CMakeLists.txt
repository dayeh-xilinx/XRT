set(XRT_XRT_CPP_HEADER_SRC
  xrt++.hpp
  xrtexec.hpp)

install (FILES ${XRT_XRT_CPP_HEADER_SRC} DESTINATION ${XRT_INSTALL_INCLUDE_DIR}/experimental COMPONENT ${XRT_DEV_COMPONENT})

message("-- XRT xrt++ header files")
foreach (header ${XRT_XRT_CPP_HEADER_SRC})
  message("-- ${header}")
endforeach()
