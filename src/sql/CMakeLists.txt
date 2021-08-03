add_library(sql Expr.cpp PrepareStatement.cpp SQLStatement.cpp statements.cpp)
target_include_directories(sql INTERFACE .)
