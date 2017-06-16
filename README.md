## Linking flags

`-rdynamic` Pass the flag -export-dynamic to the ELF linker, on targets that support it. This instructs the linker to add all symbols, not only used ones, to the dynamic symbol table. This option is needed for some uses of dlopen or to allow obtaining backtraces from within a program. 

## Unsorted flags

`-I\<path\>`
`-O2`
`-Os`
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
`-s`
`-std=c99`
`-std=gnu99`
