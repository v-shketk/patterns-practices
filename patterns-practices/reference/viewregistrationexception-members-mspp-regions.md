---
TOCTitle: ViewRegistrationException Members
Title: 'ViewRegistrationException Members (Microsoft.Practices.Prism.Regions)'
ms:assetid: 'AllMembers.T:Microsoft.Practices.Prism.Regions.ViewRegistrationException'
ms:mtpsurl: 'viewregistrationexception-members-mspp-regions.md'
---

# ViewRegistrationException Members

The [ViewRegistrationException](/patterns-practices/reference/viewregistrationexception-class-mspp-regions) type exposes the following members.

## Constructors

<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>ViewRegistrationException()</td>
<td><div class="summary">
Initializes a new instance of the [ViewRegistrationException](/patterns-practices/reference/viewregistrationexception-class-mspp-regions) class.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>ViewRegistrationException(String)</td>
<td><div class="summary">
Initializes a new instance of the [ViewRegistrationException](/patterns-practices/reference/viewregistrationexception-class-mspp-regions) class.
</div></td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>ViewRegistrationException(SerializationInfo, StreamingContext)</td>
<td><div class="summary">
Initializes a new instance of the [ViewRegistrationException](/patterns-practices/reference/viewregistrationexception-class-mspp-regions) class with serialized data.
</div></td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>ViewRegistrationException(String, Exception)</td>
<td><div class="summary">
Initializes a new instance of the [ViewRegistrationException](/patterns-practices/reference/viewregistrationexception-class-mspp-regions) class.
</div></td>
</tr>
</tbody>
</table>

## Methods

<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[Equals](http://msdn.microsoft.com/en-us/library/bsc2ak47)</td>
<td><div class="summary">
Determines whether the specified [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b) is equal to the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[Finalize](http://msdn.microsoft.com/en-us/library/4k87zsw7)</td>
<td><div class="summary">
Allows an object to try to free resources and perform other cleanup operations before it is reclaimed by garbage collection.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetBaseException](http://msdn.microsoft.com/en-us/library/49kcee3b)</td>
<td><div class="summary">
When overridden in a derived class, returns the [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59) that is the root cause of one or more subsequent exceptions.
</div>
(Inherited from [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetHashCode](http://msdn.microsoft.com/en-us/library/zdee4b3y)</td>
<td><div class="summary">
Serves as a hash function for a particular type.
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="odd">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetObjectData](http://msdn.microsoft.com/en-us/library/fwb1489e)</td>
<td><div class="summary">
When overridden in a derived class, sets the [SerializationInfo](http://msdn.microsoft.com/en-us/library/a9b6042e) with information about the exception.
</div>
(Inherited from [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[GetType](http://msdn.microsoft.com/en-us/library/44zb316t)</td>
<td><div class="summary">
Gets the runtime type of the current instance.
</div>
(Inherited from [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
<tr class="odd">
<td>![Protected method](/patterns-practices/reference/images/protmethod.gif)</td>
<td>[MemberwiseClone](http://msdn.microsoft.com/en-us/library/57ctke0a)</td>
<td><div class="summary">
Creates a shallow copy of the current [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).
</div>
(Inherited from [Object](http://msdn.microsoft.com/en-us/library/e5kfa45b).)</td>
</tr>
<tr class="even">
<td>![Public method](/patterns-practices/reference/images/public-method.gif)</td>
<td>[ToString](http://msdn.microsoft.com/en-us/library/es4y6f7e)</td>
<td><div class="summary">
Creates and returns a string representation of the current exception.
</div>
(Inherited from [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
</tbody>
</table>

## Extension Methods

<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public Extension Method](/patterns-practices/reference/images/pubextension.gif)</td>
<td>[GetRootException](/patterns-practices/reference/exceptionextensions-getrootexception-method-mspp)</td>
<td><div class="summary">
Looks at all the inner exceptions of the exception parameter to find the most likely root cause of the exception. This works by skipping all registered exception types.
</div>
(Defined by [ExceptionExtensions](/patterns-practices/reference/exceptionextensions-class-mspp).)</td>
</tr>
</tbody>
</table>

## Properties

<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Data](http://msdn.microsoft.com/en-us/library/2wyfbc48)</td>
<td><div class="summary">
Gets a collection of key/value pairs that provide additional user-defined information about the exception.
</div>
(Inherited from [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[HelpLink](http://msdn.microsoft.com/en-us/library/71tawy4s)</td>
<td><div class="summary">
Gets or sets a link to the help file associated with this exception.
</div>
(Inherited from [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[HResult](http://msdn.microsoft.com/en-us/library/sh5cw61c)</td>
<td><div class="summary">
Gets or sets HRESULT, a coded numerical value that is assigned to a specific exception.
</div>
(Inherited from [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[InnerException](http://msdn.microsoft.com/en-us/library/902sca80)</td>
<td><div class="summary">
Gets the [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59) instance that caused the current exception.
</div>
(Inherited from [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Message](http://msdn.microsoft.com/en-us/library/9btwf6wk)</td>
<td><div class="summary">
Gets a message that describes the current exception.
</div>
(Inherited from [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[Source](http://msdn.microsoft.com/en-us/library/85weac5w)</td>
<td><div class="summary">
Gets or sets the name of the application or the object that causes the error.
</div>
(Inherited from [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
<tr class="odd">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[StackTrace](http://msdn.microsoft.com/en-us/library/dxzhy005)</td>
<td><div class="summary">
Gets a string representation of the immediate frames on the call stack.
</div>
(Inherited from [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
<tr class="even">
<td>![Public property](/patterns-practices/reference/images/pubproperty.gif)</td>
<td>[TargetSite](http://msdn.microsoft.com/en-us/library/2wchw354)</td>
<td><div class="summary">
Gets the method that throws the current exception.
</div>
(Inherited from [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
</tbody>
</table>

## Events

<table>

<thead>
<tr class="header">
<th> </th>
<th>Name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>![Protected event](/patterns-practices/reference/images/protected-event.gif)</td>
<td>[SerializeObjectState](http://msdn.microsoft.com/en-us/library/ee332915)</td>
<td><div class="summary">
Occurs when an exception is serialized to create an exception state object that contains serialized data about the exception.
</div>
(Inherited from [Exception](https://msdn.microsoft.com/en-us/library/c18k6c59).)</td>
</tr>
</tbody>
</table>

## See Also
[ViewRegistrationException Class](/patterns-practices/reference/viewregistrationexception-class-mspp-regions)  
[Microsoft.Practices.Prism.Regions Namespace](/patterns-practices/reference/mspp-regions-namespace)