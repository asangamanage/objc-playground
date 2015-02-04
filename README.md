# objc-playground
Objective C learning area.

This is the quickest way to get your hands on to objective c. 

You don't even need Xcode. (Checkout the xcode branch for xcode project)
All you need is a mac and a terminal with vim.

## How to run ?

```
$> gcc -framework Foundation prog.m  -o prog && ./prog
```
Too long ?

## Use easy alias tool and set an alias !! ;)

https://github.com/asangamanage/productivity/blob/master/easy-alias.txt

```
$> aset gccf "gcc -framework Foundation"
```

Then new short version
```
$> ccf prog.m -o prog && ./prog
```
