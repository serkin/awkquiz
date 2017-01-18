## Quiz

Small quizzes on languages we like to keep us in shape.


- PHP
  - [Patterns](php/patterns.md)
- Bash
  - [awk](bash/awk.md)
- SQL
  - [joins](sql/joins.md)

#### Example

- From `bash/samples/1.txt` print *second names*

Expected result

```txt
  Runolfsdottir
  Powlowski
  ....
  Walsh
```

<details>
  <summary>Answer</summary>

    awk '{ print $2 }' bash/samples/1.txt

</details>


#### How to use tutorial

```bash
  git clone https://github.com/serkin/quiz.git
  cd quiz

  awk '{ print $2 }' bash/samples/1.txt
```

#### Contribution

Send `pull request` to `master` branch.




- https://www.careercup.com/page
- https://www.codechef.com/
- http://www.exercism.io/
- https://github.com/MaximAbramchuck/awesome-interview-questions
- http://www.codequizzes.com/
