# IT SPECIALIST : PYTHON 1
  ## LEARN "TYPE DATA PYTHON" :
  1. string :
     The string data type is used to represent text or characters.Strings can contain letters, numbers, or special characters.
     **Example:** "Hello, World!".
  2. integer :
     The integer data type is used to represent whole numbers (numbers without decimals), both positive and negative.
     **Example:** 1, -5, 100.
  3. float :
     The float (floating-point) data type is used to represent decimal numbers (numbers with decimals).
     **Example:** 3.14, -0.5, 2.71828.
  4. boolean :
     The boolean data type is used to represent two possible values True (true) or False (false). It is often used in decision making and logic.
     **Example:** True, False.
  5. complex :
     The complex data type is used to represent complex numbers in mathematics, which consist of real and imaginary parts.
     **Example:** 1+2j, -3.5+4j.
## LEARN "TYPE DATA LIST PART 1"
  The contents are a collection of ordered data. In the list the contents of the data types do not have to be the same.
The way of writing is marked with square brackets […….]in python index starts from "0",there are index calls for positive numbers and there are calls for negative numbers which will appear from the last element.
    1. index call to [..]
    refers to the act of accessing certain elements of a sequence such as a string, list or tuple in programming. Each element in a sequence has an index that identifies its position in the sequence. In many programming languages, including Python, the index starts at 0.
    **Example :** 
    my_list = [10, 20, 30, 40, 50] 
    Calling the element with index 0 (first element)
    element = my_list[0]
    print(element)  # Output: 10
    2. understanding of slicing
    Slicing is a very useful feature in the Python programming language which is used to extract portions or "slices" from sequences such as strings, lists, tuples, or even NumPy arrays. By using slicing, you can remove certain parts of the sequence without needing to change the original sequence.
    usually slicing use :
  [.... : ..... : ....]
## LEARN "TYPE DATA LIST PART 2"
  in this part 2 list learn about len, append, extend, insert, remove, pop, index, function count, sort, reverse and x.reverse.
1. len(iterable): The len function is used to return the length (number of elements) of an iterable such as a string, list, or tuple.
2. append(element): The append method is used to add elements to the end of the list.
3. extend(iterable): The extend method is used to combine (add) elements of an iterable into an existing list.
4. insert(index, element): The insert method is used to insert an element at a specific index in the list.
5. remove(element): The remove method is used to remove the first element matching the given value from the list.
6. pop(index): The pop method is used to remove and return elements from a list based on a given index. If index is not given, then the last element is deleted.
7. index(element): The index method is used to find the first index of the element with the given value in the list.
8. function count(element): The count method is used to count the number of times an element with a certain value appears in the list.
9. function sort(): The sort method is used to sort the elements in a list in ascending order.
10. function reverse(): The reverse method is used to reverse the order of elements in the list. After this method call, the elements will be reversed from their initial ones.
## LEARN SLICING ON STRING
String slicing is a technique for removing substrings from a larger string. This is done by specifying two indices that identify the range of characters you want to extract from the string.
  **Example :** 
text = "Example slicing"
slice = text[8:13] # Takes characters from index 8 to 12 (excluding index 13)
print(slice) # Output: "slicing"
## LEARN TUPLE 
 Tuple in Python is a data type that is similar to a list, but is immutable. This means that once elements are defined in a tuple, you cannot change, add, or remove those elements. Tuples are often used to store data that should not change.
   **example :**
 my_tuple = (1, 2, 3,"Four")
 Access elements in a tuple
 print(my_tuple[2]) # Output: 3

 ## LEARN SET
   learn about sets where in Python is a data type used to store a collection of unique elements in no particular order. Sets are unordered, meaning that the elements in the set do not have an index. In addition, sets can only store elements that are unique, so there is no duplication of elements in one set.
Sets are used when it is necessary to store a unique set of data and does not care about the order of elements. This is very useful in various situations such as deduplicating data (intersection) or modeling many-to-many relationships between elements in a data set (union).
## LEARN DICTIONARY
dictionay is a collection of unordered key-value pairs and is used to store small to large data. Dictionaries are not included in the implementation of sequences, so they cannot be called with index sequences, for example trying with index[0] but the result is an error (key error) because there is no key (key) 0.
## LEARN CONDITIONAL EXPRESSION 
1. **IF**(If Statement):
IF is a statement in programming that is used to test a condition. If the condition is true, it will be executed. If the condition is false, it can be ignored.
2. **ELSE** (Else Statement):
ELSE is a statement used in conjunction with IF. If the condition in IF is not met (false), then the code in ELSE will be executed.
3. **ELIF** (Else If Statement):
ELIF is short for "else if" and is used in conjunction with IF. ELIF allows testing multiple conditions sequentially. If the condition in IF is not met, then the condition in ELIF will be checked. If one of the ELIF conditions is met, the corresponding code will be executed.
4. **FOR** :
FOR is a statement in programming that is used to create repetitions or loops. It allows you to execute a specific block of code a certain number of times according to a specified condition or range.
5. **FOR LOOPING** :
for looping in Python is the use of one or more loops within another loop. The outer loop will run a certain number of times, and in each iteration of the outer loop, the inner loop will be completely executed. This is useful for accessing and processing data in a layered structure or combining combinations of multiple variables.



  
     
