# Looping

## Loop over files (reimplementation of ls)

```shell
for file in *
do
    echo $file
done
```

## Loop over space-separated things

```shell
for file in $(ls)
do
    echo $file
done
```
