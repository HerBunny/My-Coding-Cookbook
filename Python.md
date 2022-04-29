# My Coding Cookbook: Python

## Tips & Tricks

### Keeping a console open, until user hits Enter

This is a handy little trick, to add two lines and then wait for the user to hit Enter before exiting.

- using \n moves to a new line for every instance inserted into a string, in a line of code.


###### Example of how to add lines and wait for enter keystroke:

```
input("\n\nPress the enter key to exit.")

```


### Split lines of code across multiple lines

The first option is to place the formula in parenthesis or braces, and then move the variables onto subsequent lines.


###### Example with perenthesis:
```
total = (item_one 
         + item_two 
         + item_three
         )
```

The next option is to make use of back slashes without parenthesis.


###### Example using back slashes:
```
total = item_one \+ item_two \+ item_three         
```

Additionally, by using three quotation marks, whole paragraphs may be split across multiple lines.


###### Example using three quotation marks:
```
total = """Here is an example of a paragraph. The contents of this line, 
           can be easily split across multiple lines."""         
```



