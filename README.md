<h1 align="center">
	42cursus' ft_printf
</h1>

<p align="center">
	<b><i>Development repo for 42cursus' ft_printf project</i></b><br>
	For further information about 42cursus and its projects, please refer to <a href="https://github.com/iker-gonzalez/42_cursus"><b>42cursus repo</b></a>.
</p>

<p align="center">
	<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/iker-gonzalez/ft_printf?color=blueviolet" />
	<img alt="Number of lines of code" src="https://img.shields.io/tokei/lines/github/iker-gonzalez/ft_printf?color=blueviolet" />
	<img alt="Code language count" src="https://img.shields.io/github/languages/count/iker-gonzalez/ft_printf?color=blue" />
	<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/iker-gonzalez/ft_printf?color=blue" />
	<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/iker-gonzalez/ft_printf?color=brightgreen" />
</p>

<h3 align="center">
	<a href="#%EF%B8%8F-about">About</a>
	<span> · </span>
	<a href="#%EF%B8%8F-usage">Usage</a>
	<span> · </span>
	<a href="#-testing">Testing</a>
</h3>

---

## 🗣️ About

	🚀 TLDR: this project consists of coding a library that contains a simplified version of the printf function.
  
For detailed information, refer to the [**subject of this project**](https://github.com/iker-gonzalez/42_cursus/blob/main/_PDFs/en.subject_ft_printf.pdf)


## 🛠️ Usage

### Requirements

The library is written in C language and thus needs the **`gcc` compiler** and some standard **C libraries** to run.

### Instructions

**1. Compiling the library**

To compile the library, run:

```shell
$ cd path/to/ft_printf && make
```

**2. Using it in your code**

To use the library functions in your code, simply include its header:

```C
#include "ft_printf.h"
```

and, when compiling your code, add the required flags:

```shell
-lftprintf -L path/to/libftprintf.a -I path/to/ft_printf.h
```

### Testing

You can use any of this third-party testers:

* [gavinfielder/pft](https://github.com/gavinfielder/pft)
* [Mazoise/42TESTERS-PRINTF](https://github.com/Mazoise/42TESTERS-PRINTF)
* [HappyTramp/ft_printf_test](https://github.com/HappyTramp/ft_printf_test)
* [t0mm4rx/ftprintfdestructor](https://github.com/t0mm4rx/ftprintfdestructor)
* [charMstr/printf_lover_v2](https://github.com/charMstr/printf_lover_v2)
