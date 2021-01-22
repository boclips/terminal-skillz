# Redirection

## Write standard output of command to a file

```shell
echo hi > some_file.txt
```

## Read a file into standard input of a command

```shell
cat < some_file.txt
```

(yes, cat can take an argument instead)

## Pipe standard output into another command

```shell
echo hi | cat
```

## Another way to get literals into a command (BASH only)

```shell
cat <<< hi
```
