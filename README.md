# travis_qmake_gcc_cpp11_debug_gcov

[![Travis CI logo](TravisCI.png)](https://travis-ci.org)
![Whitespace](Whitespace.png)
[![Codecov logo](Codecov.png)](https://www.codecov.io)

[![Build Status](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp11_debug_gcov.svg?branch=master)](https://travis-ci.org/richelbilderbeek/travis_qmake_gcc_cpp11_debug_gcov)
[![codecov.io](https://codecov.io/github/richelbilderbeek/travis_qmake_gcc_cpp11_debug_gcov/coverage.svg?branch=master)](https://codecov.io/github/richelbilderbeek/travis_qmake_gcc_cpp11_debug_gcov?branch=master)

This GitHub is part of [the Travis C++ Tutorial](https://github.com/richelbilderbeek/travis_cpp_tutorial).

The goal of this project is to have a clean Travis CI build, with specs:
 * C++ version: `C++11`
 * Build system: `qmake`
 * C++ compiler: `g++`
 * Libraries: `STL` only
 * Code coverage: `gcov` (note: it should show the code coverage is below 100%) in debug build only
 * Source: multiple files

Additionally, the code coverage should be measured by CodeCov.

Less complex builds:
 * C++98: [travis_qmake_gcc_cpp98_debug_gcov](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp98_debug_gcov)
 * gcov in both builds: [travis_qmake_gcc_cpp11_gcov](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11_gcov)
 * debug and release mode: [travis_qmake_gcc_cpp11_debug](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp11_debug)

More complex builds:
 * C++14: [travis_qmake_gcc_cpp14_debug_gcov](https://www.github.com/richelbilderbeek/travis_qmake_gcc_cpp14_debug_gcov)
