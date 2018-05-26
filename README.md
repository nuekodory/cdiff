# cdiff
Column-selected DIFF - diff tool that compares specified column(s)
simple script that use `cut` and `diff`. with `$(mktemp)` scheme.

## use like this:
`cdiff -d "," -f 1,3 file1.csv file2.csv`

## install
put cdiff file to /usr/local/bin/ or alike.
```
git clone https://github.com/nuekodory/cdiff.git
cd cdiff
sudo cp cdiff /usr/local/bin/
sudo chmod 755 /usr/local/bin/cdiff
```
make sure you change permission to executable

## usage

like `cut` command,
 - you MUST specify column# to compare
 - you CAN specify deliminator that `cut` command treat them as separator
 
