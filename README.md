# FE Week 1 Notes: 

Data Types: 
1. Boolean - a logical value that can either be true or false.
2. Number - numeric values that can either be postive or negative, and be with or without decimals.
3. String -  alphanumeric/text values enclosed within a single ('') or double ("") quotes.
4. Undefined - a variable that has been declared but hasn't been assigned a value or the object does not exist.
5. Null - a special value that represents a deliverate nonvalue or absence of any object value.
6. Bigint - a numeric value that can represent numbers larger than the safe integer.
7. Symbol - a unique identifer that represents objects, often used to create property keys for objects.

Variables - declaring variables
1. Start by creating a new variable using the keyword <sub> var </sub>.
2. Assign a name or identifier and be intentional when assigning names. Write names using the camelCase convention.
3. Continue with the assignment operator (=).
4. Add the value.
5. Finish the line of code with a semicolon (;).

         Example:
           var firstName = "Candace";

Variables - reassigning variables 
1. Declare the variable and print to the console. Print using console.log()
2. Reassign the variable to what you want it to be without the <sub>var</sub> keyword.
3. Finally, log the reassigned variable to the console. 
    
        Example: 
        // declare the variable, assign a value, and print to console 
        var firstName = "Candace";
   
        console.log(firstName) // will print: Candace 
        // reassign the value of variable to be "Candice" 
        firstName = "Candice";
   
        // log the new value of the variable to the console 
        console.log(firstName) // will print the new value: Candice
