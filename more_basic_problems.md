- Explain how http works in detail. Use diagrams.

- Write a method that appends the words “in Ruby” to any English sentence, in Ruby.

- Explain how APIs work. In detail. Diagrams would be helpful.

- Explain how method_missing works. Show an example.

- What is the purpose of yield? Show an example.

- Implement a calculator in Ruby. Use a whiteboard.

- Explain how MVC works. Why is it beneficial? Diagrams, please.

===================================================
Implement a calculator in Ruby. Use whiteboard.
    Calculator should be able to understand expressions like “1 + 1”, “2 * 2”, “5 - 4”.
    Bonus: Implement (or explain how) a calculator that can handle order of operations.
===================================================
Write a function ‘interleave’ that alternates the contents of two or more arrays (or strings):

  interleave(“123”, “abc”, “ABC”) # => “1aA2bB3cC”
  interleave(“abc”, “12345”) # => “a1b2c345”
  interleave(“abc”, “12345”, “efghi”) # => “a1eb2fc3g4h5i”
===================================================
Write a function ‘truncate’ that shortens a string to the provided length, INCLUDING a trailing ellipsis:

  truncate(“this string”, 6) # => “thi…”
===================================================
Write a function ‘hashify’ that takes a 2D array (each inner array is a k/v pair) and creates a hash:
  
  hashify([[‘k1’, ‘v1’], [‘k2’, ‘v2’]]) # => {‘k1’ => ‘v1’, ‘k2’ => ‘v2’}
===================================================
Write a function ‘fizzbuzz’ that prints the numbers 1..100, replacing:

  numbers divisible by 3 with ‘fizz’
  numbers divisible by 5 with ‘buzz’
  numbers divisible by 3 and 5 with ‘fizzbuzz’
===================================================

Write a function that reverses an array, without using the reverse method. 

===================================================
*Flatten array*

- Write a method that flattens an array without using .flatten
(turns an array with nested arrays (which could also hold more nested arrays) into one flat array.

===================================================
*Search Sorted Array*

Write a method to search a sorted array for a specific number.  What is the runtime of the implementation?

===================================================
Write a function that counts the occurrences of each character in a string.  Choosing a suitable data structure for storage is up to you.

If the string was really really long (like all of Wikipedia) what would you need to do?

===================================================
Write a function called ‘map2x’ that takes an array of integers and returns a new array with each integer from the first array, doubled.

  map2x([1, 2, 3]) # => [2, 4, 6]

in: Ruby, then Javascript or CoffeeScript

===================================================
Write a function called ‘map’ that takes an array and returns a new array with the result of applying the passed-in block to each element of the original array.

  map([1, 2, 3]) { |x| 2 * x } # => [2, 4, 6]

in: Ruby, then in Javascript or CoffeeScript (with a callback instead of a block)

===================================================
Design a SQL table for storing a linked list of records.
Design a SQL table for storing a tree of records.

===================================================
Design some SQL tables for storing Users, Posts, and allowing Users to upvote/downvote the Posts.

===================================================

Write a method that converts x amount of dollars into change and specify how much of each coin will you have. E.g. convert $2.65 and return the amount of quarters, dimes, nickels, and pennies.

===================================================

Construct a regular expression that matches a valid email address.

===================================================
Pig latin string conversion - convert "hello" to "ellohay" &
"Hello" to "Ellohay"