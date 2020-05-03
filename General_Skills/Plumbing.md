__Question:__

- Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag? Connect to `2019shell1.picoctf.com 18944`

__Answer:__

- Used the comand `nc 2019shell1.picoctf.com 18944 >> plumbing.txt` to save the echo to _plumbing.txt_
- Then _cat_ of the file was too big so i used the command `cat plumbing.txt | grep picoCTF`

### picoCTF{digital_plumb3r_1d5b7de7}
