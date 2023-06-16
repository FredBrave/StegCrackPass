# StegCrackPass
A password cracker for files hidden inside an image. This tool uses steghide to work.
# Requirements
steghide
# Usage
If you run the script without the parameters it will open a helpPanel which will tell you what parameters to use.
```shell
./StegCrackPass 
[*] Usage: ./StegCrackPass

	f) Image with hidden data

	w) Wordlist with passwords
```
To use it correctly you will need to execute it as follows.
```shell
./StegCrackPass -f CatHide.jpg -w wordlist


[+] Information obtained with password: 123456

```
