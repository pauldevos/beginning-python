### List Comprehensions
List comprehensions are used when you want to do a number of operations on a list and you want to express it in a more succinct (or compact) way.

So instead of:

```python
my_new_list = []
for number in old_list:
    if number % 2 == 0:
        my_new_list.append(number)
```
we could write...

```python
my_new_list = [number if number % 2 == 0 for number in old_list]
```

Some other resources on list comprehensions:
- https://data-flair.training/blogs/python-list-comprehension/
- https://stackoverflow.com/questions/4260280/if-else-in-a-list-comprehension
- https://stackoverflow.com/questions/4406389/if-else-in-a-list-comprehension?noredirect=1&lq=1
- https://www.programiz.com/python-programming/list-comprehension



