# git-clang-format-style-check

```
Usage :  style-check [options] <commit>

Checks code style of files changed since <commit>.  Only pays attention to
added, changed, or modified files. Return 0 if all files conform to code
style, and otherwise if any file does not conform.

This tool requires clang-format to be available in the path.

Options:
-h            Display this message and exit
-v            Verbose output
-w            Print warning if the index and working directory are not in
              pristine state.
-W            Abort with error if the index and working directory are not
              in pristine state. This takes precedence over -w if defined.
```
