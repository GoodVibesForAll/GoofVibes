# GoofVibes
# JS Code to calculate your time left if you will be alive till 90.

function lifeInWeeks(age) {
    var x = ((90*365) - (age*365));
    var y = ((90*52) - (age*52));
    var z = ((90*12) - (age*12));
    console.log("You have " + x + " days, " + y + " weeks, and " + z + " months left.")
}
lifeInWeeks(24); 

# JS Code to create Love Calculator
function LoveCalculator(p1,p2){
    var LovePercentage = Math.floor((Math.random()*100) +1);
    return LovePercentage;
    
}
var result = LoveCalculator();
console.log(" Pallavi Loves Kier : " + result + "%");

# Another Love calc;
prompt("What's your name?");
prompt("What's thier name?");
var LovePercentage = Math.floor((Math.random()*100) +1);
alert("Your Love Percentage is " + LovePercentage + "%");

# Love Calc based on love%;
prompt("What's your name?");
prompt("What's thier name?");
var LovePercentage = Math.floor((Math.random()*100) +1);
if(LovePercentage > 80){
    alert("Your Love Percentage is " + LovePercentage + "% . Wohoo ! Soulmates");
}else{
    alert("Your Love Percentage is " + LovePercentage + "%");
}

# Leap Year Code
function isLeap(year) {  
    if(year%4===0 && year%100!==0){
        return "Leap year.";
    }else if(year%4!==0 || year%100===0 && year%400!==0 ){
        return "Not leap year.";
    }
}

# FizzBuzz
var outputArray = [] ;
var count=1;
function fizzBuzz(){
    if(count%3===0 && count%5===0){
        outputArray.push("FizzBuzz");
    }    
    else if(count%3===0){
       outputArray.push("Fizz") ;
    }else if(count%5===0){
        outputArray.push("Buzz");
    }else{
        outputArray.push(count);
    }
    count++;
    console.log(outputArray);
}

# FizzBuzz for 1 - 100
var outputArray = [] ;
var count=1;
function fizzBuzz(){
    while(count<=100){
    if(count%3===0 && count%5===0){
        outputArray.push("FizzBuzz");
    }    
    else if(count%3===0){
       outputArray.push("Fizz") ;
    }else if(count%5===0){
        outputArray.push("Buzz");
    }else{
        outputArray.push(count);
    }
    count++;
}
    console.log(outputArray);
}


# Who is buying you Lunch 

function whosPaying(names) {
    var numberOfPpl = names.length;
    var randomNamePosition = Math.floor(Math.random() * numberOfPpl);
    var randomName = names[randomNamePosition];
    return randomName + " is going to buy lunch today!";
}

# Beer Song
var count = 99;
function beer(){
    while (count >= 0){
       if (count >= 2){
          console.log(count + " bottles of beer on the wall, " + count + " bottles of beer.Take one down and pass it around, " + (count-1)  + " bottles of beer on the wall.");
       }else if (count===1){
          console.log(count + " bottle of beer on the wall, " + count + " bottle of beer.Take one down and pass it around, no more bottles of beer on the wall.");
       }else if (count===0){
          console.log("No more bottles of beer on the wall, no more bottles of beer.Go to the store and buy some more, 99 bottles of beer on the wall.") ;
       }
    
        count=count-1;
          
    }
    
    
}

# Fibonacci
function fibonacciGenerator (n) {
    var output = [];
    for(var i=0;i<=n;i++){
        if(n===1){
            output=[0];
        }
        else if(n===2){
            output=[0,1];
        }
        else{
               output = [0,1]
               for(var a = 2 ; a<n ;a++){
                   output.push(output[output.length-2]+output[output.length-1]);
               }
            }
               
        return output;       
}
    

