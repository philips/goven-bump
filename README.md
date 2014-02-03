# goven-bump

Wrapper around github.com/kr/goven to grab the mercurial or git commit.

## Install

Make sure goven is in your PATH. You will need to use my fork until the prefix
patch gets merged.

```
go install github.com/philips/goven
```

Install bump-goven into your PATH:

```
curl https://raw2.github.com/philips/goven-bump/master/bump-goven > ~/bin/bump-goven
```

## Usage

```
$ go get github.com/stretchr/testify/assert
$ goven-bump github.com/stretchr/testify/assert
9cc77fa25329013ce07362c7742952ff887361f2
```
