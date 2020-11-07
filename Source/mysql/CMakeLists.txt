set(CMAKE_CXX_STANDARD 14)

add_executable(gen_mysql  "main.cpp")
target_link_libraries(gen_mysql boost_filesystem boost_system boost_regex)