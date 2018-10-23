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
</pre>

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

## Example-3:
<pre>
a=input('Enter First Name:')
b=input('Enter Last Name:')
print(a+b)
print(a,b)
print(type(a))
print(len(a+b))

</pre>

## Output:
<pre>
Enter First Name:Rahul
Enter Last Name:Singh
RahulSingh
Rahul Singh
class 'str'
10
</pre>

## Example-4:
<pre>
a=input('Enter int Value:')
print(type(a))
b=int(a)
print(type(b))

c=input('Enter float Value:')
print(type(c))
d=float(c)
print(type(d))

e=input('Enter complex Value:')
print(type(e))
f=complex(e)
print(type(f))

g=input('Enter boolean Value:')
print(type(g))
h=bool(g)
print(type(h))

</pre>

## Output:
<pre>
Enter int Value:10
<class 'str'>
<class 'int'>
Enter float Value:123.12
<class 'str'>
<class 'float'>
Enter complex Value:12+j
<class 'str'>
<class 'complex'>
Enter boolean Value:True
<class 'str'>
<class 'bool'>
</pre>


## Example-5:

<pre>
print('Integer tpye')
a=123
print(type(a))

print('Float tpye')
c=123.3
print(type(c))

print('Complex tpye')
e=6+4j
print(type(e))

print('Boolean tpye')
g=True
print(type(g))


</pre>

## Output:

<pre>

</pre>
