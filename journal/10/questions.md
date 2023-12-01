# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > | It is a collection of modules, classes, methods, etc. They can be used by other files within the application/program |

02. What is the difference between a `class` and an `interface`?

  > | An interface is an entirely abstract class. It has properties and methods that other classes can implement or inherit from, each with their own interpretation of those methods associated with the interface. |

03. What is the method that returns an instance of a class, yet it has no return type?

  > | A Constructor |

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > | public |

06. In the Car example what is `string` an indication of?

  > | It is the return type of the Start() Function |

07. In the Car example what is `abstract` preventing?

  > | It is preventing an instance of  Car from being able to be created |

08. In a SQL table, what is the difference between information in a row and information in a column?

  > | Columns are data fields/properties and rows are entries in the table |

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > | CREATE TABLE characters(id INT PRIMARY KEY, name VARCHAR(255), age VARCHAR(255), description VARCHAR(255)) |

10. In SQL how can you query more than a single table? Provide an example.

  > | You can JOIN tables. SELECT a.*, b.*, FROM accounts a JOIN blah b ON b.id = a.foreignId |