# Welcome!

Python can print message to use screen using a print() command

```python runnable
print('Hello World!')
```

Now you make up a message:

```python runnable
print(' ')
```

The message can be personalized by means of a variable holding the name of the person.

```python runnable
name2="Your name goes here... "
print(name2,', very nice to meet you! It is great to have you here with us today!')
```

Python can gather input from the user as well. Although I can't get it to work here, it would look just like this:

print("Enter your name:")

x = input()

print("Hello, " + x)

you can try it here: https://www.w3schools.com/python/ref_func_input.asp

# Python program to print odd Numbers in given range
```python runnable
start, end = 4, 19

# iterating each number in list
for num in range(start, end + 1):
	
	# checking condition
	if num % 2 != 0:
		print(num, end = " ")
```

When you see the % symbol, you may think "percent". But in Python, as well as most other programming languages, it means something different.

The % symbol in Python is called the Modulo Operator. It returns the remainder of dividing the left hand operand by right hand operand. It's used to get the remainder of a division problem.

Also, != means not equal to.

#Now change the code so that it prints even numbers in a given range
# Python program to print EVEN Numbers in given range
```python runnable
start, end = 4, 19

# iterating each number in list
for num in range(start, end + 1):
	
	# checking condition
	if num % 2 != 0: #change might be needed here
		print(num, end = " ")
```
May have got you there.... The == operator compares the value or equality of two objects. This means you should use the equality operators == and !=, when comparing objects - which is technially what we are doing here.
