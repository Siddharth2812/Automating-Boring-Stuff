### Practice Questions

1. Does PyInputPlus come with the Python Standard Library?
> No. It is a 3rd party module.
2. Why is PyInputPlus commonly imported with import pyinputplus as pyip ?
> To make typing the code easier without having to type the whole pyinputplus always when needed.
3. What is the difference between inputInt() and inputFloat() ?
> inputInt() returns the int value, iputFloat() returns a float value.
4. How can you ensure that the user enters a whole number between 0 and 99 using PyInputPlus?
> pyip.inputInt(min=0, max=99)
5. What is passed to the allowRegexes and blockRegexes keyword arguments?
> For allowRegexes we pass the regex string that are used in the given code and we use blockRegexers to deny the usage of certain regexes.
6. What does inputStr(limit=3) do if blank input is entered three times?
> We get a exception called RetryLimitException
7. What does inputStr(limit=3, default='hello') do if blank input is entered three times?
> it returns 'hello'
