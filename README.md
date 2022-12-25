# java-script-
loop,function,string,arrays methods



//for in loop//

/*let obj={
    lalit:40,
    gafur:99,
    vikas:55,
}
for(let a in obj){
    console.log("markes of " + a + " are " + obj[(a)])
}*/


//for of loop//
/*for( let a of "lalit bhadu"){
    console.log(a)
}*/



//while loop//
/*let i = 0;
while(i<100){
console.log(i)
i++;
}*/


// do while loop//

/*let i = 0;
do{
    console.log(i)
    i++;
}
while(i < 100)*/


// funcation in java script//

/*function onePlusavg( x, y){
    return Math.round(x + y)
}


let a = 10;
let b = 23;
let c = 9;
console.log("average of a and b", a + b)
console.log("multiply of b and c", c + b)
console.log("average of a and c", a + b)*/

//string chapter//

/*let a = (" hello my self lalit kumar");
console.log(a.length)*/


/*let a = "lalit"

console.log(a[3])*/

/*let boy1="lalit"
let boy2="vikas"
let sentence = "${boy2} is a best friend of ${boy1}"

console.log(sentence)*/


// escape chartactor  single quote string//
/*let a ='apple\'s'
console.log(a)*/


// UPPER CASE AND LOWER CASE//
/*let a = "lalit kuamr"
console.log(a.toUpperCase())
console.log(a.toLocaleLowerCase())*/




//SLICE ARRAY//
 /*let a = "bhadu shab"
 console.log(a.slice(2,6))*/



 //replace string //
 /* let a = "lalit kumar"
  console.log(a.replace("kumar","bhadu"))*/



  // concety arrey//
  /*let a="lalit"
  let b="vikas"
  console.log(a.concat(" is a friend of ",b))*/


  //trim array//
 /* let a="     lalit"
  console.log(a.trim())*/

//   let a = "LALIT"
//   console.log(a[0])
//   console.log(a[1])
//   console.log(a[2])
//   console.log(a[3])
//   console.log(a[4])


// use a for loop to print a string//
// let str = "lalit";
// for (let i = 0; i < str.length; i++){
//     console.log(str[i])
// }




//ARRAYS//

// let marks=[10, 20, 30, true, false, "not desfine"]
// console.log(marks[0])
// console.log(marks[1])
// console.log(marks[2])
// console.log(marks[3])
// console.log(marks[4])
// console.log(marks[5])
// console.log(marks.length)
// marks[2] = 99 // change a value in array//
// marks[6] = 95; // add a new value on array//
// console.log(marks)


// array methods//

// array to  string//
// let lalit = [10, 20, 30, false, "not define"]
//  let a = lalit.toString()
//  console.log(a)
//  console.log(typeof[a])

//array join method//
// let lalit = [10, 20, 30, false, "not define"]
// let a = lalit.toString()
// // console.log(a)

// let c = lalit.join("_")       //array join method//
//  console.log(c)



//arrray pop method//
// let lalit = [10, 20, 30, false, true, 56, "not define"]
// let a = lalit.toString()
//  console.log(a)

// let c = lalit.pop() //arrray pop method//
// console.log(lalit,c)

// array push method//

// let a =[10, 20, 30] 
//  a.push(100)
//  a.push(500)
//  console.log(a)



//shift mehtod//

//  let a = [10, 20, 30, 40]
// a.shift(a)
// console.log(a)


//unshift method//

// let a = [10, 20,30, 50]
// a.unshift(100)
// console.log(a)


//delet medthod//

// let a = [10, 20, 50, 90]
// delete a[2]
// console.log(a)
// console.log(a.length)


// concate method//

// let a = [10, 20, 50, 90]
// let b = [30, 60, 75, 80]
// let newa = a.concat(b)
// console.log(newa)


// sort method//
// let a = [5,45,1,2,2,3,4]
// a.sort()
// console.log(a)


//sort method in aasending order and decinding oreder //
// let compare = (a, b)=>{
//     return a - b    
// }
// let a = [5,45,1,2,2,3,4]
// a.sort(compare)
// console.log(a)




//reverse method//
 
// let a = [1,2,3,4,4,5]
// a.reverse()
// console.log(a)



//splice method//

// let a = [1,2,3,4,5]
// a.splice(2,1,55,77,88)
// console.log(a)


//slice method//

// let a = [31,32,34,35,37,83]
// let newa= a.slice(2)
// console.log(newa)


// //
