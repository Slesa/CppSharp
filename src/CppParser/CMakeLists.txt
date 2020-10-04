cmake_minimum_required(VERSION 3.17)
project(CppParser)

set(CMAKE_CXX_STANDARD 14)

add_library(CppParser SHARED
        Comments.cpp
        CppParser.cpp CppParser.h
        CXXABI.h
        Decl.h
        ELFDumper.h
        Expr.cpp Expr.h
        Helpers.h
        ParseExpr.cpp
        Parser.cpp Parser.h
        ParseStmt.cpp
        Sources.cpp Sources.h
        Stmt.cpp Stmt.h
        Target.cpp Target.h
        Types.h)