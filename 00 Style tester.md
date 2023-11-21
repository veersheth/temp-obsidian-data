#Permanent 
# heading 1
## heading 2
### heading 3
#### heading 4
##### heading 5
###### heading 6

> hello this is a blockquote -->
> - by some author

normal **bold** *italic* ==highlighted== 
[[Style tester|This is a link]] 

- [ ] incomplete task
- [x] complete task

> [!yellow]+ This is a callout
>> [!SUMMARY]
>> More items


```python
for item in range(0, 100):
	print(f"{item}th print statement lol")

myInteger = int(input("Enter a number: "))
while myInteger < 100:
	print("Enter a number greater than 100...")
	myInteger = int(input())

print("End of program")
```

This is an `example of a codeblock` without syntax highlighting.

# table

| subject          | marks | diffuculty                       |
| ---------------- | ----- | -------------------------------- |
| mathematics      | 99    | very very                        |
| physics          | 93    | eh kind of                       |
| computer science | 92    | easy                             |
| chemistry        | 95    | PLEASE HELP PLEASE OH GOD OH GOD |
| biology          | 14    | lol                              |

- this is a note
	- this is a nested note
		- this is an even more nested note
		- this is an even more nested note
		- this is an even more nested note
        >[!green] indented callout

 - this is a nested note
	- this is an even more nested note
		- this is an even more nested note
	- this is a nested note
	- this is a nested note
	- this is a nested note


# dataview queries
```dataview
table Author, Type, Status
from [[Books]] and -"99 Templates"
```
