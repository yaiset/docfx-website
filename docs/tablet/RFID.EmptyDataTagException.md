# <a id="RFID_EmptyDataTagException"></a> Class EmptyDataTagException

Namespace: [RFID](RFID.md)  
Assembly: RFID.dll  

Excepción que se lanza cuando se encuentra una etiqueta de datos vacía.

```csharp
public class EmptyDataTagException : Exception, ISerializable, _Exception
```

<Details>
<Summary><strong>Inheritance</strong></Summary>

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Exception](https://learn.microsoft.com/dotnet/api/system.exception) ← 
[EmptyDataTagException](RFID.EmptyDataTagException.md)

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

### <a id="RFID_EmptyDataTagException__ctor"></a> EmptyDataTagException\(\)

Inicializa una nueva instancia de la clase <xref href="RFID.EmptyDataTagException" data-throw-if-not-resolved="false"></xref>.

```csharp
public EmptyDataTagException()
```

### <a id="RFID_EmptyDataTagException__ctor_System_String_"></a> EmptyDataTagException\(string\)

Inicializa una nueva instancia de la clase <xref href="RFID.EmptyDataTagException" data-throw-if-not-resolved="false"></xref> con un mensaje de error especificado.

```csharp
public EmptyDataTagException(string message)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

El mensaje que describe el error.

### <a id="RFID_EmptyDataTagException__ctor_System_String_System_Exception_"></a> EmptyDataTagException\(string, Exception\)

Inicializa una nueva instancia de la clase <xref href="RFID.EmptyDataTagException" data-throw-if-not-resolved="false"></xref> con un mensaje de error especificado y una referencia a la excepción interna que es la causa de esta excepción.

```csharp
public EmptyDataTagException(string message, Exception inner)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

El mensaje que describe el error.

`inner` [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

La excepción que es la causa de la excepción actual.

