### **JellyBall Programming Language**

If you are interested in this project, I'd like to say thank you for your stay.

As a C# developer, I truly understand how difficult it is to create a formal, ideal programming language. I've been working at an education association as a programming teacher that teaches 7~10-year-old kids how to code, and Python is the most common programming language we use. After the Python courses ended, they started to struggle when use languages like C++/Java.

I've talked to my boss about switching to another programming language that students are interested in. Scratch was good option but it does not require lots of keyboard input - Students need to be trained at typing codes. 

My idea is to create a new programming language that is as easy as Py, but the code format is more similar to Java/C/C++/C#.

Then I name it "JellyBall". In my imagination, "JellyBall" should have some grammar similarity with Python.



------



**1. Code Sample**

"JellyBean" will be **Procedure Oriented**.

```c#
//1. I/O
print("hello, world!");     //basic output
read(int x);                //basic input
print(x);


//2. Basic datatypes(Just like Java/C++)
int i = 0;
char c = 'a';
string s = "hello"; //yep, basic datatype.
bool b = true;


//3. Loops
for(int i = 0, i < 30, i ++){ //for loop
	//somecode
}

while(b == true){
	//somecode
}


//4. Conditions(Just like Java/C++)
if((x == true && y == true)||z == false){
	//somecode
}else if (conditions){
	//somecode
}else{
	//somecode
}

//5. Define functions
int function(int a, int b)
{
	return a + b;
}
void sayHello(string name)
{
	print("hello, "+name);
}
// No classes or interfaces in "JellyBean".
```

**2. What PL to Use to Build a Compiler**

C++/C# is my ideal option. 



**3. Basic Concepts of "JellyBean"**

"JellyBean" should not contain third-party libraries. There will be only 4 basic components in this POL(Procedure Oriented Language):

* Variables

* Functions

* Loops
* Conditions

However, you can write your own library:

```C#
<lib name = "MyLib">
	//code in this area will not run, but will called by your main program.
	void function(){
		//somecode
	}
</lib>
```



and use it in your main program:

```c#
using "MyLib";
```

There are no difference between write your functions directly in your main program and place them in a library (or "header file"), the only benefit of writing libraries is to make code easier to read and understand.

If you create a lib label in a file, you will not allowed to write any code outside of the label.



**4. Summary**

# **I NEED YOUR HELP !!!**

