# Squishy

## Pre-Alpha Notice

Squishy is in active prototype development and is not yet very functional. Please do check back soon!



## About

Squishy is a tool and scripting language for structured text transformation. The syntax is based on [semantic queries](https://en.wikipedia.org/wiki/Semantic_query) - hence the name.

It is designed to be a more flexible and powerful alternative to the classic patch/diff tools. Rather than relying on surrounding context and literally modifying text, Squishy scripts (or "squishes") transform through a virtual cursor that is guided with logical instructions. It's essentially a smarter patch tool, but obviously a bit heavier as a result.

The original inspiration behind Squishy was to create more generic and resilient patches to smali (decompiled Dalvik bytecode) in Android firmware modifications.