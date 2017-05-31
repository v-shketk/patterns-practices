---
TOCTitle: 'AddModule Method (ModuleInfoGroup, String, Type, String[])'
Title: 'ModuleInfoGroupExtensions.AddModule Method (ModuleInfoGroup, String, Type, String[]) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModuleInfoGroupExtensions.AddModule(Microsoft.Practices.Prism.Modularity.ModuleInfoGroup,System.String,System.Type,System.String[])'
ms:mtpsurl: 'addmodule-mthd-moduleinfogroup-str-type-str.md'
---

# ModuleInfoGroupExtensions.AddModule Method (ModuleInfoGroup, String, Type, array&lt;String&gt;)

Adds a new module that is statically referenced to the specified module info group.

**Namespace:** [Microsoft.Practices.Prism.Modularity](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)

**Version:** 5.0.0.0 (5.0.0.0)

## Syntax


### Parameters

moduleInfoGroup  
Type: [Microsoft.Practices.Prism.Modularity.ModuleInfoGroup](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup)
The group where to add the module info in.

moduleName  
Type: [System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)
The name for the module.

moduleType  
Type: [System.Type](http://msdn.microsoft.com/en-us/library/42892f65)
The type for the module. This type should be a descendant of [IModule](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.imodule).

dependsOn  
Type: array&lt;[System.String](http://msdn.microsoft.com/en-us/library/s1wwdcbf)&gt;
The names for the modules that this module depends on.

### Return Value

Type: [ModuleInfoGroup](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup)
Returns the instance of the passed in module info group, to provide a fluid interface.
### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [ModuleInfoGroup](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity.moduleinfogroup). When you use instance method syntax to call this method, omit the first parameter. For more information, see [Extension Methods (Visual Basic)](http://msdn.microsoft.com/en-us/library/bb384936.aspx) or [Extension Methods (C\# Programming Guide)](http://msdn.microsoft.com/en-us/library/bb383977.aspx).

## See Also


[ModuleInfoGroupExtensions Members](https://msdn.microsoft.com/allmembers.t:microsoft.practices.prism.modularity.moduleinfogroupextensions)

[AddModule Overload](https://msdn.microsoft.com/overload:microsoft.practices.prism.modularity.moduleinfogroupextensions.addmodule)

[Microsoft.Practices.Prism.Modularity Namespace](https://msdn.microsoft.com/library/microsoft.practices.prism.modularity)