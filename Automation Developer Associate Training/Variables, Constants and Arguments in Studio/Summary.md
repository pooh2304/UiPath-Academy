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
- Double.ToString Method
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

# Arguments
