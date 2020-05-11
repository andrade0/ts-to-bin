# TS-TO-BIN

Boilerplate for creating fully standalone binaries from typescript application

## Quick start

Put your code into src/main.ts (your entry point) and run the described commands 

## Available scripts

+ `start`: Build and test your TS code
+ `build`: Build your TS code ( outDir: ./build )
+ `lint`: Lint your code
+ `package`: Package all your code and imports in one js file ( outDir: ./package )
+ `bin`: Create your binary from de packaged file ( ./package/main.js ),
+ `execute-bin`: Do everything uppon this command and start yout fresh generated binary file called ./bin