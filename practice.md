3. What is a conditional statement? Give three examples.
  * A conditional statement creates a branch in a program, which will execute one set of code or another depending on the value returned by the conditional statement.
    * `puts "true" if 1 == 1`
      * This would print the string "true" because 1 == 1 will evaluate as true
    * `puts "false" unless 1 == 2`
      * This would print the string "false" because 1 == 2 will evaluate as false
    * `1 == 1 ? "true" : "false"`
      * This would print the string "true" because 1 == 1 will evaluate as true
      * The ternary operator takes a conditional argument and two sets of instructions - one will run if the conditional evaluates true, the other if it evaluates false

4. Why might you want to use an if statement?
  * An if statement is useful when you only want a piece of code to run under certain conditions
    * If you only want a message to be shown to existing users of a website, or only new users

5. What is the Ruby syntax for an if statement?
  ```ruby
  if condition
    do this thing
  end
  ```
`if condition then do this thing end`
`do this if condition`
