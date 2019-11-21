# Sphex VCS

File level VCS inspired by RCS and GIT

```bash
# init repo
$ spx init

# check in file changes
$ spx ci -m 'Updated greeting' hello.txt

# see changes
$ spx log hello.txt
7bf58c3 2019-11-20 22:05:54 Juan D.. Updated greeting
9a87b41 2019-11-20 19:18:15 Juan D.. Change file permissions
1031ebf 2019-11-20 19:17:26 Juan D.. Changed greeting
57698bb 2019-11-20 19:16:47 Juan D.. First commit

# checkout specific changes
$ spx co --commit=1031ebf hello.txt
```
