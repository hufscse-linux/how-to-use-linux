# Exercises

아래 명령어들을 하나씩 입력해본다.

## cat, more, less

아래 세 명령어의 결과가 어떻게 다른지 확인한다.

### cat

    $ cat rbtree.txt

### more

    $ more rbtree.txt

### less

    $ less rbtree.txt

## ls, mkdir, rmdir

### ls : List of Directory's Files

    $ ls
    $ ls -a
    $ ls -l
    $ ls -al
    $ ls -alh
	$ ls /
	$ ls /usr/lib -alh

### mkdir : Make Directory

    $ mkdir dir
	$ mkdir -p dir2/dir3/dir4/dir5

### rmdir : Remove Directory

    $ rmdir dir
	$ rmdir dir3/dir4/dir5

## touch, mv, cp, rm

### touch : make empty file

    $ touch test
    $ ls -al test

### touch : ???

    $ touch rbtree.txt
    $ ls -alh rbtree.txt

### mv : Move or Rename File

    $ touch origin
	$ mv origin renamed

### cp : Copy file

    $ touch original
	$ cp original copied
	$ cp -rf * /tmp

### rm : Remove file

    $ rm renamed
	$ rm copied
	$ rm renamed copied
	$ rm -rf dir2

## man : Manual

    $ man cat
	$ man ls
	$ man cp
	$ man mkdir
	$ man rm

## grep : Grep matched line

    $ grep red-black rbtree.txt
	$ grep -n red-black rbtree.txt
	$ grep -rn red-black .
