# python-sets
A set is a built-in Python data structure used to store a collection of unique items, potentially of mixed data types, in a single variable. Python sets are:

Unordered – the items of a set don’t have any defined order
Unindexed – we can’t access the items with [i] as with lists
Mutable – a set can be modified to integers or tuples
Iterable – we can loop over the items of a set

#creating set
days = {"Sunday","Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"} 
days=set(["Sunday","Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"]) 
x = set()

stringAndNum = {"one", 2, 3}

l=[1,2,3]
t=(4,5,6)
d={"one":1,"two":2,"three":3}
s="python"
print(set(l))      #output      {1, 2, 3}
print(set(t))      #output      {4, 5, 6}
print(set(d))      #output      {'one', 'three', 'two'}
print(set(s))      #output      {'t', 'y', 'p', 'h', 'n', 'o'}

