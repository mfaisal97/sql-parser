add_subdirectory(parser)
add_subdirectory(sql)
add_subdirectory(util)

add_library(src SQLParserResult.cpp SQLParser.cpp)
target_link_libraries(src parser sql util)
target_include_directories(src PUBLIC .)