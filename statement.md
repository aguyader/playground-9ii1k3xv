# Welcome!

Python can print message to use screen using a print() command

```python runnable
print('Hello World!')
```

The message can be personalized by means of a variable holding the name of the person.

```python runnable
name2="Andy"
print(name2,', very nice to meet you! It is great to have you here with us')
```

Python can gather input from the user as well

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

# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Python template](https://tech.io/select-repo/429)
