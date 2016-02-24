# jrsj-report

Latex file for JRSJ

[![Build Status](https://travis-ci.org/furushchev/jrsj-report-template.svg)](https://travis-ci.org/furushchev/jrsj-report-template)

### 1. Prerequisities

```bash
# only for ubuntu 12.04
$ sudo apt-add-repository ppa:texlive-backports/ppa
$ sudo apt-get update
```

### 2. Edit LaTeX files

### 3. Make pdf

```bash
$ make
```

### 4. Release pdf

- Install [Travis Command Line Tool](https://github.com/travis-ci/travis.rb#installation)
- Enable Travis

  ```bash
  travis enable
  travis setup releases --force
```

- Push your tag by `git push --tag`. Then you can watch pdf in github releases.

### Optional. cleaning

```bash
$ make clean
# or
$ make wipe
```