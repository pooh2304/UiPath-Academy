# Variables

### Properties of Variable
- Name (PascalCase naming convention) - Mandatory
- Variable Type - Mandatory
- Scope - Mandatory
- Default Value - Optional

**If there are two variables with the same name, the variable defined in the most inner scope tops the priority list.** <br><br>

Q. Which of the following three (3) fields are mandatory when creating a variable in UiPath Studio? Choose all the options that apply. <br>
**Scope <br>
Name** <br>
Default value <br>
**Variable type** <br>
Expression <br><br>

## Data Types (Visual Basic.Net)
- String - **System.String**
- Numeric
  - Int32 - **System.Int32** 
  - Long - **System.Int64**
  - Double - **System.Double**
- Boolean - **System.Boolean**
- Collection
  - Array - **ArrayOf<T> or System.DataType[]** stores multiple values of the same data type. The size (number of objects) is defined at creation.
  - List - **System.Collections.Generic.List<T>** stores multiple values of the same data type, just like Arrays. But unlike Arrays, the size is dynamic.
  - Dictionary - **System.Collections.Generic.Dictionary<TKey, TValue>** stores objects in the form of (key, value) pairs, where each of the two can be a separate data type.
- Data Table
- Date and Time
  - DateTime - **System.DateTime** stores specific time coordinates **(mm/dd/yyyy hh:mm:ss)**.
  - To get the current time, assign the expression **DateTime.Now**.
  - TimeSpan - **System.TimeSpan** stores information about a duration **(dd:hh:mm:ss)**.

### Conversion Methods of Data Types 
- Convert.ToString Method
- Convert.Int32 Method or CInt(String)
- Double.ToString Method or CDbl(String)
- Double.Parse Method: Converts the string representation of a number to its floating-point number equivalent
- Boolean.ToString Method
- Convert.ToBoolean Method
- Convert Date and Time to String: **DateTimeVar.ToString("dd-MM-yyyy")**

<br>

Q. What of the following method converts a specified value to an integer? Choose one of the options below. <br>
ToString(expression) <br>
**CInt(expression)** <br>
Parse(expression) <br>
ToBoolean(expression) <br>

### Workflows Layouts
Use action verbs in workflow names.
- Sequences
- Flowcharts
- State Machines

# Arguments
- Arguments pass data between workflows. 
- Arguments have specific directions: **In, Out, and In/Out**. 
- PascalCase naming convention.
- Use prefixes in argument names.

| Variables                                       | Arguments                                                         |
|-------------------------------------------------|-------------------------------------------------------------------|
| Don't have directions like In, Out, or In/Out.   | Do have directions like In, Out, In/Out.                          |
| To create a variable press: Ctrl + K.            | To create an In Argument press: Ctrl + M. To create an Out Argument press: Ctrl + Shift + M.  |
| To create variables, there must be at least one activity in the Designer Panel. | Arguments can be created if the Designer panel doesn't contain any activity. |
| Require a defined scope.                        | Do not require a scope.                                           |

<br> 

Q. What is the keyboard shortcut to create an argument of direction IN? Choose one of the options below. <br>
Ctrl + K <br>
Ctrl + Shift + M <br>
**Ctrl + M** <br>
Alt + M <br>

## Creating Variables/Arguments
- From the Data Manager
- From the Body of an Activity
- From the Properties/Arguments Panel
- From the Variables Panel

# Global Constants and Variables
- Can be accessed by all parts of an automation project.
- Easier data management.
- Can be created only from the Data Manger panel.
- The difference between a global constant and a global variable is that none of the properties of a global constant can be altered whereas the value of a global variable can be modified during the program execution.

Q. Where in Studio can global constants and variables be created and managed? Choose one of the options below. <br>
From the Variables panel <br>
From the body of an activity <br>
**From the Data Manager panel** <br>
From the Properties panel <br>


#### Note
- **vbLf**: This will add a new line in the text. 
- **Math.Round**: rounds the floating number to a given precision.
