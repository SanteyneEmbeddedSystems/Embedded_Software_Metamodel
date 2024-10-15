# Embedded_Software_Metamodel

This repository defines a metamodel allowing to model an embedded software
loaded on a microcontroller.  
The metamodel is framework and language independent.  
It is a set of metaclasses, relations and constraints dedicated to the modeling
of an embedded software.

This metamodel is intented to cover the embedded software design from the
functional architecture to the detailed design.  
Currently only the static elements of the physical software architecture are
covered.

## Software_Element

![Software_Element](doc/Software_Element.svg)

The _Identifier_ attribute is by definition unique. Only the elements that have
an _Identifier_ can be compared to one of their other version.

## Package

![Package](doc/Package.svg)

## Project

![Project](doc/Project.svg)

## Types

![Type](doc/Type.svg)

### Typed_Element

![Typed_Element](doc/Typed_Element.svg)

### Basic_Type

![Basic_Type](doc/Basic_Type.svg)

### Array_Type

![Array_Type](doc/Array_Type.svg)

### Enumerated_Type

![Enumerated_Type](doc/Enumerated_Type.svg)

### Fixed_Point_Type

![Fixed_Point_Type](doc/Fixed_Point_Type.svg)

### Record_Type

![Record_Type](doc/Record_Type.svg)

## Interface

![Interface](doc/Interface.svg)

### Client_Server_Interface

![Client_Server_Interface](doc/Client_Server_Interface.svg)

### Event_Interface

![Event_Interface](doc/Event_Interface.svg)

## Component_Type

![Component_Type](doc/Component_Type.svg)

### Port

![Port](doc/Port.svg)

### Configuration_Parameter

![Configuration_Parameter](doc/Configuration_Parameter.svg)

### OS_Operation

![OS_Operation](doc/OS_Operation.svg)

## Composition

![Composition](doc/Composition.svg)

### Component_Prototype

![Component_Prototype](doc/Component_Prototype.svg)

### Connector

![Connector](doc/Connector.svg)

### Task

![Task](doc/Task.svg)
