# Templates

Templates for C/C++ projects with Bazel or CMake build system and Python programming.

## Bazel

Requires Bazel 7+ (bzlmod).  All templates default to C++23.

* `template_bazel_cpp_generic.zip`: a library and an app which depends on it.  No unit tests support.
* `template_bazel_cpp_lib.zip`: a library with unit tests (GoogleTest).
* `template_bazel_cpp_lib_boost.zip`: a library using Boost (algorithm, geometry) with unit tests (GoogleTest).
* `template_bazel_cpp_multi.zip`: an app from multiple source files.  No unit tests support.
* `template_bazel_cpp_single.zip`: an app from a single source file.  No unit tests support.

## CMake

Requires CMake 3.25+.  C templates use C17; C++ templates use C++23.

* `template_c_exe.zip`: an app from a single C source file.  No unit tests support.
* `template_c_lib.zip`: a library in C.  Unit tests supported through C++ (GoogleTest).
* `template_cpp_exe.zip`: an app from a single C++ source file.  No unit tests support.
* `template_cpp_exe_abseil.zip`: an app from C++ using Abseil library.  No unit tests support.
* `template_cpp_exe_abseil_boost.zip`: an app from C++ using Abseil and Boost libraries.  No unit tests support.
* `template_cpp_exe_boost.zip`: an app from C++ using Boost library.  No unit tests support.
* `template_cpp_lib.zip`: a library from C++ with unit tests (GoogleTest).

## Python

* `template_python.zip`: a python project.
