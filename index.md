The CMakePP organization aims to simplify building and packaging complex C++
projects using CMake. To do this the CMakePP organization has built up a
series of projects that together form a CMake development ecosystem.

![Organization Components](organization.png)

## CMaize

- [GitHub](https://github.com/CMakePP/CMaize)
- [Documentation](https://cmaize.readthedocs.io/en/latest/)

The top-level user API for writing a build system using the CMakePP development
ecosystem. If you are building a project that uses CMaize as its build system
or you are interested in creating a project that uses the CMakePP ecosystem,
CMaize is the project to consider.

## CMakePPCore

- [GitHub](https://github.com/CMakePP/CMakePPCore)
- [Documentation](https://cmakeppcore.readthedocs.io/en/latest/)

Maybe you don't care for the CMaize user-APIs or you want to design your own.
We highly recommend using the object-oriented CMakePP language for such
endeavors. CMakePPCore implements the CMakePP language.

## CMakeTest

- [GitHub](https://github.com/CMakePP/CMakeTest)
- [Documentation](https://cmaketest.readthedocs.io/en/latest/)

A unit-testing framework for code written using CMake/CMakePP languages.

## CMinx

- [GitHub](https://github.com/CMakePP/CMinx)
- [Documentation](https://cmakedoc.readthedocs.io/en/latest/)

A tool, a la Doxygen, for generating reStructuredText documentation for APIs of
CMake/CMakePP functions.

## CMakeDev

- [GitHub](https://github.com/CMakePP/CMakeDev)
- [Documentation](https://cmakedev.readthedocs.io/en/latest/)

Developers manual for the CMakePP project. A useful community resource for
others wanting to write their own CMake modules.
