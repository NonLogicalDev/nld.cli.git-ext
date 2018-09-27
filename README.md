```
usage: git-ext [<flags>] <command> [<args> ...]

Command line utils extending git functionality.

Flags:
  -h, --help  Show context-sensitive help (also try --help-long and --help-man).

Commands:
  help [<command>...]
    Show help.


  phab list
    List current pending stacked revisions on the current branch.


  phab diff [<flags>] [<args>...]
    Update or create a diff based on current commit.

    --update=UPDATE  A spefic revision to update.

  stack edit [<target>]
    Launch interactive rebase session to edit a given commit from history.


  stack rebase-edit --prefix=PREFIX <file>
    Rewrite rebase todo file.

    --prefix=PREFIX  Target SHA prefix to mark for edits.
```