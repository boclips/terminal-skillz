# Looping

## Loop over files (reimplementation of ls)

for file in *
do
    echo $file
done

## Loop over space-separated things

for file in $(ls)
do
    echo $file
done
