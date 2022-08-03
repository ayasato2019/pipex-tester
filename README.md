# pipex-tester

## How to use
1. Place in the current directory of pipex Makefile
```
pipex 	-- Makefile
	-- tester-pipex.sh
```
2. Granting Permissions to tester-pipex.sh
```
chmod 755 tester-pipex.sh
```
3. Execution ./tester-pipex.sh
```
./tester-pipex.sh
```

## result
```
test 1 cat  wc
OK

test 2 ls wc -l
OK

test 3 grep a wc -m
OK

test 4 ls -a wc -m
OK

test 5 wc -l wc -m
OK

test 6 wc -l wc -m
OK

test 6 wc -l wc -m
OK

test 8 grep a wc -m
OK

test 9 lst echo
OK
```