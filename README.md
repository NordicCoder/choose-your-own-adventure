# choose-your-own-adventure
Choose your own adventure in JavaScript
confirm("I am ready to play Lindsey's first programming game!")
var age = prompt ("What is your age?");

if (age.length <13) {console.log ("You are allowed to play but I assume no responsibility.");
}
else
{
console.log("All Right! Lets play!")

}
console.log("You are camping in the woods when all of a sudden you see a fox making its way towards you.")

console.log("As the fox gets closer you see it really just wants the food you left out by your tent.");
var userAnswer=prompt("Do you give the fox some food?")

if (userAnswer==="yes") {
    console.log("You give the fox some food and it curls up right next to you. Unfortunately, the food attracts the company of a black bear and it eats you.");
}
else
{
    console.log ("You refuse to give the fox any food and it lunges towards you, biting you in the neck.");
}
var feedback= prompt ("Please rate my first game out of 10")
if (feedback<8) { ("Thank you! Next time it will be a happier ending!")
} 
else
 { ("I'll keep practicing coding and make the adventure longer next time!"); }
