# kitchen-sink
Random things that don't fit into any other repo yet.

## broccoffee

### What?
Bash script for setting up a new CoffeeScript npm module to be built with broccoli.

Sets up .gitignore, .npmignore, Brocfile etc. and creates a broc.sh script that you can run to start broccoli-timepiece.

For more details it is recommended to just read the script.

### How to use?
1. Create a new module with npm init, specify that the main file sits in lib, e.g. lib/index.js
2. Run broccoffee
3. Put your .coffee files in src, e.g. src/index.coffee
4. Run broc.sh to start broccoli-timepiece, it will compile your CoffeeScript files whenever you save them.
