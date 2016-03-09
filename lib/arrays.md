---
title: Arrays
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What is an Array?

- ordered integer indexed collections of any object
- each element in an array is associated with and referred to by an index.  Array indexing starts at 0
-       - it is a list of items in order. 
- 
# What are some examples of information that would be Arrays as opposed to some other data type?

    - favorite NBA teams
    - grocery list
    - favorite lottery numbers
    - list of integers

# What is one way, using Ruby, to retrieve the 6th element in an Array? How about the 8th element? What happens if you try to retrieve the value of the _9999th_ element (or some element that doesn't exist in the array)?

can be retrieved usinf the #[]method.
    - can take a single integer (index), a pair of arguments (start and length), or a range
 another eay is by using the at method.
    {arr.at(0)# =>1}
        ex:)  +my_array= ["Bulls", "Cavs", "Lakers", "Thunder", "Warriors", "Heat", "Knicks", "Celtics"]
            a.) 6th item in an array
                my_array[5] => Heat
            b.) 8th item in array
                my_array[7] => Celtics
            c.) Cannot retrieve the 999th becasue it is not part of this array

# The previous question asks about finding, for example, the 6th element in an Array. Is it possible to find the **-6th** (Notice the negative symbol!) element in an Array? What does that even mean?

    - if you need to retrieve a negative array start from the end
        ex.)  my_array["Bulls", "Cavs", "Lakers", "Thunder", "Warriors", "Heat", "Knicks", "Celtics"]
            a.) find the -6th = "Lakers"

# How would you perform an operation on every element inside an Array?

    - you would use the #.each method.

# How do you add elements to an Array?

    -use the .push method.
        ex.) my_array ["Bulls", "Cavs", "Lakers", "Thunder", "Warriors", "Heat", "Knicks", "Celtics"]
             my_array.push (Nets)

# Given the Array `["Laura", "Fiona", "Tori"]`, how would you replace `"Fiona"` with `"Florence"` so that you end up with `["Laura", "Florence", "Tori"]`?

ex.)  my_array = ["Laura", "Fiona", "Tori"]
        my_array[1] = "Florence"

# What do the methods `push`, `pop`, `shift`, and `unshift` do?

    1. push:  pushes the object to the end of the array
    2. pop:  removes a thing in the array.  "Pops off"
    3.  shift:  removes the 1st elemenet from the array and returns it.  shifting the objects up.
    4.  unshift:  puts the objects at the front and shifting the rest down.

# How do you determine how many elements are in an Array?

    -length method
    ex.)  my_array = ["Warriors", "Bulls", "Lakers", "Cavs", "Heat""]
            puts my_array.length => 5
            

# How would you reverse the order of elements in an Array?

    -reverse method
        ex.) my_arrray = {"Warriors", "Bulls", "Lakers", "Cavs", "Heat"]
            puts my_array.reverse
            => 
            Heat
            Cavs
            Lakers
            Bulls
            Warriors

# How would you convert a String `"Sumeet Jain"` into an Array `["Sumeet", "Jain"]`? How about to `["S", "u", "m", "e", "e", "t", " ", "J", "a", "i", "n"]`? How would you convert the Array back into a String?

    -"Sumeet Jain".split ||
        - use split method
    - "Sumeet Jain".split ("")