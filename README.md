AirBnB clone Project
.....................
- This project is about 0x00. AirBnB clone - The console

Background Context
.................
Welcome to the AirBnB clone project!
....................................
-Before starting, please read the AirBnB concept page.

First step: Write a command interpreter to manage your AirBnB objects.
.....................................................................
This is the first step towards building your first full web application: the AirBnB clone. This first step is very important because you will use what you build during this project with all other following projects: HTML/CSS templating, database storage, API, front-end integration…

Each task is linked and will help you to:

	- put in place a parent class (called BaseModel) to take care of the initialization, serialization and deserialization of your future instances
create a simple flow of serialization/deserialization: Instance <-> Dictionary <-> JSON string <-> file
	- create all classes used for AirBnB (User, State, City, Place…) that inherit from BaseModel
	- create the first abstracted storage engine of the project: File storage.
	- create all unittests to validate all our classes and storage engine

What’s a command interpreter?
.............................
Do you remember the Shell? It’s exactly the same but limited to a specific use-case. In our case, we want to be able to manage the objects of our project:

	-  Create a new object (ex: a new User or a new Place)
	- Retrieve an object from a file, a database etc…
	- Do operations on objects (count, compute stats, etc…)
	- Update attributes of an object
	- Destroy an object

Resources
................
1. https://docs.python.org/3.8/library/cmd.html
2. https://docs.python.org/3.8/library/cmd.html
3. http://pymotw.com/2/cmd/
4. https://docs.python.org/3.8/library/uuid.html
5. https://docs.python.org/3.8/library/datetime.html
6. https://docs.python.org/3.8/library/unittest.html#module-unittest
7. https://yasoob.me/2013/08/04/args-and-kwargs-in-python-explained/
8. https://www.pythonsheets.com/notes/python-tests.html
9. https://wiki.python.org/moin/CmdModule
10. https://realpython.com/python-testing/
