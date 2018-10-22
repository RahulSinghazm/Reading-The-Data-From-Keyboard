# Reading-The-Data-From-Keyboard

* We can read the data from the keyboard by calling input() function.
* Input function is predefine function which read the data in the form of string format only.
* After reading the data in the form of the string format we can convert string represented data in the form required form by using TYPE CONVERSION FUNCTION.

## Example-1:
<pre>
a=input('Enter First Name:')
b=input('Enter Last Name:')
print(a+b)
print(a,b)

</pre>

## Output:
<pre>
Enter First Name:Rahul
Enter Last Name:Singh
RahulSingh
Rahul Singh
</>

## Example-2:
<pre>
a=input('Enter First no.:')
a=int(a)
b=input('Enter Second no.:')
b=int(b)
print(a+b)
print(a,b)

</pre>

## Output:
<pre>
Enter First no.:4
Enter Second no.:5
9
4 5
</pre>
