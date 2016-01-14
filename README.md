# Tema12
In the world of classes, implicit conversions can be controlled by means of three member functions:

    Single-argument constructors: allow implicit conversion from a particular type to initialize an object.
    Assignment operator: allow implicit conversion from a particular type on assignments.
    Type-cast operator: allow implicit conversion to a particular type.


*see example shown in repostiory*

The type-cast operator uses a particular syntax: it uses the operator keyword followed by the destination type and an empty set of parentheses. Notice that the return type is the destination type and thus is not specified before the operator keyword.
