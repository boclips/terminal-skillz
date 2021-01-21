# Grep

## Filter results

ls | grep nav

## Takes a regexp

ls | grep n.v

## Can be case insensitive

ls | grep -i N.V

## Get names of files that contain 'ls' in all .txt files

grep -l ls *.txt

(the *.txt is shell, not grep)

## Open all of those files in Vim

vim $(grep -l ls *.txt)

(they become buffers - navigate through them with :next and :previous)

## Replace all instances of 'ls' with 'poop' in those files (even inside words)

sed -i 's/ls/poop/' $(grep -l ls *.txt)

(-i is for change-in-place)

## git grep (uses the git index - faster)

git grep Filter
