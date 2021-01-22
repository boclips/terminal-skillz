# Redirection

## Write standard output of command to a file

echo hi > some_file.txt

## Read a file into standard input of a command

cat < some_file.txt

(yes, cat can take an argument instead)

## Pipe standard output into another command

echo hi | cat

## Another way to get literals into a command (BASH only)

cat <<< hi
