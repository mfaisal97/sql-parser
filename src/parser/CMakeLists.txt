add_library(parser bison_parser.cpp flex_lexer.cpp)
target_include_directories(parser INTERFACE .)
