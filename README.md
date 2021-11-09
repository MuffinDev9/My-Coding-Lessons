# My Coding Lessons
This Is A Github Page About The Coding Lessons I Teach My Class.  
I Teach Them The Python 3 Programming Language, And Some Fun Things To Make With It.  
## Lesson 1
These Are The Basics Of Python. First, Choose A Code Editor.  
For This Tutorial, We Will Be Using The JDoodle Python 3 Editor, As Linked Here:  
https://www.jdoodle.com/python3-programming-online/  
You Need To Delete All The Existing Code, And Fullscreen Before You Start.  
  
Before You Do Any Coding, You Will Probably Want To Switch To Dark Theme.  
The Way You Do This Is By Pressing The Three Dots, And Then Pressing The *Dark Theme* Switch.  
### Hello World
A Hello World Program Is One Of The Most Simple Programs You Can Make.
All You Need To Do Is Type:
```shell
print("hello World")
```
After That, Just Press *Execute*, And It Will Appear On The Result Section.  
### Comments
Comments Are Like Code, But They Don't Actually Effect The Program, So When You Execute The Code, It Doesn't Show What Is In The Comment.  
All You Have To Do Is Type A Hastag, And Then Whatever Text You Want.
```shell
# This Is A Comment!
```
Again, Press Execute, But If You Look, It Will Not Show Your Comment In The Output.  
### Variables
Variables Are Like Objects That Store Some Kind Of Data Inside Them.  
There Are Lots Of Data Types, But The Main Ones Are These:  
 - Boolean: Sets The Variable To True Or False  
 - Integer: A Number Value  
 - String: A String Of Text  
  
This Is What A Boolean Looks Like:  
```shell
Boolean = True
```
This Is What An Integer Looks Like:  
```shell
Integer = 123
```
And, This Is What A String Looks Like:  
```shell
String = "I Am A String!"
```
### Printing Variables  
With Variables, You Can Actually Print Them Onto The Screen Using The Print Command.  
You *Can Not* Print Different Types Of Strings Together, And I Will Be Covering That More Later.  
The Way You Print A Variable Is By Typing The Print Command *With No Speech Marks* And Then The NAme Of The Variable Inside The Brackets.  
```shell
variable = "Hello, World!"
print(variable)
```
### Combining Strings  
When You Want To Print A Story, If You Want To Change A Character's Name, But Not The Entire Sentence,  
You May Want To Use A Variable For Their Name, But You Don't Know How To Put A Variable Inside A Sentence,  
So If You Are Ever In This Situation, This is What You Do.  
 - First, Declare A String Variable:  
```shell
name = "Muffin"
```
 - After, Print What You Want:  
```shell
name = "Muffin"
print("My Name Is ")
```
 - Last, Add A Plus After The Speech Marks, And Then The Variable Name:  
```shell
name = "Muffin"
print("My Name Is " + name)
```
### Converting Integers(Or Boolean) To Strings
If You Try The Previous Step With An Integer Or A Boolean, You May Realise It Won't Work.  
What You Need To Do Is Convert Them To Strings.  
Now, This Is Simple, You Just Put __str(YourVariable)__ Instead Of Typing Just The Variable Name.  
```shell
integer = 2
print("The Number Is " + str(integer)
```
## Homework  
For Your Homework This Time, I Want You To Make A Short Story, Where There Are At Least Three Things That Can Be Changed Using Variables.  
You Can Make Anything You Want, But I Want At Least Three Variables To Change.  
  
Here Is An Example:
```shell
name = "Dave"
age = 23
friend = "Dan"
print("My Name Is " + Name + ",")
print("I Am " + str(age) + ".")
print("And I Have A Friend Named " + friend + ",")
print("We Are " + name + " And " + friend + ".")
```
## Lesson 2  
In This Lesson, We Will Be Learning About Functions.  
We Will Be Doing Programming That Is A Tiny Bit More Complicated, So Get Ready.  
### Functions  
Functions Are Bits Of Code That Store Code Inside Them, They Can Be Activated Multiple Times,  
And Can Be Minimised To Tidy Up Your Code.  
An Example Of A Function Would Be Like This:  
```shell
# Creating The Function
def myfunction():
  print("I Am Inside A Function!")

# Calling The Function
myfunction()
```
### Function Parameters
Parameters Are Variables, But Their Values Are Assigned When You Call A Function.  
These Parameters Are Created Inside The Brackets Of A Function:  
When You Are Creating A Function, You Can Put The Parameter Names In The Brackets, Seperated By Commas.  
And Then, When You Call The Function, Put The Values Inside Those Brackets.  
```shell
def MyFunction(MyParameter)
  print(MyParameter)
MyFunction("QWERTYUIOPASDFGHJKLZXCVBNM")
```





