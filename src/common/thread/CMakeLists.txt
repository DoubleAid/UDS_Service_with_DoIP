
add_library(common_thread
		thread_pool.cpp
		threadsafe_queue.h
)

#install(
#		TARGETS common_thread E
#)

add_executable(thread_test
		main.cpp
		thread_pool.cpp
)