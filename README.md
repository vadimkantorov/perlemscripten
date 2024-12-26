# Primer script for basic build of a recent Perl 5.40.0 with Emscripten
> [!WARNING]
> No tests besides a `node` run with `-e 'print("hello world\n");'`
> No hooks for JavaScript or repeated runs / reinitialization - likely would need https://github.com/haukex/emperl5/blob/emperl_v5.28.1/perlmain_noexit_patch
> Unstripped, builds in statically all Perl modules from the standard install

[`.github/workflows/buildperlwasm.yml`](.github/workflows/buildperlwasm.yml)

# References
- https://github.com/Perl/perl5/issues/22793
- https://webperl.zero-g.net/
- https://webperl.zero-g.net/building.html
- https://github.com/Perl/perl5/compare/blead...haukex:emperl5:emperl_v5.30.0
- https://github.com/haukex/webperl
