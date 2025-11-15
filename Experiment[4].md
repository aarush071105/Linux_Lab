## Experiment [4]: [Bash Scripting}
### Name:Aarush Prasad, Roll No.590027630, Date: 2025-09-13
### Aim:
* [For understanding the fundamentals of bash scripting.]
### Requirements
* [Any Linux Distro, any kind of text editor (vs code, vim, notepad, nano, etc)]
## Theory

* [To learn how to use bash scripting]

## Exercise 1: [Hello world script]
## Task Statement: [Basic Usage of Shell Scripts]
## Explanation: [I learrnt how to do the basic shell scripting]
## Command(s):
```
#!/bin/bash

echo "Hello, World!"
```

## Output:
<p align="center">
<img align="center" src="/img/helloworld.png" width="900">
</p>

## Exercise 2: [Personalized Greeting Script]
## Task Statement: [Basic Shell Script to callout user defined function.]
## Explanation: [The script accepts user input, assigns it to a variable, and outputs the stored value.]
## Command(s):
```
#!/bin/bash
echo "Enter your name: "
read name     # 'read' takes user input
echo "Hello, $name! Welcome to Shell Scripting."
```

## Output:
<p align="center">
<img align="center" src="/img/greeting.png" width="900">
</p>

## Result
* [I learnt how to use the basic bash scripting.]
## Challenges Faced & Learning Outcomes
* Challenge 1: [I was facing issues in remembering how to call a variable].
* Challenge 2: [I was forgetting how to do looping and take input from users].
* Challenge 3: [I was forgetting how to do proper formatting in bash scripting.]
## Learning: 
* How to takew input from user
* Learnt proper way to use formatting in bash script
## Conclusion
* I learnt how to do bash scripting.

## Exercise 3: [Arithmetic Operations in Shell Scripting]

## Task Statement:
* [Using Basic Arithmetic Operations in Shell Scripts]

## Explanation:
* [I learned how to execute arithmetic operations in a Bash script.]

## Command(s):
```
#!/bin/bash
echo "Enter first number: "
read num1
echo "Enter second number: "
read num2

echo "Addition: $((num1 + num2))"
echo "Subtraction: $((num1 - num2))"
echo "Multiplication: $((num1 * num2))"
echo "Division: $((num1 / num2))"
```

## Output:
<p align="center">
<img align="center" src="/img/number.png" width="900">
</p>

## Exercise 4:
* [Voting Eligibility]

## Task Statement:
* [Using if else loop to check if the person is eligible to vote or not.]

## Command(s):
```
#!/bin/bash
echo "Enter your age: "
read age

if [ $age -ge 18 ]
then
    echo "You are eligible to vote."
else
    echo "Sorry, you are not eligible to vote."
fi
```

## Output:
<p align="center">
<img align="center" src="/img/age.png" width="900">
</p>

## Result
* The Exercises were successfully completed for Basic Shell Scripting.