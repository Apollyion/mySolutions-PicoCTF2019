__Question:__

- Can you find the flag in `/problems/first-grep--part-ii_1_4496a9af2273007b52d4a1adec323b76/files` on the shell server? Remember to use grep.

__Answer:__

- First i used the command `grep -nr 'picoCTF*' .`
```
-n            Show relative line number in the file
'yourString*' String for search, followed by a wildcard character
-r            Recursively search subdirectories listed
.             Directory for search (current directory)

```

- i saw the flag but it returned too much files and crap, so another command makes more precise `grep -r 'picoCTF'`

### picoCTF{grep_r_to_find_this_af11356f}
