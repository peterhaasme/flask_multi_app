Goal is to get multiple Flask apps to run from the same development server.

https://flask.palletsprojects.com/en/1.1.x/patterns/appdispatch/

Special Note: Make sure to use relative and not absolute import statements when you're building out your apps. Otherwise when you attempt to import and run one of the nested apps the import will fail. Here is a handy reference https://realpython.com/absolute-vs-relative-python-imports
