# node-express

steps 

1: make repo in github 
2: clone the repo in your local directory 
3: use the command npm init -y or npm init if you want to be more descriptive
4: touch index.js or what you named as the entry point
5: create your functions and put them in your module exports 
6: declare them in your other JS file with require("./mymodule");


module.exports= {
    beBasic,
    add,
    subtract,
}

const { add, subtract } = require("./mymodule");


7: after that call the functions in your terminal with index.js