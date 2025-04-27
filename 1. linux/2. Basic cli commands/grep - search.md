## Search text in file

```bash
    grep "hello" file.txt
    grep -i "hello" *           // search in all files
    grep -R "hello" *             // search in all files, in all the subdirectories (recursive)
    grep -i "hello" file.txt    // ignore case sensitive
    grep -vi "hello" file.txt   // search anything except hello
    grep -n "hello" file.txt    // show line
    grep -w "hello" file.txt    // search for whole words only
    grep -o "hello" file.txt    // show only matching part
```
