## Warning flags

`-Wconversion` Warn about things like assigning an `int` to a `char`.

## Linking flags

`-rdynamic` Pass the flag -export-dynamic to the ELF linker, on targets that support it. This instructs the linker to add all symbols, not only used ones, to the dynamic symbol table. This option is needed for some uses of dlopen or to allow obtaining backtraces from within a program. 

## Optimization flags

`-O2`

`-Os` Optimize for size. -Os enables all -O2 optimizations that do not typically increase code size. It also performs further optimizations designed to reduce code size.

## Unsorted flags

`-I\<path\>`
`-Wall`
`-Werror` 
`-Wextra`
`-Wformat-security`
`-Wformat=2`
`-Winit-self`
`-Winline`
`-Wjump-misses-init`
`-Wlarger-than-65500`
`-Wmissing-declarations`
`-Wmissing-format-attribute`
`-Wmissing-noreturn`
`-Wmissing-prototypes`
`-Wnested-externs`
`-Wno-unused-value` 
`-Wold-style-definition`
`-Wp,-D_FORTIFY_SOURCE=2`
`-Wpacked`
`-Wpointer-arith`
`-Wredundant-decls`
`-Wstrict-aliasing=2`
`-Wstrict-prototypes`
`-Wswitch-enum`
`-Wundef`
`-Wunsafe-loop-optimizations`
`-Wwrite-strings`
`-fPIC`
`-fno-common`
`-fno-strict-aliasing`
`-g`
`-ggdb3`
`-pg` For profiling your code.
`-pedantic`
`-s`
`-std=c99`
`-std=gnu99`
