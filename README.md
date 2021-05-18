>>> a=[1,2,3]
>>> len(a)
3
>>> dir(a)
['__add__', '__class__', '__class_getitem__', '__contains__', '__delattr__', '__delitem__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__getitem__', '__gt__', '__hash__', '__iadd__', '__imul__', '__init__', '__init_subclass__', '__iter__', '__le__', '__len__', '__lt__', '__mul__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__reversed__', '__rmul__', '__setattr__', '__setitem__', '__sizeof__', '__str__', '__subclasshook__', 'append', 'clear', 'copy', 'count', 'extend', 'index', 'insert', 'pop', 'remove', 'reverse', 'sort']
>>> a*2
[1, 2, 3, 1, 2, 3]
>>> score=[20, 50,60,40,30]
>>> sum(score)
200
>>> sum(score)/len(a)
66.66666666666667
>>> sum(score)/5
40.0
>>> sum(score)/len(score)
40.0
>>> a
[1, 2, 3]
>>> b=[4,5,6]
>>> a=[1,2,3]
>>> a
[1, 2, 3]
>>> b
[4, 5, 6]
>>> c=[a,b]
>>> c
[[1, 2, 3], [4, 5, 6]]
>>> len(c)
2
>>> c[1][1]
5
>>> t=[i*3 for i in range(1,11)]
>>> t
[3, 6, 9, 12, 15, 18, 21, 24, 27, 30]
>>> len(t)
10
>>> t[:]
[3, 6, 9, 12, 15, 18, 21, 24, 27, 30]
>>> t[2:]
[9, 12, 15, 18, 21, 24, 27, 30]
>>> t[:5]
[3, 6, 9, 12, 15]
>>> t[3:5]
[12, 15]
>>> 
>>> Tot=0
>>> for i in range(10):
	Tot += i

	
>>> Tot
45
>>> for i in range(10):
	Tot += t[i]

	
>>> Tot
210
>>> Tot/ len(t)
21.0
>>> a
[1, 2, 3]
>>> b
[4, 5, 6]
>>> t
[3, 6, 9, 12, 15, 18, 21, 24, 27, 30]
>>> t*3
[3, 6, 9, 12, 15, 18, 21, 24, 27, 30, 3, 6, 9, 12, 15, 18, 21, 24, 27, 30, 3, 6, 9, 12, 15, 18, 21, 24, 27, 30]
>>> np1=np.array(t)
Traceback (most recent call last):
  File "<pyshell#40>", line 1, in <module>
    np1=np.array(t)
NameError: name 'np' is not defined
>>> type(t)
<class 'list'>
>>> dir(t)
['__add__', '__class__', '__class_getitem__', '__contains__', '__delattr__', '__delitem__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__getitem__', '__gt__', '__hash__', '__iadd__', '__imul__', '__init__', '__init_subclass__', '__iter__', '__le__', '__len__', '__lt__', '__mul__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__reversed__', '__rmul__', '__setattr__', '__setitem__', '__sizeof__', '__str__', '__subclasshook__', 'append', 'clear', 'copy', 'count', 'extend', 'index', 'insert', 'pop', 'remove', 'reverse', 'sort']
>>> t+3
Traceback (most recent call last):
  File "<pyshell#43>", line 1, in <module>
    t+3
TypeError: can only concatenate list (not "int") to list
>>> 2**8
256
>>> 2**16
65536
>>> 2**32
4294967296
>>> 2**64
18446744073709551616
>>> import sys
>>> sys.getsizeof(t)
184
>>> t*2
[3, 6, 9, 12, 15, 18, 21, 24, 27, 30, 3, 6, 9, 12, 15, 18, 21, 24, 27, 30]
>>> sys.getsizeof(t*2)
216
