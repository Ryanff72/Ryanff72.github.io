---
layout: default
title: Conditions
parent: Learn To Code
nav_order: 5
---

# Conditions
If statements can be used to check the value of one variable in relation to another. As an example, let's ask the user a yes or no question, and then give a 
response based off of the user's input. When using **if** statements, we will use **two equal signs** to check if one value is equal to another. This is different than using one equal sign because one equal sign will set the first value equal to the second value (for example, if b = 2 and a = 0 and you write a = b, a will equal 2).
<br><br>
<code>print("Do you like my new hat? (respond with 'yes' or 'no')")</code><br>
<code>response = input()</code><br><br>
<code>if response == "yes":</code><br>
<code>  &nbsp;&nbsp;&nbsp;&nbsp;print("Thank you very much!")</code><br>
<code>if response == "no":</code><br>
<code>  &nbsp;&nbsp;&nbsp;&nbsp;print("How could you say that! I'll have you know my grandmother made it for me!")</code><br><br>
Pay attention to the **syntax**, or how if statements are written. The code that will be run if the **if** statement is true is after the **colon** and **tabbed over.** When ran, the conversation should flow as follows:<br><br>
![image](https://user-images.githubusercontent.com/64915846/189805710-88ef04b1-1c15-4edc-9dbd-92b5ed800430.png){: width="450"}
## Challenge 2
Before you go on, try making a question with more than 2 possible responses. Go on! This tutorial will be here for you when you come back.
## Else If and Else statements
**Else if** and **else** statements are useful if you need to account for alternative values a variable can have. **Else if** statements go below an **if** statement, and will only be ran if the **if** statement above them is false. If you want to do something if all **if** and **else if** statements return false, then you can use an **else** statement. Here is a flow chart to help you to understand the concept better.<br><br>
**if**  >  **elif**  >  **elif** > **elif**  >  ...  >  **else**<br><br>
Let's alter the code above to make use of **else if** and **else** statements. Pay attention to the **syntax**!!! Else if statements are written as **elif** in python.
<br><br>
<code>print("Do you like my new hat? (respond with 'yes' or 'no')")</code><br>
<code>response = input()</code><br><br>
<code>if response == "yes":</code><br>
<code>  &nbsp;&nbsp;&nbsp;&nbsp;print("Thank you very much!")</code><br>
<code>elif response == "no":</code><br>
<code>  &nbsp;&nbsp;&nbsp;&nbsp;print("How could you say that! I'll have you know my grandmother made it for me!")</code><br>
<code>else:</code><br>
<code>  &nbsp;&nbsp;&nbsp;&nbsp;print("I don't care about that! I want to know what you think of my hat!")</code><br><br>
It is important to note that the **else** statement lacks a condition. This means that it will simply run if all **if** or **else if** statements above it return false. This means that if we input something other than "yes" or "no", the program will run what is in the **else** statement. Lets see what will happen if we respond with something random!<br><br>
![image](https://user-images.githubusercontent.com/64915846/189808764-da83fd65-b02b-4f4e-b7e2-dd087dc1d7a1.png){: width="450"}<br><br>
## Greater and Less Than
Using conditions, we can also check if one value is **greater than (>)**, **less than (<)**, **greater than or equal to (>=)**, **less than or equal to (<=)**, or **not equal to (!=)** another value. To implement them in our code, we can simply use these inequality symbols in place of our **double equal signs (==)**. Let's try implementing these in tandem with numbers. You will notice that the code below uses some things we haven't yet discussed. This includes the **isdigit()** method, **int()** and **conditions inside conditions**. The **isdigit()** method can be used to check if a **string of characters** can be converted to an **integer**. If you want to learn more about the **isdigit()** method, click [here](https://appdividend.com/2022/03/15/how-to-check-if-string-is-integer-in-python/#:~:text=To%20check%20if%20a%20string,string%20are%20digits%20or%20not.). The **int()** function can be used to convert a variable of any data type (in this case it is a string) to an **integer**. This is required because we need to compare the value of two integers in this exercise. Click [here](https://www.w3schools.com/python/ref_func_int.asp) to find out more about them. As for **conditions inside conditions**, they work as you might expect them to. When the inside of a condition is being run, if there are conditionals within, then they will be ran as well.
<br><br>
<code>print("I have 45 muffins. How many cookies do you have?")</code><br>
<code>response = input()</code><br><br>
<code>if response.isdigit():</code><br>
<code>&nbsp;&nbsp;&nbsp;&nbsp;response = int(response)</code><br>
<code>&nbsp;&nbsp;&nbsp;&nbsp;if response == 45:</code><br>
<code>  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print("We have the same amount of muffins! This is awesome.")</code><br>
<code>&nbsp;&nbsp;&nbsp;&nbsp;elif response > 45:</code><br>
<code>  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print("How did you get so many muffins?! Give me some NOW or i'll tell my mom!!!")</code><br>
<code>&nbsp;&nbsp;&nbsp;&nbsp;elif response < 45:</code><br>
<code>  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;print("HAHAHA LOOSERRR!!! I have more muffins than you and I bet you are jealous.")</code><br><br>
<code>else:</code><br>
<code>  &nbsp;&nbsp;&nbsp;&nbsp;print("I don't care about that! I want to know how many muffins you have!")</code><br><br>
Let's check out the results!
![image](https://user-images.githubusercontent.com/64915846/189814720-2c512d60-01b6-469f-a30a-7ef88e1623c4.png){: width="450"}
Neat! If you don't understand what is going on here, feel free to reread the page or do some research in the [python documentation](https://docs.python.org/3/) yourself. Best wishes!
## Challenge 3
Now that you've learned about conditions, try creating your own game show! You can make whatever sort of game show you want (death wager, comedy, guessing, etc). Just make something goofy and fun, and be sure to use this page for reference if you need help. Enjoy (:
