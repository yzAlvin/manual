# setup

maybe have done some programming tutorials or have run code snippets

problem is only know coding from context of browser - lets set up so can write code locally on machine

## code editor

you could use any text editor like notepad

problem is there are better tools that can help you write code

examples are notepad++, sublime text, visual code they offer syntax highlighting and with language server protocol can have code suggestions

i recommend [visual studio code](https://code.visualstudio.com/) for beginner

### other

can also use an integrated development environment (IDE), that is specific for the language you write

* Java - IntelliJ
* Python Pycharm
* C# - Visual Studio (not the same as visual studio code)

often has more powerful features but more specific to a language

can also use less GUI and more keyboard focused editors like vim, emacs, don't recommend for beginners, but definitely worth learning if interested

## running code

### javascript

need a javascript runtime environment to execute JavaScript code outside a web browser

#### node

[node](https://nodejs.org/en/)

with a `.js` file, run command `node path/to/.js file` in terminal

##### example

create a file `example.js` with the content

```js
console.log('Hello World');
```

run `node example.js` in a terminal to run the code in the file.

#### deno

#### bun

#### web browser

most (all?) web browsers have dev tools which you can reach with `F12` or right click -> inspect

there will be a `console` tab where you can type and run code

### html

html is a markup language, not really 'code' but including it anyway

you dont need anything special to 'run' html, you can open it in a browser, drag and drop into browser and it will render the html

### python

python is pre-installed on some operating systems, like mac. if don't already have it, download [python](https://www.python.org/)

#### example

create a file `example.py` with the content

```js
print('Hello World');
```

run `python example.py` in a terminal to run the code in the file.
