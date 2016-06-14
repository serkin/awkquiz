## AWK & SED Quiz

Check your knowledge in `awk&sed`

- Level 1 - [1 question](level1.md) (*1 point each*)
- Level 2 - [0 questions](level2.md) (*5 points each*)
- Level 3 - [0 questions](level3.md) (*10 points each*)

#### Example

- From `samples/1.txt` print *second* column

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

</details>


#### How to use tutorial

```bash
  git clone https://github.com/serkin/awkquiz.git
  cd awkquiz
  
  awk '{ print $2 }' samples/1.txt
```

#### Scores

`0 - 10 points` - Need more training? Look through some of the resources below and try again.

`11 - 20 points` - Good job.

`21 - 30 points` - :+1: Can you add some questions to our quiz?

#### Contribution

Send `pull request` to `master` branch.


#### Where to learn about `awk` & `sed`

##### Articles

- [Article 1](level3.md)

##### Courses

##### Books
