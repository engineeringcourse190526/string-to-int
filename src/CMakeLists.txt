set(Main_SRCS main.c)

include_directories(${PROJECT_SOURCE_DIR}/include)

add_library(core ${Main_SRCS})
add_executable(string-to-int main.c)
target_link_libraries(string-to-int core)
