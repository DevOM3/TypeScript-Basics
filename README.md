# TypeScript-Basics
Website implementing "Basics of TypeScript" - (credits - The Net Ninja)

## Get basic environment set up
Firstly, you need **Node** installed.
I'm using a **Visual Studio Code** for writing code as it by-default supports TypeScript.

## Get started with TypeScript
Open **Command Prompt** and type **npm i -g typescript** to install TypeSript Compiler.
Now your TypeScript environment is set up.

###### How to compile TypeScript into JavaScript
Our Web Browsers do not understand TypeScript. So, we need to compile it to JavaScript.
For that the command is **tsc filename.ts**.
but the problem is that you have to run it always when you make changes to your TypeScript file. To automatically recognize that the file is changed and automatically compile it down to JavaSscript use the command **tsc filename.ts -w**.

You can also use **tsc --init** and generate a TypeScript config file for cusom configurations.
