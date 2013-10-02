# NAME

Devel::CheckCompiler - Check the compiler's availability

# SYNOPSIS

    use Devel::CheckCompiler;

    check_c99_or_exit();

# DESCRIPTION

Devel::CheckCompiler is checker for compiler's availability.

# FUNCTIONS

- `check_c99()`

    Returns true if the current system has a working C99 compiler, false otherwise.

- `check_c99_or_exit()`

    Check the current system has a working C99 compiler, if it's not available, exit by 0.

- `check_compile($src: Str)`

    Compile `$src` as C code. Return 1 if it's available, 0 otherwise.

# AUTHOR

Tokuhiro Matsuno <tokuhirom AAJKLFJEF@ GMAIL COM>

# SEE ALSO

[ExtUtils::CBuilder](http://search.cpan.org/perldoc?ExtUtils::CBuilder)

# LICENSE

Copyright (C) Tokuhiro Matsuno

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.
