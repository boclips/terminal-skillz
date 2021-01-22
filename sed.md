# Sed

## Replace things with regexp!

```shell
echo 'hi there' | sed 's/i/ello/'
```

## Replace multiples

```shell
echo 'hi there' | sed 's/i/ello/;s/ere/ad/'
```

## Groups and backreferences

```shell
echo 'hi there' | sed 's/hi t\(here\)/\1 you go/'
```
