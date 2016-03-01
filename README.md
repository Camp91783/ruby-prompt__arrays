# Prompt - Ruby

## Arrays

### Objectives

1. Learn about arrays in Ruby.

### Instructions

Research and then write answers to the following questions in **lib/strings.md**.

- What is an Array?
- ordered integer indexed collections of any object.  Each elemenet in an array is associated with and referred to by an index.  Array indexing starts at 0.
-       -  it is a list of items in order.
-     
- What are some examples of information that would be Arrays as opposed to some other data type?
- favorite NBA teams
- favorite numbers to play in the lottery
- list of integers
- 
- What is one way, using Ruby, to retrieve the 6th element in an Array? How about the 8th element? What happens if you try to retrieve the value of the _9999th_ element (or some element that doesn't exist in the array)?
- can be retrieved using the #[] method
-   can take a single integer (index), a pair of arguments (start and lenth), or a range.
-   another way is by using the at method.
-     ex:)  my_array= ["Bulls", "Cavs", "Lakers", "Thunder", "Warriors", "Heat", "Knicks","Celtics"]
-       a.  6th item in the array
-         ans:  my_array[5]=> Heat
-       b.  8th item in array
-         ans: my_array=> Celtics
-       c.  Cannot retrieve.
-       
- The previous question asks about finding, for example, the 6th element in an Array. Is it possible to find the **-6th** (Notice the negative symbol!) element in an Array? What does that even mean?
-   - if you need to retrieve a negative array start from the end.
-       ex:)  my_array ["Bulls", "Cavs", "Lakers", "Thunder", "Warriors", "Heat", "Knicks", "Celtics"]
-         a.) find the -6th = "
-         Lakers"
- How would you perform an operation on every element inside an Array?
-   - you would use the #.each method
-   
- How do you add elements to an Array?
-   - use the .push method
-     ex.) my_array ["Bulls", "Cavs", "Lakers", "Thunder", "Warriors", "Heat", "Knicks", "Celtics"]
-       my_array.push(Nets)
-       
- Given the Array `["Laura", "Fiona", "Tori"]`, how would you replace `"Fiona"` with `"Florence"` so that you end up with `["Laura", "Florence", "Tori"]`?
-   my_array = ["Laura", "Fiona", "Tori"]
-   my_array[1]= "Florence"
-   
- What do the methods `push`, `pop`, `shift`, and `unshift` do?
-   push: pushes the object to the end of the array
-   pop: Removes thing in the array.  "Pops Off"
-   Shift: removesthe 1st element from the array and returns it.  shifting objects up.
-   Unshift:  puts objects at the front and shifts the rest down.
-   
- How do you determine how many elements are in an Array?
-   - length method
-   ex:) my_array= ["Warriors", "Bulls", "Lakers", "Cavs","Heat"]
-         puts my_array.length=> 5
-   
- How would you reverse the order of elements in an Array?
-   -reverse method
-   ex:)  my_array = ["Warriors", "Bulls", "Lakers", "Cavs","Heat"]
-         puts my_array.reverse
-           Heat
-           Cavs
-           Lakers
-           Bulls
-           Warriors
-           
- 
- How would you convert a String `"Sumeet Jain"` into an Array `["Sumeet", "Jain"]`? How about to `["S", "u", "m", "e", "e", "t", " ", "J", "a", "i", "n"]`? How would you convert the Array back into a String?
-   - use split method
-       "Sumeet Jain".split(")
-       "Sumeet Jain".split("")
-       

Remember two things:

1. You don't need to submit any code to us for this assignment. Just provide in-your-own-words answers for the questions above.
2. We're not looking for any kind of advanced writing skills nor any kind of length. Just be clear and thoughtful about what you write--organize it however it makes sense for you.

### Resources

As always, one resource is Google. Some of the questions above can by entered verbatim into a Google search, and for others that won't be as effective. Either way, expect to read (or watch videos) about more than just the simple answer to each question. Often a question's answer--even one that seems short or simple--doesn't really make sense until after you've read the paragraphs before and after it.

- http://ruby.bastardsbook.com/chapters/collections/ - There is more here than you need, but it's a good reference.
