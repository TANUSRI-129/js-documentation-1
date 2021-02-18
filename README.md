# js-documentation-1

### Functions
Functions without parameters
```javascript
function addition(){
    var a=10;
    var b=30;
    return a+b;
}

addition()
40
```
function with parameters
```javascript
function addition(a,b){
return (a+b)
}
addition(6,4)
10
```
```javascript
function multiplecation(){
    var a=2;
    var b=6;
    return (a*b)
}
multiplecation()
12
```

Anonymous function

```javascript
var substraction=function(a,b){
    return(a-b)
}
substraction(4,5)
-1
```
Arrow function
```javascript
var mul=(a,b)=>{
    return(a*b)
}

mul(2,3)
6
```
Higher order functions
```javascript
arr.map(function(tanus){
    console.log(tanus)
})
VM1807:2 tanus
VM1807:2 geethas
VM1807:2 priyas
VM1807:2 syamas
VM1807:2 deepus
VM1807:2 yammus
(6
```

```javascript
arr.map((item,index)=>{
    console.log(item+"is having index of:"+index)
})
tanusis having index of:0
VM2107:2 geethasis having index of:1
VM2107:2 priyasis having index of:2
VM2107:2 syamasis having index of:3
VM2107:2 deepusis having index of:4
VM2107:2 yammusis having index of:5
```
