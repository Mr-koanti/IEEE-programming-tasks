#STACKE 
-------
hello ieee great frineds i hope you 😀  ARE DOING WELL😀
A stack is a linear data structure that stores items in a Last-In/First-Out (LIFO) or First-In/Last-Out (FILO) manner
In stack, a new element is added at one end and an element is removed from that end only. The insert and delete operations are often called push and pop.

Stake in ELectronic is part of memory which used to storing intterupt address and calling functions.

i am here with you writing simple code function for stack:
```
Stack=[] #here is empty stacke
def push(element):
    global Stack #make it global variable
    y=[element] 
    Stack=Stack+y #push the element into stacke 😎
    print(f"{element} is added succsessfuly.")
def pop():
    global Stack
    x=len(Stack)-1 #pop the elemnt from stack 😈
    if Stack== []:
        print("the stake is empty")
    else:
        Stack=Stack[:x]
        print(f"{Stack[x-1]} elemnt is removed succsessfully.")
        
        
for i in range(10):   
    push(i)
print(Stack)
pop()
print(Stack)
        
 ```
 my output is:
 ----------
 ```
0 is added succsessfuly.
1 is added succsessfuly.
2 is added succsessfuly.
3 is added succsessfuly.
4 is added succsessfuly.
5 is added succsessfuly.
6 is added succsessfuly.
7 is added succsessfuly.
8 is added succsessfuly.
9 is added succsessfuly.
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
8elemnt is removed succsessfully.
[0, 1, 2, 3, 4, 5, 6, 7, 8]
 ```
 
 This is my own stack 👋 🤚 🖐 ✋ 🖖 byee !
 -------------------- 
