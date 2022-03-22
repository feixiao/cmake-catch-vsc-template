# If you create new headers/cpp files, add them to these list!
set(HEADER_FILES
	catch.hpp
)

set(SOURCE_FILES	
	tests.cpp
)

# 直接引用了cpplib
set(LIBRARY_NAME cpplib)

add_executable(tests ${SOURCE_FILES})
target_link_libraries(tests ${LIBRARY_NAME})
