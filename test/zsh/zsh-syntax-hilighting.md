## This highlighter defines the following styles:

- [x] `unknown-token` - unknown tokens / errors
- [x] `reserved-word` - shell reserved words (`if`, `for`)
- [x] `alias` - aliases
- [x] `suffix-alias` - suffix aliases (requires zsh 5.1.1 or newer)
- [x] `builtin` - shell builtin commands (`shift`, `pwd`, `zstyle`)
- [ ] `function` - function names
- [ ] `command` - command names
- [x] `precommand` - precommand modifiers (e.g., `noglob`, `builtin`)
- [x] `commandseparator` - command separation tokens (`;`, `&&`)
- [ ] `hashed-command` - hashed commands
- [x] `path` - existing filenames
- [x] `path_pathseparator` - path separators in filenames (`/`); if unset, `path` is used (default)
- [x] `path_prefix` - prefixes of existing filenames
- [x] `path_prefix_pathseparator` - path separators in prefixes of existing filenames (`/`); if unset, `path_prefix` is used (default)
- [x] `globbing` - globbing expressions (`- [ ] .txt`)
- [x] `history-expansion` - history expansion expressions (`!foo` and `^foo^bar`)
- [x] `single-hyphen-option` - single-hyphen options (`-o`)
- [x] `double-hyphen-option` - double-hyphen options (`--option`)
- [x] `back-quoted-argument` - backtick command substitution (`` `foo` ``)
- [x] `back-quoted-argument-unclosed` - unclosed backtick command substitution (`` `foo ``)
- [x] `single-quoted-argument` - single-quoted arguments (`` 'foo' ``)
- [x] `single-quoted-argument-unclosed` - unclosed single-quoted arguments (`` 'foo ``)
- [x] `double-quoted-argument` - double-quoted arguments (`` "foo" ``)
- [x] `double-quoted-argument-unclosed` - unclosed double-quoted arguments (`` "foo ``)
- [x] `dollar-quoted-argument` - dollar-quoted arguments (`` $'foo' ``)
- [x] `dollar-quoted-argument-unclosed` - unclosed dollar-quoted arguments (`` $'foo ``)
- [x] `rc-quote` - two single quotes inside single quotes when the `RC_QUOTES` option is set (`` 'foo''bar' ``)
- [x] `dollar-double-quoted-argument` - parameter expansion inside double quotes (`$foo` inside `""`)
- [x] `back-double-quoted-argument` -  backslash escape sequences inside double-quoted arguments (`\"` in `"foo\"bar"`)
- [x] `back-dollar-quoted-argument` -  backslash escape sequences inside dollar-quoted arguments (`\x` in `$'\x48'`)
- [x] `assign` - parameter assignments (`x=foo` and `x=( )`)
- [x] `redirection` - redirection operators (`<`, `>`, etc)
- [x] `comment` - comments, when `setopt INTERACTIVE_COMMENTS` is in effect (`echo # foo`)
- [x] `arg0` - a command word other than one of those enumerated above (other than a command, precommand, alias, function, or shell builtin command).
- [x] `default` - everything else