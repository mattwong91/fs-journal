# Intro to Server side concerns with JavaScript
01. What do the letters of the acronym `CRUD` stand for?

  > | Create, Read, Update, Delete |

02. Each action that `CRUD` represents maps to an HTTP request. What HTTP request does each `CRUD` action correspond to?

  > | Create -> POST, Read -> GET, Update -> PUT, Delete -> Delete |

03. What does `ORM` stand for? Which `ORM` do we use when interacting with MongoDB

  > | Object Relationship Mapper. We use Mongoose  |

04. Which two `HTTP` request types include a body?

  > | POST and PUT |

05. In a/an _______ coding model, when you call a function, it returns only when the action has finished and stops your program for the time the action takes. Likewise in a/an _______ coding model, multiple things are allowed to happen at one time. When you perform an action, your program continues to run.  Fill in the blanks.

  > | Synchronous, Asynchronous |

06. What are the three types of data relationships? Provide an example of each.

  > | One to one (ex: Auther and address), One to many (ex: Blog and comments), Many to many (ex: Application to Developer) |

07. What is middleware?

  > | Middleware is software that provides applications with a layer in which they can communicate with each other. |

08. The ______ pipeline delivers information from the client while the ______ pipeline returns it. Fill in the blanks. 

  > | Request, Response |

09. Demonstrate the pattern that is used to include a request query with the client's `HTTP` request providing the property `tag` and the value `winter`.

  > | https://someurl.com/api/data?tag=winter |

10. What is a ***virtual property***?

  > | Virtual properties are addtional fields that don't actually exist on the object model but can be defined and interacted with like a normal property would be. They do not persist in any database. |
