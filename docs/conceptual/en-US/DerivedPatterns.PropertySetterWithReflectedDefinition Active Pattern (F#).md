# DerivedPatterns.PropertySetterWithReflectedDefinition Active Pattern (F#)

Recognizes property **set** accessors that have an associated **ReflectedDefinition**.

**Namespace/Module Path**: Microsoft.FSharp.Quotations.DerivedPatterns

**Assembly**: FSharp.Core (in FSharp.Core.dll)


## CAPS_SYNTAX_MD

```
// Signature:
( |PropertySetterWithReflectedDefinition|_| ) : (propertyInfo:PropertyInfo) -> Expr option
```

#### CAPS_PARAMETERS_MD
*propertyInfo*
Type: **T:System.Reflection.PropertyInfo**


The description of the property.



**The expression of the method definition if it is found; otherwise, None.**
## CAPS_REMARKS_MD
This function is named **PropertySetterWithReflectedDefinitionPattern** in the .NET Framework assembly. If you are accessing the member from a .NET Framework language other than F#, or through reflection, use this name.


## Platforms
Windows 8, Windows 7, Windows Server 2012, Windows Server 2008 R2


## Version Information
**F# Core Library Versions**

Supported in: 2.0, 4.0, Portable




## See Also
[Quotations.DerivedPatterns Module &#40;F&#35;&#41;](Quotations.DerivedPatterns+Module+%28F%23%29.md)

[Microsoft.FSharp.Quotations Namespace &#40;F&#35;&#41;](Microsoft.FSharp.Quotations+Namespace+%28F%23%29.md)
