# File Encoder
This project was made to develop my skills in file handling and manipulation. It takes an input from a .txt file and encodes the characters based on a cipher I made and allows for the downloading of both the encoded and decoded formats.

## How It's Made

Packages Used: Python, tkinter, os

This encoding script works by creating a tkinter window where you can open a .txt file and encode it, or open an encoded .txt file and decode it. The encoding/decoding works by matching every character in the file to a 2D array, with the left column representing the input character and the right column representing the encoded character, and replacing the text letter by letter with the matching character.


## Lessons Learned

The main things I learned from this project is how to manipulate files. I learned how to prompt a window asking for a file to be opened, I learned how to read that file and get the filepath using the "os" package, how to manipulate and change the data within that file, and how to download new files to any format I'd like.

## Future Updates

While this script does the job of making a .txt file unreadable to humans, I would like to revamp this program to be able to take in all file formats, and to actually encode the file rather than just switching up some characters so computers can't even read it. Also the UI is terrible so a better looking one would be much nicer.

## How to Use

Simply run the script
