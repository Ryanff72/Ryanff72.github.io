---
layout: default
title: If Statements
parent: Learn To Code
nav_order: 5
---

# If Statements
If statements can be used to check if a variable is equal to another value. As an example, let's ask the user a yes or no question, and then give a 
response based off of the user's input.
<br><br>
<code>print("Do you like my new hat? (respond with 'yes' or 'no')")</code><br>
<code>response = input()</code><br>
<code>if response == "yes":</code><br>
<code>  &nbsp;&nbsp;&nbsp;&nbsp;print("Thank you very much!")</code><br>
<code>if response == "no":</code><br>
<code>  &nbsp;&nbsp;&nbsp;&nbsp;print("How could you say that! I'll have you know my grandmother made it for me!")</code><br><br>
When ran, the conversation should flow as follows:<br><br>
![image](https://user-images.githubusercontent.com/64915846/189805710-88ef04b1-1c15-4edc-9dbd-92b5ed800430.png){: width="450"}
## Challenge 2
Before you go on, try making a question with more than 2 possible responses. Go on! This tutorial will be here for you when you come back.
## Else If and Else statements
**Else if** and **else** statements are useful if you need to account for alternative values a variable can have. **Else if** statements go below an **if** statement, and will only be ran if the **if** statement above them is false. If you want to do something if all **if** and **else if** statements return false, then you can use an **else** statement. Here is a flow chart to help you to understand the concept better.<br><br>
**if**  >  **else if**  >  **else if** > **else if**  >  ...  >  **else**<br><br>
Let's alter the code above to make use of


