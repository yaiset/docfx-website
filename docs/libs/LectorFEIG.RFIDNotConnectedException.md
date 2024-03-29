# <a id="LectorFEIG_RFIDNotConnectedException"></a> Class RFIDNotConnectedException

Namespace: [LectorFEIG](LectorFEIG.md)  
Assembly: LectorFEIGCOM.dll  

Define una clase que representa una excepción personalizada que se produce cuando se intenta realizar una operación con el dispositivo RFID sin estar conectado.

```csharp
public class RFIDNotConnectedException : Exception, ISerializable, _Exception
```

<Details>
<Summary><strong>Inheritance</strong></Summary>

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Exception](https://learn.microsoft.com/dotnet/api/system.exception) ← 
[RFIDNotConnectedException](LectorFEIG.RFIDNotConnectedException.md)

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

### <a id="LectorFEIG_RFIDNotConnectedException__ctor"></a> RFIDNotConnectedException\(\)

Inicializa una nueva instancia de la clase RFIDNotConnectedException sin especificar un mensaje de error.

```csharp
public RFIDNotConnectedException()
```

### <a id="LectorFEIG_RFIDNotConnectedException__ctor_System_String_"></a> RFIDNotConnectedException\(string\)

Inicializa una nueva instancia de la clase RFIDNotConnectedException con un mensaje de error especificado.

```csharp
public RFIDNotConnectedException(string message)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

El mensaje que describe el error.

### <a id="LectorFEIG_RFIDNotConnectedException__ctor_System_String_System_Exception_"></a> RFIDNotConnectedException\(string, Exception\)

Inicializa una nueva instancia de la clase RFIDNotConnectedException con un mensaje de error especificado y una referencia a la excepción interna que es la causa de esta excepción.

```csharp
public RFIDNotConnectedException(string message, Exception inner)
```

#### Parameters

`message` [string](https://learn.microsoft.com/dotnet/api/system.string)

El mensaje que describe el error.

`inner` [Exception](https://learn.microsoft.com/dotnet/api/system.exception)

La excepción que es la causa de la excepción actual, o una referencia nula si no se especifica ninguna excepción interna.

