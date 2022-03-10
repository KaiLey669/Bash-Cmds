# Bash-Cmds

tail -n 40 file.txt > file2.txt
head -n 10 file2.txt > file3.txt
cat file2.txt | grep "коко" > tmp.txt
sed -i 's/коко/куку/g' tmp.txt
head -n 3 tmp.txt >> file3.txt
cat file3.txt | sort | uniq > file3.txt
sort file3.txt | uniq -c

![screen](https://user-images.githubusercontent.com/80998934/157645814-1ccfd412-be8c-4c13-8678-759ad3e97350.png)
