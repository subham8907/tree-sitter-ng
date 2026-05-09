# Third-party notices

This repository includes a small number of bundled third-party files that are
used for native builds and runtime loading.

## OpenJDK 11 JNI headers

The JNI, JAWT, and Windows AccessBridge header files under `include/jni` are
copied from OpenJDK 11. Their license texts are included under
`third_party_licenses/openjdk-11`.

## Gradle wrapper

The Gradle wrapper files are provided by Gradle. The full Apache License 2.0
text is included under `third_party_licenses/gradle`.

## Unicode ConvertUTF

`tree-sitter/src/main/c/ConvertUTF.c` and
`tree-sitter/src/main/c/ConvertUTF.h` are Unicode conversion source files. The
Unicode license text is included under `third_party_licenses/unicode`.

## Zig

The native build downloads Zig to compile the bundled native artifacts. The Zig
license text is included under `third_party_licenses/zig`.

## Minisign

The native build downloads Minisign to verify Zig release signatures. The
Minisign license text is included under `third_party_licenses/minisign`.

## Android NDK

The Android native build can use or download Android NDK r27c. The Android SDK
license text referenced by the NDK package metadata is included under
`third_party_licenses/android-ndk`.

The Android NDK Clang/LLVM toolchain is based on the LLVM project. The upstream
LLVM license text, including the Apache License 2.0 with LLVM exceptions, is
included under `third_party_licenses/android-ndk/LLVM-CLANG-NOTICE`. It is
copied from
https://raw.githubusercontent.com/llvm/llvm-project/main/llvm/LICENSE.TXT.

## tree-sitter core

The core `tree-sitter` native library is built from the tree-sitter source
archive. Its license text is included under
`third_party_licenses/tree-sitter-core`.

The tree-sitter core source also includes Unicode data/code under
`lib/src/unicode`; that license text is included under
`third_party_licenses/tree-sitter-core/lib-src-unicode`.

## Grammar sources

The checked-in grammar native artifacts are compiled from downloaded
tree-sitter grammar source archives. Each grammar license text is included under
`third_party_licenses/grammars/<grammar-project>/LICENSE`.
