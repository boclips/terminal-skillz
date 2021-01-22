# History

## Boclips has a special setting for up/down

Type thing then press up - completes from history

## Standard history search

C-r then type
Press C-r again to cycle backwards
Press C-s to cycle forwards (assuming stty -ixon)

## Repeat last command

```shell
!!
```

## Paste last argument

M-.

e.g.

```shell
echo hi > you.txt
cat <M-.>
```
