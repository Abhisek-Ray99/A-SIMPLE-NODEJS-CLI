c:node>npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See npm help json for definitive documentation on these fields
and exactly what they do.

Use npm install  --save afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
name: (node)



c:node>npm install lodash --save


c:node>npm install nodemon -g

c:node>node app.js addTodo
Running app.js
Running todos.js
You ran the command: addTodo

c:node>node app.js listTodos
Running app.js
Running todos.js
You ran the command: listTodos

c:node>node app.js readTodo
Running app.js
Running todos.js
You ran the command: readTodo

c:node>node app.js deleteTodo
Running app.js
Running todos.js
You ran the command: deleteTodo

//the add list is save in todo.json file

c:node>node app.js addTodo --title="Go to work"
Running app.js
Starting todos.js
Running Command:  addTodo

c:node>node app.js addTodo --title="Read the paper"
Running app.js
Starting todos.js
Running Command:  addTodo

c:node>node app.js addTodo --title="Netflix and chill"
Running app.js
Starting todos.js
Running Command:  addTodo

//delete the list of item in the json file

c:node>node app.js deleteTodo --title="Netflix and chill"
Running app.js
Starting todos.js
Running Command:  deleteTodo
Todo was deleted

c:node>node app.js deleteTodo --title="Watch Pulp Fiction"
Running app.js
Starting todos.js
Running Command:  deleteTodo
Todo not found


//read the list of item from todo.json

c:node>node app.js readTodo --title="Mow the lawn"
Running app.js
Starting todos.js
Running Command:  readTodo
Great! The todo was found.
------
It's title is: Mow the lawn

c:node>node app.js readTodo --title="Netflix and chill"
Running app.js
Starting todos.js
Running Command:  readTodo
Whoops! The todo was not found.


//print the list of item from todo.json


c:node>node app.js listTodos
Running app.js
Starting todos.js
Running Command:  listTodos
Printing 3 todo(s).
------
It's title is: Mow the lawn
------
It's title is: Go to work
------
It's title is: Read the paper