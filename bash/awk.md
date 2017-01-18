# AWK quiz


- From `samples/1.txt` print *second names*

Expected result

```txt
  Runolfsdottir
  Powlowski
  ....
  Walsh
```

<details>
  <summary>Answer</summary>

    awk '{ print $2 }' samples/1.txt

  Alternative

    cut -d ' ' -f 2 samples/1.txt


</details>

<hr>

- From `samples/2.txt` print *names*

Expected result

```txt
  Cortney
  Mya
  ....
  Steve
```

<details>
  <summary>Answer</summary>

    awk -F ',' '{ print $1 }' samples/2.txt

</details>

<hr>



#### Where to learn about `awk`

##### Articles


##### Courses

##### Books
