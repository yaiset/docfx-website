# <a id="LectorINI_InvalidFileException"></a> Class InvalidFileException

Namespace: [LectorINI](LectorINI.md)  
Assembly: LectorINI.dll  

Excepción producida cuando el tipo de archivo no es válido.

```csharp
public class InvalidFileException : Exception, ISerializable, _Exception
```

<Details>
<Summary><strong>Inheritance</strong></Summary>

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Exception](https://learn.microsoft.com/dotnet/api/system.exception) ← 
[InvalidFileException](LectorINI.InvalidFileException.md)

</Details><br>

<Details>
<Summary><strong>Implements</strong></Summary>

[ISerializable](https://learn.microsoft.com/dotnet/api/system.runtime.serialization.iserializable), 
[\_Exception](https://learn.microsoft.com/dotnet/api/system.runtime.interopservices.\_exception)

</Details><br>

<Details>
<Summary><strong>Inherited Members</strong></Summary>

[Exception.GetBaseException\(\)](https://learn.microsoft.com/dotnet/api/system.exception.getbaseexception), 
[Exception.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.exception.tostring), 
[Exception.GetObjectData\(SerializationInfo, StreamingContext\)](https://learn.microsoft.com/dotnet/api/system.exception.getobjectdata), 
[Exception.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.exception.gettype), 
[Exception.Message](https://learn.microsoft.com/dotnet/api/system.exception.message), 
[Exception.Data](https://learn.microsoft.com/dotnet/api/system.exception.data), 
[Exception.InnerException](https://learn.microsoft.com/dotnet/api/system.exception.innerexception), 
[Exception.TargetSite](https://learn.microsoft.com/dotnet/api/system.exception.targetsite), 
[Exception.StackTrace](https://learn.microsoft.com/dotnet/api/system.exception.stacktrace), 
[Exception.HelpLink](https://learn.microsoft.com/dotnet/api/system.exception.helplink), 
[Exception.Source](https://learn.microsoft.com/dotnet/api/system.exception.source), 
[Exception.HResult](https://learn.microsoft.com/dotnet/api/system.exception.hresult), 
[Exception.SerializeObjectState](https://learn.microsoft.com/dotnet/api/system.exception.serializeobjectstate), 
[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

</Details><br>

## Constructors

### <a id="LectorINI_InvalidFileException__ctor"></a> InvalidFileException\(\)

```csharp
public InvalidFileException()
```

### <a id="LectorINI_InvalidFileException__ctor_System_String_"></a> InvalidFileException\(string\)

```csharp
public InvalidFileException(string message)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="LectorINI_InvalidFileException__ctor_System_String_System_Exception_"></a> InvalidFileException\(string, Exception\)

```csharp
public InvalidFileException(string message, Exception inner)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

`inner` [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

