# Python

### `sorted(list)` and `list.sort()`
1. `sorted(list)` generates the copy of sorted list
2. `list.sort()` sorts list in-place

### Delete a key in dict
`dict.pop(key,None)`

### Parse huge XML file
Use lxml to parse huge xml file:
```python
for event, elem in etree.iterparse('XML file', tag='some tag'):
  do something with elem
  if event == 'end':
    elem.clear()
```
### Make a copy of list
1. use slice. `list_new = list_old[:]`
2. use `list()` function. `list_new = list(list_old)`
