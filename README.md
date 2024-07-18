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
