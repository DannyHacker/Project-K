Everything is an object.

A string is not a sequence of characters but an object with properties.
  There should only be one instance [so no need to type the same string over and over]
  Translation is context based.
A file is not a sequence of bytes but an object with properties based on extension:
CSV for comma separated values [normally a 2D text array].
Image file has height, width, format, and other details.
Movie file has screen size and format.

Services are:
  Error/Exception handling
  Status + Logging (status could be the last logged item)
  Analytics
  Undo/Redo -- or journalling of changes -- for practically infinity
  Framework for Unit and Integration testing
  

Running, testing, debugging and editing are modes of any object -- so editing an object at run-time is OK.




Danny Hacker, Copyright 2019, Soli Deo Gloria, Apache License 2.0
