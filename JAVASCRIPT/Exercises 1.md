# Javascript
## 1 : Prompt and Alert
1. Define a Variable and show it in an Alert
```
	var variable 	= 99;
	alert(variable);
```
2. Define Three Variables: name, firstname and city.
```
	let xname 	= {word:"Name 	: ", value:"Doe" };
	let xfirstname 	= {word:"Firstame 	: ", value:"John"};
	let xcity 	= {word:"City 		: ", value:"Genk"};
```
And Show them in an Alert, each fitting one line.
```
 	 alert(
		xname.word + xname.value + '\n' +
		xfirstname.word + xfirstname.value + '\n' +
		xcity.word + xcity.value + '\n'
  	);
```
3. Prompt input for the users name, Then Alert "Hello, " followed by the name.
```
	var name	= prompt("name :");
	alert("Hello " + name + "!");
```
4. Repeat 3. , but also ask for firstname and city.
```
	var xinit 		= {word:"Init 		: ", value:"null" };
	var xname 		= {word:"Νame 	: ", value:"Doe" };
	var xfirstname 		= {word:"Firstame 	: ", value:"John"};
	var xcity 		= {word:"City 		: ", value:"Genk"};

	var name 		= prompt("name : ");
	var firstname 		= prompt("firstname : ");
	var city 			= prompt("city : ");

	xname.value		= name;
	xfirstname.value	= firstname;
	xcity.value		= city;
```
```
 	 alert(
		xname.word + xname.value + '\n' +
		xfirstname.word + xfirstname.value + '\n' +
		xcity.word + xcity.value + '\n'
  	);
```

5. Prompt the user to input two numbers, multiply them and Alert.
```
	var numberOne 	= prompt("First Number : ");
	var numberTwo 	= prompt("Second Number : ");
	alert( numberOne * numberTwo)
```
6. In your html link a file,  in which you create a function that alerts the modulo of two numbers.
```
  	var numberOne	= prompt("First Number : ");
  	var numberTwo	= prompt("Second Number : ");
  	alert("The Modulo of " + numberOne + " and " + sn + " is: " + (numberOne%numberTwo));
```
7. Prompt the users Lenght and BirthYear, and perform following calculations on them.
* (((( Lenght * 2 ) + 5 ) * 50 ) - Birthyear ) + 1766
```
	var lenght 		= prompt("Your Lenght in cm :");
	var birthyear 		= prompt("Your BirthYear :");
	var strangenumber	= (((( lenght * 2 ) + 5 ) * 50 ) - birthyear ) + 1766 ;
	alert(strangenumber);
```
8. Prompt the user for their birthyear, and conclude if they are an adult.
```
	var birthyear 	= prompt("Your BirthYear : ")
	var today 	= new Date();
	var age 		= today.getFullYear() - birthyear;

	if (age > 18){	alert("u are an adult");	}
	else {	alert("u are a minor");	}
```
## SUMMARY
Creating objects, Prompting Values, Assigning variables and values
```
  	var xname 	= {word:"NAME	: ", value:"null" };
	var NAMEvalue	= prompt("name : ");
	xname.value	= NAMEvalue;
```
Alert on multiple lines with \n Newline character
```
 	 alert(
		xname.word + xname.value + '\n' +
		xfirstname.word + xfirstname.value + '\n' +
  	);
```
