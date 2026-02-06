# C++ Smart A.T.M
A simple smart ATM in C++ that calculates the minimum number of banknotes needed to fufill a withdrawal request.

## What I'm Learning 
In this project, I moved away from coding (long if/else chains) and focused on Mathematical Effeciency.

  1. Integer division vs. module: Understanding how / discards decimals (truncation) and how % captures the remainder.
  
  3. The "Logic Funnel": Using sequential calculations to update a value (the remainder) rather than checking every possible condition.

  4. Input Validation: Learning to "short circuit" a function using return if the user input is logically impossible for the symtem

## What It Does: 
This program simulates a campus ATM that only dispenses 50 Cedis, 20 Cedis, and 10 Cedis notes. 
  1. Validate Input: Rejects any amount that isn't a multiple of 10 or is zero/negative.

  2. Calculatate Minimum Notes: Uses an algorithm to ensure the user gets the fewest number of banknotes possible.

  3. Dynamic Output: Instead of hardcoded values, it calculates the breakdown for any valid integer entered.
 
## How To Run It: 
To run this project on your machine, ensure you have C++ Compiler (like g++) installed. 
 1. Open your terminal or command prompt.
 2. Navigate to the folder containing smartATM.cpp.
 3. Compile the code
    g++ smartATM.cpp
    
 4. Run the executable:
    ./smartATM

  ## What I Want Feedback On: 
  1.Logic Efficiency: Did I handle the remainder updates correctly, or is there a more cleaner way to write the funnel?
  
  2. Error handling: Is my validation if statement robust enough to prevent the "Bank heist"? lol

  3. Code Structure: is the seperation between main() and the calculatesNotes function clear and logical?

  4. Variable naming: Are my variable names (num50s reaminder, etc.) intuitive for another developer to read? 
