cmake_minimum_required(VERSION 2.8)	 
										

project(LAB2_BY_HUTSALIUK)			
add_library(
	lab_2 
	STATIC 
	lab_2.cpp
)	

add_executable(
	main 
	main.cpp
)	

target_link_libraries(main lab_2)		
