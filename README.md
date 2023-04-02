# Design Patterns

## UML Diagrams

### Types

![](images/1.jpg)

### Class diagram

- Represented as rectangle with 3 sections
  - Class name
  - Class attributes
  - Class methods
- Only class name is **mandatory**
- Access Modifiers
  - +: public
  - -: private
  - #: protected
  - ~: package local
- Parameter Directionality (wrt caller)

  - in: not changed by the method
  - out: serves as output value for the method
  - inout: provided by caller and used as the output value for the method

  ![](images/2.jpg)

- Levels of specifications of class diagrams
  - Conceptual perspective
    ![](images/3.jpg)
  - Specification perspective
    ![](images/4.jpg)
  - Implementation perspective
    ![](images/5.jpg)
- Relationships between classes
  ![](images/6.jpg)

  - Association
    ![](images/7.jpg)
  - Inheritance (Generalization)

    - Name of **abstract class** in written in _italics_

    ![](images/8.jpg)

  - Realization
    ![](images/9.jpg)
  - Dependecy
    ![](images/10.jpg)
  - Aggregation
    ![](images/11.jpg)
  - Composition

    - Type of aggregation where the component classes are destroyed when the aggregate class is destroyed

    ![](images/12.jpg)

![](images/13.jpg)

---
