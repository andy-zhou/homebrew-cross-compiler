# Cross Compiler (Homebrew)

Modified the `i686-elf-*` formulas to also include
freestanding C++ libraries.

For more information, see [this](https://www.reddit.com/r/osdev/comments/1066sdh/im_compling_in_a_freestanding_environment_with_c/) and [this](https://www.reddit.com/r/osdev/comments/10lfdjy/for_those_using_c_freestanding_libraries_with/) Reddit thread.

## Original Formulae

- [i686-elf-binutils](https://github.com/Homebrew/homebrew-core/blob/7dfd89029a400f4d27de43832fe3958ca7bbd541/Formula/i/i686-elf-binutils.rb)
- [i686-elf-gcc](https://github.com/Homebrew/homebrew-core/blob/7dfd89029a400f4d27de43832fe3958ca7bbd541/Formula/i/i686-elf-gcc.rb)
- [i686-elf-gdb](https://github.com/Homebrew/homebrew-core/blob/7dfd89029a400f4d27de43832fe3958ca7bbd541/Formula/i/i386-elf-gdb.rb)
