# Ruby Assessments

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.


#### 1. What is a method in Ruby? How is it different or similar to functions in JavaScript?

A method in Ruby is very similar to a javascript function.They both in data and return outputs.

#### 2. What does it mean that a class inherits from another class? Try to explain Ruby inheritance. 


[Your Answer]
There is parent class that holds data which needs to be passed down to the child classes. When the data is passed doen to the other classses, it is inheriting it.


[Googled Answer]


#### 3. What is rspec and what is the general process for writing tests in RSpec?

//Your Answer
rspec is how we test in ruby.The process is writing the first test that is going to fail, then we type the test code to make sure it passes. After that we type the actual code in ruby.

//Googled Answer


#### 4. Name three possible non-inheritance relationships between ruby objects? 

//Your Answer

I am not sure. Don't remember.

//Googled Answer


#### 5. What do we call the #{} convention used below? What is it accomplishing?

```ruby
x = 1022
puts "I am printing a random number #{x}"
```
It is the same thing as string interpolation, which prints out whatever you put. The #{} will print out the variable that is put inside the brackets.

#### 6. How do you feel about testing right now? What potential pros/cons/barriers/advantages do you see to implementing BDD in your own code?

//Your Answer

some of the pros that come with testing are, making sure everything is going to work how you want it to, and makes you write the code multiple times, which can make you inderstand it better.
Some cons of testing are, it takes a long time to do and it can be frustrating if it doesn't work right away.
//Googled Answer


#### 7. What is an instance variable in Ruby? How is it different from a normal, local variable?

//Your Answer

An instance variable is a name that starts with the @ symbol.

//Googled Answer

The body of the initialize method now does nothing else but assign the value of the local variable name to an instance variable @name.

#### 8. Ruby has a great community and tons of free resources to help you learn. Here is the long list of great resources: https://www.ruby-lang.org/en/documentation/. Below are a few popular ones:
- Interactive Ruby tutorial (http://tryruby.org/levels/1/challenges/0)
- Why's (poigniant) Guide to Ruby: comics, anecdotes, and microscopic canaries (http://poignant.guide/book/chapter-1.html)
- Ruby in 20 min (https://www.ruby-lang.org/en/documentation/quickstart/)


Choose one of these resources and go through the material (not for hours, only looking for around 10min of your time) then come back here and list a few new things you learned about Ruby.
I chose tho look through "Ruby in 20 min"
This is what I learned:
-It was a good refresher on how ruby works
-_FILE_ is something new I learned. It contains the name of the current file
-.each is much more elegent than a for loop. This should be the way we always do it.