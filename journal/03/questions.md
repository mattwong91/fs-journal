# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > | Abstraction, Encapsulation, Inheritance, and Polymorphism |

02. How does `export` differ from `export default`?
  
  > | Default exports are used to export single objects, variables, etc. Any name can be used to import them. Normal exports are used to export multiple values and must be specifically named in the import |

03. What is Encapsulation?
  
  > | Encapsulation is grouping data and methods which transform or act upon that data. The data is kept restricted and only methods can change it |

04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > | The proxy object can override the get and set functions of an object. This can potentially help keep certain data safe from users trying to access properties that shouldn't be accessible via dot notation. |

05. What the difference between a `class` and an instance of a `class`?
  
  > | A class is a definition of an object. An instance of a class is an object which has the data specified by the class definition |

06. What is a computed Property?
  
  > | This is an object property where the property name is derived by a variable |

07. What is the purpose of the `MVC` pattern?
  
  > | To help create more predictable and maintainable code. |

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > | The controller interacts with the view. It draws to the view, recives user input, and gives requests to a service to interact with data models |

09. What is the job of the `Service` in `MVC`?
  
  > | The service interacts directly with data held in the Appstate and class models |

10. What is the job of the `Model` in `MVC`?
  
  > | Models exist to hold data and define objects |
