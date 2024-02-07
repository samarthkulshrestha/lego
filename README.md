<div align="center">
<h1>LEGO</h1>

samarth kulshrestha

![release version](https://img.shields.io/github/v/release/samarthkulshrestha/lego?color=%23a039fa&include_prereleases&style=for-the-badge)
![code quality](https://img.shields.io/codefactor/grade/github/samarthkulshrestha/lego/main?style=for-the-badge)
![top language](https://img.shields.io/github/languages/top/samarthkulshrestha/lego?color=%234877f7&style=for-the-badge)
<br>
![license](https://img.shields.io/github/license/samarthkulshrestha/lego?color=%23f2e85a&style=for-the-badge)
![release date](https://img.shields.io/github/release-date-pre/samarthkulshrestha/lego?color=%23f76ad4&style=for-the-badge)
<br/><br/><br/>
![lego logo](assets/lego.png)
<br/><br>
</div>

## Introduction

**LEGO** is my implementation of a memory allocator in C. This project is not
meant for production use; I built this purely as an exercise to get a better
understanding of how memory allocation works under the hood.

The `heap_alloc()` and `heap_free()` functions allocate and deallocate memory
respectively.

The motive of this project wasn't performance, by any stretch of the
imagination. Most of the operations in this algorithm run in linear time. This
codebase was meant to be concise and self-documenting enough to be easy to
follow.

## Usage

+ clone the repository
```console
$ git clone https://github.com/samarthkulshrestha/lego.git
$ cd lego
```

+ compile the build-system
```console
$ cc -o nob bld/nob.c
```

+ compile the codebase
```console
$ ./nob
```

+ run the executable
```console
$ ./target/main
```

## Contribute

+ I <3 pull requests and bug reports!
+ Don't hesitate to [tell me my code-fu sucks](https://github.com/samarthkulshrestha/lego/issues/new), but please tell me why.
+ Feel free to fork the project and try out your own optimisations.

## License

LEGO is licensed under the MIT License.

Copyright (c) 2024 Samarth Kulshrestha.
