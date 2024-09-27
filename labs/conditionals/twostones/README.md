# CS0 Lab - Conditionals and Unit testing

Possible Points: 100

Write a Python program to solve the Kattis problem called twostones [https://open.kattis.com/problems/twostones](https://open.kattis.com/problems/twostones). Read the problem statement carefully to design a correct solution.

## Lab Instructions

- Open your CS0Lab-... repo in VS Code
- Create lab folder **twostones** inside your CS0Lab-... repository
- Inside the lab folder, create two files: main.py and test_main.py
- Type the partial code stub provided in main.py and test_main.py files and fix all FIXMEs. (80 points)
- Follow best programming practices by using proper white spaces, comments, etc.

```note
IMPORTANT: Never ask the user telling what data to enter for Kattis problems. Kattis knows what to enter. 
Directly read the input. Print only the answer as displayed in the sample output. 
Print as asked: nothing less; nothing more!
Kattis is a computer program that provides specific input and expects exact output – to a space to give the correct verdict.
```

- Run unit test using pytest and create screenshot when all the test cases pass. Install pytest if required. Pick one of the following ways to run pytest.

```bash
  $ pytest --version
  $ pip install -U pytest
  $ pytest test_main.py
  $ python -m pytest test_main.py
```

- Test the whole program manually. While testing, provide input using the same format as described in the Input section and shown in input samples.
- Upload only the solution script to Kattis for testing. You can test your solution as many times as you wish. Kattis uses its own hidden test cases to test your program against. However, your goal is to get the accepted verdict in the first try.
- Create screenshots showing your local testing and the kattis final Accept verdict and save them to the lab folder. (10 points)
- Update your README file (10 points) as shown here: [https://github.com/rambasnet/csci000-astudent](https://github.com/rambasnet/csci000-astudent)

## Submission

- Make sure to format the code using pep8 or black before submission.
- Add all the relevant source file(s), documents, and screenshots into the correct lab folder and do a final add, commit, and push before the due date.

```bash
$ git pull
$ git status
$ git add <filename>… - add each file in the red that is part of this lab
$ git status
$ git commit -m "Final Submission"
$ git push
$ git status
```

- Check and make sure the files are actually pushed to your GitHub repo.
