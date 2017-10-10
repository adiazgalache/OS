# Operating System Cheats

### Files System

```bash
stat -c "%a %n" *
```


### Sed

*_Searching and replacing text in directory_*

```bash
grep -rl . | xargs sed -i 's/src="\//src="\/app\/2\//g'
```
