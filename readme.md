# JS Assignment -4

## Write a chained if / else-if statement to fill in the following conditions

## val  < 5  =>  Tiny
## val  < 10  =>  Small
## val  < 15  =>  Medium
## val  < 20  => Large
## val  >= 20  => Huge 


Ans :

```js


let num=20
if (num<5){
    console.log("tiny")
if (num<10)
    console.log("small")
if (num<15)
    console.log("medium")
}else if (num<20){
    console.log("large")
}else {
    console.log("huge")
    
}


```



## Use the switch case and create an application with the following roles.

## admin => gets full access
## subAdmin => gets access to create and delete courses
## testPrep => gets access to create and delete tests
## user => gets access to consume contents


Ans :


```js


let roles=["admin,subAdmin,testPrep,user"]

let role="admin"

switch(role){

    case "admin":
    console.log("gets full access")
       
        break

    case "subAdmin":
    console.log("gets access to create and delete course")

        break

    case "testPrep":
    console.log("gets access to create and delete tests")

        break

    case 'user':
    console.log("gets access to consume contents")

}
    ```
        
