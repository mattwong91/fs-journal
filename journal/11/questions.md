# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > | It allows us to declare base classes or interfaces that other classes can implement or override. It can allow for more complex data modeling by using a shared base set of properties or methods. |

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > | A child class will inherit all members of its parent except a constructor or any private members of the parents class. |

3. How does ***accessibility*** affect inheritance?

  > | members that are declared as private are not inherited by child classes. If a child class is declared within a parent class it will have access to private members though. |

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > | A primary key is a unique value that identifies a row of data. A foreign key is a value that corresponds to a primary key on a different table. |

5. What is an ***alias***?

  > | A custom shorthand name that is used to reference a table. |

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```

  > | SELECT 
  p.*,
  d.*,
  pd.*
  FROM patients p
  JOIN doctors d ON d.id = pd.doctorId
  JOIN patient_doctors pd ON p.id = pd.patientId |
