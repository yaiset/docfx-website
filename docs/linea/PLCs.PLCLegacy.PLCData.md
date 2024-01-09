# <a id="PLCs_PLCLegacy_PLCData"></a> Class PLCLegacy.PLCData

Namespace: [PLCs](PLCs.md)  
Assembly: PLC.dll  

Clase que alberga todas las variables del PLC.

```csharp
public class PLCLegacy.PLCData
```

<Details>
<Summary><strong>Inheritance</strong></Summary>

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[PLCLegacy.PLCData](PLCs.PLCLegacy.PLCData.md)

</Details><br>

<Details>
<Summary><strong>Inherited Members</strong></Summary>

[object.ToString\(\)](https://learn.microsoft.com/dotnet/api/system.object.tostring), 
[object.Equals\(object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\)), 
[object.Equals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.equals\#system\-object\-equals\(system\-object\-system\-object\)), 
[object.ReferenceEquals\(object, object\)](https://learn.microsoft.com/dotnet/api/system.object.referenceequals), 
[object.GetHashCode\(\)](https://learn.microsoft.com/dotnet/api/system.object.gethashcode), 
[object.GetType\(\)](https://learn.microsoft.com/dotnet/api/system.object.gettype), 
[object.MemberwiseClone\(\)](https://learn.microsoft.com/dotnet/api/system.object.memberwiseclone)

</Details>

## Properties

### <a id="PLCs_PLCLegacy_PLCData_EstadoLinea"></a> EstadoLinea

Estado de la línea.

```csharp
public object EstadoLinea { get; set; }
```

#### Property Value

 [object](https://learn.microsoft.com/dotnet/api/system.object)

### <a id="PLCs_PLCLegacy_PLCData_FotocelulaFinalActiva"></a> FotocelulaFinalActiva

Indica si la fotocélula final está activa.

```csharp
public bool FotocelulaFinalActiva { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="PLCs_PLCLegacy_PLCData_ListoParaPesar"></a> ListoParaPesar

Indica si está listo para pesar.

```csharp
public bool ListoParaPesar { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="PLCs_PLCLegacy_PLCData_PesadoCorrectamente"></a> PesadoCorrectamente

Indica si el pesaje se ha realizado correctamente.

```csharp
public bool PesadoCorrectamente { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="PLCs_PLCLegacy_PLCData_TransponderLeido"></a> TransponderLeido

Indica si el transpondedor ha sido leído.

```csharp
public bool TransponderLeido { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

