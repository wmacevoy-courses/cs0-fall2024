# CS0 Lab - Lists and Unit testing

Possible Points: 100

Write a Python program to solve the Kattis problem called pet: [https://open.kattis.com/problems/pet](https://open.kattis.com/problems/pet). Read the problem statement carefully to design a correct solution.

## Lab Instructions

1. Open your CS0Lab-... repo in VS Code
2. Create lab folder **lists** inside your CS0Lab-... repository
3. Inside the lab folder, create two files: pet.py and test_pet.py
4. Type the partial code stub provided in the lab folder and fix all FIXMEs. (80 points)
5. Follow best programming practices by using proper white spaces, comments, etc.

```text
IMPORTANT: Never ask the user telling what data to enter for Kattis problems. Kattis knows what to enter.
Directly read the input. Print only the answer as displayed in the sample output.
Print as asked: nothing less; nothing more!
Kattis is a computer program that provides specific input and expects exact output – to a space to give the correct verdict.
```

6. Unittest all the important functions using pytest. Install pytest if required.

```bash
  $ pytest --version
  $ pip install -U pytest
  $ pytest .
  $ python -m pytest .
```

7. Test the whole program manually. While testing, provide input using the same format as described in the Input section and shown in input samples.
8. Upload only the solution script to Kattis for testing. You can test your solution as many times as you wish. Kattis uses its own hidden test cases to test your program against. However, your goal is to get the accepted verdict in the first try.
9. Create screenshots showing your local testing and the kattis final Accept verdict and save them to the lab folder. (10 points)
10. Update your README file (10 points) as shown here: [https://github.com/rambasnet/csci000-astudent](https://github.com/rambasnet/csci000-astudent)

## Submission

Add all the relevant source file(s), documents, and screenshots into the correct lab folder and do a final add, commit, and push before the due date.

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
