# Reflection

## Question 1 (50 words)
#### When and why should you use a function like `carefulSubract` rather than `subtract`? 
It provides more stability and ensures your code works properly.  It takes the possible problem of the code trying to subtract non-numbers and the tests ensure it does not happen. It also creates a better user experience, because it tells the user why their instructions are not working and gives them instructions  as how to fix it.  

## Question 2 (100 words)
#### What are `data types`, and how does data typing work in JavaScript? Name at least 4 built-in data JS data types. 

## Question 3 (100 words)
#### What is the advantage to storing information as an object (`{firstName: 'Italo', lastName: 'Calvino', profession: 'novelist' }`) rather than as an array (`['Italo', 'Calvino', 'novelist']`)? Are there any disadvantages?
The advantage of an object is that it allows the data to be sorted and labelled, making it a superior way to store that information. In an array, the elements are just listed with little context. Once they start getting larger, it becomes very hard to remember exactly what got put in an array and what order it is in so it can be recovered. It becomes very unwieldly, while an object’s ability to sort makes it much easier to recover the exact piece you are looking for. One disadvantage of an item is that it is the complexity might not be worth it in simple functions. If you have an item with two pieces of information in it, an array might be both more efficient and less likely to break.

## Question 4 (150 words)
#### The function `sentences` transforms a data structure (in this case, a list of object literals) into a sequence of sentences. If the data structure were less predictable (e.g., if some properties of each object were occasionally missing, or if their data type was not always the same), what programming techniques could you use to ensure that your function produced a coherent output? Also, can you think of a more interesting "transform" that could be done with the same data structure?
