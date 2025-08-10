
# Dice Roller 🎲

A simple **Java console application** that simulates rolling one or more dice. It displays each die's ASCII art, the value rolled, and the total score.

## 📜 Features

* Roll **any number** of dice in a single game.
* Displays **ASCII art** for each rolled die.
* Shows the **total score** of all dice rolled.
* Input validation for zero or negative dice count.

## 🛠️ Technologies Used

* **Java** (JDK 8 or higher)
* `Random` for dice rolls
* `Scanner` for user input
* Java text blocks for multi-line ASCII art

## 🚀 How to Run

1. **Compile the program**

   ```
   javac Rolldice.java
   ```

2. **Run the program**

   ```
   java Rolldice
   ```

3. **Example session**

```
Enter the number of dice to be rolled: 
3

----------
| ●     ●|
|    ●   |
| ●     ●|
----------

You rolled 5

----------
| ●      |
|        |
|       ●|
----------

You rolled 2

----------
|        |
|    ●   |
|        |
----------

You rolled 1
Your total is: 8
```

## 📌 Rules

* Each die produces a random number between **1** and **6**.
* ASCII art updates based on the number rolled.
* Must roll **at least one die**.

## 📄 License

This project is licensed under the MIT License – feel free to use and modify it.

---
