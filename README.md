# boilr-docs

> Boilr templates for docs.

> **Retired:** boilr templates predate AI coding tools and no longer make sense. This repository is archived read-only and will receive no further updates.

---

## Purpose
Boilr templates for docs.

The following files are generated:

```
.
|-- .verb.md
`-- docs
    |-- author.md
    `-- contributing.md

1 directory, 3 files

```

## Installation
Install [boilr](https://github.com/tmrts/boilr) first. 

Then use 

```
$ boilr download stefanwalther/boilr-docs <template-tag>
```

e.g.
```
$ boilr download stefanwalther/boilr-docs boilr-docs
```

## Usage
### Download the template

```
$ boilr template download stefanwalther/boilr-docs <template-tag>
```

### Fork, modify locally and save it

```
$ git clone stefanwalther/boilr-docs
```

cd into it, then

```
$ boilr template save $(PWD) <template-tag>

# e.g. 
$ boilr template save $(PWD) boilr-docs
```

if you have for force the local updates, use

```
$ boilr template save $(PWD) <template-tag> -f
```

### Use it

```
$ boilr template use boilr-docs .
```

### Get all templates

Get a list of all - locally installed - templates:

```
$ boilr template list
```

## About

### Related projects
Some related projects:

- [stefanwalther/boilr-editorconfig](https://github.com/stefanwalther/boilr-editorconfig)
- [stefanwalther/boilr-gitignore](https://github.com/stefanwalther/boilr-gitignore)
 

### Author
**Stefan Walther**

* [twitter/waltherstefan](http://twitter.com/waltherstefan)  
* [github.com/stefanwalther](http://github.com/stefanwalther) 
* [LinkedIn](https://www.linkedin.com/in/stefanwalther/) 
* [qliksite.io](http://qliksite.io)

### License
MIT

