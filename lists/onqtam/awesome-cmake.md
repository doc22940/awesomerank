---
layout: default
title: Awesome Rank for onqtam/awesome-cmake
---

<p align="center">
	This list is a copy of <a href="https://github.com/onqtam/awesome-cmake">onqtam/awesome-cmake</a> with ranks
</p>
---
# Awesome CMake [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★87749](https://github.com/sindresorhus/awesome)

[<img src="https://rawgit.com/onqtam/awesome-cmake/master/cmake-logo.svg" align="right" width="100">](https://cmake.org/)

> A curated list of awesome [CMake](https://cmake.org/) scripts, modules, examples and others

Your contributions are highly welcome (first see [CONTRIBUTING.md](https://github.com/onqtam/awesome-cmake/blob/master/CONTRIBUTING.md)).

## Contents

- [Community](#community)
- [Resources](#resources)
- [Package Management / Build Systems](#package-management--build-systems)
- [Modules](#modules)
- [Utility Scripts](#utility-scripts)
- [Toolchains](#toolchains)
- [Examples / Templates](#examples--templates)
- [Other](#other)

## Community

* [```#cmake``` on Freenode](http://webchat.freenode.net/?channels=cmake)
* [```/r/cmake``` on Reddit](https://www.reddit.com/r/cmake/)
* [```/r/cpp``` on Reddit](https://www.reddit.com/r/cpp/)
* [Mailing Lists](https://cmake.org/mailing-lists/)
* [Stack Overflow](http://stackoverflow.com/questions/tagged/cmake)

## Resources

* [Latest Documentation](https://cmake.org/cmake/help/latest/)
* [FAQ](https://cmake.org/Wiki/CMake_FAQ)
* [Wiki](https://cmake.org/Wiki/CMake)
* [Webinars](https://cmake.org/webinars/)
* [CGold ★114](https://github.com/ruslo/CGold) - The Hitchhiker’s [Guide](https://cgold.readthedocs.io) to the CMake. [```[BSD2]```][BSD-2-Clause]
* [Modern CMake](https://github.com/toeb/moderncmake) - Modern CMake **PDF** and samples by the creator of [cmakepp ★279 ⏳1Y](https://github.com/toeb/cmakepp). [```[MIT]```][MIT]
* [Article - Easily supporting CMake install and find_package()](http://foonathan.net/blog/2016/03/03/cmake-install.html).
* [Article - Easy dependency management for C++ with CMake and Git](http://foonathan.net/blog/2016/07/07/cmake-dependency-handling.html).
* [Article - Opt-in header-only libraries with CMake](https://steveire.wordpress.com/2016/08/09/opt-in-header-only-libraries-with-cmake/).
* [Article - Ultimate Guide to Modern CMake](https://rix0r.nl/blog/2015/08/13/cmake-guide/).
* [Article - A list of common CMake antipatterns (from 2013 but still relevant)](http://voices.canonical.com/jussi.pakkanen/2013/03/26/a-list-of-common-cmake-antipatterns/).
* [Article - How to Build a CMake-Based Project](http://preshing.com/20170511/how-to-build-a-cmake-based-project/).
* [Article - Learn CMake's Scripting Language in 15 Minutes](http://preshing.com/20170522/learn-cmakes-scripting-language-in-15-minutes/).
* [Article - The architecture of CMake](http://aosabook.org/en/cmake.html).
* [Lecture - Effective CMake - by Daniel Pfeifer, C++Now 2017](https://www.youtube.com/watch?v=bsXLMQ6WgIk).
* [Article - Building Cross-Platform CUDA Applications with CMake](https://devblogs.nvidia.com/parallelforall/building-cuda-applications-cmake/).
* [Tutorial - A step-by-step guide for understanding CMake](https://github.com/Wigner-GPU-Lab/Teaching/tree/master/CMake).
* [Article + Lecture - Embracing Modern CMake - by Stephen Kelly](https://steveire.wordpress.com/2017/11/05/embracing-modern-cmake/).
* [Lecture - CppCon 2017: Mathieu Ropert “Modern CMake for Modular Design”](https://www.youtube.com/watch?v=eC9-iRN2b04).
* [Article - Modern C++ CI (although it uses non-modern CMake like ```include_directories()```)](https://juan-medina.com/2017/07/01/moderncppci/).
* [Article - It's Time To Do CMake Right](https://pabloariasal.github.io/2018/02/19/its-time-to-do-cmake-right/) (one of the best articles about CMake).
* Articles - A series on CMake - by Martin Hořeňovský
    * [Basic CMake usage](https://codingnest.com/basic-cmake/)
    * [Basic CMake, part 2: libraries](https://codingnest.com/basic-cmake-part-2/)
* [Lecture - Introduction to CMake - by Florent Castelli, C++ Sweden 2018](https://www.youtube.com/watch?v=jt3meXdP-QI).
* [Article - Some nice and accurate CMake tips](http://bastian.rieck.me/blog/posts/2018/cmake_tips/)
* [Article - Modern CMake for Library Developers](http://unclejimbo.github.io/2018/06/08/Modern-CMake-for-Library-Developers/)
* [Article - Effective Modern CMake: a great summary of most good practices - by Manuel Binna](https://gist.github.com/mbinna/c61dbb39bca0e4fb7d1f73b0d66a4fd1)

## Package Management / Build Systems

* [hunter ★1266](https://github.com/ruslo/hunter) - Cross-platform package manager for C++ (based on CMake ExternalProject). [```[BSD2]```][BSD-2-Clause]
* [cget ★232](https://github.com/pfultz2/cget) - CMake package retrieval. This can be used to download and install CMake packages. [```[BOOST]```][BOOST]
* [cppan](https://cppan.org/) - C++ Archive Network - C++ Package Manager based on CMake, implemented in C++14. [```[APACHE2]```][APACHE2]
* [cpm ★637 ⏳1Y](https://github.com/iauns/cpm) - C++ Package Manager based on CMake and Git. [```[MIT]```][MIT]
* [conan ★1904](https://github.com/conan-io/conan) - Conan C++ Package Manager, implemented in Python and has a CMake integration backend. [```[MIT]```][MIT]
* [fips ★199](https://github.com/floooh/fips) - High-level build system/dependency management for distributed, multi-platform C/C++ projects. [```[MIT]```][MIT]
* [Ninja ★3456](https://github.com/ninja-build/ninja) - Build system that differs from others in two major respects: it is designed to have its input files generated by a higher-level build system (like CMake), and it is designed to run builds as fast as possible. [```[APACHE2]```][APACHE2]
* [vcpkg ★3254](https://github.com/Microsoft/vcpkg) - A tool to acquire and build C++ open source libraries. Uses CMake internally as a build script language. [```[MIT]```][MIT]

## Modules

* [cmake-modules ★479](https://github.com/rpavlik/cmake-modules) - [Ryan Pavlik](https://github.com/rpavlik)'s collection of CMake modules. There are a number of find modules, especially for virtual reality and physical simulation, some utility modules, and some patches or workarounds for CMake itself. [```[BOOST]```][BOOST]
* [cmake-modules ★157](https://github.com/bilke/cmake-modules) - This is a collection of additional CMake modules. Most of them are from Ryan Pavlik. [```[BOOST]```][BOOST]
* [CMake ★81](https://github.com/Eyescale/CMake) - [Eyescale](https://github.com/Eyescale)'s common CMake modules. [```[BSD3]```][BSD-3-Clause]
* [sdl2-cmake-scripts ★127](https://github.com/tcbrindle/sdl2-cmake-scripts) - CMake scripts for finding the SDL2, SDL2_image and SDL2_ttf libraries and headers. [```[BSD2]```][BSD-2-Clause]
* [vfxcmake ★75](https://github.com/nerdvegas/vfxcmake) - CMake Find modules for common vfx software, and general CMake utility code. [```[LGPL]```][LGPL]
* [cmake-modules ★57](https://github.com/jedbrown/cmake-modules) - CMake modules for some scientific libraries. [```[BSD2]```][BSD-2-Clause]
* [cgcmake ★46](https://github.com/chadmv/cgcmake) - CMake modules for common applications related to computer graphics. [```[MIT]```][MIT]
* [FindMathematica ★27](https://github.com/sakra/FindMathematica) - CMake module for Mathematica. [```[MIT]```][MIT]
* [extra-cmake-modules ★28](https://github.com/KDE/extra-cmake-modules) - [KDE](https://github.com/KDE)'s extra modules and scripts for CMake. [```[BSD3]```][BSD-3-Clause]
* [FindICU.cmake ★23 ⏳1Y](https://github.com/julp/FindICU.cmake) - CMake module to find International Components for Unicode (ICU) Library. [```[BSD2]```][BSD-2-Clause]
* [FindTBB ★55](https://github.com/justusc/FindTBB) - CMake find module for Intel Threading Building Blocks. [```[MIT]```][MIT]
* [cmake-modules ★23 ⏳3Y](https://github.com/hanjianwei/cmake-modules) - [hanjianwei](https://github.com/hanjianwei)'s CMake module collection. [```[MIT]```][MIT]
* [YCM](https://github.com/robotology/ycm) - Extra CMake Modules for [Yet Another Robot Platform ★204](https://github.com/robotology/yarp) and friends. [```[BSD3]```][BSD-3-Clause]

## Utility Scripts

These provide a wide range of functionality - from dealing with compiler flags to using tools. Some also contain modules.

* [cotire ★777](https://github.com/sakra/cotire) - Cotire (compile time reducer) is a CMake module that speeds up the build process of CMake based build systems by fully automating techniques as precompiled headers and unity builds for C and C++. [```[MIT]```][MIT]
* [ucm ★99 ⏳1Y](https://github.com/onqtam/ucm) - For managing compiler/linker flags, collecting sources, precompiled headers, unity builds and others. [```[MIT]```][MIT]
* [cmakepp ★279 ⏳1Y](https://github.com/toeb/cmakepp) - Enhancement Suite for the CMake Build System. [```[MIT]```][MIT]
* [sugar ★78](https://github.com/ruslo/sugar) - CMake tools and examples: collecting source files, warnings suppression, etc. [```[BSD2]```][BSD-2-Clause]
* [DownloadProject ★205 ⏳1Y](https://github.com/Crascit/DownloadProject) - CMake module for downloading an external project's source at configure time. [```[MIT]```][MIT]
* [buildem ★25 ⏳1Y](https://github.com/janelia-flyem/buildem) - Modular CMake-based system that leverages ExternalProject to simplify builds. [```[LICENSE]```](https://github.com/janelia-flyem/buildem/blob/master/LICENSE.txt)
* [coveralls-cmake ★66](https://github.com/JoakimSoderberg/coveralls-cmake) - Coveralls JSON coverage generator and uploader for CMake. [```[MIT]```][MIT]
* [compatibility ★60 ⏳1Y](https://github.com/foonathan/compatibility) - Improved version of cmake-compile-features. [```[LICENSE]```](https://github.com/foonathan/compatibility/blob/master/LICENSE)
* [cmake-modules ★27 ⏳2Y](https://github.com/Tronic/cmake-modules) - LibFindMacros development repository and other cool CMake stuff. [```[LICENSE]```](https://github.com/Tronic/cmake-modules/blob/master/LibFindMacros.cmake#L2)
* [GreatCMakeCookOff ★22](https://github.com/UCL/GreatCMakeCookOff) - This is a repository of useful and less than useful CMake recipes. [```[MIT]```][MIT]
* [cppcheck-target-cmake ★14 ⏳2Y](https://github.com/polysquare/cppcheck-target-cmake) - Per-target CPPCheck for CMake. [```[MIT]```][MIT]
* [clang-tidy-target-cmake ★10 ⏳2Y](https://github.com/polysquare/clang-tidy-target-cmake) - Add clang-tidy checks to a target using CMake. [```[MIT]```][MIT]
* [cmake-unit ★27 ⏳1Y](https://github.com/polysquare/cmake-unit) - Unit testing framework for CMake. [```[MIT]```][MIT]
* [cmake-header-language ★2 ⏳2Y](https://github.com/polysquare/cmake-header-language) - CMake macro to determine the language of a header file. [```[MIT]```][MIT]
* [tooling-cmake-util ★2 ⏳2Y](https://github.com/polysquare/tooling-cmake-util) - Utility and common library for all polysquare CMake tools. [```[MIT]```][MIT]
* [iwyu-target-cmake ★3 ⏳2Y](https://github.com/polysquare/iwyu-target-cmake) - CMake integration for include-what-you-use. [```[MIT]```][MIT]
* [sanitizers-cmake ★100](https://github.com/arsenm/sanitizers-cmake) - CMake module to enable sanitizers for binary targets. [```[MIT]```][MIT]
* [cmake-precompiled-header ★85](https://github.com/larsch/cmake-precompiled-header) - Visual Studio and GCC precompiled header macro. [```[LICENSE]```](https://github.com/larsch/cmake-precompiled-header/blob/master/PrecompiledHeader.cmake#L31)
* [CMakePCHCompiler ★40](https://github.com/nanoant/CMakePCHCompiler) - CMake precompiled headers via custom compiler extension - with reuse support! [```[MIT]```][MIT]
* [CMake-codecov](https://github.com/RWTH-ELP/CMake-codecov) - Enables code coverage and generates coverage reports with CMake targets. [```[GPL]```][GPL]
* [leatherman ★31](https://github.com/puppetlabs/leatherman) - Collection of C++ and CMake utility libraries. [```[APACHE2]```][APACHE2]
* [cmake-get ★41](https://github.com/pfultz2/cmake-get) - Get dependencies in config or script mode. ```[NO LICENSE]```

## Toolchains

* [dockcross ★617](https://github.com/dockcross/dockcross) - Cross compiling toolchains in Docker images. [```[MIT]```][MIT]
* [android-cmake ★872](https://github.com/taka-no-me/android-cmake) - CMake toolchain file and other scripts for the Android NDK. [```[BSD3]```][BSD-3-Clause]
* [ios-cmake ★207 ⏳1Y](https://github.com/cristeab/ios-cmake) - Toolchain file and examples using CMake for iOS development. [```[BSD3]```][BSD-3-Clause]
* [qt-android-cmake ★85 ⏳1Y](https://github.com/LaurentGomila/qt-android-cmake) - For building and deploying Qt based apps on Android without QtCreator. [```[LICENSE]```](https://github.com/LaurentGomila/qt-android-cmake/blob/master/license.txt)
* [mingw-w64-cmake ★72](https://github.com/lachs0r/mingw-w64-cmake) - CMake-based MinGW-w64 Cross Toolchain - to build Windows binaries of mpv. [```[ISC]```][ISC]
* [cmake-avr ★81](https://github.com/mkleemann/cmake-avr) - CMake toolchain for AVR. [```[LICENSE]```](https://github.com/mkleemann/cmake-avr/blob/master/LICENSE)
* [arduino-cmake ★32](https://github.com/francoiscampbell/arduino-cmake) - This is the CMake project settings for the Arduino platform. [```[MPL]```][MPL]
* [polly ★423](https://github.com/ruslo/polly) - Collection of CMake toolchain files and scripts for cross-platform build and CI testing. [```[BSD2]```][BSD-2-Clause]
* [toolchains ★19](https://github.com/mosra/toolchains) - For crosscompiling with CMake. They are meant to be mainly used on ArchLinux. ```[NO LICENSE]```
* [cmake](https://github.com/staticlibs/cmake/tree/master/toolchains) - Collection of CMake toolchain files, mostly for static linking. [```[APACHE2]```][APACHE2]

## Examples / Templates

* [cmake-init ★265](https://github.com/cginternals/cmake-init) - Template for reliable, cross-platform C++ project setup using CMake. [```[LICENSE]```](https://github.com/cginternals/cmake-init/blob/master/LICENSE)
* [learning-cmake ★607](https://github.com/Akagi201/learning-cmake) - This is a simple CMake practice project which contains some different scenarios. [```[GPL2]```][GPL2]
* [cmake_test ★12](https://github.com/skebanga/cmake_test) - Small example project using CMake. ```[NO LICENSE]```
* [android-cmake](https://github.com/forexample/android-cmake) - Examples of using [ruslo/hunter ★1266](https://github.com/ruslo/hunter) package manager for an Android application. [```[BSD2]```][BSD-2-Clause]
* [hunter-simple](https://github.com/forexample/hunter-simple) - Example of downloading/installing dependencies using [ruslo/hunter ★1266](https://github.com/ruslo/hunter) package manager. [```[BSD2]```][BSD-2-Clause]
* [weather ★18 ⏳2Y](https://github.com/ruslo/weather) - Example of using [Hunter](http://github.com/ruslo/hunter) cross-platform package manager for CMake to build application which use Boost, CppNetlib.URI, GTest, JSON Spirit. Platforms: Windows (Visual Studio), Linux, Mac OS X + iOS. [```[BSD2]```][BSD-2-Clause]
* [package-example ★154](https://github.com/forexample/package-example) - Config mode of find_package (examples for [this](http://stackoverflow.com/questions/20746936/cmake-of-what-use-is-find-package-if-you-need-to-specify-cmake-module-path-an) Stack Overflow question). ```[NO LICENSE]```
* [CMakeTemplates ★42 ⏳1Y](https://github.com/OutOfOrder/CMakeTemplates) - Set of initial CMake templates that I use for every game port I work on. ```[NO LICENSE]```
* [minimal_cmake_example ★91](https://github.com/krux02/minimal_cmake_example) - Minimal CMake example, that covers dependencies and packaging. [```[CC0-1.0]```][CC0-1.0]
* [cmake-example ★70](https://github.com/bast/cmake-example) - Example project which demonstrates various CMake features. [```[BSD3]```][BSD-3-Clause]
* [cmake-examples ★398](https://github.com/ttroy50/cmake-examples) - Useful CMake examples in a tutorial format. [```[MIT]```][MIT]
* [cmake-templates ★178](https://github.com/district10/cmake-templates) - Some CMake Templates. Qt, Boost, OpenCV, C++11, etc. [```[MIT]```][MIT]
* [CppProjectTemplate ★162 ⏳2Y](https://github.com/Barthelemy/CppProjectTemplate) - Basic, but working, C++ project using CMake, boost and Doxygen. [```[MIT]```][MIT]
* [mini-cmake-qt ★96 ⏳1Y](https://github.com/euler0/mini-cmake-qt) - Minimal CMake template for Qt 5 projects. [```[LICENSE]```](https://github.com/euler0/mini-cmake-qt/blob/master/LICENSE)
* [CMake-VisualStudio-Example ★58 ⏳1Y](https://github.com/cognitivewaves/CMake-VisualStudio-Example) - CMake example for Visual Studio developers - [blog post](http://cognitivewaves.wordpress.com/cmake-and-visual-studio/). ```[NO LICENSE]```
* [Cpp-Project-Template ★51 ⏳3Y](https://github.com/NewProggie/Cpp-Project-Template) - C++ bootstrap project template including CMake build system. [```[MIT]```][MIT]
* [BASIS ★16 ⏳1Y](https://github.com/cmake-basis/BASIS) - CMake [BASIS](https://cmake-basis.github.io) makes it easy to create sharable software and libraries that work together. [```[BSD2]```][BSD-2-Clause]
* [OpenGL_CMake_Skeleton ★35 ⏳2Y](https://github.com/ArthurSonzogni/OpenGL_CMake_Skeleton) -  A ready to use CMake skeleton using GLFW, Glew and glm. [```[MIT]```][MIT]
* [coveralls-cmake-example](https://github.com/JoakimSoderberg/coveralls-cmake-example) - Example project for [coveralls-cmake ★66](https://github.com/JoakimSoderberg/coveralls-cmake). ```[NO LICENSE]```
* [cppbase ★87](https://github.com/kartikkumar/cppbase) - Template for a simple CMake-based C++ project. [```[MIT]```][MIT]
* [Arduino-CMake-Template ★3](https://github.com/maxbader/Arduino-CMake-Template) - Starting point for Arduino development using CMake. ```[NO LICENSE]```
* [c-template ★33](https://github.com/fletcher/c-template) - Boilerplate to set up a c project, include CuTest, CMake build setup. [```[MIT]```][MIT]
* [cpp_project_template ★26](https://github.com/duckie/cpp_project_template) - Simple template to start quickly a C++ project managed by CMake. [```[MIT]```][MIT]
* [cpp-boilerplate ★47](https://github.com/Lectem/cpp-boilerplate) - Template that aims to be a reference for modern CMake and CI. [```[MIT]```][MIT]
* [ci_helloworld ★142](https://github.com/ainfosec/ci_helloworld) - A simple example of how to setup a complete CI environment for C and C++. [```[MIT]```][MIT]
* [how-to-export-cpp-library ★7](https://github.com/robotology/how-to-export-cpp-library) - An OS-agnostic C++ library template sporting ctest and CI support, written in plain CMake with line-by-line guiding comments. [```[MIT]```][MIT]
* [ModernCppCI ★59 ⏳1Y](https://github.com/LearningByExample/ModernCppCI) - An example of doing a Modern C++ project with CI (although it uses non-modern CMake like ```include_directories()```). [```[MIT]```][MIT]
* [modern-cmake-sample ★77](https://github.com/pabloariasal/modern-cmake-sample) - Best practices and proper usage of CMake by using targets. ```[NO LICENSE]```
* [CMakeInstallExample ★9](https://github.com/DeveloperPaul123/CMakeInstallExample) - Installation example for a C++ project (Windows) with Cmake. ```[NO LICENSE]```
* [cpp14-project-template ★10](https://github.com/arnavb/cpp14-project-template) - A C++14 template with CI, tests, code coverage, docs and static analysis integration. [```[CC0-1.0]```][CC0-1.0]
* [cmake_templates ★38](https://github.com/acdemiralp/cmake_templates) - Templates for creating C++ libraries and executables (including conan). ```[NO LICENSE]```
* [cmake_snippets ★16](https://github.com/adishavit/cmake_snippets) - Short copy-pasteable CMake snippets. [```[BSD3]```][BSD-3-Clause]
* [cmake-cookbook ★30](https://github.com/dev-cafe/cmake-cookbook) - A huge CMake cookbook full of recipes. [```[MIT]```][MIT]

## Other

* [autocmake ★24](https://github.com/coderefinery/autocmake) - Using a autocmake.yml file [Autocmake](http://autocmake.readthedocs.io/en/latest/) composes CMake building blocks into a CMake project and generates CMakeLists.txt as well as a setup script, which serves as a front-end to CMakeLists.txt. [```[BSD3]```][BSD-3-Clause]
* [UseLATEX ★125](https://github.com/kmorel/UseLATEX) - Collection of CMake macros to simplify building LaTeX files. [```[BSD3]```][BSD-3-Clause]
* [python-cmake-buildsystem ★180](https://github.com/python-cmake-buildsystem/python-cmake-buildsystem) - Replacement buildsystem for CPython. [```[APACHE2]```][APACHE2]
* [scikit-build ★54](https://github.com/scikit-build/scikit-build) - Improved build system generator for CPython C extensions. [```[MIT]```][MIT]
* [protobuf-cmake ★26 ⏳2Y](https://github.com/jesperes/protobuf-cmake) - CMake build support for Google Protobufs. [```[BSD3]```][BSD-3-Clause]
* [node-cmake ★44](https://github.com/cjntaylor/node-cmake) - CMake-based build system for node.js native modules. [```[ISC]```][ISC]
* [cmake-font-lock ★21 ⏳1Y](https://github.com/Lindydancer/cmake-font-lock) - Advanced syntax coloring support for CMake scripts inside Emacs. [```[GPL]```][GPL]
* [stm32-cmake ★269](https://github.com/ObKo/stm32-cmake) - Used to develop applications for the STM32 - ST's ARM Cortex-M0(3,4,7) MCUs. [```[MIT]```][MIT]
* [autovala ★109](https://github.com/rastersoft/autovala) - Program that automatically generates CMake configuration files for your Vala project. [```[GPL]```][GPL]
* [catkin ★137](https://github.com/ros/catkin) - CMake-based build system that is used to build all packages in Robot Operating System (ROS). [```[BSD3]```][BSD-3-Clause]
* [suitesparse-metis-for-windows ★157](https://github.com/jlblancoc/suitesparse-metis-for-windows) - CMake scripts for painless usage of SuiteSparse+METIS. [```[BSD3]```][BSD-3-Clause]
* [cython-cmake-example ★110 ⏳1Y](https://github.com/thewtex/cython-cmake-example) - Utilities and example for using CMake to build Cython modules. [```[LICENSE]```](https://github.com/thewtex/cython-cmake-example/blob/master/LICENSE)
* [osg-3rdparty-cmake ★86](https://github.com/bjornblissing/osg-3rdparty-cmake) - CMake scripts for building OpenSceneGraph third party libraries. ```[MIXED LICENSE]```
* [cmake-d ★33](https://github.com/dcarp/cmake-d) - CMake for D2. [```[MIT]```][MIT]
* [cmakeprojectmanager2 ★44](https://github.com/h4tr3d/cmakeprojectmanager2) - Enhanced CMake Project Manager plugin for Qt Creator. ```[NO LICENSE]```
* [cmake-lint ★49 ⏳1Y](https://github.com/richq/cmake-lint) - Check for coding style issues in CMake files. cmakelint requires Python. [```[APACHE2]```][APACHE2]
* [git-cmake-format ★26](https://github.com/kbenzie/git-cmake-format) - Integrate clang-format into your CMake project hosted in a git repository. [```[LICENSE]```](https://github.com/kbenzie/git-cmake-format/blob/master/license.txt)
* [configure-cmake ★54 ⏳1Y](https://github.com/nemequ/configure-cmake) - configure-cmake is an autotools-style configure script for CMake-based projects. [```[CC0-1.0]```][CC0-1.0]
* [tbb ★68](https://github.com/wjakob/tbb) - Threading Building Blocks with CMake build. [```[APACHE2]```][APACHE2]
* [sqlite.cmake.build ★12 ⏳1Y](https://github.com/snikulov/sqlite.cmake.build) - CMake script for sqlite amalgamation. ```[NO LICENSE]```
* [cmake-ast ★14](https://github.com/polysquare/cmake-ast) - Python module to reduce a CMake file to an AST. [```[MIT]```][MIT]
* [cmake_format ★110](https://github.com/cheshirekow/cmake_format) - Source code formatter for CMakeLists.txt files. [```[GPL]```][GPL]
* [cmake-checks-cache ★8](https://github.com/cristianadam/cmake-checks-cache) - CMake checks cache helper modules. [```[MIT]```][MIT]

## License

This is released under the [**```Creative Commons Attribution 4.0 International```**](http://creativecommons.org/licenses/by/4.0/) License ```(CC BY 4.0)```.

[ISC]: https://opensource.org/licenses/ISC
[GPL]: https://www.gnu.org/licenses/gpl-3.0.html
[GPL2]: https://www.gnu.org/licenses/old-licenses/gpl-2.0.html
[LGPL]: https://www.gnu.org/licenses/lgpl-3.0.en.html
[MIT]: https://opensource.org/licenses/MIT
[BOOST]: http://www.boost.org/LICENSE_1_0.txt
[BSD-2-Clause]: https://opensource.org/licenses/BSD-2-Clause
[BSD-3-Clause]: https://opensource.org/licenses/BSD-3-Clause
[APACHE2]: http://www.apache.org/licenses/LICENSE-2.0
[CC0-1.0]: https://creativecommons.org/publicdomain/zero/1.0/
[MPL]: https://www.mozilla.org/en-US/MPL/2.0/
---
<p align="center">
	This list is a copy of <a href="https://github.com/onqtam/awesome-cmake">onqtam/awesome-cmake</a> with ranks
</p>
