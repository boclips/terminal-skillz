# Sed

## Replace things with regexp!

echo 'hi there' | sed 's/i/ello/'

## Replace multiples

echo 'hi there' | sed 's/i/ello/;s/ere/ad/'

## Groups and backreferences

echo 'hi there' | sed 's/hi t\(here\)/\1 you go/'
