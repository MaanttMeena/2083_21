# Grocery Store 
A grocery store has list of fruits available for sale. When a customer requests for a particular fruit, display if the fruit is available or not.

Following Mandatory Business Rules needs to be implemented: 

Input should be entered in two rows.
Enter fruit names as input in the first row separated by a comma . This is considered as the stock which is available in the store.
Provide exactly 5 input values separated by comma in the first row. If more values are provided then  print a message “Enter exactly 5 fruit names separated by comma”
Enter the fruit name as input to check the availability. This input should be entered in the second row.
Display the output as per the condition
if fruit is available  "Fruit <FruitName> is available, enjoy shopping !”  
else  “Fruit <fruitname> is NOT available”

Sample Input and Output - 1

    Input:
       Apple,Orange,Banana,Guava,Pineapple
       Pomegranate 

    Expected Output:
       Fruit Pomegranate is NOT available

Sample Input and Output - 2

   Input:
      Apple,Orange,Banana,Guava,Pineapple,Grapes
      Orange

    Expected Output:
       Enter exactly 5 fruit names separated by comma

 
Hints:
1. Receive fruit names as a comma separated values
2. Store the fruit names into a list using comma (,) separator
3. Validate the number of values in the list
4. Receive desired fruit name as input and store it in a variable
5. When input is wrong, stop the program with appropriate message
6. Process the values (check desired fruit availability in the list of fruit names)
7. Print appropriate message
