# Static Analyzers
 This research project will focus on 3 free open source static analyzers for C++: Cppcheck, 
Clang, Source Trail. This page is for a little information on each of these analyzers. 

### Cppcheck
Cppcheck claims 
* unique code analysis to detect bugs and focuses on detecting undefined behavior and dangerous coding constructs
* very few false alarms
* unsound flow sensitive anaysis 
    * this is presented as a positive because other analyzers will more commonly use path sensitive analysis
* Documentation for undefined behavior
    * Dead pointers
    * Division by zero
    * Integer overflows
    * Invalid bit shift operands
    * Invalid conversions
    * Invalid usage of STL
    * Memory management
    * Null pointer dereferences
    * Out of bounds checking
    * Uninitialized variables
    * Writing const data
* see full documentation for [Cppcheck](http://cppcheck.sourceforge.net/)

### Clang
Clang is also a static analyzer for bugs in C++ typically found during runtime by analyzing source code
* although popular, documentation claims to be a work in progress
* [Documentation](https://clang-analyzer.llvm.org/scan-build.html)
* [Usage](https://clang-analyzer.llvm.org/scan-build.html#scanbuild_basicusage)

### Source Trail
