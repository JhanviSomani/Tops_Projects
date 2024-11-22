**Q-1**:What is JavaScript?
**Ans**: JavaScript abbreviated known as JS is a programming language that allows us to implement complex feature on web pages. It enables us to create dynamically updating content, control multimedia, animate images,etc.

**Q-2**:What is the use of isNaN function?
**Ans**:isNaN() method returns true if a value is Not-a-Number. It determines whether a value is NaN, first converting the value to a number if necessary.
E.g. isNaN(123) = output : false , isNaN('100F') = output : true

**Q-3**:What is negative Infinity?
**Ans**:The negative infinity in JavaScript is a constant value that is used to represent a value that is the lowest available. It represents something that is smaller than any number you can think of. It’s like the lowest point on a number line.

**Q-4**:Which company developed JavaScript?
**Ans**:Javascript was created by Brendan Eich at Netscape Communications in 1995.

**Q-5**:What are undeclared and undefined variables?
**Ans**:**Undefined variable**: when we declare a variable but do not assign a value to it is called undefined variable. E.g. let a;
**Undeclared variable**: It is the variable which we have not declared with a keyword like 'var','let','const'. E.g. a = 10;

**Q-6**:Write the code for adding new elements dynamically?
**Ans**:To add new elements dynamically we use createElement() method.

```
E.g.
box = document.createElement('div')
```

**Q-7**:What is the difference between ViewState and SessionState?
**Ans**:
|ViewState|SessionState|
|---------|------------|
|It is used for client-side state management|It is used on the server-side management|
|Maintained at page level only.|Maintained at session level.|
|View state can only be visible from a single page and not multiple pages.|Session state value availability is across all pages available in a user session.|

**Q-8**:What is === operator?
**Ans**:The operator is called **strict equality** operator. It check value as well as data type of both operands and if they are same (in value as well as type) it gives true else false.
E.g.
let n1 = 10;
let n2 = 10;

console.log(n1 === n2);

Output: True ("Here the output will be true as the value and the operand(let) both are same")

**Q-9**:How can the style/class of an element be changed?
**Ans**:We can use add,remove,toggle methods to do any change in class.
**add**:It is used to add the class in the classList of the element

```
<div class="some thing is there">Some thing is there</div>

<script>

some = document.querySelector('.some');
some.classList.add('initially');

</script>


```

**remove**:It is used to remove the class from the classList of the element

```
<div class="some thing is there">Some thing is there</div>

<script>

some = document.querySelector('.some');
some.classList.remove('thing');

</script>
```

**toggle**:It is used to add the class if it doesn't exit and also used to remove the class if we want to remove it.

```
<div class="some thing is there">Some thing is there</div>

<script>

some = document.querySelector('.some');
some.classList.toggle('toggle');

</script>
```

**Q-10**:How to read and write a file using JavaScript?
**Ans**:To read a file:
**fs.readFile()**:The file is read using the fs.readFile() function, which is an inbuilt method. This technique reads the full file into memory and stores it in a buffer.

**Parameters**:
**filename**: It contains the filename to be read, or the whole path if the file is saved elsewhere.
**encoding**: It stores the file’s encoding. ‘utf8’ is the default setting.
**callback function**: This is a function that is invoked after the file has been read. It requires two inputs:
**err**: If there was an error.
**data**: The file’s content.
**Return Value**: It returns the contents contained in the file, as well as any errors that may have occurred.

**Syntax**:
fs.readFile( file_name, encoding, callback_function );

To write a file:
**fs.writeFile()**:The fs.writeFile() function is used to write data to a file in an asynchronous manner. If the file already exists, it will be replaced.

