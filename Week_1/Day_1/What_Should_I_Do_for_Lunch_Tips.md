### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript

function whatToDoForLunch(hungry, availableTime) {
  if (hungry === false){
    console.log("Get back to work!");
  } else if (hungry ===true){
    if (availableTime <= 20){
      console.log("Get something from the kitchen!");
    } else if ((availableTime => 20) && (availableTime <= 30)) {
      console.log("Try a place nearby!");
    } else {
      console.log("We're in a bootcamp. Reconsider how much time we have");
    }
  }
}; 

```