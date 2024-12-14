# JAVASCRIPT-TUTORIAL
//ways to print in js
 console.log("hello cashew");
 alert("me")
 document.write("this is example of document write")   //avoid using this
  
 //javascript console api(app prog interface)
 console.log("hello ",4+6," cashew");
 console.warn("this is warning")
 console.error("this is a error")

 // variables in js-conatiners for store data
 var num=34;
 var num2=90;
 console.log(num+num2);
 
 //comments
 //this is example of single line comment
 //multiline comment
  /*
  this 
  is
  example 
  of 
  multi line comment
  */

 //DATATYPES IN JAVASCRIPT
 //numbers
 var num4 = 34;
 var num3 = 67;

 //string
 var str1 = "my name is san i am practicing js";
 var str2 = 'this is string in single quotes';

 //object
 var marks={
    Ravi:34,
    sano:45,
    divya:87.89,

 }
 console.log(marks);

 //booleans
 var a = true;
 var b = false;
 console.log(a,b);

 //undefined--variable has not been assigned value or variable withput a value
 var und = undefined;
 var und2;
 console.log(und);
 console.log(und2);

 //null-intential absence of a value
 var n = null;
 console.log(n);

 /*
 two types of datatype in JS
 -primitive dt(6)--undefined ,null,number,string,boolean,symbol
 reference dt --arrays & objects
 */

 //symbol-- it genterates unique key,immutable
 let sym1 = Symbol('example');
let sym2 = Symbol('example');
console.log(sym1 === sym2); // false

//arrays ---collection of similar datatype
var arr=[1,2,3,"sann",4,5];
console.log(arr); //[1, 2, 3, 4, 5]
console.log(arr[2]); //3
//console.log(len[arr]); //invalid syntax


//OPERATORS
//arithmetic operators (++ increment,+,-,*,/,-- decrement,**,%,)
var a =  23;
var b = 10;
console.log("the value of a+b =",a+b);

//assisment operator(+=,-+,*+,/=,**=,==,%=,=)
var c = b;
c+= 1;//c=c+1
console.log(c);

//comparison operators(==(equal to),===(equal value and equal type),!=,!==,<,>,>=,<=,?(tenary))
var x=20;
var y = 20;
console.log(x==y);//true
console.log(x===y);//true (equal value and equal type)


//logical operators

//logical and &&
console.log(true && true);   //true
console.log(true && false); //false
console.log(false && false);  //false

//logical or ||
console.log(true || true);   //true
console.log(true || false); //true
console.log(false || false);  //false

//logical not !
console.log(!true);
console.log(!false);