**Parameters**:
**file_name**: It’s a string, a buffer, a URL, or a file description integer that specifies the location of the file to be written. When you use a file descriptor, it will function similarly to the fs. write() method.
**data**: The data that will be sent to the file is a string, Buffer, TypedArray, or DataView.
**options**: It’s a string or object that may be used to indicate optional output options. It includes three more parameters that may be selected.
**encoding**: It’s a string value that indicates the file’s encoding. ‘utf8’ is the default setting.
**mode**: The file mode is specified by an integer number called mode. 0o666 is the default value.
**flag**: This is a string that indicates the file-writing flag. ‘w’ is the default value.
**callback**: This function gets invoked when the method is run.
**err**: If the process fails, this is the error that will be thrown.

**Syntax**:fs.writeFile( file_name, data, options, callback );

**Q-11**:What are all the looping structures in JavaScript?
**Ans**:There are three types of looping structure in javascript:
(1)**For loop**: Entry control loop
E.g.
for(i=0;i<=10;i++)
{
console.log('Hello');
}
(2)**While loop**: Entry control loop
E.g.
let result = 0;
let counter = 1;
while (counter <= 10) {
result += counter;
counter++;
}
console.log(result);

(3)**Do-while loop**: Exit control loop
E.g.
let result = 0;
let counter = 11;
do {
result += counter;
counter++;
} while (counter <= 10);
console.log(result);

**Q-12**:How can you convert the string of any base to an integer in JavaScript?
**Ans**:To convert the string of any base to integer we use parseInt() which parses a string argument and returns the integer.The function expects the value to be a string if it not a string than it is automatically converted into string using the toString() method.

E.g. parseInt("FXX123", 16);

**Q-13 What is the function of the delete operator?**
**Ans**:The delete operator removes a property from an object. If the property's value is an object and there are no more references to the object, the object held by that property is eventually released automatically.

E.g. let alphabets = {
a:10
b:20

delete alphabets.b;
console.log(alphabets.b)

output: undefined
}

**Q-14**:What are all the types of Pop up boxes available in JavaScript?
**Ans**:There are 3 types of pop-up boxes in javascript.
**(1)Alert box**:It displays a simple dialog box which displays a message to the user. It has a "OK" button which dismisses the alert.
E.g. alert("This is an alert");

**(2)Confirm box**:It provides a user with two options typically "OK" and "Cancel". It resolves into true or false.
E.g.confirm('Are you sure you want to return back?');

**(3)Prompt box**:It provides a dialog box to retrieve the input and returns the input as a string, otherwise, if no input, ‘null’.It has two options "OK" and "Cancel".
E.g. prompt('Enter your Name here: ');

**Q-15**:What is the use of Void (0)?
**Ans**:javascript:void(0) is a pseudo-URL that does nothing when clicked. It’s commonly used as a placeholder in href attributes to prevent the browser from navigating to a new page while still executing JavaScript code.
E.g.

```
<a href="javascript:void(document.body.style.backgroundColor='green');">
Click here for green background
</a>
```

**Q-16**:How can a page be forced to load another page in JavaScript?
**Ans**:(1)**By Using window.location.replace**: The replace function is used to navigate to a new URL without adding a new record to the history.
E.g. window.location.replace('https://www.google.com');
(2)**By Using window.location.assign Property**:The assign function is similar to the href property as it is also used to navigate to a new URL.
Unlike the replace method, the assign method adds a new record to history.
E.g. window.location.assign("https://www.google.com/");

**Q-17**:What are the disadvantages of using innerHTML in JavaScript?
**Ans**:(1)**The use of innerHTML very slow**: The process of using innerHTML is much slower as its contents as slowly built, also already parsed contents and elements are also re-parsed which takes time.
(2)**Preserves event handlers attached to any DOM elements**: The event handlers do not get attached to the new elements created by setting innerHTML automatically. To do so one has to keep track of the event handlers and attach it to new elements manually. This may cause a memory leak on some browsers.
(3)**Can break the document**: There is no proper validation provided by innerHTML, so any valid HTML code can be used. This may break the document of JavaScript. Even broken HTML can be used, which may lead to unexpected problems.
