# Homework. 1: Bash
## Modern C++ for Computer Vision and Image Processing 
## Institute of Geodesy and Geoinformation

Tejas Acharya [Twitter](https://twitter.com/achte_te)

[Assignment](https://www.ipb.uni-bonn.de/html/teaching/modern-cpp/homeworks/homework_1.pdf)


To Run:
```sh
bash commands.sh
```
Source Code:
```sh
#Count how many lines are there in “data.dat”.
echo "Number of lines in data.dat: "
wc -l data.dat

# Count how many lines of those contain “dolor” or “dalor”?
echo "Number of lines that contain dolor or dalor in data.dat: "
egrep -w 'dolor|dalor' data.dat | wc -l

# Count how many words are there in “data.dat”?
echo "Number of words in data.dat: "
wc -w data.dat

# Count how many of those start with “mol”?
echo "Number of words that begin with \"mol\" in data.dat: "
grep -c '\bmol' data.dat
```