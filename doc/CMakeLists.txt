find_package(Doxygen)
if(DOXYGEN_FOUND)
	add_subdirectory(doxygen)
else(DOXYGEN_FOUND)
	MESSAGE("Doxygen not found. Will not be able to build documentation")
endif(DOXYGEN_FOUND)