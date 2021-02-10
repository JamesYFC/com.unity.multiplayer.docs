---  
id: MLAPI.Exceptions.NotServerException  
title: MLAPI.Exceptions.NotServerException  
---

<div class="markdown level0 summary" markdown="1">

Exception thrown when the operation can only be done on the server

</div>

<div class="markdown level0 conceptual" markdown="1">

</div>

<div class="inheritance" markdown="1">

##### Inheritance

<div class="level0" markdown="1">

System.Dynamic.ExpandoObject

</div>

<div class="level1" markdown="1">

System.Dynamic.ExpandoObject

</div>

<div class="level2" markdown="1">

System.Dynamic.ExpandoObject

</div>

</div>

<div markdown="1" classs="implements">

##### Implements

<div markdown="1">

System.Runtime.InteropServices.\_Exception

</div>

<div markdown="1">

System.Runtime.Serialization.ISerializable

</div>

</div>

<div class="inheritedMembers" markdown="1">

##### Inherited Members

<div markdown="1">

Exception.GetBaseException()

</div>

<div markdown="1">

Exception.GetObjectData(SerializationInfo, StreamingContext)

</div>

<div markdown="1">

Exception.GetType()

</div>

<div markdown="1">

Exception.ToString()

</div>

<div markdown="1">

Exception.Data

</div>

<div markdown="1">

Exception.HelpLink

</div>

<div markdown="1">

Exception.HResult

</div>

<div markdown="1">

Exception.InnerException

</div>

<div markdown="1">

Exception.Message

</div>

<div markdown="1">

Exception.Source

</div>

<div markdown="1">

Exception.StackTrace

</div>

<div markdown="1">

Exception.TargetSite

</div>

<div markdown="1">

Object.Equals(Object)

</div>

<div markdown="1">

Object.Equals(Object, Object)

</div>

<div markdown="1">

Object.GetHashCode()

</div>

<div markdown="1">

Object.MemberwiseClone()

</div>

<div markdown="1">

Object.ReferenceEquals(Object, Object)

</div>

</div>

##### **Namespace**: System.Dynamic.ExpandoObject

##### **Assembly**: MLAPI.dll

##### Syntax [MLAPI_Exceptions_NotServerException_syntax]

    public class NotServerException : Exception, _Exception, ISerializable

## Constructors 

### NotServerException() [MLAPI_Exceptions_NotServerException__ctor]

<div class="markdown level1 summary" markdown="1">

Constructs a NotServerException

</div>

<div class="markdown level1 conceptual" markdown="1">

</div>

#### Declaration [declaration]

    public NotServerException()

### NotServerException(String) [MLAPI_Exceptions_NotServerException__ctor_System_String_]

<div class="markdown level1 summary" markdown="1">

Constructs a NotServerException with a message

</div>

<div class="markdown level1 conceptual" markdown="1">

</div>

#### Declaration [declaration-1]

    public NotServerException(string message)

#### Parameters [parameters]

| Type          | Name    | Description           |
|---------------|---------|-----------------------|
| System.String | message | The exception message |

### NotServerException(String, Exception) [MLAPI_Exceptions_NotServerException__ctor_System_String_System_Exception_]

<div class="markdown level1 summary" markdown="1">

Constructs a NotServerException with a message and a inner exception

</div>

<div class="markdown level1 conceptual" markdown="1">

</div>

#### Declaration [declaration-2]

    public NotServerException(string message, Exception inner)

#### Parameters [parameters-1]

| Type             | Name    | Description           |
|------------------|---------|-----------------------|
| System.String    | message | The exception message |
| System.Exception | inner   | The inner exception   |

### Implements [implements]

<div markdown="1">

System.Runtime.InteropServices.\_Exception

</div>

<div markdown="1">

System.Runtime.Serialization.ISerializable

</div>