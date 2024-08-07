# ULF Project Sub-Projects

The following projects make up the ULF Project:

## [runtime](https://github.com/uncommon-language-framework/runtime)

By far the largest project of the ULF. The Uncommon Language Runtime (ULR) contains the ULR Loader, the ULR JIT Compiler, GC/other runtime features, and the ULR C++ API (ULRAPI). Currently unportable to other machines (as ulrhost uses relative paths to load the standard library and standard debugger)

## [uilasm](https://github.com/uncommon-language-framework/uilasm)

UILAsm is an assembler for Uncommon Intermediate Language (UIL). It produces `.ulas` assemblies that can be loaded and run by the ULR.

## [debugger](https://github.com/uncommon-language-framework/debugger)

The Uncommon Language Debugger (ULD) is a simple debugger that uses the ULR C++ API (ULRAPI) to provide basic information about the runtime and program when a ULR breakpoint is reached.

## [stdlib](https://github.com/uncommon-language-framework/stdlib)

The ULF standard library is implemented in this project.

## [tool](https://github.com/uncommon-language-framework/tool)

The ULF tool aims to provide an easy way for developers to create, build, modify, and run ULF projects.

## [cblunt](https://github.com/uncommon-language-framework/cblunt)

A ULF language that aims to have similar syntax and semantics to C# but is compiled to run on the ULR.

## [spec](https://github.com/uncommon-language-framework/spec)

The specifiecation for all projects implemented by the ULF and all projects aiming to support execution on the ULF. Currently not up-to-date.