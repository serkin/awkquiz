# AWK quiz


- What command takes you back to previous working directory


<details>
  <summary>Answer</summary>

    cd -

</details>

<hr>

- How to create directories ~/dir1 and ~/dir2 in single command


<details>
  <summary>Answer</summary>

    mkdir ~/{folder1,folder2}

</details>

<hr>



- How to create directory ~/a/b/c/dir and all intermediate directories in a single command


<details>
  <summary>Answer</summary>

    mkdir -p ~/a/b/c/dir

</details>

<hr>



- How to port tunnel to remote server and connect to port 27017


<details>
  <summary>Answer</summary>

    ssh -L 27017:localhost:27017 username@yourmongodb.host

</details>

<hr>


- How to run a command as another user


<details>
  <summary>Answer</summary>



</details>

<hr>



- How to port tunnel to remote server and connect to port 27017


<details>
  <summary>Answer</summary>

    ssh -L 27017:localhost:27017 username@yourmongodb.host

</details>

<hr>


- Find out who is listening on port 3000


<details>
  <summary>Answer</summary>

    lsof -i :3000

</details>

<hr>



- How to count lines in file


<details>
  <summary>Answer</summary>

    # Count lines
    wc -l , characters (-m), words (-w) and bytes (-c).

</details>

<hr>


- Remove all files with `.sh` extension



<details>
  <summary>Answer</summary>

    find . -name "*.sh"| xargs rm -rf

  Alternative

    find . -name "*.sh" -exec rm -rf '{}' \

</details>

<hr>


sed 's/Hello/Hi/g' test.txt
grep 'student` file1.txt


$ cat sample.txt
This is a sample text file
$ cat sample1.txt
This is another sample file
$ cmp sample.txt sample1.txt
sample.txt sample1.txt differ: byte 10, line 1

#### Where to learn about `awk`

https://github.com/jlevy/the-art-of-command-line
https://github.com/awesome-lists/awesome-bash
https://github.com/alebcay/awesome-shell

##### Articles


##### Courses

##### Books



https://github.com/alebcay/awesome-shell
https://github.com/awesome-lists/awesome-bash
https://git.framasoft.org/ErwanT/awesome-shell
https://google.github.io/styleguide/shell.xml
http://mywiki.wooledge.org/BashPitfalls
http://tldp.org/HOWTO/Bash-Prog-Intro-HOWTO.html#toc
https://github.com/rtomayko/git-sh/blob/master/git-completion.bash
https://github.com/cfenollosa/bashblog
http://www.tldp.org/LDP/Bash-Beginners-Guide/html/sect_07_01.html
https://github.com/arzynik/dockerphish/blob/master/run.sh
http://wiki.bash-hackers.org/doku.php
