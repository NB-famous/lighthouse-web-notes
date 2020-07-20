### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.


``` javascript

function whatToDoForLunch(hungry, availableTime)
{
  if (hungry === true){ console.log("I'm hungry and I have " +  availableTime  +  " minutes for lunch.") ;
    if (availableTime < 20) { console.log("With "+ availableTime + " minutes I can only go brew some coffe."); }
    else if (availableTime >= 20 && availableTime <= 30 ){console.log("With "+ availableTime + " minute break I will go buy snacks at the dep.");}
    else if (availableTime >= 50){ console.log("With "+ availableTime + " minutes I have enough time to order some food at a restaurant. But get back fast we are in bootcamp so no time to waste.");}
    else{console.log("not hungry! get back to work");} }
}

```